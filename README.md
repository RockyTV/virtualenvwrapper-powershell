# virtualenvwrapper-powershell
A port of Doug Hellmann's virtualenvwrapper to Powershell.

## Features
1. Organizes all of your virtual environments in one place.
2. Wrappers for creating, copying and deleting environments, including user-configurable hooks.
3. Use a single command to switch between environments.
4. User-configurable hooks for all operations.
5. Plugin system for more creating sharable extensions.

## Installation and setup
- `python setup.py install`

virtualenvwrapper is installed as a module in `~/Documents/WindowsPowerShell/Modules`. To load the module, do `import-module virtualenvwrapper`.
Alternatively, see the [original project documentation](http://www.doughellmann.com/docs/virtualenvwrapper/) for guidance on installation and setup.

## Supported Shells
Powershell 2.0+

## Python Versions
virtualenvwrapper-powershell is tested under Python 2.7, and this port was tested under Python 3.5. However, this port should be able to work on Python 2.7 as well.

## Support
Report bugs via the [bug tracker on GitHub](https://github.com/RockyTV/virtualenvwrapper-powershell/issues)

## Shell Aliases
Since virtualenvwrapper is largely a shell script, it uses shell commands for a lot of its actions. If your environment makes heavy use of shell aliases or other customizations, you may encounter issues. Before reporting bugs in the bug tracker, please test without your aliases enabled. If you can identify the alias causing the problem, that will help make virtualenvwrapper-powershell more robust.

## License
Copyright Guillermo López, All Rights Reserved

Permission to use, copy, modify, and distribute this software and its documentation for any purpose and without fee is hereby granted, provided that the above copyright notice appear in all copies and that both that copyright notice and this permission notice appear in supporting documentation, and that the name of Guillermo López not be used in advertising or publicity pertaining to distribution of the software without specific, written prior permission.

GUILLERMO LÓPEZ DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS, IN NO EVENT SHALL GUILLERMO LÓPEZ BE LIABLE FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
