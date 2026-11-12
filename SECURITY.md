# Security Policy

Thank you for helping keep **Task Manager Pause Button** safe.

This project is a Windhawk mod that runs inside the Windows 11 Task Manager (`Taskmgr.exe`). A security issue could affect Task Manager or other actions inside that process.

## Supported versions

| Version | Security updates |
| --- | --- |
| Latest release | Supported |
| All previous versions | Not supported |

Only the latest published release receives security updates. Please update to the newest version before reporting an issue.

## Reporting a vulnerability

**Do not share security details or proof-of-concept code in a public GitHub issue.**

1. Open the [repository security page](https://github.com/luizbizzio/task-manager-pause-button/security).
2. If **Report a vulnerability** is available, use it to send a private report.
3. If private reporting is not available, [open a general issue](https://github.com/luizbizzio/task-manager-pause-button/issues/new) asking for a private way to contact the maintainer. Do not include the vulnerability details there.

Please include, if possible:

- A short description of the issue and its possible impact.
- Your Windows 11 version and build number.
- Your Windhawk version and the affected mod version.
- Clear steps to reproduce the issue in a safe test setup.
- Relevant logs or screenshots with personal information removed.

Do not share passwords, private files, tokens, or other sensitive information.

## Security considerations

- The mod runs inside `Taskmgr.exe` and uses internal Windows XAML interfaces to add a button.
- It uses Task Manager's Ctrl-key refresh hold behavior. While paused, some Ctrl-based actions inside Task Manager may behave differently.
- It pauses the Task Manager view, **not** running processes.
- The mod does not need to edit the Windows Registry or install a separate service.
- Windows updates can change Task Manager's internal behavior. Use the latest mod version and report unexpected behavior.

## What happens next

The maintainer will review the report and may ask for more details. If the issue is confirmed, a fix may be released and a security advisory may be published when appropriate. No fixed response or release time is guaranteed.

Please allow time for investigation before making technical details public.

## Non-security bugs

For normal bugs, missing buttons, display problems, or feature requests, use [GitHub Issues](https://github.com/luizbizzio/task-manager-pause-button/issues).

## Project license

Task Manager Pause Button is distributed under the [Apache License 2.0](LICENSE).
