# ESLint & Prettier Setup

## Setup Guide

### Install Extensions:

-   **ESLint**: [VS Code Extension Link](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-   **Prettier**: [VS Code Extension Link](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Configure your `settings.json`:

**Default code formatter**:

```
"editor.defaultFormatter": "esbenp.prettier-vscode"
```

**For React TypeScript (.tsx) files**:

```
"[typescriptreact]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

**For React JavaScript (.jsx) files**:

```
"[javascriptreact]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

**For TypeScript (.ts) files**:

```
"[typescript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

**For JavaScript (.js) files**:

```
"[javascript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

### Install Prettier Dependencies:

Using **NPM**:

```
npm install --save-dev --save-exact prettier
```

Using **PNPM**:

```
pnpm add --save-dev --save-exact prettier
```

Using **YARN**:

```
yarn add --dev --exact prettier
```

### Install ESLint Dependencies:

Using **NPM**:

```
npm init @eslint/config@latest
```

Using **PNPM**:

```
pnpm create @eslint/config@latest
```

Using **YARN**:

```
yarn create @eslint/config
```

### Configuration

Copy the contents of your configuration files (`.eslint.config.mjs`, `.prettierignore`, `.prettierrc`) and paste them into the respective config files in your project.
