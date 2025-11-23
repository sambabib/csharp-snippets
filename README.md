# C# Snippets Extension

A Visual Studio Code extension that provides useful code snippets for C# and .NET development.

## Features

This extension provides snippets for common C# patterns and constructs:

- `pcl` - Create a C# class
- `prop` - Create a property
- `ctor` - Create a constructor
- `meth` - Create a method
- `interface` - Create an interface
- `enum` - Create an enum
- `try` - Create a try-catch block
- `for` - Create a for loop
- `foreach` - Create a foreach loop
- `if` - Create an if statement

## Usage

1. Open a C# file in VS Code
2. Type one of the snippet prefixes (e.g., `pcl`)
3. Press `Tab` to insert the snippet
4. Use `Tab` to navigate through the placeholders

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "C# Snippets"
4. Click Install

## Development

### Building the Extension

1. Clone this repository
2. Run `npm install`
3. Press F5 to launch a new VS Code window with the extension loaded

### Packaging the Extension

```bash
npm install -g vsce
vsce package
```

This will create a `.vsix` file that can be installed in VS Code.

## License

MIT
