# Terminal & Logs

KubeTile's terminal integration provides shells and log streams automatically configured for your cluster.

## Log Streaming

Select a Pod and press `l` to stream its logs in a new pane.

| Key | Action |
|---|---|
| `f` | Toggle follow mode |
| `/` | Filter log lines |
| `w` | Toggle line wrapping |
| `Ctrl+S` | Save visible logs (including any active filter) to a file |
| `Ctrl+E` | Export (download) the full available log |

## Exec into Pods

Select a Pod and press `e` to open an interactive shell inside its container (uses the shell configured in `[general] shell`).

- Press `Esc` to switch from the terminal to `NORMAL` mode.
- Press `i` to switch back to `INSERT` mode and resume typing in the terminal.
