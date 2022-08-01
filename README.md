# slack_emoji_usability
オンラインでユーザビリティ評価をする時に便利そうなSlack絵文字集です。

プロダクトを評価していて指摘や仮説がSlackに書き込まれた時に、それにフィードバックする場面を想定して、分類や重要度ラベルとして使えそうなものをラインナップしてみました。

![Sample](https://user-images.githubusercontent.com/946147/80343961-bff77800-88a1-11ea-8ece-4fee59b58e7d.png)

「視認性」があえて視認性低いカラーにしてあったりしますが、ガチで見辛いとかあれば直していきます。白バックと黒バックの両方で視認性を担保するのは難しいですね。「要件、構造、骨格、表層」とかグループになるものの色を揃えたりとかもやりかけましたが心が折れました...現状、かなりテキトーです。
でも要望やプルリクは歓迎です。

あと下記一括アップロード方法だとファイル名はそのまま絵文字ショートコードになるので、タイプしやすい名前を設定しています。例えば「構造」がkouzou.pngなのは私がstructureを綴れなかったせいではありませんよ！「フロー」はfuroだけど「ユースケース」はusecaseなんです。まぁ好きに変えてお使いください。

# 使い方
- 緑の「Clone or Download」ボタンからzipを取得していただき、展開してpng画像群を取り出します（README.mdはこの文章ファイルなので捨ててください）。
- お使いになりたいものを選別してSlackに登録（当該ワークスペースにおけるカスタム絵文字登録権限が必要です。「絵文字を追加する」ボタンが出現しない時は管理者にお問い合わせください）。
- 下記のアップローダーを使うと一括登録できて便利です。

# 活用させていただいたツール
## 1. 絵文字ジェネレーター
https://emoji-gen.ninja/
「生成履歴に絵文字を表示する」のチェックを外しておけばサイトの公開履歴には残りません。

## 2. 絵文字を一括でアップロードする
https://chrome.google.com/webstore/detail/neutral-face-emoji-tools/anchoacphlfbdomdlomnbbfhcmcdmjej
Chromeのこちらのプラグインを使わせていただいています。最低1つはカスタム絵文字が登録済みでないと機能しないようです。
- 最低1つは手動でカスタム絵文字を登録
- このプラグインを導入したブラウザで、ワークスペースにアクセスする
- 絵文字追加ページに行く
-- https://(ワークスペースID).slack.com/customize/emoji を開くのが簡単
- プラグインが表示するドラッグ＆ドロップ枠にFinder/Explorerからアイコン群を一括ドロップ
- エラーが出たらファイル名などを修正
- 絵文字名称はファイル名がそのまま使われる模様



