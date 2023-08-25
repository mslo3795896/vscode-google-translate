![Demo](demo.gif)

## Usage

### Translate selected text

1. Select some text to translate
1. Press `ALT+SHIFT+T`
1. Select the output languages you want and enjoy 👍

### Translate a line under cursor

This feature inserts a newline under the current one with translation

1. Set cursor/cursors on line(s) to translate
1. Select menu 'Translate line(s) under the cursor'
1. Select the output languages you want and enjoy

## Preferred language settings

Want to quickly translate into a specific language?
Run Command 'Set Preferred Language' or Set it in VSCode extension settings

## Tooltip Hover Translation

By default when you hover over comments and code, you will get a translation into
your preferred language hovering above the element. If you want to turn this off
go into extension settings and un-check HoverTranslations then restart VSCode.

## Proxy Support

You can use a proxy to translate text with the following settings:

```js
"vscodeGoogleTranslate.host": "120.0.0.1"       // Proxy disabled if empty
"vscodeGoogleTranslate.port": "8080"            // Proxy port
"vscodeGoogleTranslate.username": "admin"       // Proxy auth disabled if empty
"vscodeGoogleTranslate.password": "password"    // Proxy password
```

## Development
```js
// 安裝
npm i

// 開發測試
fn + F5
```

## How to share extension
```js
// 安装对应的模块vsce
npm i @vscode/vsce -g

// 利用vsce进行打包，生成对应的vsix文件
vsce package
```
將產生於專案目錄下的 .vsix 檔案傳給別人
![從 VSIX 安裝...](https://segmentfault.com/img/remote/1460000040720766)
