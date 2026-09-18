# GunPAD
A minimal [gunDB](https://gun.eco/) collaborative notepad.

Add `#yournotepadname` to the URL for a designated notepad.

Short link: [tfi.la/g](https://tfi.la/g)

*Warning: Everything is ephemeral!*

### Use as a temporary URL shortener

Use `?yournotepadname` in the URL (instead of the hash) to grab and open the first URL from the notepad.
You can omit the `/g` from the short link, e.g. [tfi.la?short](https://tfi.la?short) (currently points here, but may change...)

### Editor special keys
- `Tab`, `Shift`+`Tab` - Indent / unindent at caret or multi-line for selection (but `Tab` will replace a selection of only tabs and spaces)
- `Enter`, `Shift`+`Enter` - New line with current or coding-language-based extra indentation (`Shift` skips to line end beforehand)
- `Home`, `Shift`+`Home` (excluding MacOS) - Move caret to indentation; if already there, move to logical line start (`Shift` for selection)
- `End`, `Shift`+`End` (excluding MacOS) - For wrapped lines, second press moves caret to logical line end (`Shift` for selection)


- `Esc` - Remove selection
- `Ctrl`+`C` without selection - Duplicate line (clipboard untouched)
- `Ctrl`+`X` without selection - Delete line (clipboard untouched)


- `Ctrl`+`/` - Multi-line `//` comment / uncomment
- `Ctrl`+`'` / `Ctrl`+`"` / `Ctrl`+`` ` `` - Quote / unquote selection or expression at caret, bare quote also works for selection (whitespace and `,` `:` stay outside)
- `Ctrl`+`Space` (Mac: `Option`+`Space`) - Unmangle English <-> Hebrew (assuming SI 1452-2 aka ARKN) keyboard language mistypes for line or selection


- `Ctrl`+`Shift`+`J` - Join next line / selected lines with a single space
- `Ctrl`+`Shift`+`O` or `Ctrl`+`Click` / `Ctrl`+`Select` - Open (partially) selected links in new tabs
- `Ctrl`+`S` - Save text to file

On Mac use `⌘ Command` anywhere `Ctrl` is mentioned above, unless stated otherwise.