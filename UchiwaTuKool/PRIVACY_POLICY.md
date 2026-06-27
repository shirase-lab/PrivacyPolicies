# プライバシーポリシー / Privacy Policy

**最終更新日 / Last updated: 2026-06-27**

Shirase Lab（以下「当方」）は、モバイルアプリケーション「推しミテ！」（以下「本アプリ」）における利用者情報の取扱いについて、本プライバシーポリシー（以下「本ポリシー」）を定めます。

Shirase Lab ("we", "us") provides this Privacy Policy describing how we handle information in the mobile application "推しミテ！" (Oshimite!) (the "App").

---

## 1. 取得する情報 / Information We Collect

本アプリは、サービス提供および改善のため次の情報を取得することがあります。

We may collect the following information for service operation and improvement:

### 1-1. 利用者が直接入力・作成した情報 / User-provided content
- うちわデザインデータ（テキスト本文、画像、レイアウト等）
- アプリ設定情報

これらは利用者の端末内にのみ保存され、当方サーバには送信されません。

User-created content is stored locally on the device and is **not transmitted to our servers**.

### 1-1-2. 制作タイムラプス動画 / Timelapse video

本アプリの「録画（タイムラプス）」機能で生成される制作過程の動画（MP4）は、**端末内でのみ生成・保存**され、当方サーバには送信されません。動画を SNS 等で共有する場合は、**OS の共有シートを通じて利用者自身が送信先を選ぶ**もので、当方サーバを経由しません。動画を端末の写真ライブラリへ保存する際は、OS の写真追加権限を求めます。

The timelapse video (MP4) created by the in-app recording feature is generated and stored **only on your device** and is not sent to our servers. Sharing is performed via the OS share sheet at your own choice (not through our servers). Saving to the device photo library requests the OS add-to-photos permission.

### 1-1-3. うちわ画像の保存 / Saving the uchiwa image

本アプリの「画像を保存」機能で書き出すうちわの画像（PNG）は、**端末内でのみ生成**され、当方サーバには送信されません。画像を端末の写真ライブラリ（iOS の写真／Android のギャラリー）へ保存する際は、OS の写真追加権限を求めます。権限が無い場合や非対応環境では、OS の共有シートを通じて利用者自身が保存先を選びます。

The uchiwa image (PNG) exported by the in-app "Save image" feature is generated **only on your device** and is not sent to our servers. Saving to the device photo library (iOS Photos / Android Gallery) requests the OS add-to-photos permission. If the permission is unavailable or unsupported, you choose the destination yourself via the OS share sheet.

### 1-2. 自動的に取得される情報 / Automatically collected
- 広告 ID (Android: AAID / iOS: IDFA。利用者が許可した場合のみ)
- アプリ内行動ログ（画面遷移、機能利用頻度等の集計値）
- クラッシュレポート（端末モデル、OS バージョン、スタックトレース）
- 言語・タイムゾーン等の端末設定

Advertising IDs (where consented), in-app behavior logs, crash reports, and device/locale metadata.

---

## 2. 利用目的 / Purpose of Use

- 広告の配信および最適化
- 不正アクセス・不正課金の検知
- アプリの安定性向上およびバグ修正
- 新機能の検討・改善
- 利用状況の統計的分析

Ad delivery and optimization, fraud detection, stability improvement, feature development, and statistical analytics.

---

## 3. 第三者サービスへの提供 / Third-Party Services

本アプリは以下の第三者サービスを利用し、情報の一部を共有します。各サービスのプライバシーポリシーは各社のページをご参照ください。

The App uses the following third-party services. Refer to each provider's policy for details.

| サービス / Service | 用途 / Purpose | プライバシーポリシー |
|---|---|---|
| Google AdMob | 広告配信 / Ad serving | https://policies.google.com/privacy |
| Google Firebase (Analytics / Crashlytics / Remote Config) | 分析・クラッシュ収集・構成配信 | https://firebase.google.com/support/privacy |
| Google Play Billing | Android 課金処理 | https://policies.google.com/privacy |
| Apple App Store / StoreKit | iOS 課金処理 | https://www.apple.com/legal/privacy/ |

これら以外の第三者には、法令に基づく場合を除き、個人を特定できる情報を提供しません。

We do not provide personally identifiable information to other third parties except as required by law.

### 3-1. オンデバイス画像処理（背景の自動切り抜き）/ On-device image processing (auto background removal)

「画像の背景を自動で切り抜く」機能は、**端末内（オンデバイス）の機械学習フレームワーク**で処理します。Android では Google ML Kit（被写体セグメンテーション）、iOS では Apple Vision を使用します。**処理する画像は端末内で完結し、当方サーバや Google / Apple のサーバへ送信されません**（ML Kit は被写体抽出用のモデルを端末へダウンロードして利用しますが、利用者の画像がアップロードされることはありません）。

The automatic background-removal feature runs **entirely on-device** using on-device machine-learning frameworks: Google ML Kit (Subject Segmentation) on Android and Apple Vision on iOS. **The images you process stay on your device and are not sent to our servers or to Google/Apple** (ML Kit downloads the segmentation model to the device, but your images are never uploaded).

---

## 4. 同意の取得 / Consent

- **EU/UK/EEA・カリフォルニア州在住の利用者**: 初回起動時に Google UMP (User Messaging Platform) による同意ダイアログを表示します。同意がない限り、パーソナライズ広告は配信されません。
- **iOS 利用者**: 端末横断の追跡 (ATT) について、初回起動時にシステムダイアログで許可を求めます。拒否された場合、追跡を伴う広告 ID は使用しません。

Users in the EU/UK/EEA and California will be shown a UMP consent dialog. iOS users will be prompted via App Tracking Transparency. Personalized ads will not be served without consent.

---

## 5. 課金情報の取扱い / Purchases

「広告を消す」等の課金は、Google Play / Apple App Store の決済システムを通じて行われます。当方はクレジットカード番号等の決済情報を**取得・保持しません**。購入レシートは、課金の有効性確認のため Google / Apple のサーバまたは当方サーバ（Firebase Functions）で検証される場合があります。

In-app purchases are processed by Google Play / Apple App Store. We do **not** receive or store payment card details. Purchase receipts may be validated via Google/Apple APIs or our Firebase Functions.

---

## 6. 情報の保管期間 / Retention

- 利用者端末内のデザインデータ: アプリをアンインストールするまで
- 分析・クラッシュデータ: Firebase の既定保持期間（最大 14 ヶ月）
- 課金検証ログ: 法令上必要な期間

Local design data persists until uninstall. Analytics/crash data is retained per Firebase defaults (up to 14 months). Purchase logs are retained as legally required.

---

## 7. 利用者の権利 / Your Rights

利用者は、当方が取得した情報について以下の権利を有します:
- 開示請求 / Access
- 訂正・削除請求 / Correction or deletion
- 利用停止請求 / Opt-out of processing
- データポータビリティ / Data portability (GDPR 該当時)

請求は下記連絡先までお願いします。本人確認後、合理的な期間内に対応します。

To exercise these rights, contact us using the information below.

---

## 8. 児童に関する事項 / Children

本アプリは 13 歳未満の児童を対象としていません。13 歳未満であることを認識した場合、該当情報を速やかに削除します。

The App is not directed to children under 13. We will delete any information we discover to belong to a child under 13.

---

## 9. セキュリティ / Security

当方は、業界標準の合理的な技術的・組織的措置により情報の保護に努めますが、インターネット通信および電子的保存の完全な安全性を保証するものではありません。

We use reasonable technical and organizational measures, but no method of internet transmission or electronic storage is 100% secure.

---

## 10. 本ポリシーの変更 / Changes to This Policy

本ポリシーは予告なく変更される場合があります。重要な変更を行う場合は、アプリ内通知またはストア掲載情報を通じて告知します。

We may update this policy. Material changes will be announced in-app or on the store listing.

---

## 11. 連絡先 / Contact

| | |
|---|---|
| 運営者 / Operator | Shirase Lab |
| ウェブサイト / Website | https://x.com/oshimite_app |
| お問い合わせ / Contact | https://x.com/oshimite_app |

---

*This policy is provided in both Japanese and English. In case of any inconsistency, the Japanese version shall prevail.*
