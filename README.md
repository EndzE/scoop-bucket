# scoop-bucket

Personal Scoop bucket for apps not available in official buckets.

## Usage

```powershell
scoop bucket add scoop-bucket https://github.com/EndzE/scoop-bucket
scoop install scoop-bucket/blur-autoclicker
```

## Apps

| Manifest | Repo | Notes |
|----------|------|-------|
| `blur-autoclicker` | [Blur009/Blur-AutoClicker](https://github.com/Blur009/Blur-AutoClicker) | GitHub releases, auto-update |
| `samrewritten` | [PaulCombal/SamRewritten](https://github.com/PaulCombal/SamRewritten) | Steam achievements manager, GitHub releases, auto-update |
| `depotdownloadermod` | [SteamAutoCracks/DepotDownloaderMod](https://github.com/SteamAutoCracks/DepotDownloaderMod) | Needs .NET 9 Desktop Runtime, auto-update via workflow (no upstream checksums) |
| `server-picker-x` | [FN-FAL113/server-picker-x](https://github.com/FN-FAL113/server-picker-x) | CS2 server picker GUI, `settings.json` persisted across updates |
| `f95checker` | [WillyJL/F95Checker](https://github.com/WillyJL/F95Checker) | F95zone game updates checker, x64 only, data stored in `%APPDATA%\f95checker` |
| `sandboxie-plus` | [sandboxie-plus/Sandboxie](https://github.com/sandboxie-plus/Sandboxie) | Portable-mode install of the official Inno Setup installer (/portable=1): no admin, no pre-registered driver, unlike official Nonportable `sandboxie-plus-np`; upstream sha256-checksums for auto-update |
