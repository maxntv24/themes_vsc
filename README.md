# RSM Highlighter - Visual Studio Code Extension

Syntax highlighting support for .rsm and .log files with a built-in dark theme.

## Features

- Syntax highlighting for RSM log files (.rsm, .log)
- Dark theme optimized for RSM syntax
- Language support including:
  - Basic syntax coloring
  - Bracket matching
  - Code folding

## Installation

<!-- 1. Open VS Code
2. Go to Extensions view (Ctrl+Shift+X)
3. Search for "RSM Highlighter"
4. Click Install -->

Alternatively, install from VSIX:
1. Download the .vsix file from Releases
2. Open VS Code
3. Go to Extensions view
4. Click "..." and select "Install from VSIX"
5. Select the downloaded file

## Usage

1. Open any .rsm or .log file
2. The syntax highlighting will be automatically applied
3. To use the dark theme:
   - Open Command Palette (Ctrl+Shift+P)
   - Search for "Color Theme"
   - Select "RSM Theme"

## Configuration

Customize the theme colors by editing:
```
themes/rsm-color-theme.json
```

Customize syntax highlighting by editing:
```
syntaxes/rsm.tmLanguage.json
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

[MIT](LICENSE)
