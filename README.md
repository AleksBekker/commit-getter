# My git commit getter

This is my script that gets my commit links from a repository in a RCOS (Rensselaer Center for Open
Source) compatible manner.

# Installation

Put `my-commits` into your `~/.local/bin` or similar directory that is added to your `$PATH`

# Uninstallation

`my-commits` doesn't generate any other files, so simply removing the script is enough to uninstall
it from your system

# Usage

```
Usage: $0 [OPTIONS]
  -h            Display this help.
  -b            Enable boring mode: no colors.
  -e <email>    The email associated with commits. Defaults to 'user.email' from your git configuration.
  -c            Check if the links are valid.
  -d <dir>      Directory of the git repository. Defaults to the current directory.
  -r <remote>   Git remote name to use. Defaults to 'origin'.
  -s <since>    Date since. Defaults to the beginning of time itself (1970-01-01).
  -v            Enable verbose output (doesn't interfere with stdout).
```
