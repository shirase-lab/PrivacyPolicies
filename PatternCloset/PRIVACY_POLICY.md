# プライバシーポリシー（パタクロ！） / Privacy Policy (Pattern Closet) / 隱私權政策（Pattern Closet） / 개인정보 처리방침（Pattern Closet）

**最終更新日 / Last updated / 最後更新 / 최종 수정일: 2026-10-21**

本書は日本語版を正本とし、英語・中国語・韓国語版は参考訳です。内容に相違がある場合は日本語版が優先します。

This document is governed by its Japanese version; the English, Chinese and Korean versions are reference translations. In case of any discrepancy, the Japanese version prevails.

本文件以日文版為正本，英文、中文及韓文版均為參考譯文。各版本內容如有歧異，以日文版為準。

본 문서는 일본어판을 정본으로 하며, 영어·중국어·한국어판은 참고용 번역본입니다. 내용에 차이가 있는 경우 일본어판이 우선합니다.

Shirase Lab（以下「当方」）は、モバイルアプリケーション「パタクロ！」（Android パッケージ名・iOS バンドル ID: `com.shiraselab.patterncloset`、以下「本アプリ」）における利用者情報の取扱いについて、本プライバシーポリシーを定めます。

Shirase Lab ("we") provides this Privacy Policy describing how we handle information in the mobile application "Pattern Closet" (Android package name and iOS bundle ID: `com.shiraselab.patterncloset`, the "App").

Shirase Lab（以下稱「本方」）就行動應用程式「Pattern Closet」（Android 套件名稱及 iOS Bundle ID：`com.shiraselab.patterncloset`，以下稱「本應用程式」）中使用者資訊的處理方式，訂定本隱私權政策。

Shirase Lab(이하 "당사")는 모바일 애플리케이션 "Pattern Closet"(Android 패키지 이름 및 iOS 번들 ID: `com.shiraselab.patterncloset`, 이하 "본 앱")에서의 이용자 정보 취급에 관하여 본 개인정보 처리방침을 정합니다.

---

## 1. 基本方針：データは端末内のみ / Basic policy: your data stays on your device / 基本方針：資料只存在您的裝置中 / 기본 방침: 데이터는 기기 안에만

本アプリには会員登録・ログインの機能はありません。利用者が入力・作成した次の情報は、お使いの端末内にのみ保存され、当方を含む外部へ送信されることはありません。
- ぬいの採寸値、色などの設定
- 作成・編集した型紙、ギャラリーに保存した型紙
- 印刷設定・印刷補正の値、型紙設定の既定値

The App has no account registration or sign-in. The following information that you enter or create is stored only on your device and is never sent outside, including to us:
- Plush measurements and settings such as colors
- Patterns you create or edit, and patterns saved to the gallery
- Print settings, print calibration values, and default pattern settings

本應用程式沒有會員註冊或登入功能。您輸入或建立的下列資訊只會儲存在您的裝置中，不會傳送到包括本方在內的任何外部對象：
- 娃娃的尺寸、顏色等設定
- 您建立或編輯的紙型，以及儲存在圖庫中的紙型
- 列印設定、列印校正值，以及紙型設定的預設值

본 앱에는 회원 가입 및 로그인 기능이 없습니다. 이용자가 입력하거나 작성한 다음 정보는 이용 중인 기기 안에만 저장되며, 당사를 포함한 외부로 전송되지 않습니다.
- 인형의 치수, 색상 등의 설정
- 작성·편집한 옷본 및 갤러리에 저장한 옷본
- 인쇄 설정, 인쇄 보정 값, 옷본 설정의 기본값

## 2. 外部との通信 / Communication with external services / 與外部服務的通訊 / 외부와의 통신

### 2-1. 服テンプレの配信（Google Cloud Firestore） / Distributed clothing templates (Google Cloud Firestore) / 服裝範本的發布（Google Cloud Firestore） / 의상 템플릿 배포（Google Cloud Firestore）

本アプリは、追加の服テンプレ（型紙の設計データ）を当方が管理する Google Cloud Firestore（Firebase）から読み込みます。あわせて、新しい版があるかを確かめるため、最新の版の番号などの設定を同じ Firestore から読み込みます（アプリの版との比較は端末の中で行います）。この通信は読み込みのみで、採寸値や作成した型紙などの利用者の情報は送信しません。通信の際、IP アドレスなどの通常の通信情報が Google のサーバーで処理されます。詳しくは Google のプライバシーポリシー（https://policies.google.com/privacy ）および Firebase のプライバシーとセキュリティ（https://firebase.google.com/support/privacy ）をご覧ください。

The App downloads additional clothing templates (pattern design data) from Google Cloud Firestore (Firebase) managed by us. It also downloads settings such as the latest version number from the same Firestore to check whether a new version is available (the comparison with your installed version is done on your device). This communication is read-only; your information such as measurements and patterns you create is not sent. During the connection, standard network information such as your IP address is processed by Google's servers. For details, see Google's Privacy Policy (https://policies.google.com/privacy ) and Firebase Privacy and Security (https://firebase.google.com/support/privacy ).

本應用程式會從本方管理的 Google Cloud Firestore（Firebase）讀取額外的服裝範本（紙型設計資料）。此外，為確認是否有新版本，也會從同一個 Firestore 讀取最新版本編號等設定（與已安裝版本的比較在您的裝置上進行）。此通訊僅為讀取，不會傳送尺寸或您建立的紙型等使用者資訊。通訊時，IP 位址等一般通訊資訊會由 Google 的伺服器處理。詳情請參閱 Google 隱私權政策（https://policies.google.com/privacy ）及 Firebase 隱私權與安全性說明（https://firebase.google.com/support/privacy ）。

본 앱은 당사가 관리하는 Google Cloud Firestore(Firebase)에서 추가 의상 템플릿(옷본 설계 데이터)을 불러옵니다. 또한 새 버전이 있는지 확인하기 위해 최신 버전 번호 등의 설정을 같은 Firestore에서 불러옵니다(설치된 버전과의 비교는 기기 안에서 이루어집니다). 이 통신은 읽기 전용이며, 치수나 작성한 옷본 등 이용자의 정보는 전송하지 않습니다. 통신 시 IP 주소 등 일반적인 통신 정보가 Google 서버에서 처리됩니다. 자세한 내용은 Google 개인정보처리방침(https://policies.google.com/privacy ) 및 Firebase 개인정보 보호 및 보안(https://firebase.google.com/support/privacy )을 참고해 주세요.

### 2-2. 型紙 PDF の印刷・共有 / Printing and sharing pattern PDFs / 紙型 PDF 的列印與分享 / 옷본 PDF 인쇄·공유

型紙 PDF の印刷・共有は、端末の OS の印刷機能・共有機能を通じて行います。PDF の送り先（プリンター、アプリ、保存先など）は利用者自身が選び、当方には送信されません。送り先での取扱いは、各サービスの規約・ポリシーに従います。

Pattern PDFs are printed or shared through your device's built-in print and share features. You choose where the PDF goes (a printer, an app, a storage location, etc.), and it is not sent to us. How it is handled there is governed by that service's terms and policies.

紙型 PDF 的列印與分享，是透過裝置作業系統內建的列印及分享功能進行。PDF 的傳送對象（印表機、App、儲存位置等）由您自行選擇，不會傳送給本方。傳送對象如何處理該檔案，依各服務的條款與政策而定。

옷본 PDF의 인쇄·공유는 기기 OS의 인쇄 기능·공유 기능을 통해 이루어집니다. PDF를 보낼 곳(프린터, 앱, 저장 위치 등)은 이용자가 직접 선택하며, 당사로는 전송되지 않습니다. 보낸 곳에서의 취급은 각 서비스의 약관·정책을 따릅니다.

## 3. 広告・解析・課金 / Ads, analytics and purchases / 廣告、分析與付費 / 광고·분석·결제

現在の本アプリには、広告、利用状況の解析、アプリ内課金の機能はありません。これらを導入する場合は、事前に本ポリシーを改定します。

The App currently has no advertising, usage analytics or in-app purchases. If we introduce any of them, we will update this Policy beforehand.

目前本應用程式沒有廣告、使用情形分析及 App 內購買功能。若日後導入，將事先修訂本政策。

현재 본 앱에는 광고, 이용 현황 분석, 앱 내 결제 기능이 없습니다. 이를 도입하는 경우 사전에 본 방침을 개정합니다.

## 4. 端末の権限 / Device permissions / 裝置權限 / 기기 권한

本アプリは、カメラ・位置情報・連絡先などの特別な権限を使用しません（服テンプレの読み込みのためのインターネット接続を除く）。

The App does not use special permissions such as the camera, location or contacts (other than internet access to download clothing templates).

本應用程式不使用相機、位置資訊、聯絡人等特殊權限（為讀取服裝範本而使用的網路連線除外）。

본 앱은 카메라, 위치 정보, 연락처 등 특별한 권한을 사용하지 않습니다(의상 템플릿을 불러오기 위한 인터넷 연결은 제외).

## 5. お子さまの利用について / Children / 兒童使用 / 아동의 이용

本アプリは利用者の個人情報を収集しないため、年齢にかかわらずご利用いただけます。13 歳未満の方は、保護者の方と一緒にご利用ください。

Because the App does not collect personal information, it can be used regardless of age. Users under 13 should use it together with a parent or guardian.

由於本應用程式不蒐集使用者的個人資訊，因此任何年齡皆可使用。未滿 13 歲者請與家長或監護人一同使用。

본 앱은 이용자의 개인정보를 수집하지 않으므로 연령과 관계없이 이용할 수 있습니다. 13세 미만인 분은 보호자와 함께 이용해 주세요.

## 6. データの削除 / Deleting your data / 刪除資料 / 데이터 삭제

本アプリのデータは端末内にのみあるため、保存した採寸値や型紙はアプリ内で削除できるほか、本アプリをアンインストールするとすべて削除されます。当方のサーバーに利用者のデータはないため、当方への削除依頼は不要です。

Because all App data is stored only on your device, you can delete saved measurements and patterns in the App, and uninstalling the App deletes everything. We hold no user data on our servers, so no deletion request to us is needed.

由於本應用程式的資料只存在您的裝置中，您可以在 App 內刪除已儲存的尺寸與紙型，解除安裝本應用程式時也會全部刪除。本方的伺服器上沒有任何使用者資料，因此無須向本方申請刪除。

본 앱의 데이터는 기기 안에만 있으므로, 저장한 치수와 옷본은 앱 안에서 삭제할 수 있으며 본 앱을 삭제(제거)하면 모두 삭제됩니다. 당사 서버에는 이용자의 데이터가 없으므로 당사에 삭제를 요청하실 필요가 없습니다.

## 7. 本ポリシーの変更 / Changes to this Policy / 本政策的變更 / 본 방침의 변경

当方は、必要に応じて本ポリシーを変更することがあります。重要な変更がある場合は、本ページの更新などによりお知らせします。

We may update this Policy as needed. We will notify you of significant changes by updating this page or by other means.

本方得視需要變更本政策。如有重大變更，將透過更新本頁面等方式通知。

당사는 필요에 따라 본 방침을 변경할 수 있습니다. 중요한 변경이 있는 경우 본 페이지 갱신 등을 통해 알려 드립니다.

## 8. お問い合わせ / Contact / 聯絡方式 / 문의

- 提供者 / Provider / 提供者 / 제공자: Shirase Lab
- お問い合わせ / Contact / 聯絡我們 / 문의: https://www.shirase-lab.com/inquiry-form/
