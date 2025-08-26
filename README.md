# GunPAD
A minimal [gunDB](https://gun.eco/) collaborative notepad.

Add `#yournotepadname` to the URL for a designated notepad.

Short link: [tfi.la/g](https://tfi.la/g)

*Warning: Everything is ephemeral!*

### Use as a temporary URL shortener

Use `?yournotepadname` in the URL (instead of the hash) to grab and open the first URL from the notepad.
You can omit the `/g` from the short link, e.g. [tfi.la?short](https://tfi.la?short) (currently points here, but may change...)

### Editor special keys
- `Tab`, `Shift`+`Tab` - Indent / unindent at caret or selection start
- `Enter`, `Shift`+`Enter` - New line with current or coding-language-based extra indentation (`Shift` skips to line end beforehand)
- `Home`, `Shift`+`Home` - Move caret to indentation; if already there, move to logical line start (`Shift` for selection)
- `End`, `Shift`+`End` - For wrapped lines, second press moves caret to logical line end (`Shift` for selection)
- `Ctrl`+`C` with no selection - Duplicate line
- `Ctrl`+`X` with no selection - Delete line