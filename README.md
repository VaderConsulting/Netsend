# Netsend

Freelance VB6 messenger (`Send.exe`, VBP title netsend) that sends Windows Messenger / Net Send style messages. Primary UI (`frmNetSend`) collects To, From, and Message and drives a `clsNetSend` helper (class source supplied as `cnetsend.cls.example`). An alternate `frmSend` shells a generated `c:\temp\netsend.bat` with the classic `Net Send user message` command line.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `NetSend` (`netsend.vbp`) | VB6 | WinForms exe | Net Send / Messenger UI (`Send.exe`) |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `netsend.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMCTL32.OCX`
- Restore or implement `clsNetSend` from `cnetsend.cls.example` for the primary form path

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Netsend`.
Company names in project files: Freelance.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
