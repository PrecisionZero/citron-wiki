# Reading Logs

Logs help distinguish a real failure from a warning that can be harmless.

## Where to look

Most launchers provide an instance folder or a button such as **Open logs**, **Open game folder**, or **View crash report**. Common Minecraft files include:

- `logs/latest.log` — the most recent game session.
- `crash-reports/` — crash reports created after a crash.

The exact path depends on the launcher and instance layout.

## What to search for

Look near the end of the log and around the time the problem occurred. Useful terms include `ERROR`, `Exception`, `Caused by:`, `Mixin apply failed`, and `Could not`. A warning by itself does not prove that it caused the issue.

## Share logs safely

Before posting logs publicly, review them for usernames, local file paths, server addresses, or other private information. Do not post authentication tokens or account credentials.

For an issue report, include the full relevant crash report where possible, not only a single error line. See [Reporting an Issue](../support/issue-reporting.md).
