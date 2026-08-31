# Tabletop Dice Roller — Support

This repo hosts support requests and bug reports for the [Tabletop Dice Roller](https://corneliusbrackett.com/tabletop-dice-roller/) browser extension (Chrome / Edge). There's no source code here — it's just an issue tracker.

Found a bug, or a site you'd like added to the allowed-sites list? [Open an issue](https://github.com/corneliusbrackett/tabletop-dice-roller-support/issues/new).

## Checkout

Canonical tree is WSL ext4 (not `C:\Repository`):

- Linux: `/home/corne/work/tabletop-dice-roller-support`
- Windows view: `\\wsl.localhost\Ubuntu-24.04\home\corne\work\tabletop-dice-roller-support`

Product source is [`corneliusbrackett/TabletopDiceRoller`](https://github.com/corneliusbrackett/TabletopDiceRoller). Do not implement extension fixes here.

## Inventory (WSL)

There is no build, pack, test, or launcher in this repository. No `cmd.exe` / PowerShell wrappers and no `C:\Repository` paths.

| Path | Role |
| --- | --- |
| `README.md` | Support instructions |
| `AGENTS.md` | Agent operating notes |
| `.github/ISSUE_TEMPLATE/` | Bug and site-request forms |
| `tabletop-dice-roller-support.code-workspace` | VS Code workspace (relative `.` folder) |

From WSL:

```bash
cd /home/corne/work/tabletop-dice-roller-support
pwd
ls
```

That is the whole local workflow: clone/open the tree and use GitHub Issues. There is no `npm`/`make` target to run.
