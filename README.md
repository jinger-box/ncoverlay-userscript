# NCOverlay ユーザースクリプト版（Safari + Userscripts）

動画配信サービス（ABEMA・Prime Video など）の再生画面に、ニコニコのコメントを流すユーザースクリプトです。
[Midra](https://github.com/Midra429) 氏のブラウザ拡張機能 [NCOverlay](https://github.com/Midra429/NCOverlay)（MIT ライセンス）を、
Safari の [Userscripts](https://apps.apple.com/app/userscripts/id1463298887) アプリで動くように作り替えた**個人用の改造版**です。

- 不具合や要望を、元の NCOverlay の作者に問い合わせないでください
- 動作を確かめているのは、iPhone・iPad・Mac の Safari で見る ABEMA と Prime Video です。ほかのサービスは確かめていません

## 入れ方

1. App Store から [Userscripts](https://apps.apple.com/app/userscripts/id1463298887) を入れ、Safari の機能拡張で有効にする（動画サイトへのアクセスを許可する）
2. Safari で次の 2 つを順に開き、それぞれ Userscripts のボタンを押してインストールする（2 つとも必要）
   - 本体: https://raw.githubusercontent.com/jinger-box/ncoverlay-userscript/main/ncoverlay.user.js
   - ページ側: https://raw.githubusercontent.com/jinger-box/ncoverlay-userscript/main/ncoverlay-page.user.js
3. 動画のページで画面に触れる（マウスを動かす）と、右端に「NCO」ボタンが出ます

新しい版は、Userscripts がこのリポジトリを見て更新します。

## ライセンス

MIT（[LICENSE](LICENSE)）。元の NCOverlay の著作権表示を含みます。
