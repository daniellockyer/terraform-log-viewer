# Terraform Log Viewer

A browser-based viewer for GitHub Actions Terraform plan and apply logs. Drop a log file (or paste text) to see a timeline of phases, resource refreshes, and changes.

**Live demo:** https://daniellockyer.github.io/terraform-log-viewer/

<img width="3906" height="3140" alt="CleanShot 2026-07-01 at 10 44 47@2x" src="https://github.com/user-attachments/assets/6ab2e17c-ff2f-4db6-8254-d917d053ada9" />

## Usage

1. Open the [live demo](https://daniellockyer.github.io/terraform-log-viewer/) or serve `index.html` locally.
2. Drop a `.log` / `.txt` file, click to choose one, or paste log text with `Ctrl`/`Cmd`+`V`.
3. Explore the summary, cumulative log chart, and refresh swimlanes grouped by module.

Logs should use GitHub Actions timestamps, for example:

```
2026-03-09T09:03:14.0427158Z Terraform will perform the following actions:
```

Everything runs in the browser — no upload, no server.

## License

MIT
