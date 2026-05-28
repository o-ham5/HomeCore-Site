# HomeCore Privacy Policy

Last Updated: May 28, 2026  
Effective Date: May 28, 2026

このページは、HomeCore の現在の実装に基づくプライバシーポリシーを日本語と英語で掲載しています。  
This page provides the Privacy Policy for HomeCore in Japanese and English, based on the current app implementation.

---

## 日本語

### 1. 基本方針

HomeCore（以下「当アプリ」）をご利用いただきありがとうございます。

当アプリは、在庫管理・TODO 管理・買い物管理・掃除管理・スライドショー表示などの機能を提供する iOS アプリです。

当アプリは、主要なアプリデータの保存・同期のための独自バックエンドを運用していません。主要なデータは、ユーザーのデバイス上および Apple の iCloud / CloudKit 上に保存されます。

ただし、ユーザーがアプリ内の「Feedback」機能から明示的に送信した場合に限り、限定的なサポート用情報が外部サービスを経由して開発者に送信されます。詳細は本ポリシーの第 7 条をご確認ください。

### 2. 当アプリが保存またはアクセスする情報

#### 2.1 ユーザーが入力する情報

当アプリは、以下の情報をデバイス上および iCloud（有効な場合）に保存します。

- 在庫管理: アイテム名、数量または割合、購入場所、購入URL、メモ、しきい値設定、画像、担当者、グループ情報、テンプレート情報
- TODO 管理: タスク名、詳細、期限、完了状態、優先度、画像、担当者、グループ情報、テンプレート情報
- 買い物管理: 商品名、数量、カテゴリ、購入済み状態、優先度、価格情報、購入場所、メモ、画像、担当者、グループ情報、テンプレート情報
- 掃除管理: タスク名、頻度、初回予定日、前回実施日、次回予定日、担当者名、メモ、画像、グループ情報、テンプレート情報

#### 2.2 アプリ内で生成される情報

当アプリは、以下のアプリ動作に伴う情報を保存する場合があります。

- 各データに付与される ID、日時、優先度判定等のメタデータ
- 操作ログ: 追加、編集、削除、複製などの操作履歴
- 削除済みデータの復元に必要な関連情報、削除日時、削除フラグ
- 機能選択、スライドショー設定、通知設定、レイアウト設定、テーマ設定、言語設定などのアプリ設定

機能データの削除はソフト削除として保持される場合があり、削除後 30 日以内はアプリ内の復元機能の対象となることがあります。その後、完全に削除される場合があります。

#### 2.3 購入状態

アプリ内課金は Apple App Store および StoreKit を通じて処理されます。開発者は決済情報にアクセスしません。

当アプリは、プレミアム版の購入状態をローカルで確認し、共有機能が有効な場合は、共有グループ内の機能制御のために必要な範囲でプレミアム状態を共有参加者に同期することがあります。

#### 2.4 iCloud アカウント情報

iCloud 同期や共有機能を利用する際、Apple が許可した場合に限り、当アプリは iCloud アカウントの表示名、メールアドレス、または電話番号に端末上でアクセスすることがあります。これらはアカウント状態の表示や共有機能の補助のために利用され、通常のアプリ利用において開発者へ送信されるものではありません。

#### 2.5 通知設定

ユーザーが通知を有効にした場合、通知時刻などの設定がデバイス上に保存されます。通知はローカル通知として処理され、外部サーバーによるプッシュ通知配信は行いません。

### 3. 収集しない情報

当アプリは、以下の目的で情報を収集しません。

- アカウント登録のための氏名、住所、連絡先の収集
- 位置情報の収集
- 連絡先の収集
- 広告識別子の収集
- 広告配信のための追跡
- 利用統計や広告目的のアナリティクス SDK の利用

写真ライブラリについては、ユーザーが画像を選択した場合に、その選択された画像のみにアクセスします。ライブラリ全体を読み取ることはありません。

### 4. 情報の利用目的

保存またはアクセスした情報は、以下の目的でのみ利用します。

- アプリ機能の提供
- データの表示、編集、削除、復元
- iCloud を通じたデバイス間同期
- アカウント共有機能によるユーザー間共有
- プレミアム機能や機能選択状態の制御
- オーナーのプレミアム状態、選択中機能、読み取り専用状態など共有機能に必要な状態の同期
- ローカル通知の配信
- サポート対応および不具合報告への対応

### 5. データの保存場所

#### 5.1 ローカル保存

主要なアプリデータは、まずユーザーのデバイス上の Core Data ストアおよび一部のローカル設定ストレージに保存されます。

#### 5.2 iCloud / CloudKit

iCloud 同期または共有機能が利用される場合、データは Apple CloudKit を通じて iCloud 上に同期・保存されます。iCloud に保存されたデータの取り扱いは Apple のポリシーに従います。

Apple Privacy Policy: https://www.apple.com/jp/privacy/

### 6. 共有機能で同期される情報

当アプリは Apple CloudKit の共有機能を利用して、異なる iCloud アカウント間でデータを共有します。

共有が有効な場合、対象機能に関する以下の情報が共有参加者に表示または同期されることがあります。

- アイテム名、数量、購入済み状態、カテゴリ、価格、場所、メモ、画像、担当者名、期限や予定日、グループ・テンプレートに関する情報などの共有対象データ
- 追加、編集、削除、複製などの操作ログ
- 共有中の機能利用に必要なアプリ状態
- オーナー側のプレミアム利用状態
- オーナーが選択している機能
- 共有中の読み取り専用状態

オーナーは共有を停止でき、参加者は共有から退出できます。共有データへのアクセス制御は Apple CloudKit の仕組みに従います。

### 7. 第三者提供・外部サービス

#### 7.1 Apple

課金、iCloud 同期、共有機能は Apple の App Store、StoreKit、CloudKit を利用します。

#### 7.2 フィードバック送信

ユーザーがアプリ内の Feedback 機能から明示的に送信した場合、以下の情報が外部サービス（Google Apps Script）を経由して開発者に送信されます。

- フィードバック種別
- メッセージ本文
- アプリバージョン
- デバイスモデル
- iOS バージョン
- タイムスタンプ

この送信は、ユーザーが自ら送信操作を行った場合にのみ実行されます。

#### 7.3 それ以外の第三者提供

上記を除き、当アプリはユーザー情報を第三者に販売、交換、または広告目的で提供しません。法令に基づく開示要求がある場合を除き、ユーザー情報を提供しません。

### 8. セキュリティ

当アプリは、以下の方法でデータ保護を行います。

- iOS の標準セキュリティ機能の利用
- アプリサンドボックスによるローカルデータ保護
- Apple による iCloud / CloudKit の保護機構の利用
- 共有データに対する Apple CloudKit のアクセス制御の利用

ただし、完全な安全性を保証するものではありません。

### 9. ユーザーの権利

ユーザーは以下を行うことができます。

- アプリ内データへのアクセス
- データの修正および更新
- データの削除（削除された機能データは一定期間アプリ内の復元機能の対象となる場合があり、その後完全に削除されることがあります）
- iCloud 同期の利用可否の管理（当アプリには iCloud 同期を手動でオフにする設定はなく、利用可否は iOS、Apple Account、および iCloud の設定状況に依存します）
- 通知の無効化
- 共有の停止または退出
- フィードバック送信の任意選択

### 10. 子どものプライバシー

当アプリは特定の年齢層を対象としたものではなく、意図的に子どもから個人情報を収集することはありません。

### 11. 本ポリシーの変更

本プライバシーポリシーは、必要に応じて更新されることがあります。重要な変更がある場合は、アプリ内または本ページで案内することがあります。

### 12. お問い合わせ

プライバシーに関するお問い合わせは、アプリ内の Feedback 機能、または以下の連絡先までお願いします。

- アプリ名: HomeCore
- 開発者: HomeCore Developer
- 連絡先: homecore.app@gmail.com

---

## English

### 1. Core Principle

Thank you for using HomeCore.

HomeCore is an iOS app that provides Stock, TODO, Shopping, Cleaning, and slideshow features.

The App does not operate its own backend service for primary app data. Primary app data is stored on the user's device and in Apple iCloud / CloudKit.

However, if you explicitly submit feedback through the in-app Feedback feature, limited support-related information is transmitted to the developer through an external service. See Section 7 for details.

### 2. Information the App Stores or Accesses

#### 2.1 Information You Enter

The App stores the following information on your device and in iCloud, if enabled.

- Stock: item names, quantities or percentages, purchase locations, purchase URLs, notes, threshold settings, images, assignees, group information, and template information
- TODO: task names, details, due dates, completion status, priorities, images, assignees, group information, and template information
- Shopping: product names, quantities, categories, purchase status, priorities, price information, purchase locations, notes, images, assignees, group information, and template information
- Cleaning: task names, frequencies, first/last/next scheduled dates, assignee names, notes, images, group information, and template information

#### 2.2 App-Generated Information

The App may also store information generated through app usage, including:

- IDs, timestamps, and related metadata used to manage app data
- activity logs for actions such as add, edit, delete, and duplicate
- deletion flags, deletion timestamps, and related data used to support restore behavior
- app settings such as selected feature, slideshow settings, notification settings, layout settings, theme settings, and language settings

Deleted feature data may be retained as soft-deleted data for a limited period. In the current implementation, deleted feature data may remain restorable in the App for up to 30 days before being permanently removed.

#### 2.3 Purchase Status

In-app purchases are processed through the Apple App Store and StoreKit. The developer does not access payment details.

The App checks premium purchase status locally. When account sharing is enabled, the App may synchronize premium availability to share participants to control feature access within the shared group.

#### 2.4 iCloud Account Information

When you use iCloud sync or sharing features, and if Apple grants permission, the App may access your iCloud display name, email address, or phone number locally on the device. This is used to display account status and support sharing-related UI. It is not routinely transmitted to the developer during normal app usage.

#### 2.5 Notification Settings

If you enable notifications, notification time settings are stored on your device. Notifications are delivered as local notifications. The App does not use a remote push service for the daily summary notification feature.

### 3. Information the App Does Not Collect for Analytics or Advertising

The App does not collect information for the following purposes:

- account registration using name, address, or contact details
- location tracking
- contact list collection
- advertising identifier collection
- advertising tracking
- analytics SDK usage for marketing or ad targeting

For the photo library, the App accesses only the image you explicitly choose. It does not read your full photo library.

### 4. How Information Is Used

Stored or accessed information is used only for the following purposes:

- providing app features
- displaying, editing, deleting, and restoring data
- syncing data across devices through iCloud
- sharing data between users through the account sharing feature
- controlling premium features and feature-selection state
- synchronizing owner state needed for sharing, such as premium status, selected feature, and read-only state
- delivering local notifications
- handling support inquiries and bug reports

### 5. Where Data Is Stored

#### 5.1 Local Storage

Primary app data is first stored in the App's local Core Data stores and local settings storage on your device.

#### 5.2 iCloud / CloudKit

If iCloud sync or sharing is used, data is synchronized and stored in iCloud through Apple CloudKit. Data stored in iCloud is handled according to Apple's policies.

Apple Privacy Policy: https://www.apple.com/privacy/

### 6. Information Synchronized During Sharing

The App uses Apple CloudKit sharing to share data across different iCloud accounts.

When sharing is enabled, the following information may be shown or synchronized to share participants:

- shared feature data such as item names, quantities, purchase status, categories, prices, locations, notes, images, assignee names, due or scheduled dates, and group or template-related information
- activity logs for actions such as add, edit, delete, and duplicate
- app state needed for shared feature access
- owner premium availability
- the feature selected by the owner
- shared read-only state

Owners can stop sharing, and participants can leave a share. Access control for shared data follows Apple's CloudKit sharing mechanisms.

### 7. Third Parties and External Services

#### 7.1 Apple

Purchases, iCloud sync, and sharing features use Apple's App Store, StoreKit, and CloudKit services.

#### 7.2 Feedback Submission

If you explicitly submit feedback through the in-app Feedback feature, the following information is transmitted to the developer through an external service (Google Apps Script):

- feedback type
- message content
- app version
- device model
- iOS version
- timestamp

This transmission occurs only when you intentionally submit feedback.

#### 7.3 Other Third-Party Sharing

Except as described above, the App does not sell, trade, or provide user information to third parties for advertising purposes. Information may be disclosed only when required by law.

### 8. Security

The App protects data by using:

- standard iOS security features
- local sandbox-based data protection
- Apple's protection mechanisms for iCloud / CloudKit
- Apple's access control for shared data

No security measure can guarantee absolute safety.

### 9. Your Choices and Rights

You can:

- access your data in the App
- edit and update your data
- delete your data (deleted feature data may remain restorable in the App for a limited period before being permanently removed)
- manage the availability of iCloud sync (the App does not provide an in-app switch to disable iCloud sync; availability depends on your iOS, Apple Account, and iCloud settings)
- disable notifications
- stop or leave sharing
- choose whether to submit feedback

### 10. Children's Privacy

The App is not directed to a specific age group and does not intentionally collect personal information from children.

### 11. Changes to This Policy

This Privacy Policy may be updated as needed. Significant changes may be announced in the App or on this page.

### 12. Contact

For privacy-related questions, please use the in-app Feedback feature or contact:

- App Name: HomeCore
- Developer: HomeCore Developer
- Contact: homecore.app@gmail.com
