
---

## **BSD.md**
```markdown
# BSD Package Managers & OS Detection

## **Package Managers**
| BSD Variant | Package Manager | Install Command | Usage Example |
|------------|---------------|----------------|--------------|
| FreeBSD | pkg | `pkg install <package>` | `pkg info` |
| OpenBSD | pkg_add | `pkg_add <package>` | `pkg_info` |
| NetBSD | pkgin | `pkgin install <package>` | `pkgin list` |

## **Check OS Version**
```bash
uname -a
freebsd-version
