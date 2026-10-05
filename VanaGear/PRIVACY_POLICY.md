# プライバシーポリシー / Privacy Policy

**最終更新日 / Last updated: 2026-10-05**

Shirase Lab（以下「当方」）は、モバイルアプリケーション「ヴァナギア」（Android パッケージ名: `com.shiraselab.vana_gear` / iOS バンドル ID: `com.shiraselab.vana-gear`、以下「本アプリ」）における利用者情報の取扱いについて、本プライバシーポリシー（以下「本ポリシー」）を定めます。本アプリはファイナルファンタジーXI（FFXI）の装備管理・ダメージ計算などを支援する非公式のファンツールであり、株式会社スクウェア・エニックスとは一切関係ありません。

Shirase Lab ("we", "us") provides this Privacy Policy describing how we handle information in the mobile application "VanaGear" (Android package name: `com.shiraselab.vana_gear`; iOS bundle ID: `com.shiraselab.vana-gear`, the "App"). The App is an unofficial fan tool for gear management and damage calculation for FINAL FANTASY XI (FFXI) and is not affiliated with SQUARE ENIX.

---

## 1. 取得する情報 / Information We Collect

### 1-1. 端末内に保存される情報 / Data stored on your device
装備セット、所持品、プレイヤー／ジョブ設定、アプリ設定などは、原則としてお使いの端末内にのみ保存され、外部送信されません。バックアップ機能を使う場合、利用者ご自身の操作でこれらをファイルとして書き出し・読み込みできます。

Gear sets, inventory, player/job settings and app preferences are stored only on your device and are not transmitted externally. With the backup feature, you can export/import this data as files yourself.

### 1-2. アカウント情報 / Account information (Firebase Authentication)
「みんなの装備」（共有機能）のため、匿名認証、Google サインイン、または Sign in with Apple（iOS 版のみ）を行います。当方はユーザーを識別する**識別子（UID）**を利用します。Google サインイン利用時は認証が Google／Firebase により、Sign in with Apple 利用時は Apple／Firebase により処理され、メールアドレスが認証基盤に送信されます。Sign in with Apple では「メールアドレスを非公開」を選択でき、その場合は Apple の転送用アドレスが使われます。**当方は利用者の氏名を保存しません。**

ログインしたアカウントは、本アプリ内の「設定」からいつでも削除できます。

For the "Community Gear" feature, the App uses anonymous authentication, Google Sign-In, or Sign in with Apple (iOS only). We use a **user identifier (UID)**. Google Sign-In is handled by Google/Firebase and Sign in with Apple by Apple/Firebase; your email address is transmitted to the authentication backend. Sign in with Apple lets you choose "Hide My Email", in which case Apple's private relay address is used. **We do not store your name.**

You can delete your account at any time from Settings in the App.

### 1-3. みんなの装備（公開データ）/ Community Gear (public data)
利用者が投稿した場合、以下がサーバー（Google Cloud Firestore）に保存され、**他の利用者に公開表示**されます。氏名・メールアドレスは含まれません。
- ジョブ、セット名、装備の構成、タグ、投稿日時、投稿者の匿名識別子（UID）

When you post, the following is stored on the server (Google Cloud Firestore) and is **publicly visible to other users**. Your name and email are not included:
- Job, set name, gear configuration, tags, timestamp, and an anonymous poster ID (UID).

### 1-4. 広告 / Advertising (Google AdMob)
広告配信のため、**広告識別子（Advertising ID）や端末情報**が Google および広告パートナーにより取得・利用されることがあります。本アプリは Google AdMob の**メディエーション**を利用しており、AdMob が「3-1. 広告メディエーションのパートナー」記載の広告ネットワークにも広告枠を割り当てます（各社に広告 ID・端末情報・おおよその地域が共有されることがあります）。

For ad delivery, the **advertising ID** and device information may be collected and used by Google and its advertising partners. The App uses Google AdMob **mediation**, which may allocate ad requests to the ad networks listed in "3-1. Ad mediation partners" (your advertising ID, device information, and coarse location may be shared with them).

### 1-5. アプリ内購入 / In-app purchases (Google Play Billing / App Store)
寄付・広告除去の購入は **Google Play（Android）または App Store（iOS）が決済を処理**し、当方はクレジットカード等の決済情報を取得・保持しません。

Donations and the ad-removal purchase are **processed by Google Play (Android) or the App Store (iOS)**; we do not collect or store payment details.

### 1-6. アプリ設定の取得 / App configuration (Firebase Remote Config)
アプリ動作設定値の取得に Firebase Remote Config を利用します。個人を特定する情報は含まれません。

Firebase Remote Config is used to fetch configuration values and contains no personally identifiable information.

---

## 2. 利用目的 / Purposes
- 本アプリの機能提供（装備の管理・共有、ダメージ計算）
- アカウントの認証・管理
- 広告の表示（AdMob）
- 不具合対応・品質改善

- Providing app features (gear management/sharing, damage calculation)
- Authentication and account management
- Showing ads (AdMob)
- Troubleshooting and quality improvement

---

## 3. 第三者提供・外部送信 / Third Parties
本アプリは以下のサービスを利用します。各社の取扱いは各社のポリシーに従います。
The App uses the following services, governed by their respective policies:
- Firebase Authentication / Cloud Firestore / Remote Config — https://firebase.google.com/support/privacy
- Google AdMob（**メディエーション**経由で下記「3-1」の広告ネットワークへも配信を委託）— https://policies.google.com/technologies/ads
- Google Play Billing（Android）— https://policies.google.com/privacy
- Sign in with Apple / App Store 課金（iOS）— https://www.apple.com/legal/privacy/

広告ID以外の利用者データを、当方が第三者に販売・提供することはありません。
We do not sell or share user data (other than the advertising ID used for ads) with third parties.

### 3-1. 広告メディエーションのパートナー / Ad mediation partners

本アプリの広告は Google AdMob の**メディエーション**を利用しており、AdMob が下記の広告ネットワークにも広告枠を割り当てます。広告が表示される際、各ネットワークに対して**広告 ID（AAID。利用者が端末設定で許可した場合のみ）・端末情報・おおよその地域**が共有されることがあります。取扱いは各社のプライバシーポリシーに従います。パーソナライズ広告のオプトアウトは「4. 広告のオプトアウト」をご覧ください。

Ads in the App are served through Google AdMob **mediation**. AdMob may allocate ad requests to the ad networks listed below. When an ad is served, these networks may receive your **advertising ID (AAID, only where you allowed it in device settings), device information, and coarse location**. Their handling is governed by each provider's privacy policy. To opt out of personalized ads, see "4. Opting Out of Personalized Ads".

| 広告ネットワーク / Ad network | プライバシーポリシー / Privacy policy |
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

AdMob が利用する広告パートナーの一覧は Google のページ（https://support.google.com/admob/answer/9012903 ）でも公開されています。
The list of ad partners used by AdMob is also published by Google (https://support.google.com/admob/answer/9012903 ).

---

## 4. 広告のオプトアウト / Opting Out of Personalized Ads
パーソナライズ広告は端末設定で無効化できます。
- **Android**: 設定 → Google → 広告 → 「広告のパーソナライズをオプトアウト」。同画面で広告IDのリセットも可能です。
- **iOS**: 設定 → プライバシーとセキュリティ → トラッキング でアプリのトラッキング要求を拒否できます。設定 → プライバシーとセキュリティ → Apple の広告 でパーソナライズ広告を無効化できます。

You can disable personalized ads in device settings.
- **Android**: Settings → Google → Ads → "Opt out of Ads Personalization"; you can also reset your advertising ID there.
- **iOS**: Settings → Privacy & Security → Tracking to deny app tracking requests, and Settings → Privacy & Security → Apple Advertising to turn off personalized ads.

---

## 5. 保存期間と削除 / Retention and Deletion
- 端末内データ：本アプリのアンインストールで削除されます。
- みんなの装備の投稿：アプリ内でいつでも自分の投稿を削除できます。
- アカウントの削除：本アプリ内の「設定」からいつでも削除できます。詳細は[アカウント・データ削除の手引き](./ACCOUNT_DELETION.md)をご覧ください。
- その他、全データの削除：上記の手引きに沿ってご連絡ください（リクエストから30日以内に削除）。

- On-device data: removed when you uninstall the App.
- Community Gear posts: you can delete your own posts anytime in the App.
- Account deletion: you can delete your account anytime from Settings in the App. See [Account & Data Deletion](./ACCOUNT_DELETION.md).
- Full data deletion: contact us as described in that guide (deleted within 30 days of request).

---

## 6. 対象年齢 / Children
本アプリは13歳未満の子どもを対象としていません。
The App is not directed to children under 13.

---

## 7. 安全管理 / Security
当方は取得した情報の安全管理のために必要かつ適切な措置を講じます。なお「みんなの装備」への投稿は、その性質上、公開されます。

We take reasonable measures to protect information. Note that posts to "Community Gear" are public by nature.

---

## 8. 本ポリシーの変更 / Changes
本ポリシーは必要に応じて変更されることがあります。重要な変更は本ページで告知します。
We may update this Policy; significant changes will be posted here.

---

## 9. お問い合わせ / Contact
- 提供者 / Provider: Shirase Lab
- 連絡先 / Contact: shirase.develop@gmail.com
