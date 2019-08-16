# VS code 設定
###### tags: `設定` `VS code`
[如何在vscode中使用GitLab](https://segmentfault.com/a/1190000016593233)
[prettier 設定](https://ithelp.ithome.com.tw/articles/10205684)
```json=
{
  {
  //設定:https://poychang.github.io/my-vscode-config/
  "explorer.openEditors.visible": 0,
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.triggerExpansionOnTab": true,
  "editor.fontFamily": "'Fira Code', 'Microsoft YaHei Mono', Consolas, 'Courier New', monospace",
  "editor.fontSize": 18,
  "editor.fontWeight": "600",
  // 要啟用連體字型(Fira Code)必須將以下設定打開
  "editor.fontLigatures": true,
  "editor.formatOnPaste": true, // 貼上程式碼時會自動幫你排版
  "editor.formatOnSave": true, //存檔時自動排版
  "files.insertFinalNewline": true, // 儲存檔案時在其結尾插入最後一個新行
  "editor.minimap.enabled": true, //MiniMap 功能
  "editor.minimap.renderCharacters": false, //MiniMap 不渲染實際字元
  "editor.renderWhitespace": "boundary", //顯示空白字元
  "editor.renderIndentGuides": true, //顯示縮排線
  "editor.wordWrap": "on", //斷行顯示
  "files.autoSave": "onWindowChange", //離開視窗焦點時自動儲存
  "files.autoGuessEncoding": true, //猜測檔案編碼
  "emmet.includeLanguages": {
    "js": "html"
  },
  "prettier.singleQuote": true, //自動單引號
  "window.titleBarStyle": "custom", //VSCode 變得漂亮一點
  "typescript.updateImportsOnFileMove.enabled": "always", //當檔案移動時，自動更新匯入的路徑
  "workbench.iconTheme": "vscode-icons",
  "liveSassCompile.settings.formats": [
    {
      "savePath": "/css"
    }
  ], //sass儲存設定
  "gitlens.views.fileHistory.enabled": true,
  "gitlens.views.lineHistory.enabled": true,
  "tslint.enable": true,
  "tslint.autoFixOnSave": true, //TSLint自動修復
  "git.autofetch": true,
  "git_autoconfig.configList": [
    {
      "user.email": "ruru_lin@gmail.com",
      "user.name": "ruru_lin"
    }
  ],
  "gitlens.views.repositories.files.layout": "tree"
}

```
```json=
{
  'editor.formatOnSave': true,
  'prettier.singleQuote': true,
  'prettier.semi': false,
  'prettier.printWidth': 120,
  'prettier.trailingComma': 'es5',
  'prettier.tabWidth': 4
}
```
`formatOnSave` 儲存時自動格式化
`singleQuote` 使用單引號
`semi` 結束是否加分號
`printWidth` 行寬
`trailingComma` 尾隨逗號
`tabWidth` 縮排空幾格