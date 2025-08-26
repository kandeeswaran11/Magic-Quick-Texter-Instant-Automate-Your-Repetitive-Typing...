# Magic-XLSX-Quick-Texter-InstantAutomate
Magic XLSX Quick Texter - by InstantAutomate - is a Tiny shortcut text into long text + Auto Form filler utility powered by AutoHotkey v2.
Its lets you turn tiny shortcuts (Hotstring or Hotkey) into long text instantly, fully customizable from Excel without editing scripts.

# How it works
Prepare your Excel file (Shortcuts.xlsx) with 3 columns:
Type → Hotstring or Hotkey
Trigger Key → e.g., ahk or ^q (^ means Ctrl, ! means Alt, + means Shift)
Action Text → The full expanded text
<Br>
## Example:

| Type | Name | Key | Actions |
|--|--|--|--|
| Hotstring | Greeting | Gm | Good Morning ! |
| Hotstring | Thanks| Thx | Thanks for contacting us. Our team will respond to you as soon as possible. |
| Hotkey | Sorry | ^r | We regret any inconvenience this has caused you! |
| Hotkey | Welcome | ^w| We regret any inconvenience this has caused you! |

Run the script → It reads the Excel file and auto-creates the hotkeys & hotstrings.

Use in daily typing:

Type ahk → It becomes “AutoHotkey Text Expander”.

Press Ctrl+Q → It inserts “Thanks for Contacting us. We will get back to you soon !!”.

Edit Excel file anytime → Restart the script → Your new shortcuts are ready.
