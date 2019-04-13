# blog
日本マイクロソフト Azure Identity サポート チームのブログです。

チームの担当製品である Azure Active Directory、Azure AD Connect、AD FS の情報を中心にお届けします。その他の Azure 関連サポートチームのブログへのリンクもありますのでぜひご確認ください。

## Azure Active Directory

- [PowerShell にて全ユーザーの最終サインイン日時を一括で取得する方法](./azure-active-directory/last-signin-reports.md)
- [サブスクリプション作成時のエラー「アカウントが Azure サブスクリプションに関連付けられないディレクトリに属しています。別のアカウントでサインインしてください」](./azure-active-directory/create-subscription-error.md)
- [多要素認証 (MFA) のリセット手順](./azure-active-directory/mfa-reset.md)
- [条件付きアクセスの基本的な考え方](./azure-active-directory/conditional-access-basuc.md)
- [Azure AD の ディレクトリロールが割り当てられたメンバーの一覧を取得したい](./azure-active-directory/output-directory-roll-members.md)
- [テナント制限について](./azure-active-directory/tenant-restriction.md)
- [Azure Active Directory への接続で使用する IP アドレス範囲の変更](./azure-active-directory/changed_aad_ip_range.md)
- [Azure MFA の多要素認証設定の統合](./azure-active-directory/mfasetupinteg.md)
- [Azure AD におけるロール管理の新しい方法](./azure-active-directory/roles-and-administrators.md)
- [「ユーザーはアプリケーションを登録できる」の設定について](./azure-active-directory/users-can-register-applications.md)
- [RBAC のスコープについて](./azure-active-directory/about-rbac.md)
- [Azure AD B2B におけるユーザーの新しい招待方法](./azure-active-directory/b2b-invitation.md)
- [Azure AD のサインイン画面に関するアップデートのお知らせ](./azure-active-directory/azure-ad-sign-in-experience.md)
- [ハイブリッド Azure Active Directory 参加済みデバイスの構成について](./azure-active-directory/hybrid-azuread-joined-devices-setup.md)
- [Azure AD プロビジョニング機能について](./azure-active-directory/azure-ad-provisioning.md)
- [Azure AD が発行するトークンの有効期間について](./azure-active-directory/aad-token-lifetime.md)
- [Azure AD 有償ライセンスの購入方法](./azure-active-directory/azure-ad-purchase.md)
- [クレーム ルールと条件付きアクセスの比較](./active-directory-federation-service/claim-rule-conditional-access.md)
- [Azure AD Reporting API を利用して PowerShell より Azure AD のサインイン アクティビティ レポートと監査アクティビティ レポートを CSV ファイルで取得する方法](./azure-active-directory/azure-ad-reporting-api.md)
- [Azure AD の追加・変更・削除](./azure-active-directory/add-modify-delete-directory.md)
- [Azure ポータルへのアクセス制限](./azure-active-directory/access-restriction-azure-portal.md)
- ACS の移行スケジュール
- [Member ユーザーと Guest ユーザーについて](./azure-active-directory/member-and-guest-user.md)
- [Azure AD B2B とは](./azure-active-directory/what-is-b2b.md)
- [Azure AD の条件付きアクセスに関する Q&A](./azure-active-directory/qanda-conditional-access.md)
- [Azure Active Directory の PowerShell モジュール](./azure-active-directory/powershell-module.md)
- [Azure サブスクリプションと Azure AD の管理者](./azure-active-directory/subscription-azure-ad-relationship.md)
- [「アクセス権がありません」のエラーについて](./azure-active-directory/azuread-access-denied.md)
- [サブスクリプションが見えない](./azure-active-directory/subscription-azuread.md)
- 招待したユーザーが利用できない
- 招待メールを使用しないユーザーの追加方法
- 登録されたデバイスの管理方法
- [調査に有効な採取情報] Azure AD に関する問題全般
- [調査に有効な採取情報] ブラウザ経由での Azure AD 認証
- [“Baseline policy: Require MFA for admins” について](./azure-active-directory/about-baseline-policy-require-mfa-for-admins.md)
- [Azure AD と AD FS のベスト プラクティス: パスワード スプレー攻撃の防御](./azure-active-directory/password-sprey-attack.md)
- [Microsoft Graph API を利用して Azure AD のサインイン アクティビティ レポートを CSV ファイルで取得する PowerShell スクリプト](./azure-active-directory/microsoft-graph-api-signin-activity-reports.md)
- [Office 365 へのアクセスで iOS Accounts 登録のメッセージが表示され接続できない](./azure-active-directory/ios-accounts.md)
- [Azure AD の ExpressRoute サポート変更](./azure-active-directory/expressroute-support.md)
- [Microsoft 365 を用いたゼロ トラスト ネットワークの実現](./azure-active-directory/zero-trust-network.md)
- [4/6 RCA - Azure Active Directory - 認証エラー (日本語抄訳)](./azure-active-directory/20180406-rca-azure-ad.md)
- [Azure MFA を求められるタイミングについて](./azure-active-directory/azure-mfa-timing.md)
- [入れ子 (ネスト) グループへの権限付与について](./azure-active-directory/nesting-group.md)
- [Azure AD サインイン ログ 取得方法まとめ](./azure-active-directory/how-to-get-sign-in-logs.md)

## Azure AD Connect

- [Azure AD Connect : ステージング サーバーのすゝめ](./azure-active-directory-connect/introduction-staging-server.md)
- [Azure AD Connect : ディレクトリ同期の応用 – オブジェクト間の属性値の移動](./azure-active-directory-connect/move-attribute-values-between-objects.md)
- [Azure AD Connect : 2018/11/7 以降 AADC 1.0.8641.0 以前では Password Writeback が利用できない](./azure-active-directory-connect/cantphsback-aadc.md)
- [Office 365 の TLS 1.0/1.1 無効化に伴うAzure AD Connectの対応](./azure-active-directory-connect/azure-ad-connect-tls.md)
- [Azure AD Connect サーバーの CPU 使用率が頻繁に 100% になる問題について](./azure-active-directory-connect/problem-cpu-usage-100-aadc-server.md)
- [Azure AD Connect アップグレード手順](./azure-active-directory-connect/how-to-upgrade.md)
- [Azure AD Connect サーバー : ウィルス対策ソフト除外項目 / 使用する通信ポート](./azure-active-directory-connect/port-used-by-aadc.md)
- [Azure AD Connect : ディレクトリ同期の基本的なポイント](./azure-active-directory-connect/basic-points-directory-synchronization.md)
- [Azure AD Connect：属性フロー（変換フロー）のためのカスタム同期ルールの作り方](./azure-active-directory-connect/how-to-create-a-custom-aadsync-synchronization-rule.md)
- [AAD Notification から送られた DirSync に関するメールについて](./azure-active-directory-connect/aad-notification.md)
- [Azure AD Connect Health Notification メールについて](./azure-active-directory-connect/azure-ad-connect-health-notification.md)
- [Azure AD Connect ビルド 1.1.749.0 の注意点](./azure-active-directory-connect/azure-ad-connect-117490.md)
- [Azure AD Connect サービスアカウントに関するセキュリティ アドバイザリについて (MC125948)](./azure-active-directory-connect/azure-ad-connect-mc125948.md)
- [Azure AD (Office 365) 上のユーザーをオンプレミス Active Directory ユーザーと紐付ける方法](./azure-active-directory-connect/upn-hard-match.md)
- [Azure AD Connect で実現するシングル サインオン](./azure-active-directory-connect/seamless-sso.md)
- [DirSync & ADSync – 2017/12/31 で終了のお知らせ](./azure-active-directory-connect/dirsync-adsync-20171231.md)
- [[Azure AD Connect] ID 同期と重複属性の回復性の動作について](./azure-active-directory-connect/duplicate-attribute-recoverability-behavior.md)
- [自動アップグレード機能の問題](./azure-active-directory-connect/auto-upgrade-issue.md)
- [[調査に有効な採取情報] Azure AD Connect サーバーの全般情報](./azure-active-directory-connect/general-information.md)
- [[調査に有効な採取情報] Azure AD Connect でユーザー同期ができない問題](./azure-active-directory-connect/problem-user-synchronize.md)

## AD FS

- [AD FS クレームルール関連のトラブルシューティング](./active-directory-federation-service/adfs-crule-ts.md)
- [AD FS 証明書認証のトラブルシューティング](./active-directory-federation-service/adfs-cba-ts.md)
- Windows Server 2019 AD FS の新機能
- AD FS プロキシの混雑回避アルゴリズムの動作
- [デバイス ベースのアクセス制御](./azure-active-directory/device-based-access-control.md)
- [Office 365 の TLS 1.0/1.1 無効化に伴う AD FS / WAP (AD FS Proxy) の対応](./active-directory-federation-service/adfs-tls12.md)
- [フェデレーション環境 (Windows 統合認証) で [サインインの状態を維持しますか？] の画面が表示されない](./active-directory-federation-service/kmsi-not-shown-wia.md)
- [AD FS の自動証明書ロールオーバー機能について](./active-directory-federation-service/ad-fs-auto-rollover.md)
- [AD FS の証明書更新手順 (SSLサーバー証明書)](./active-directory-federation-service/update-ssl-server-certificate.md)
- [AD FS の証明書更新手順 (トークン署名証明書、トークン暗号化解除証明書)](./active-directory-federation-service/update-token-certificate.md)
- AD FS が PDC と通信するケース
- 証明書利用者信頼のセキュア ハッシュ アルゴリズムについて
- Extranet Lockout について

## その他
- サブスクリプションや請求・課金について (Azure サブスクリプション サポートチーム ブログ)
- Azure IaaS、PaaS、Azure Backup について (Azure テクニカル サポートチーム ブログ)
