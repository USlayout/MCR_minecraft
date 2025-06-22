# Minecraft Launcher with Cloudflared セットアップガイド

## 必要なもの

- [Cloudflared](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/install-and-setup/installation/)  
    インストールしていない場合は、以下のコマンドを管理者権限で実行してください。

    ```sh
    winget install --id Cloudflare.cloudflared
    ```
-MCR-minecraft-launcher.exe
    ダブルクリックで実行してください。
    [WindowsによってPCが保護されました]と表示される場合は、詳細情報を押してそのまま実行してください。
    実行すると最初にMinecraftランチャーのパスを入力してください。
    次にポートを入力してください、デフォルトは20100に設定されています。
    ホスト名はデフォルトのままで大丈夫です。

    <p>.exeファイルを実行すると.exeファイルのあるディレクトリにconfig.josonファイルが生成されます。
    <p>適宜ショートカットリンクを用いるなどしてください。
    
- Minecraft Launcher  
    パスの例:  
    C:\Program Files\Minecraft\launcher.exe


- リンクをクリック>ウェブサイトの"Code">"Zip"の順にクリックしてダウンロード
  <P>[github]https://github.com/mcr-2024b/MineCRaft_ModCliant

    .zipファイルを展開(解凍)

- [Java 8]
    入っていない場合インストールしてください
    JavaSetup8u421.exeをクリックしてJava 8をインストール

- [Forge 1.12.2]
`forge-1.12.2-14.23.5.2860-installer.jar` を実行してインストールしてください。

## サーバーへの接続方法
1. Minecraft LauncherでForgeを一度起動し、すぐ終了してください。  
⚠pathを正しく指定しないと無意味なので注意してください

2. 生成されたModファイルに.zipに存在するすべてのmodデータを入れてください

3. もう一度起動して個人用に設定を調整する

## サーバーの追加

1. Minecraft内で「サーバーを追加（Add Server）」をクリックします。
2. サーバーアドレスには、自分が指定したポートを入力します。  
   例: `localhost:00000`

---

何か問題が発生した場合は、Discordからご連絡ください。
