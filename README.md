# TypeSteady
> Keyboard macro toolkit for browser environments

## About

_TBA_.

### Macros

The following macros are supported:

| Macro                     | Description                               | Outputs   |
|---------------------------|-------------------------------------------|-----------|
| `{ALT}`                   | Alt key                                   |           |
| `{BACKSPACE}`             | Backspace key                             |           |
| `{CTRL}`                  | Control key                               |           |
| `{DELETE}` / `{DEL}`      | Delete key                                |           |
| `{DOWN}`                  | Down arrow key                            |           |
| `{END}`                   | End key                                   |           |
| `{ENTER}`                 | Enter key                                 |           |
| `{HOME}`                  | Home key                                  |           |
| `{LEFT}`                  | Left arrow key                            |           |
| `{RIGHT}`                 | Right arrow key                           |           |
| `{SHIFT}`                 | Shift key                                 |           |
| `{TAB}`                   | Tab key                                   |           |
| `{UP}`                    | Up arrow key                              |           |
| `{$username}`             | Read property `username` from vault entry.|           |
| `{@"input.username"}`     | Focus HTML element


```
{$username}
{@"input[type=text].login"}
{WAIT 3s}{SUBMIT}{BACKSPACE}{DELETE}
{HOME}{SHIFT+END}{COPY}{DELETE}
```