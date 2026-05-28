# poLite Language Support for VS Code

Welcome to the official Visual Studio Code extension for **poLite**! 
This extension provides rich syntax highlighting and intelligent code snippets for the courteous, strongly-typed *poLite* programming language.

## ✨ Features

- **Syntax Highlighting:** Full tokenization for all poLite structural keywords (`pls`, `do this`, `thanks`, `say`), data types, and operators.
- **Smart Snippets:** Autocompletion for common language constructs (e.g., function declarations, `if-otherwise` blocks, and `while` loops).
- **Comment Support:** Accurate toggling and highlighting for single-line comments (`//`).
- **Bracket Matching:** Seamless pairing for parentheses and logical blocks.

## 📝 Syntax Preview

When writing your `.plt` files, the extension will automatically recognize and format your code politely:

```text
const string WELCOME = "Welcome to poLite!" pls

int calculate_age() do this
    int age = 20 pls
    return age pls
thanks

if (true) do this
    say(WELCOME) pls
thanks
```

## 🚀 Installation (Manual)

Since this extension is tailored for academic purposes and not hosted on the VS Code Marketplace, you can install it locally in just a few steps:

### Method 1: Using the VSIX package
1. Download the latest `polite-x.x.x.vsix` file from the Releases page.
2. Open Visual Studio Code.
3. Go to the **Extensions** view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
4. Click the three dots `...` in the top right corner of the Extensions panel.
5. Select **"Install from VSIX..."** and choose the downloaded file.

### Method 2: From Source
1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/vscode-polite.git](https://github.com/yourusername/vscode-polite.git)
   ```
2. Open the cloned folder in VS Code.
3. Press `F5` to open a new window with the extension loaded (Extension Development Host).
4. Open any `.plt` file to see the highlighting in action!

## 🛠️ Development

To modify the syntax rules or add new snippets:
1. Edit the `syntaxes/polite.tmLanguage.json` file for TextMate grammar rules.
2. Edit the `snippets/snippets.json` file to expand the autocompletion library.
3. Reload the Extension Development Host window (`Ctrl+R` / `Cmd+R`) to test your changes.

## 📜 License
Developed for academic purposes.