# scoop-bucket

Personal Scoop bucket for apps not available in official buckets.

## Usage

```powershell
scoop bucket add scoop-bucket https://github.com/EndzE/scoop-bucket
scoop install scoop-bucket/blur-autoclicker
```

## Apps

| Manifest | Notes |
|----------|-------|
| `blur-autoclicker` | AutoClicker (GitHub releases, auto-update) |
| `samrewritten` | Steam achievements manager (GitHub releases, auto-update) |
| `depotdownloadermod` | DepotDownloader fork, needs .NET 9 Desktop Runtime, auto-update via workflow (no upstream checksums) |
| `server-picker-x` | CS2 server picker GUI, `settings.json` persisted across updates |

## Auto-updates

The [Excavator workflow](.github/workflows/excavator.yml) runs every 6 hours:
`scoop checkver -u` for every manifest, then fills fresh hashes from the GitHub
release API (asset `digest`, with download-and-hash fallback).
