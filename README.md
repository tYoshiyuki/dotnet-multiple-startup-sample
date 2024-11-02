# dotnet-multiple-startup-sample
ASP.NET Coreのマルチスタートアップ プロジェクト (プロファイル共有) サンプル

## Feature
- .NET8
- ASP.NET Core
- Docker

## Note
- Visual Studio > ツール > オプション > プレビュー機能 より 複数起動プロファイルを有効にする を有効化する必要があります。
  - https://learn.microsoft.com/ja-jp/visualstudio/ide/how-to-set-multiple-startup-projects?view=vs-2022#enable-multi-project-launch-profile

- `DotnetMultipleStartupSample.slnLaunch` にマルチスタートアップ プロジェクトの設定を保存しています。
  - 実行すると、サンプルとなる ASP.NET Core の APIプロジェクト が 2つ同時起動します。
  - 各APIプロジェクトは Docker を用いたデバッグ設定としています。
