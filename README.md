# volesim
A self-contained, cross-platform Brookshear Vole Machine simulator/editor with a pure C execution engine and a C++/FLTK UI. 


<img width="1551" height="643" alt="11" src="https://github.com/user-attachments/assets/c8ae7752-3525-4625-8900-c4b2ad97ab62" />


## Download

Download the latest version of volesim from
[GitHub Releases](../../releases/latest).

| Platform | Format | Requirements |
|---|---|---|
| Windows | `.exe` | Windows x64 |
| Linux | `.AppImage` | Linux x86-64 |
| macOS Universal | `.zip` | macOS 11+ (Intel / Apple Silicon) |
| macOS Legacy | `.zip` | OS X 10.9+ (Intel) |

volesim is free to download and use.

No installation of FLTK or additional third-party
runtimes is required.



## Installation

### Windows
Download `volesim.exe` and run it.

### Linux
Download the AppImage, make it executable, and launch it:

```bash
chmod +x volesim-x86_64.AppImage
./volesim-x86_64.AppImage
```

### macOS
Download the appropriate ZIP archive and extract it
using Finder.

Open `volesim.app` to launch the application.

Because volesim is not currently signed or notarized,
macOS may block it on first launch.

If macOS blocks it, open System Settings >
Privacy & Security and use "Open Anyway" after
attempting to launch the application.



## Bug Reports and Feedback

Found a bug or have a suggestion?

Please open an issue in the
[GitHub Issues](../../issues) section.

When reporting a bug, please include:

- Operating system and version.
- volesim version.
- Steps to reproduce the issue.
- Expected and actual behavior.
- Relevant assembly code, if applicable.


## Acknowledgments

volesim implements the Vole Machine architecture
described in J. Glenn Brookshear's
*Computer Science: An Overview*.

Inspired by [SimpSim](https://www.anne-gert.nl/projects/simpsim/).

Nixie tube artwork by [Glionox](https://glionox.itch.io/nixie-tubes).

volesim is based in part on the work of the
[FLTK project](https://www.fltk.org/).
