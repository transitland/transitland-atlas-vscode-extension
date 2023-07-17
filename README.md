# Visual Studio Code extension for Transitland Atlas DMFR files

Make it easier to create and edit DMFR files using Visual Studio Code.

Commands (access from the command palette):

- `Create new DMFR file`
- `Apply opinionated format to current DMFR file`

Snippets (while editing a JSON file):

- `DMFR file`: Create the base structure for a new Transitland Atlas DMFR file

## Development

To build the extension:

```sh
npm install -g @vscode/vsce
yarn run package
```

To install the extension:

```sh
code --install-extension transitland-atlas-vscode-extension-0.0.2.vsix
```

Perhaps in the future we'll publish this to the Visual Studio Code extension marketplace.
