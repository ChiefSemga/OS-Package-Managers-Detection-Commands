
---

## **Solaris.md**
```markdown
# Solaris Package Managers & OS Detection

## **Package Managers**
| Package Manager | Install Command | Usage Example |
|---------------|----------------|--------------|
| IPS (pkg) | `pkg install <package>` | `pkg list --installed` |
| OpenCSW (pkgutil) | `pkgutil -i <package>` | `pkgutil -l` |

## **Check OS Version**
```bash
uname -a
cat /etc/release
