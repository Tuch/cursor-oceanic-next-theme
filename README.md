# Oceanic Next Theme for VSCode/Cursor

A beautiful, modern Oceanic Next-inspired dark color theme for VSCode and Cursor, with soft borders and carefully tuned syntax highlighting.

<img width="1351" alt="image" src="https://github.com/user-attachments/assets/f57df20a-2867-4617-ab93-93b7f0f15762" />

## ✨ Features

- Deep blue-gray background and soft, readable colors
- Transparent, elegant borders
- Carefully selected syntax highlighting for JavaScript, TypeScript, and more
- Works great in both VSCode and Cursor

## 📦 Installation

### 1. Build the VSIX package

If you haven't already, install the VSCE tool:

```bash
npm install -g vsce
```

Then, in the theme folder:

```bash
vsce package
```

This will create a file like `oceanic-next-theme-0.0.1.vsix`.

### 2. Install the theme in VSCode/Cursor

```bash
code --install-extension oceanic-next-theme-0.0.1.vsix
```

### 3. Activate the theme

- Open the Command Palette (`Cmd+Shift+P` or `Ctrl+Shift+P`)
- Type `Color Theme`
- Select **Oceanic Next** from the list

## 🛠️ Development

- Edit `themes/oceanic-next-color-theme.json` to tweak colors
- Update `package.json` if you want to change metadata
- Rebuild the `.vsix` after changes with `vsce package`

## 📁 Structure

```
oceanic-next-theme/
├── package.json
├── README.md
└── themes/
    └── oceanic-next-color-theme.json
```

## 🤝 Contributing

Pull requests and suggestions are welcome! Feel free to fork and improve this theme.

## 📜 License

MIT
