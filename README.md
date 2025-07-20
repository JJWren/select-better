# 🧠 Select Better

Select smarter, not harder.

**Select Better** is a lightweight Visual Studio Code extension that allows you to quickly select intelligent text ranges under your cursor — including:

- ✅ Full URLs (with or without Markdown wrapping)
- ✅ Emails
- ✅ Localhost URLs and IPs (e.g., `http://localhost:3000`)
- ✅ Extended variable names (`some_variable-name`)
- ✅ Fallback to normal word selection when nothing matches

## 🚀 Features

- 🔍 One shortcut to rule them all
- 🎯 Detects and highlights the **entire semantic unit** under your cursor
- 🧠 Automatically trims trailing punctuation from Markdown or inline links
- 💻 Lightweight and fast — no dependencies or heavy tooling

## ✨ Usage

1. Move your cursor into or onto:
   - A URL like `https://github.com/user/repo)`
   - An email like `someone@example.com`
   - A variable like `some-variable_name`
2. Press the keyboard shortcut:
   - **Mac:** `Ctrl + Option + Shift + U`
   - **Windows/Linux:** `Ctrl + Alt + Shift + U`
3. The full match will be selected automatically

## 🛠️ Customization

You can change the keyboard shortcut by editing your keybindings in VSCode:

```json
{
  "key": "cmd+option+ctrl+u",
  "command": "select-better.selectedExtendedWord",
  "when": "editorTextFocus"
}
```

> **Note:** This README was generated using AI. I'm not good at making these look good, so enjoy.