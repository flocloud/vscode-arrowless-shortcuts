# Arrowless Shortcuts

> **Note**: This extension is for macOS only.

This VS Code extension provides keyboard shortcuts to replace the arrow keys, Home, End, Page Down, and Page Up, helping to reduce finger movement.

## Features

This extension offers the following shortcuts:

- `Ctrl + U`: Deletes the entire line where the cursor is located.
- `Ctrl + Shift + B`: Extends the selection left by one character.
- `Ctrl + Shift + F`: Extends the selection right by one character.
- `Ctrl + Shift + P`: Extends the selection up by one line.
- `Ctrl + Shift + N`: Extends the selection down by one line.
- `Ctrl + Alt + P`: Moves the current line up.
- `Ctrl + Alt + N`: Moves the current line down.
- `Alt + B`: Moves the cursor left by one word.
- `Alt + F`: Moves the cursor right by one word.
- `Alt + H`: Deletes the word to the left of the cursor.
- `Alt + D`: Deletes the word to the right of the cursor.
- `Alt + P`: Moves the cursor up by one page.
- `Alt + N`: Moves the cursor down by one page.
- `Alt + A`: Moves the cursor to the start of the document.
- `Alt + E`: Moves the cursor to the end of the document.
- `Alt + C`: Capitalizes the current word.
- `Alt + L`: Converts the current word to lowercase.
- `Alt + U`: Converts the current word to uppercase.
- `Alt + Shift + B`: Extends the selection left by one word.
- `Alt + Shift + F`: Extends the selection right by one word.

> Note: On macOS, pressing the Option key with a letter can produce special characters, which might interfere with some shortcuts. If you encounter this issue, you can disable this default OS behavior by changing the *Input Source*:
> 
> 1. Open *System Settings/Preferences*.
> 2. Go to *Keyboard*.
> 3. Edit *Input Source*.
> 4. Click the "+" button at the bottom left.
> 5. Select and add *Unicode Hex Input*.

## Reference for Shortcuts, Including Built-in Shortcuts

VS Code includes several similar shortcuts, and combining them with the shortcuts from this extension can boost your efficiency. This document lists these shortcuts for reference.

Some of these shortcuts can also be used in Linux and macOS Terminal; this will be noted below.

### `Ctrl` for Character/Line Operations

| Key Combination | Description | Equivalent Key | VS Code Built-in | Terminal Supported |
| --- | --- | --- | --- | --- |
| `Ctrl + A` | Move to the line start | `Cmd + ←` or `Home` | Yes | Yes |
| `Ctrl + E` | Move to the line end | `Cmd + →` or `End` | Yes | Yes |
| `Ctrl + B` | Move left by character | `←` | Yes | Yes |
| `Ctrl + F` | Move right by character | `→` | Yes | Yes |
| `Ctrl + H` | Delete character to the left of the cursor | `Backspace` | Yes | Yes |
| `Ctrl + D` | Delete character to the right of the cursor | - | Yes | Yes |
| `Ctrl + K` | Delete all text after the cursor | - | Yes | Yes |
| `Ctrl + N` | Move to the next line | `↓` | Yes | Yes |
| `Ctrl + P` | Move to the previous line | `↑` | Yes | Yes |
| `Ctrl + O` | Insert a new line without moving the cursor | - | Yes | Yes |
| `Ctrl + T` | Transpose two characters before the cursor | - | Yes | Yes |
| `Ctrl + U` | Delete the current line | `Cmd + Backspace` | No | Yes |

### `Alt` for Word/Page Operations

| Key Combination | Description | Equivalent Key | VS Code Built-in | Terminal Supported |
| --- | --- | --- | --- | --- |
| `Alt + B` | Move left by one word | `Alt + ←` | No | Yes |
| `Alt + F` | Move right by one word | `Alt + →` | No | Yes |
| `Alt + H` | Delete the word to the left of the cursor | `Alt + Backspace` | No | Yes |
| `Alt + D` | Delete the word to the right of the cursor | - | No | Yes |
| `Alt + P` | Move the cursor up by one page | `Page Up` | No | No |
| `Alt + N` | Move the cursor down by one page | `Page Down` | No | No |
| `Alt + A` | Move the cursor to the start of the document | `Cmd + ↑` | No | No |
| `Alt + E` | Move the cursor to the end of the document | `Cmd + ↓` | No | No |
| `Alt + C` | Capitalize the current word | - | No | Yes |
| `Alt + L` | Convert the current word to lowercase | - | No | Yes |
| `Alt + U` | Convert the current word to uppercase | - | No | Yes |

### `Ctrl`/`Alt` + `Shift` for Selection

| Key Combination | Description | Equivalent Key | VS Code Built-in | Terminal Supported |
| --- | --- | --- | --- | --- |
| `Ctrl + Shift + B` | Select left by one character | `Ctrl + Shift + ←` | No | No |
| `Ctrl + Shift + F` | Select right by one character | `Ctrl + Shift + →` | No | No |
| `Ctrl + Shift + P` | Select up by one line | `Ctrl + Shift + ↑` | No | No |
| `Ctrl + Shift + N` | Select down by one line | `Ctrl + Shift + ↓` | No | No |
| `Alt + Shift + B` | Select left by one word | `Alt + Shift + ←` | No | No |
| `Alt + Shift + F` | Select right by one word | `Alt + Shift + →` | No | No |

### `Ctrl` + `Alt` for Line Movement

| Key Combination | Description | Equivalent Key | VS Code Built-in | Terminal Supported |
| --- | --- | --- | --- | --- |
| `Ctrl + Alt + P` | Move the line up | `Alt + ↑` | No | No |
| `Ctrl + Alt + N` | Move the line down | `Alt + ↓` | No | No |
