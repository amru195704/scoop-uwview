# scoop-uwview

[Scoop](https://scoop.sh) bucket for [UwView](https://github.com/amru195704/UwView) — open and search huge text/log files, with the `uvf` command.

```powershell
scoop bucket add uwview https://github.com/amru195704/scoop-uwview
scoop install uwview
```

This installs the GUI (Start menu shortcut "UwView") and puts `uvf` on your PATH.

```powershell
uvf app.log 'ERROR'          # search
uvf app.log 'ERROR' -open    # search, then show the hits in the viewer
```

The manifest downloads the official archive from [GitHub Releases](https://github.com/amru195704/UwView/releases) and checks its SHA256. Nothing is re-hosted here.

License of UwView: PolyForm Internal Use 1.0.0 — see [LICENSE](https://github.com/amru195704/UwView/blob/main/LICENSE). The Windows build is not code-signed yet; SmartScreen may ask on first launch.
