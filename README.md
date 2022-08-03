# @wzh994/eslint-config

## Usage

### Install

```bash
pnpm add -D eslint @wzh994/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": "@wzh994"
}
```

### Add script for package.json

```json
{
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  }
}
```

### Config VS Code auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
