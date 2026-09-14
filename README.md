# ServerStarter

ServerStarterは、Minecraft: Java Editionの友達用Vanillaサーバーを、Windowsでかんたんに作成・起動・管理するための初心者向けツールです。必要なJavaやMinecraft公式サーバーは、利用時に公式配布元から取得します。

> [!IMPORTANT]
> 現在はBeta版です。不具合や仕様変更が残る可能性があります。重要なワールドは、利用者自身でも別の安全な場所へ保管してください。

## 対応環境

- Windows 11 64-bit（実機確認済み）
- Minecraft: Java Edition
- .NET RuntimeはEXEに同梱済みで、別途インストール不要

Windows 10 64-bitは今回の実機E2Eでは未確認のため、確認済み環境には含めていません。

## 主な機能

- 新しいVanillaワールドの作成と、作成済みワールドの再開
- 必要なJavaとMinecraft公式サーバーの自動取得・検証
- サーバーの起動、状態表示、コンソール表示、正常停止
- 人数、ゲームモード、難易度、PvP、Whitelistなどの設定
- 起動前の自動バックアップ
- Windows Firewall、UPnP、PCP、NAT-PMPなどの接続診断と案内

## ダウンロード

公開後は、このリポジトリの **Releases** から配布ZIPをダウンロードしてください。

現在、一般公開済みのReleaseはありません。配布ZIP以外のファイルや第三者サイトから入手したファイルは使用しないでください。

## 既知の制限

- 現在はBeta版です。
- 動作確認済み環境はWindows 11 64-bitのみです。
- EXEは未署名で、Windows SmartScreenに発行元不明の警告が出る場合があります。
- バックアップはサーバー起動前に自動作成されます。
- アプリ内からの手動バックアップ作成およびUIからの復元には対応していません。
- ネットワーク環境によって自動公開できない場合があります。
- UPnP、PCP、NAT-PMPを利用できない環境があります。
- MOD、Forge、Fabric、NeoForge、Paper、プラグイン、Bedrock Editionには対応していません。

## Minecraftに関する表示

**NOT AN OFFICIAL MINECRAFT PRODUCT.**  
**NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**

ServerStarter is an independent unofficial tool provided by use pon's lab.

ServerStarterはuse pon's labが提供する独立した非公式ツールです。Minecraft、Mojang、Microsoftによる承認・提携・公認を受けた製品ではありません。

## 提供者・問い合わせ

- 提供者: use pon's lab
- 問い合わせ: https://use-pons-lab-site.pages.dev/contact/

## 文書

- [ライセンス](LICENSE)
- [利用条件](docs/TERMS.txt)
- [プライバシー](docs/PRIVACY.txt)
- [セキュリティ](docs/SECURITY.txt)
- [NOTICE](NOTICE)
- [第三者通知](THIRD_PARTY_NOTICES)
- [.NETおよびWindows SDK関連文書](licenses/)

