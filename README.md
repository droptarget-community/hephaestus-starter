# Local development

> Before first run: Install Node and Yarn.
>
> Then to start:
>
> ```sh
> yarn
> yarn start
> ```

### Formatting on save with VSCode and ESlint extension

- Open your settings file (Shift+Cmd+P and type "settings JSON")
- Remove `editor.formatOnSave` if present
- Remove `eslint.autoFixOnSave` (deprecated) if present
- Add:

```json
"editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
},
"editor.codeActionsOnSaveTimeout": 3000
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
```

test
