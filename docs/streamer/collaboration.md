# コラボレータガイド

## コラボレータについて

**コラボレータ**は、この配信内で配信者さんに招待されたユーザが**コメント管理**や**配信に参加**することのできる権限です。
何をして良いかは配信者さんから聞いてください。

<Note type="warning">

コラボレータは KnzkLive の配信権限を持っていなくても、一時的に配信をする事のできるようになる権限です。配信者さんは、信頼できる人のみを追加してください。

</Note>

## コメント管理

[モデレーションガイド](moderation.md) をお読みください。

## コラボ配信

#### 1. (コラボ配信用)配信枠を取得する

まず、コラボレータは対象の配信で下記のようなパネルが表示されています。この **配信に参加** をクリックしてください。

<ImageZoom
  url="https://i.imgur.com/a4fxxn9.png"
  :border="false"
/>

そうすれば、また次のようなポップアップが表示されます。利用規約に同意して、 **コラボ配信に参加** をクリックしてください。

<ImageZoom
  url="https://i.imgur.com/MoQKPHK.png"
  :border="false"
/>

そうすると、ダイアログが表示されます。OK を押すとページが再読み込みされますので、もう一度 **配信に参加** をクリックしてください。

#### 2. 配信クライアントに設定する

次に、配信枠が取得できていれば配信サーバ情報が表示されますので、配信クライアントに設定してください。

<ImageZoom
  url="https://i.imgur.com/lZHsY90.png"
  :border="false"
/>

##### OBS の場合の設定

<ImageZoom
  url="https://i.imgur.com/uUHkEWh.png"
  :border="false"
/>

設定 > 配信より、

- 配信識別: **カスタムストリーミングサーバー**
- URL: KnzkLive 配信サーバ情報の、**URL**
- ストリームキー: KnzkLive 配信サーバ情報の、**ストリームキー**

を入力して、適用をクリックしてください。

##### xSplit の場合の設定

準備中

#### 3. 配信する

Enjoy!

#### 4. 配信を終了する

次のいずれかの状態になると、あなたの配信クライアントは切断され、自動的にリスナー全員からあなたの配信を表示するプレイヤーが非表示になります。

- あなたがクライアント側で配信停止をした場合。
- 配信主が配信終了をした場合。
- 配信主があなたのコラボレータ権限を剥奪した場合。
