# プライバシーポリシー（パタクロ！） / Privacy Policy (Pattern Closet) / 隱私權政策（Pattern Closet） / 개인정보 처리방침（Pattern Closet）

**最終更新日 / Last updated / 最後更新 / 최종 수정일: 2026-10-22**

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

ただし、広告の表示のために、広告の部品が端末の情報を Google などの広告の会社へ送ります（第 3 条）。上の情報（採寸値・型紙など）は送りません。

However, to show ads, the ad components send device information to ad companies such as Google (Section 3). The information above (measurements, patterns, etc.) is not sent.

不過，為了顯示廣告，廣告元件會將裝置資訊傳送給 Google 等廣告公司（第 3 條）。上述資訊（尺寸、紙型等）不會傳送。

다만 광고 표시를 위해 광고 구성 요소가 기기 정보를 Google 등 광고 회사에 전송합니다(제3조). 위의 정보(치수, 옷본 등)는 전송하지 않습니다.

## 2. 外部との通信 / Communication with external services / 與外部服務的通訊 / 외부와의 통신

### 2-1. 服テンプレの配信（Google Cloud Firestore） / Distributed clothing templates (Google Cloud Firestore) / 服裝範本的發布（Google Cloud Firestore） / 의상 템플릿 배포（Google Cloud Firestore）

本アプリは、服テンプレ（型紙の設計データ。アプリに入っている服の新しい版と追加の服）と、新しい服を作る画面の部位のひな形を、当方が管理する Google Cloud Firestore（Firebase）から読み込みます。あわせて、新しい版があるかを確かめるため、最新の版の番号などの設定を同じ Firestore から読み込みます（アプリの版との比較は端末の中で行います）。この通信は読み込みのみで、採寸値や作成した型紙などの利用者の情報は送信しません。通信の際、IP アドレスなどの通常の通信情報が Google のサーバーで処理されます。詳しくは Google のプライバシーポリシー（https://policies.google.com/privacy ）および Firebase のプライバシーとセキュリティ（https://firebase.google.com/support/privacy ）をご覧ください。

The App downloads clothing templates (pattern design data: newer versions of the outfits included in the App and additional outfits) and the part templates used on the outfit creation screen from Google Cloud Firestore (Firebase) managed by us. It also downloads settings such as the latest version number from the same Firestore to check whether a new version is available (the comparison with your installed version is done on your device). This communication is read-only; your information such as measurements and patterns you create is not sent. During the connection, standard network information such as your IP address is processed by Google's servers. For details, see Google's Privacy Policy (https://policies.google.com/privacy ) and Firebase Privacy and Security (https://firebase.google.com/support/privacy ).

本應用程式會從本方管理的 Google Cloud Firestore（Firebase）讀取服裝範本（紙型設計資料：App 內建服裝的新版本與額外的服裝），以及建立新服裝畫面所用的部位範本。此外，為確認是否有新版本，也會從同一個 Firestore 讀取最新版本編號等設定（與已安裝版本的比較在您的裝置上進行）。此通訊僅為讀取，不會傳送尺寸或您建立的紙型等使用者資訊。通訊時，IP 位址等一般通訊資訊會由 Google 的伺服器處理。詳情請參閱 Google 隱私權政策（https://policies.google.com/privacy ）及 Firebase 隱私權與安全性說明（https://firebase.google.com/support/privacy ）。

본 앱은 당사가 관리하는 Google Cloud Firestore(Firebase)에서 의상 템플릿(옷본 설계 데이터: 앱에 들어 있는 의상의 새 버전과 추가 의상)과 새 의상 만들기 화면에서 쓰는 부위 템플릿을 불러옵니다. 또한 새 버전이 있는지 확인하기 위해 최신 버전 번호 등의 설정을 같은 Firestore에서 불러옵니다(설치된 버전과의 비교는 기기 안에서 이루어집니다). 이 통신은 읽기 전용이며, 치수나 작성한 옷본 등 이용자의 정보는 전송하지 않습니다. 통신 시 IP 주소 등 일반적인 통신 정보가 Google 서버에서 처리됩니다. 자세한 내용은 Google 개인정보처리방침(https://policies.google.com/privacy ) 및 Firebase 개인정보 보호 및 보안(https://firebase.google.com/support/privacy )을 참고해 주세요.

### 2-2. 型紙 PDF の印刷・共有、服のファイルの書き出し・読み込み / Printing and sharing pattern PDFs, exporting and importing outfit files / 紙型 PDF 的列印與分享、服裝檔案的匯出與匯入 / 옷본 PDF 인쇄·공유, 의상 파일 내보내기·가져오기

型紙 PDF の印刷・共有は、端末の OS の印刷機能・共有機能を通じて行います。PDF の送り先（プリンター、アプリ、保存先など）は利用者自身が選び、当方には送信されません。送り先での取扱いは、各サービスの規約・ポリシーに従います。自作の服のファイルの書き出しも同じく端末の共有機能で行い、読み込みは利用者が選んだファイルを端末の中で読むだけです。どちらも当方には送信されません。

Pattern PDFs are printed or shared through your device's built-in print and share features. You choose where the PDF goes (a printer, an app, a storage location, etc.), and it is not sent to us. How it is handled there is governed by that service's terms and policies. Exporting your own outfit files also uses your device's share feature, and importing only reads the file you choose on your device. Neither is sent to us.

紙型 PDF 的列印與分享，是透過裝置作業系統內建的列印及分享功能進行。PDF 的傳送對象（印表機、App、儲存位置等）由您自行選擇，不會傳送給本方。傳送對象如何處理該檔案，依各服務的條款與政策而定。匯出自製服裝的檔案同樣透過裝置的分享功能進行，匯入則只會在您的裝置上讀取您選擇的檔案。兩者都不會傳送給本方。

옷본 PDF의 인쇄·공유는 기기 OS의 인쇄 기능·공유 기능을 통해 이루어집니다. PDF를 보낼 곳(프린터, 앱, 저장 위치 등)은 이용자가 직접 선택하며, 당사로는 전송되지 않습니다. 보낸 곳에서의 취급은 각 서비스의 약관·정책을 따릅니다. 직접 만든 의상 파일의 내보내기도 기기의 공유 기능으로 이루어지며, 가져오기는 이용자가 선택한 파일을 기기 안에서 읽기만 합니다. 어느 쪽도 당사로 전송되지 않습니다.

## 3. 広告・解析・課金 / Ads, analytics and purchases / 廣告、分析與付費 / 광고·분석·결제

### 3-1. 広告（Google AdMob） / Ads (Google AdMob) / 廣告（Google AdMob） / 광고（Google AdMob）

本アプリは、無料でお使いいただくために Google AdMob の広告を表示します（ホーム画面と型紙画面の上のバナー、型紙 PDF の印刷・共有の前に見る動画広告〔リワード〕、アプリに戻ったときの全画面の広告。購入した服と有料プランでは表示しません）。広告を表示する際、Google と下記 3-2 の広告ネットワークに、**広告 ID**（Android の広告 ID・iOS の IDFA。iOS は利用者がトラッキングを許可した場合のみ）、**端末の情報**（機種・OS・言語など）、**おおよその地域・IP アドレス**、**広告の表示やタップの記録**、**同意の状態**が送られることがあります。これらは広告の表示・効果の計測・不正の防止に使われ、取扱いは各社のプライバシーポリシーに従います。採寸値・型紙・ぬいの名前など、利用者が入力・作成した情報は送りません。
- iOS では、初めて起動したときにトラッキングの許可（App Tracking Transparency）を伺います。許可しなくてもアプリの機能はすべて使えます（広告は表示されます）。
- 欧州経済領域・英国など同意が必要な地域では、Google の同意管理（UMP）で、広告のための情報の利用に同意するかを伺います。同意しない場合、パーソナライズされた広告は表示されません。選び直すには、設定ページの「プライバシー設定」を使います（同意が必要な地域だけ表示されます）。
- Google による情報の取扱い: https://policies.google.com/technologies/partner-sites

To keep the App free, it shows ads from Google AdMob (banners at the top of the home and pattern screens, a video ad [rewarded ad] you watch before printing or sharing a pattern PDF, and a full-screen ad when you return to the App; no ads for purchased outfits or on the paid plan). When ads are shown, Google and the ad networks in 3-2 below may receive your **advertising ID** (the Android advertising ID or the iOS IDFA; on iOS only if you allow tracking), **device information** (model, OS, language, etc.), **coarse location and IP address**, **records of ad views and taps**, and your **consent state**. They are used to show ads, measure their performance and prevent fraud, and are handled under each company's privacy policy. Information you enter or create, such as measurements, patterns and plush names, is not sent.
- On iOS, the App asks for tracking permission (App Tracking Transparency) the first time you open it. All features work even if you don't allow it (ads are still shown).
- In regions where consent is required, such as the European Economic Area and the UK, Google's consent management (UMP) asks whether you consent to the use of your information for ads. If you don't consent, personalized ads are not shown. To change your choice, use "Privacy settings" on the Settings page (shown only in regions where consent is required).
- How Google uses information: https://policies.google.com/technologies/partner-sites

為了讓您免費使用，本應用程式會顯示 Google AdMob 的廣告（首頁與紙型畫面上方的橫幅廣告、列印或分享紙型 PDF 前觀看的影片廣告〔獎勵廣告〕，以及返回 App 時的全螢幕廣告；購買的服裝與付費方案不顯示廣告）。顯示廣告時，可能會將**廣告 ID**（Android 的廣告 ID、iOS 的 IDFA；iOS 僅在您允許追蹤時）、**裝置資訊**（機型、作業系統、語言等）、**大概的地區與 IP 位址**、**廣告的顯示與點按紀錄**以及**同意狀態**傳送給 Google 與下列 3-2 的廣告聯播網。這些資訊用於顯示廣告、評估成效與防止詐欺，並依各公司的隱私權政策處理。您輸入或建立的資訊（尺寸、紙型、娃娃的名稱等）不會傳送。
- 在 iOS 上，首次開啟時會詢問是否允許追蹤（App Tracking Transparency）。即使不允許，也能使用 App 的所有功能（仍會顯示廣告）。
- 在歐洲經濟區、英國等需要同意的地區，會透過 Google 的同意管理（UMP）詢問您是否同意將資訊用於廣告。若不同意，將不會顯示個人化廣告。若要重新選擇，請使用設定頁的「隱私權設定」（僅在需要同意的地區顯示）。
- Google 的資訊處理方式：https://policies.google.com/technologies/partner-sites

본 앱은 무료로 이용하실 수 있도록 Google AdMob 광고를 표시합니다(홈 화면과 옷본 화면 위의 배너, 옷본 PDF를 인쇄·공유하기 전에 보는 동영상 광고〔보상형 광고〕, 앱으로 돌아왔을 때의 전면 광고. 구매한 의상과 유료 플랜에서는 표시하지 않습니다). 광고를 표시할 때 Google과 아래 3-2의 광고 네트워크에 **광고 ID**(Android 광고 ID·iOS IDFA. iOS는 이용자가 추적을 허용한 경우에만), **기기 정보**(기종·OS·언어 등), **대략적인 지역·IP 주소**, **광고 표시 및 탭 기록**, **동의 상태**가 전송될 수 있습니다. 이 정보는 광고 표시, 효과 측정, 부정 방지에 사용되며 각 회사의 개인정보 처리방침에 따라 취급됩니다. 치수, 옷본, 인형 이름 등 이용자가 입력·작성한 정보는 전송하지 않습니다.
- iOS에서는 처음 실행할 때 추적 허용(App Tracking Transparency)을 여쭙니다. 허용하지 않아도 앱의 모든 기능을 사용할 수 있습니다(광고는 표시됩니다).
- 유럽 경제 지역·영국 등 동의가 필요한 지역에서는 Google의 동의 관리(UMP)를 통해 광고를 위한 정보 이용에 동의하는지 여쭙니다. 동의하지 않으면 맞춤형 광고는 표시되지 않습니다. 다시 선택하려면 설정 페이지의 '개인정보 설정'을 이용해 주세요(동의가 필요한 지역에서만 표시됩니다).
- Google의 정보 취급: https://policies.google.com/technologies/partner-sites

### 3-2. 広告メディエーションのパートナー / Ad mediation partners / 廣告中介合作夥伴 / 광고 미디에이션 파트너

本アプリの広告は Google AdMob の**メディエーション**を利用しており、AdMob が下記の広告ネットワークにも広告枠を割り当てます。各ネットワークに送られる情報は 3-1 と同じで、同意の状態も Google の同意管理を通して各社へ伝えられます（同意しない場合、各社でもパーソナライズされた広告は表示されません）。

Ads in the App are served through Google AdMob **mediation**, and AdMob may also allocate ad slots to the ad networks below. They may receive the same information as in 3-1, and your consent state is passed to them through Google's consent management (without consent, they do not show personalized ads either).

本應用程式的廣告使用 Google AdMob 的**中介服務**，AdMob 也會將廣告版位分配給下列廣告聯播網。傳送給各聯播網的資訊與 3-1 相同，同意狀態也會透過 Google 的同意管理傳達給各公司（若不同意，各公司也不會顯示個人化廣告）。

본 앱의 광고는 Google AdMob의 **미디에이션**을 이용하며, AdMob이 아래 광고 네트워크에도 광고 지면을 할당합니다. 각 네트워크에 전송되는 정보는 3-1과 같으며, 동의 상태도 Google의 동의 관리를 통해 각 회사에 전달됩니다(동의하지 않으면 각 회사에서도 맞춤형 광고는 표시되지 않습니다).

| 広告ネットワーク / Ad network | プライバシーポリシー / Privacy policy |
|---|---|
| LY Ads Network（LINEヤフー広告ネットワーク） / LY Corporation | https://www.lycorp.co.jp/ja/company/privacypolicy/ |
| Unity Ads | https://unity.com/legal/game-player-and-app-user-privacy-policy |
| Pangle | https://www.pangleglobal.com/privacy |
| Meta Audience Network | https://www.facebook.com/about/privacy/ |
| Liftoff Monetize（旧 Vungle） | https://liftoff.io/privacy-policy |
| ironSource | https://www.is.com/privacy-policy/ |
| Mintegral | https://www.mintegral.com/en/privacy/ |
| maio（運営は i-mobile） | https://www.i-mobile.co.jp/privacy.html |
| i-mobile | https://www.i-mobile.co.jp/privacy.html |

AdMob が利用する広告パートナーの一覧は Google のページでも公開されています / Google also publishes the list of ad partners used by AdMob / Google 也公開了 AdMob 使用的廣告合作夥伴清單 / AdMob이 이용하는 광고 파트너 목록은 Google 페이지에서도 공개하고 있습니다: https://support.google.com/admob/answer/9012903

### 3-3. 利用状況の解析（Google アナリティクス for Firebase） / Usage analytics (Google Analytics for Firebase) / 使用情形分析（Google Analytics for Firebase） / 이용 현황 분석（Google Analytics for Firebase）

アプリの改善のため、Google アナリティクス for Firebase で、開いた画面と、服を開いた・型紙 PDF を共有／印刷した・ギャラリーに保存した・自作の服を作った・ぬいを追加したといった操作（服の種類・用紙・縫い代などの設定を含む）と、端末の情報（機種・OS・言語・おおよその地域・アプリの版）、アプリごとの識別子を Google に送ります。採寸値そのもの、利用者が付けた名前（ぬい・服・型紙）は送りません。同意が必要な地域では、広告と同じ同意の画面（3-1）で同意した場合だけ送ります。取扱いは Google のポリシーに従います: https://policies.google.com/technologies/partner-sites

To improve the App, we use Google Analytics for Firebase to send Google the screens you open, actions such as opening an outfit, sharing or printing a pattern PDF, saving to the gallery, creating your own outfit and adding a plush (including settings such as the outfit type, paper and seam allowance), device information (model, OS, language, coarse region, app version) and an app-specific identifier. Your measurements and the names you give (plushies, outfits, patterns) are not sent. In regions where consent is required, this is sent only if you consent on the same consent screen as for ads (3-1). Google handles the data under its policy: https://policies.google.com/technologies/partner-sites

為了改善本應用程式，我們使用 Google Analytics for Firebase，將您開啟的畫面，以及開啟服裝、分享或列印紙型 PDF、儲存到圖庫、建立自製服裝、新增娃娃等操作（包含服裝種類、紙張、縫份等設定）、裝置資訊（機型、作業系統、語言、大概的地區、App 版本）與 App 專用的識別碼傳送給 Google。尺寸本身以及您取的名稱（娃娃、服裝、紙型）不會傳送。在需要同意的地區，只有在您於與廣告相同的同意畫面（3-1）中同意時才會傳送。Google 依其政策處理資料：https://policies.google.com/technologies/partner-sites

앱 개선을 위해 Google Analytics for Firebase로, 연 화면과 의상 열기·옷본 PDF 공유/인쇄·갤러리에 저장·나만의 의상 만들기·인형 추가 등의 조작(의상 종류, 용지, 시접 등의 설정 포함), 기기 정보(기종·OS·언어·대략적인 지역·앱 버전), 앱별 식별자를 Google에 전송합니다. 치수 자체와 이용자가 붙인 이름(인형·의상·옷본)은 전송하지 않습니다. 동의가 필요한 지역에서는 광고와 같은 동의 화면(3-1)에서 동의한 경우에만 전송합니다. Google은 자사 정책에 따라 데이터를 취급합니다: https://policies.google.com/technologies/partner-sites

### 3-4. 課金 / Purchases / 付費 / 결제

現在の本アプリには、アプリ内課金の機能はありません。導入する場合は、事前に本ポリシーを改定します。

The App currently has no in-app purchases. If we introduce them, we will update this Policy beforehand.

目前本應用程式沒有 App 內購買功能。若日後導入，將事先修訂本政策。

현재 본 앱에는 앱 내 결제 기능이 없습니다. 도입하는 경우 사전에 본 방침을 개정합니다.

## 4. 端末の権限 / Device permissions / 裝置權限 / 기기 권한

本アプリは、カメラ・位置情報・連絡先を使いません。インターネット接続は、服テンプレの読み込みと広告の表示に使います。iOS では、トラッキングの許可を伺います（第 3 条 3-1）。また、広告の部品がカメラや位置情報の機能を参照するため、その利用目的の説明を設定していますが、本アプリからカメラや位置情報の許可を求めることはありません。

The App does not use the camera, location or contacts. Internet access is used to download clothing templates and to show ads. On iOS, the App asks for tracking permission (Section 3-1). Because the ad components reference the camera and location features, the App includes purpose descriptions for them, but the App itself never asks for camera or location permission.

本應用程式不使用相機、位置資訊及聯絡人。網路連線用於讀取服裝範本與顯示廣告。在 iOS 上會詢問是否允許追蹤（第 3 條 3-1）。另外，由於廣告元件會參照相機與位置資訊功能，因此設定了其使用目的的說明，但本應用程式不會要求相機或位置資訊的權限。

본 앱은 카메라, 위치 정보, 연락처를 사용하지 않습니다. 인터넷 연결은 의상 템플릿을 불러오고 광고를 표시하는 데 사용합니다. iOS에서는 추적 허용을 여쭙니다(제3조 3-1). 또한 광고 구성 요소가 카메라와 위치 정보 기능을 참조하므로 그 이용 목적에 대한 설명을 설정해 두었지만, 본 앱에서 카메라나 위치 정보 권한을 요청하지는 않습니다.

## 5. お子さまの利用について / Children / 兒童使用 / 아동의 이용

本アプリは広告を表示し、広告の会社が端末の情報を使うことがあります（第 3 条）。13 歳未満の方は、保護者の方の同意のうえ、保護者の方と一緒にご利用ください。

The App shows ads, and ad companies may use device information (Section 3). Users under 13 should use the App together with a parent or guardian, with their consent.

本應用程式會顯示廣告，廣告公司可能會使用裝置資訊（第 3 條）。未滿 13 歲者請在取得家長或監護人同意後，與其一同使用。

본 앱은 광고를 표시하며, 광고 회사가 기기 정보를 이용할 수 있습니다(제3조). 13세 미만인 분은 보호자의 동의를 받아 보호자와 함께 이용해 주세요.

## 6. データの削除 / Deleting your data / 刪除資料 / 데이터 삭제

本アプリのデータは端末内にのみあるため、保存した採寸値や型紙はアプリ内で削除できるほか、本アプリをアンインストールするとすべて削除されます。当方のサーバーに利用者のデータはないため、当方への削除依頼は不要です。広告の会社に送られた情報は、各社のポリシーに従って扱われます。広告 ID は端末の設定でリセット・制限できます（Android: 設定 → Google → 広告、iOS: 設定 → プライバシーとセキュリティ → トラッキング）。

Because all App data is stored only on your device, you can delete saved measurements and patterns in the App, and uninstalling the App deletes everything. We hold no user data on our servers, so no deletion request to us is needed. Information sent to ad companies is handled under their policies. You can reset or limit your advertising ID in your device settings (Android: Settings → Google → Ads; iOS: Settings → Privacy & Security → Tracking).

由於本應用程式的資料只存在您的裝置中，您可以在 App 內刪除已儲存的尺寸與紙型，解除安裝本應用程式時也會全部刪除。本方的伺服器上沒有任何使用者資料，因此無須向本方申請刪除。傳送給廣告公司的資訊依各公司的政策處理。您可以在裝置設定中重設或限制廣告 ID（Android：設定 → Google → 廣告；iOS：設定 → 隱私權與安全性 → 追蹤）。

본 앱의 데이터는 기기 안에만 있으므로, 저장한 치수와 옷본은 앱 안에서 삭제할 수 있으며 본 앱을 삭제(제거)하면 모두 삭제됩니다. 당사 서버에는 이용자의 데이터가 없으므로 당사에 삭제를 요청하실 필요가 없습니다. 광고 회사에 전송된 정보는 각 회사의 정책에 따라 취급됩니다. 광고 ID는 기기 설정에서 재설정하거나 제한할 수 있습니다(Android: 설정 → Google → 광고, iOS: 설정 → 개인정보 보호 및 보안 → 추적).

## 7. 本ポリシーの変更 / Changes to this Policy / 本政策的變更 / 본 방침의 변경

当方は、必要に応じて本ポリシーを変更することがあります。重要な変更がある場合は、本ページの更新などによりお知らせします。

We may update this Policy as needed. We will notify you of significant changes by updating this page or by other means.

本方得視需要變更本政策。如有重大變更，將透過更新本頁面等方式通知。

당사는 필요에 따라 본 방침을 변경할 수 있습니다. 중요한 변경이 있는 경우 본 페이지 갱신 등을 통해 알려 드립니다.

## 8. お問い合わせ / Contact / 聯絡方式 / 문의

- 提供者 / Provider / 提供者 / 제공자: Shirase Lab
- お問い合わせ / Contact / 聯絡我們 / 문의: https://www.shirase-lab.com/inquiry-form/
