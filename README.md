# SkEditor
Skriptを簡単に編集できるように[Hot Soup Processor v3.6](https://hsp.tv/)で作られたエディタです。
## Requirements
SkEditorではWindowsが必要です。当然のことですが、MacやLinuxでは動作しません。Windows 10が推奨されます。  
  
SkEditorは現在Windows 10でしか動作確認が取れていませんが、Windows XP～Windows 8.1、Windows 11でも動作すると思います。  
  
仮想環境ではどうなるかわかりません。Wineでは動作すると思いますが、テストしていないのでわかりません。
## Download
各バージョンのダウンロードとリリースノートは、[リリースページ](https://github.com/nennneko5787/SkEditor/releases/)で見つけることができます。
## Documentation
準備中です、しばらくお待ち下さい...
## Reporting Issues
問題の報告は[issues](https://github.com/nennneko5787/SkEditor/issues/)かPlayerRealms Skript CommunityのDiscordでどうぞ。
## Help Us Test
Skript の新機能とリリースのテストを手伝いたいですか? PlayerRealms Skript CommunityのDiscordにアクセスすると、新しい機能やリリースのテストが開始されるたびに、最初に知ることができます。  
  
え？PlayerRealms Skript Communityがどこかわからないって？Googleで探せば出るのでGoogleで調べ~~ろ~~ください。
## Compiling
SkEditorはコンパイルに[Hot Soup Processor v3.6](https://hsp.tv/)を使用します。ＨＳＰスクリプトエディタを使用して、``SkEditor.hsp``を開きます。。その後、[ＨＳＰ(P)]→[実行ファイル自動作成(A)](Ctrl + F9)を使用しSkEditorをコンパイルし、実行ファイルにするだけです。
![ＨＳＰスクリプトエディタのスクリーンショット](https://i.imgur.com/tLgrLuL.png)
ソース コードは[リリースページ](https://github.com/nennneko5787/SkEditor/releases/)から入手できます。このリポジトリのクローンを作成することもできますが、そのコードは安定していない可能性があります。
### テスト
ＨＳＰスクリプトエディタでコードをテストしたいだけの場合は、[ＨＳＰ(P)]→[コンパイル・実行(C)](F5)を使用してください。
### Visual Studio Codeの使用
[この記事](https://qiita.com/yama_1983/items/4d02b52c2698108d4bbd)をの通りにVisual Studio Codeを設定し、[F1]キー→[hsp:Automatic exe file creation]を使用し、SkEditorをコンパイルし、実行ファイルにします。  
  
奇妙な問題が発生した場合は、上記の手順に従い、しっかりと設定するか、実行ファイルの生成はＨＳＰスクリプトエディタを使用してください。Visual Studio Codeから実行ファイルを作成しようとすると、``#No file [C:\hsprt].``エラーが出てうまく動作しません。また、Hot Soup Processor v2.xは使用しないでください。それは時代遅れです。
### Visual Studio Codeでのテスト
Visual Studio Codeでコードをテストしたいだけの場合は、右上の[Run HSP program]を使用してください。
## Contributing
このリポジトリに[プルリクエスト](https://github.com/nennneko5787/SkEditor/pulls/)を送信してください。それが良いものであれば採用されるでしょう。
## Relevant Links
* [SkriptLang 公式リポジトリ](https://github.com/SkriptLang/Skript)
* [SkriptLang ドキュメント](https://docs.skriptlang.org/)
* [skUnity フォーラム](https://forums.skunity.com)
* [skUnity アドオンのリリース](https://forums.skunity.com/forums/addon-releases)
* [skUnity Discord招待リンク](https://discord.gg/0l3WlzBPKX7WNjkf)
* [Skript Chat Discordの招待リンク](https://discord.gg/0lx4QhQvwelCZbEX)
* [Skript Hub](https://skripthub.net)
* [Original Skript at Bukkit](https://dev.bukkit.org/bukkit-plugins/skript) (非アクティブ)
* [PlayerRealms Skript CommunityをGoogleで検索した結果](https://www.google.com/search?q=playerrealms+skript+community)  
これらのリソースは SkEditorの開発者によって保守されていないことに注意してください。これらに関して発生する可能性のある問題については、SkEditorに質問しないでください！！
## Developers
すべての協力者は[ここ](https://github.com/nennneko5787/SkEditor/graphs/contributors)か[ここ](https://github.com/nennneko5787/SkEditor/blob/main/contributors.md)で確認することができます。  
  
すべてのコードはその作成者が所有しており、特に指定がない限り、GPLv3(ライセンスを参照)に基づいて他のコードにライセンスされています。(※ライセンスは変更する予定です)
## Skriptさんごめんなさい！！
このREADME.mdは[SkriptLang 公式リポジトリ](https://github.com/SkriptLang/Skript)のREADME.mdに似せました。ごめんなさい！！