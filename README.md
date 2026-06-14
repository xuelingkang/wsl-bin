# WSL utilities for Windows interop

[`wsl-copy`](wsl-copy) — copy text from WSL to Windows clipboard (PowerShell `SetText`)

[`wsl-paste`](wsl-paste) — paste text from Windows clipboard to WSL (PowerShell `GetText`)

[`weasel-mode`](weasel-mode) — toggle Weasel input method ASCII mode from WSL (`ascii`/`nascii`)

[`wsl-open`](wsl-open) — open URLs/files/directories on Windows host from WSL.
Used as `$BROWSER` for `xdg-open`: URLs open in Windows default browser (Vivaldi),
files in their default app, directories in Windows Explorer.

Used by:
- [tmux-config](https://github.com/xuelingkang/tmux-config) — `@override_copy_command`
- [vim-config](https://github.com/xuelingkang/vim-config) — WSL clipboard workaround
- `$BROWSER` env var — `tmux-open` / `xdg-open` forwarding to Windows host
