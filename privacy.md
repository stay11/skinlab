# プライバシーポリシー

最終更新日: 2026年10月4日

ナチュラル美肌（以下「本アプリ」）における情報の取り扱いについて説明します。
**写真も動画も端末の中だけで処理され、外部へ送信されることはありません。**

## 開発者が収集する情報

ありません。

開発者は、氏名、メールアドレス、電話番号、位置情報、写真、利用状況などを集めるサーバーを持っていません。
アカウント登録もありません。

## 外部との通信

本アプリが外部と通信するのは、広告を表示するためだけです（次の「広告について」）。
写真・動画・顔のデータが広告のために送られることはありません。

- 利用状況の解析（アナリティクス）を行う仕組みは組み込んでいません
- 加工・撮影・保存は、通信できない状態（機内モードなど）でもすべて使えます

## 広告について

バージョン 1.2 から、ホーム・設定・ミラー・編集画面のツールの一覧・保存したあとの画面に、Google LLC の広告配信サービス「AdMob」による広告を表示します。
ツールで調整している間と、撮影中の画面には表示しません。初めて保存し終えるまでは表示しません。

AdMob は、広告の表示や効果の測定のために、端末に関する情報（IPアドレス、広告用の識別子など）や、
広告の表示・操作の記録を収集することがあります。これらの扱いは Google のポリシーに従います。

- [Google のプライバシーポリシー](https://policies.google.com/privacy)
- [Google のサービスを使用するサイトやアプリから収集した情報の Google による使用](https://policies.google.com/technologies/partner-sites)

本アプリは、端末の広告識別子を使う許可（App Tracking Transparency）を求めていません。

## 写真・動画・カメラ・マイク

- **写真**: 加工のために利用者が選んだ写真だけをアプリが受け取ります。
  加工した結果は、利用者が保存を選んだときだけ写真ライブラリに保存されます。
- **カメラ**: 撮影のときだけ使います。映像は端末内で処理され、保存前に外部へ出ることはありません。
- **マイク**: 動画モードにしたときだけ使い、録画した音声は動画ファイルの中にのみ入ります。
- 「最近編集した写真」は端末内のアプリ領域に保存されます。
  アプリを削除すると一緒に消えます。

## 顔データ（Face Data）

このアプリは、写真や映像の中で**顔がどこにあるか**を調べるために、Apple の Vision
フレームワーク（`VNDetectFaceLandmarksRequest`）を利用します。得られるのは、
顔の外接矩形と、輪郭・目・眉・鼻・唇・瞳の**位置を表す座標の並び**だけです。
肌をなめらかにする範囲や、メイクを乗せる位置を決めるために使います。

- **収集しません。** 座標は処理のあいだ端末のメモリ上にあるだけで、
  ファイルにも設定にも書き出しません。処理が終わると同時に破棄されます。
- **保存しません。** アプリが端末内に残すのは「最近編集した写真」の
  元画像・サムネイル・加工の設定値（数値）だけで、顔の座標は含まれません。
- **送信しません。** 顔の座標を端末の外へ送ることはありません。本アプリの通信は広告の表示のためだけで、
  写真や顔のデータは含まれません。したがって第三者へ渡ることもありません。
- **個人の識別には使いません。** 顔を見分ける・照合する・特徴量（テンプレート）を
  作るといった処理は行いません。同じ人物かどうかを判定する仕組みもありません。
- **保持期間はありません。** 保存していないため、削除の対象になるものもありません。
  アプリを削除すれば、「最近編集した写真」も一緒に消えます。

## Face Data (English)

This app uses Apple's Vision framework (`VNDetectFaceLandmarksRequest`) solely to
locate where a face is within a photo or video frame. The only values produced are a
face bounding box and coordinate arrays for the face contour, eyes, eyebrows, nose,
lips and pupils. They are used to decide which pixels to smooth and where to place
makeup.

- **Not collected.** The coordinates exist only in device memory while a frame is being
  processed, and are discarded as soon as processing finishes. They are never written
  to a file or to app settings.
- **Not stored.** The only things the app keeps on device are the source image,
  a thumbnail and the numeric editing settings for "recently edited photos".
  No face coordinates are included.
- **Not shared or transmitted.** Face data never leaves the device. The app's only network
  traffic is for displaying ads (Google AdMob), which never includes photos or face data,
  so face data cannot reach us or any third party.
- **Not used for identification.** The app does not recognise, match, or build a
  template or faceprint for any person, and has no ability to tell whether two
  photos show the same person.
- **No retention period.** Nothing is retained, so there is nothing to delete.
  Deleting the app also removes the "recently edited photos".

## 第三者への提供

開発者が収集する情報はないため、提供するものはありません。
広告の表示のために AdMob が収集する情報については、上の「広告について」をご覧ください。

## お問い合わせ

<atosaki.app@icloud.com>
