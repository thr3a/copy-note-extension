# 特徴

- Chrome Extension Manifest V3対応
- [esbuild](https://esbuild.github.io/)による超高速ビルド
- TypeScriptとReact(TSX)対応
- [webextension-polyfill](https://github.com/mozilla/webextension-polyfill)採用
- [web-ext](https://github.com/mozilla/web-ext)による自動拡張機能更新
- [Mantine](https://mantine.dev/)によるUIフレームワーク


note.comのコンテンツをテキストでワンクリックでクリップボードにコピーするChrome拡張機能を作成したい
ex. https://note.com/prettyfish/n/nd24b93813c85
Chromeのアクションボタンのアイコンをクリックしたらpopup.htmlが表示され、
その中の「コピー」ボタンをクリックしたときのカレントタブのnoteサイトのコンテンツをクリップボードにコピーする
note.comのhtml構成は ./note.html を参考にすること。divのdata-name=bodyがいいかな
pタグなどHTMLを含まないようにする。imgタグは丸ごと削除
popup.htmlはmantine+react構成　既存コードを参考にしろ
