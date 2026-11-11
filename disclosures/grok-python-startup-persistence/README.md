# Grok: Python startup-hook persistence

**Researcher:** [YeandAmen](https://github.com/YeandAmen)  
**Status:** Fixed, as confirmed by the researcher following private disclosure to xAI.  
**Report date:** 16 June 2026

## What happened

During testing of Grok's code interpreter, an uploaded ZIP led the assistant to execute Python code that modified the runtime's user-site directory. The assistant also corrected execution problems and continued running the supplied code.

The script installed a `usercustomize.py` module. Python can automatically import this module during startup when the user-site mechanism is enabled. Subsequent Python processes in the same environment therefore executed the added code without a new, explicit request to run that module.

The recorded demonstration shows the module being installed, a new Python subprocess starting, and process environment information appearing in its error output. The module remained in place afterward.

## Demonstration

https://github.com/user-attachments/assets/50032307-699f-472e-ad1b-dfbbdacb85d8

## Why it mattered

A single execution could change later Python invocations within the tested session. That allowed earlier uploaded code to influence future output and expose information available inside that environment.

This write-up describes the demonstrated runtime persistence. It does not claim access to other users' sessions or independently establish a host-level escape.

## Resolution and prevention

The researcher reports that xAI fixed the issue and that it no longer reproduces. The implementation details of xAI's fix have not been provided here.

The following are defensive recommendations, rather than a description of xAI's patch:

- Keep uploaded content and its instructions untrusted; inspect code before execution.
- Prevent untrusted code from modifying Python startup and import locations.
- Use isolated Python startup where appropriate, alongside operating-system isolation. Python's `-I` option excludes user-site packages and ignores Python environment variables; it is not a complete sandbox by itself.
- Reset execution environments across trust boundaries so one task cannot leave runtime modifications for another.
- Run with minimal privileges and restrict access to process information, secrets, filesystem mounts, and unnecessary network destinations.

## Technical references

- [Python 3.12: site and usercustomize](https://docs.python.org/3.12/library/site.html)
- [Python 3.12: isolated mode and startup options](https://docs.python.org/3.12/using/cmdline.html#cmdoption-I)

[Back to profile](../../README.md)
