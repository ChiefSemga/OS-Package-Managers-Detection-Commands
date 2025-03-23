
---

## **Linux.md**
```markdown
# Linux Package Managers & OS Detection

## **Package Managers**
| Distro | Package Manager | Install Command | Usage Example |
|--------|---------------|----------------|--------------|
| Debian/Ubuntu | APT | `sudo apt update && sudo apt install <package>` | `apt list --installed` |
| Fedora | DNF | `sudo dnf install <package>` | `dnf list installed` |
| Arch Linux | Pacman | `sudo pacman -S <package>` | `pacman -Q` |
| OpenSUSE | Zypper | `sudo zypper install <package>` | `zypper se <package>` |

## **Check OS Version**
```bash
cat /etc/os-release
lsb_release -a
uname -a
hostnamectl
