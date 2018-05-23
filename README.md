urwid_readline
----

Text input widget for [urwid](https://github.com/urwid/urwid) that supports
readline shortcuts.

### Installation

`pip install urwid-readline`

Example how to use the program can be found in the
[examples](https://github.com/rr-/urwid_readline/blob/master/example/)
directory.

### Features

Supported operations (names consistent with bash):

| Command                                               | Key Combination    |
| ----------------------------------------------------- | ------------------ |
| Beginning of line                                     | `Ctrl`+`A`         |
| Backward one character                                | `Ctrl`+`B` / `←`   |
| Backward one word                                     | `Meta`+`B`         |
| Send io.EOF                                           | `Ctrl`+`C`         |
| Delete one character                                  | `Ctrl`+`D`         |
| Delete one word                                       | `Meta`+`D`         |
| End of line                                           | `Ctrl`+`E`         |
| Forward one character                                 | `Ctrl`+`F` / `→`   |
| Forward one word                                      | `Meta`+`F`         |
| Delete previous character                             | `Ctrl`+`H`         |
| Transpose characters                                  | `Ctrl`+`T`         |
| Kill (cut) forwards to the end of the line            | `Ctrl` + `K`       |
| Kill (cut) backwards to the start of the line.        | `Ctrl` + `U`       |
| Kill (cut) forwards to the end of the current word    | `Meta` + `D`       |
| Kill (cut) backwards to the start of the current word | `Ctrl` + `W`       |
| Autocomplete                                          | See examples       |

Notable unsupported operations (let me know if you need these):

- word transposing
- clipboard
- history, undo
