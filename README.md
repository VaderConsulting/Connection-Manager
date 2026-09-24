# Connection Manager

D. Robinson VB6 Connection Manager (`ConnManager.exe`, © 2001): tray app that stores named multi-domain drive mappings in Jet `ConnManager.mdb` and connects them via `WNetAddConnection2` (Add New / Connect). Open `ConnManager.vbp` in the VB6 IDE (needs `flshtray.ocx`).

**Source last updated:** 2001-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ConnManager` (`ConnManager.vbp`) | VB6 | WinForms exe | Manage connections to multiple Domains. |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ConnManager.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSADODC.OCX`
  - `flshtray.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Connection Manager`.
Company names in project files: D. Robinson.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
