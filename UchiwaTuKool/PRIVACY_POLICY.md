# プライバシーポリシー / Privacy Policy

**最終更新日 / Last updated: 2026-09-17**

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

### 1-1-4. うちわファイルの取り込み / Importing uchiwa files

本アプリで「開く」またはほかのアプリ・ファイルアプリからうちわファイル（`.uchiwa`）を受け取ると、そのファイルは**利用者の端末内のアプリ管理フォルダ（アプリ内ライブラリ）にコピーして保存**され、アプリ内のギャラリーに表示されます。取り込んだファイルは**端末内でのみ扱われ、当方サーバには送信されません**。取り込みに OS の追加権限は不要です（利用者が「開く」で選ぶ、または OS がアプリに渡したファイルのみを対象とします）。

When you "Open" a uchiwa file (`.uchiwa`), or receive one from another app / the Files app, the file is **copied and stored in the app's managed folder (in-app library) on your device** and shown in the in-app gallery. Imported files are handled **only on your device** and are not sent to our servers. No additional OS permission is required (only files you choose via "Open" or that the OS hands to the app are processed).

### 1-1-5. ライブ前リマインダー（ローカル通知）/ Pre-live reminder (local notification)

本アプリの「ライブ前リマインダー」機能では、利用者が登録した**参戦予定日**とメモを**端末内にのみ保存**し、その日の数日前に「うちわ制作」をうながす**ローカル通知**を出します。通知はすべて**端末内で完結**し、当方サーバや FCM 等の外部サーバには**送信されません**（参戦日・メモが外部へ送られることはありません）。通知を出すには OS の通知許可が必要で、iOS では必須、Android 13 以降では通知権限（`POST_NOTIFICATIONS`）を求めます。許可しなくても日付の登録自体は可能です（通知が出ないだけ）。

The "pre-live reminder" feature stores the **event dates** and notes you register **only on your device** and shows **local notifications** a few days before, prompting you to make your uchiwa. Everything is handled **on-device**; no data (dates/notes) is sent to our servers or any external server such as FCM. Showing notifications requires OS notification permission (required on iOS; on Android 13+ the `POST_NOTIFICATIONS` permission is requested). You can still register dates without granting permission (only the notification will not appear).

### 1-1-6. ライブ日程の取得（カレンダーのゴースト表示）/ Fetching live schedules (calendar ghost overlay)

本アプリのカレンダー画面では、参考情報として当方が公開するライブ日程データ（`shirase-lab.github.io` 上の暗号化 JSON）を**閲覧目的で取得（ダウンロード）のみ**します。取得は一方向の**ダウンロード（GET）**で、**利用者の情報（登録した参戦日・メモ・端末内データ等）を当方サーバや外部へ送信することはありません**。取得したデータは**利用者の端末内にのみキャッシュ**され、一定時間で再取得します。通信できない場合は前回取得分を表示するか、何も表示しません（機能はオフになるだけです）。

On the calendar screen, the app **only downloads (GET)** our published live-schedule data (an encrypted JSON hosted on `shirase-lab.github.io`) for reference. This is a one-way **download**; **none of your information** (registered dates, notes, or on-device data) is sent to our servers or any third party. The fetched data is **cached only on your device** and refreshed periodically. If the network is unavailable, the app shows the last cached data or nothing (the feature simply turns off).

### 1-1-7. アップデート通知（更新情報の取得）/ Update notification (version info fetch)

本アプリは起動時に、公開ページ `https://shirase-lab.github.io/updates/` にある**公開のバージョン情報ファイル（JSON）を読み取り**、新しいバージョンの有無や更新内容を通知します。この通信は**公開ファイルの取得（HTTPS GET）のみ**で、**利用者の個人情報・端末内のうちわデータ・識別子等は送信しません**（当方サーバもありません。配信は GitHub Pages）。取得に失敗（オフライン等）しても通知を出さないだけで、アプリの利用に支障はありません。「アップデート」ボタンを押した場合は、OS のブラウザで各ストアのページを開きます。

At startup the App **reads a public version-information file (JSON)** hosted at `https://shirase-lab.github.io/updates/` to notify you of new versions and what's changed. This is a **read-only public fetch (HTTPS GET)**; **no personal information, on-device uchiwa data, or identifiers are transmitted** (we operate no server; the file is served by GitHub Pages). If the fetch fails (e.g., offline), no notification is shown and the App works normally. Tapping "Update" opens the relevant store page in the OS browser.

### 1-1-8. 配信コンテンツ（テンプレート／スタンプ／ステッカー／フォント）の取得 / Fetching distributed content (templates, stamps, stickers, fonts)

本アプリの配信ギャラリーでは、当方が制作・公開するうちわテンプレート・スタンプ（SVG）・ステッカー（PNG）（`https://shirase-lab.github.io/` 上の公開マニフェスト JSON・各ファイル・サムネ画像）を**閲覧・利用目的で取得（HTTPS GET）のみ**します。3D プレビューの会場背景に映る「他の人のうちわ」も、この公開サムネを取得して描画しています。取得は一方向の**ダウンロード**で、**利用者の個人情報・端末内のうちわデータ・識別子等を送信することはありません**（配信は GitHub Pages）。取得したデータは**利用者の端末内にのみキャッシュ**されます。通信できない場合や配信が無い場合は、一覧が空になるだけで、うちわ作成機能には影響しません。配信コンテンツは投稿型ではなく**当方制作のみ**で、利用者が投稿・アップロードする仕組みはありません。また「おすすめフォント」の**インストール**は、再配布が許諾された書体のフォントファイルを同じ公開場所（`https://shirase-lab.github.io/fonts/`）から**ダウンロードして端末内に保存する**だけで、送信は行いません（インストールしない書体については配布元サイトへのリンクを表示するのみです）。

In the distribution gallery, the App **only fetches (HTTPS GET)** uchiwa templates, stamps (SVG), and stickers (PNG) that we author and publish (public manifest JSON, the files themselves, and thumbnails hosted at `https://shirase-lab.github.io/`) for browsing and use. The "other people's fans" shown in the 3D preview venue background are drawn from these same public thumbnails. This is a one-way **download**; **no personal information, on-device uchiwa data, or identifiers are transmitted** (files are served by GitHub Pages). Fetched data is **cached only on your device**. If the network is unavailable or nothing is published, the list is simply empty and the design tools are unaffected. Distributed content is **author-provided only**; there is no user submission or upload mechanism. The “Install” action for recommended fonts likewise only **downloads** a redistribution-permitted font file from the same public location (`https://shirase-lab.github.io/fonts/`) and stores it on your device; nothing is uploaded (for fonts we do not redistribute, the App merely links to the original site).

### 1-1-9. 印刷データ（PDF）の書き出しとプリントアプリへの受け渡し / Exporting print data (PDF) and handing it to a print app

本アプリの「コンビニ印刷データ作成」「印刷データを共有」で書き出す印刷データ（PDF）は、**端末内でのみ生成**され、当方サーバには送信されません。「印刷データを共有」を選ぶと、**利用者が選んだコンビニのプリントアプリへ、OS のアプリ間受け渡しの仕組みで PDF を渡します**（Android は選択中の「印刷場所」に対応するアプリを名指しで起動、iOS は「○○で開く」から利用者が選択）。受け渡しは**当方サーバを経由しません**。渡した後の PDF の取り扱い（各社サーバへのアップロード、保管期間等）は**受け取り側のプリントアプリの規約・プライバシーポリシーに従います**ので、そちらをご確認ください。なお「印刷場所」「うちわ台紙」の選択内容は**端末内にのみ保存**されます。

The print data (PDF) exported by "Create convenience store print data" / "Share print data" is generated **only on your device** and is not sent to our servers. Choosing "Share print data" hands the PDF to **a convenience store print app of your choice through the OS app-to-app handoff mechanism** (on Android the app matching your selected store is launched by name; on iOS you pick it from the "Open in" menu). The handoff **does not pass through our servers**. Once handed over, how the PDF is handled (upload to that company's servers, retention, etc.) is governed by **the receiving print app's own terms and privacy policy**, which you should review. Your "print location" and "fan mount" selections are stored **only on your device**.

### 1-1-10. 配信スタンプ／ステッカーのダウンロード数の集計 / Download counts for distributed stamps and stickers

配信スタンプ／ステッカーを利用者がダウンロードしたとき、**どの素材が何回ダウンロードされたか**の合計値だけを、Google Firebase Realtime Database 上の公開カウンタ（`dlcounts/<種別>/<素材ID>`）に **+1** します。送信するのは**素材の ID と「+1」という操作のみ**で、**利用者を識別する情報（アカウント・端末 ID・IP に紐づく個人情報等）や、端末内のうちわデータは一切送信しません**。用途は**人気素材の把握（当方の制作の参考）**に限られ、個人単位の分析はできません（誰がダウンロードしたかは記録されない設計です）。通信に失敗しても素材の利用には影響しません（集計されないだけです）。

When you download a distributed stamp or sticker, the App increments a public counter on Google Firebase Realtime Database (`dlcounts/<kind>/<asset ID>`) by **+1** — that is, only the **total number of downloads per asset**. What is transmitted is **only the asset ID and the "+1" operation**; **no information identifying you (account, device ID, personal data tied to an IP, etc.) and none of your on-device uchiwa data are sent**. It is used solely to **see which assets are popular** (to inform what we create next); per-user analysis is not possible, as who downloaded an asset is not recorded by design. If the request fails, it does not affect your use of the asset (the count is simply not recorded).

### 1-1-11. ご要望・ご意見フォーム / Feedback form

設定画面の「ご要望・ご意見」は、**端末の外部ブラウザ**で当方サイト `oshimite.jp/feedback/` の**要望フォーム（Google フォーム）**を開きます（アプリ内ブラウザは使いません＝アプリ自体が入力内容を取得・送信することはありません）。フォームでは、ご要望の本文に加えて、**返信をご希望の方のみ任意でメールアドレス**をご入力いただけます（**入力は任意**で、空欄のままでも送信でき、その場合は匿名のご意見として受け取ります）。メールアドレスは Google アカウントから自動取得するのではなく、**ご自身で入力いただいた場合にのみ**取得します。入力いただいた内容は Google 経由で当方が受け取り、**ご要望への回答およびアプリの改善のためだけに利用**します。ご本人の同意なく第三者へ提供することはありません。保管期間は**対応に必要な期間のみ**とし、不要となった時点で速やかに削除します。削除をご希望の場合は末尾の窓口（`uchiwa.tu.kool@gmail.com`）までご連絡ください。フォームの説明文では、ご要望の本文に個人が特定できる情報（氏名・SNS の ID 等）を書かないようご案内しています。フォームの運用には Google LLC が提供する Google フォームを利用しており、入力内容は同社のサーバーに保存されます。Google フォームでの入力・送信には Google のプライバシーポリシーが適用されます。

The "Feedback" item in Settings opens our feedback form (a Google Form) at `oshimite.jp/feedback/` in your device's **external browser** (not an in-app web view; the App itself neither collects nor transmits what you enter). In addition to your message, you may **optionally provide an email address if you would like a reply**. Providing it is **entirely optional** — you can submit the form with the field left blank, in which case we receive your feedback anonymously. The email address is not taken automatically from your Google account; we receive it **only if you type it in yourself**. We receive your submission via Google and use it **solely to reply to your feedback and to improve the App**. We do not provide it to third parties without your consent. We retain it **only for as long as needed to handle your feedback** and delete it promptly once it is no longer needed. To request deletion, contact us at the address listed at the end of this policy (`uchiwa.tu.kool@gmail.com`). The form asks you not to enter personally identifying information (name, social media IDs, etc.) in the message body. The form is operated using Google Forms provided by Google LLC, and your input is stored on their servers. Google's privacy policy applies to the input and submission on Google Forms.

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
- お寄せいただいたご要望・ご意見への回答（任意でメールアドレスをご入力いただいた場合のみ）

Ad delivery and optimization, fraud detection, stability improvement, feature development, statistical analytics, and replying to feedback (only when you optionally provide an email address).

---

## 3. 第三者サービスへの提供 / Third-Party Services

本アプリは以下の第三者サービスを利用し、情報の一部を共有します。各サービスのプライバシーポリシーは各社のページをご参照ください。

The App uses the following third-party services. Refer to each provider's policy for details.

| サービス / Service | 用途 / Purpose | プライバシーポリシー |
|---|---|---|
| Google AdMob | 広告配信 / Ad serving（**メディエーション**経由で下記 3-2 の広告ネットワークへも配信を委託） | https://policies.google.com/privacy |
| Google Firebase (Analytics / Crashlytics / Remote Config / Realtime Database) | 分析・クラッシュ収集・構成配信・配信素材のダウンロード数集計（[1-1-10](#1-1-10-配信スタンプステッカーのダウンロード数の集計--download-counts-for-distributed-stamps-and-stickers)） | https://firebase.google.com/support/privacy |
| Google Play Billing | Android 課金処理 | https://policies.google.com/privacy |
| Apple App Store / StoreKit | iOS 課金処理 | https://www.apple.com/legal/privacy/ |
| Google フォーム / Google Forms | ご要望・ご意見フォーム（本文＋**任意**のメールアドレス・[1-1-11](#1-1-11-ご要望ご意見フォーム--feedback-form)） | https://policies.google.com/privacy |

これら以外の第三者には、法令に基づく場合を除き、個人を特定できる情報を提供しません。

We do not provide personally identifiable information to other third parties except as required by law.

### 3-1. オンデバイス画像処理（背景の自動切り抜き）/ On-device image processing (auto background removal)

「画像の背景を自動で切り抜く」機能は、**端末内（オンデバイス）の機械学習フレームワーク**で処理します。Android では Google ML Kit（被写体セグメンテーション）、iOS では Apple Vision を使用します。**処理する画像は端末内で完結し、当方サーバや Google / Apple のサーバへ送信されません**（ML Kit は被写体抽出用のモデルを端末へダウンロードして利用しますが、利用者の画像がアップロードされることはありません）。

The automatic background-removal feature runs **entirely on-device** using on-device machine-learning frameworks: Google ML Kit (Subject Segmentation) on Android and Apple Vision on iOS. **The images you process stay on your device and are not sent to our servers or to Google/Apple** (ML Kit downloads the segmentation model to the device, but your images are never uploaded).

### 3-2. 広告メディエーションのパートナー / Ad mediation partners

本アプリの広告は Google AdMob の**メディエーション**を利用しており、AdMob が下記の広告ネットワークにも広告枠を割り当てます。広告が表示される際、各ネットワークに対して**広告 ID（AAID / IDFA。利用者が許可した場合のみ）・端末情報・おおよその地域・同意状態**が共有されることがあります。取扱いは各社のプライバシーポリシーに従います。**同意しない場合、パーソナライズ広告は各社でも配信されません**（同意状態は Google UMP 経由で各社へ伝達されます）。

Ads in the App are served through Google AdMob **mediation**. AdMob may allocate ad requests to the ad networks listed below. When an ad is served, these networks may receive your **advertising ID (AAID / IDFA, only where you consented), device information, coarse location, and consent state**. Their handling is governed by each provider's privacy policy. **Without consent, personalized ads are not served by these networks either** (the consent state is forwarded to them via Google UMP.)

| 広告ネットワーク / Ad network | プライバシーポリシー |
|---|---|
| LINEヤフー広告ネットワーク (FIVE) / LY Corporation | https://www.lycorp.co.jp/ja/company/privacypolicy/ |
| Unity Ads | https://unity.com/legal/game-player-and-app-user-privacy-policy |
| Pangle | https://www.pangleglobal.com/privacy |
| Meta Audience Network | https://www.facebook.com/about/privacy/ |
| Liftoff Monetize (旧 Vungle) | https://liftoff.io/privacy-policy |
| ironSource | https://www.is.com/privacy-policy/ |
| Mintegral | https://www.mintegral.com/en/privacy/ |
| maio（2020-12 に i-mobile Ad Network へ統合・運営は i-mobile） | https://www.i-mobile.co.jp/privacy.html |
| i-mobile | https://www.i-mobile.co.jp/privacy.html |
| Zucks（**Android 版のみ**） | https://zucks.co.jp/privacy/ |

※ Zucks は **Android 版でのみ**利用します（iOS 版は現時点で対応アダプタが無いため未使用）。

Zucks is used **on Android only** (no compatible adapter is available for the iOS build at this time).

AdMob が利用する広告パートナーの一覧は Google のページ（https://support.google.com/admob/answer/9012903 ）でも公開されています。

---

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
| ウェブサイト / Website | https://oshimite.jp |
| お問い合わせ / Contact | uchiwa.tu.kool@gmail.com |

---

*This policy is provided in both Japanese and English. In case of any inconsistency, the Japanese version shall prevail.*
