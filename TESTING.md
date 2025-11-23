# Testing the C# Snippets Extension

This document provides instructions on how to test the C# Snippets extension locally.

## Prerequisites

- Visual Studio Code
- Node.js and npm

## Testing Steps

1. Open the extension project in VS Code:
   ```bash
   code /path/to/csharp-snippets-extension
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Press F5 to launch a new VS Code window with the extension loaded.

4. In the new VS Code window, create a new file with a `.cs` extension.

5. Try out the snippets by typing the prefix and pressing Tab:
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

## Example Usage

1. Create a new file named `Person.cs`
2. Type `pcl` and press Tab
3. Enter `Person` as the class name
4. Press Tab to move to the body of the class
5. Type `prop` and press Tab
6. Enter `string` as the property type
7. Enter `Name` as the property name

The result should be:

```csharp
public class Person
{
    public string Name { get; set; }
}
```

## Troubleshooting

If snippets are not working:

1. Make sure the file has a `.cs` extension
2. Check that the extension is properly loaded (you should see it in the Extensions view)
3. Try reloading the window (Ctrl+R or Cmd+R on Mac)
4. Check the Developer Tools console for any errors (Help > Toggle Developer Tools)

## Packaging for Distribution

To package the extension for distribution:

```bash
npm install -g vsce
vsce package
```

This will create a `.vsix` file that can be installed in VS Code.
