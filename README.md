# UpdateTrendGUID

VB6 UpdateTrendGUID (`UpdateTrendGUID.exe`) that creates a new GUID and writes it to Trend Micro PC-cillin NT Corp registry (`SOFTWARE\TRENDMICRO\PC-CILLINNTCORP\CurrentVersion\GUID`) via REGTool5 when missing or force-updated. Open `UpdateTrendGUID.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `UpdateGUID` (`UpdateTrendGUID.vbp`) | VB6 | WinForms exe | Set/refresh Trend Micro PC-cillin client GUID |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `UpdateTrendGUID.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Historical deps as referenced: REGTool5

## Attribution and provenance

Working copy from my Historical Dev folder `VB/UpdateTrendGUID`.
Company names in `.vbp` files: Freelance.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
