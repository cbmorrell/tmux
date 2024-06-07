# tmux-config

Holds tmux configuration.

## Troubleshooting

If randomly getting the "returned 127" bug, try to fix by updating all plugins. If not just redownload all of them by following these steps:

- Delete `plugins` directory
- Reinstall tpm (`git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm`)
- Source configuration (`tmux source tmux.conf`)
- Open a tmux session and press `prefix` + `I` to install plugins (a screen should pop up saying that environment was installed)

