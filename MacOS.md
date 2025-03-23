
---

## **MacOS.md**
```markdown
# MacOS Package Managers & OS Detection

## **Package Managers**
| Package Manager | Install Command | Usage Example |
|---------------|----------------|--------------|
| Homebrew | `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` | `brew install <package>` |
| MacPorts | `sudo port selfupdate` (after installation) | `sudo port install <package>` |
| Fink | Installed via `.pkg` file | `fink install <package>` |

## **Check OS Version**
```bash
sw_vers
system_profiler SPSoftwareDataType
uname -a
