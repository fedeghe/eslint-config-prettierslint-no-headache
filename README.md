### eslint, prettier in a snap

I use vscode **with** the eslint extension, **without** prettier extension

```
yarn add -D eslint-prettier-no-headache
```

vscode config:

```
"editor.formatOnSave": true,
"[javascript]": {
  "editor.formatOnSave": false
},
"[javascriptreact]": {
  "editor.formatOnSave": false
},
"eslint.autoFixOnSave": true,
"prettier.disableLanguages": ["javascript", "javascriptreact"],
```


in the `.eslintrc.js` include `'prettierslint-no-headache'` in the `extends` array.
```
