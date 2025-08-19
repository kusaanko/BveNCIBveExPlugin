# BveNCIBveExPlugin

![C#](https://img.shields.io/badge/-C%23-512BD4?logo=csharp&style=for-the-badge)
![.NET Framework](https://img.shields.io/badge/-.NET%20Framework-512BD4?logo=.NET&style=for-the-badge)
![Supports BVE5](https://img.shields.io/badge/supports-Bve5-green?style=for-the-badge)
![Supports BVE6](https://img.shields.io/badge/supports-Bve6-orange?style=for-the-badge)
![Made for BveEX](https://img.shields.io/badge/Made%20for-BveEX-68EDD1?style=for-the-badge)
![Release](https://img.shields.io/github/v/release/kusaanko/bvencibveexplugin?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/kusaanko/bvencibveexplugin/total?style=for-the-badge)

BVE5、6 用のコントローラー入力プラグイン NumerousContollerInterface に BveEX と連携する機能を追加するための BveEX プラグイン

Supported language is only Japanese now.

> [!WARNING]
> BveEX との連携機能はまだまだ不安定であり、手動でのインストールが必要です。詳しくは下の項目をご覧ください。

# ダウンロード

[Releases](https://github.com/kusaanko/BveNCIBveExPlugin/releases)からダウンロード

`NumerousControllerInterfaceBveExPlugin.zip`がプラグインの本体です。

# インストール

まだこの機能は不安定のためインストーラーから自動でインストールできません。

`NumerousControllerInterfaceBveExPlugin.zip`をダウンロードし、中にある`NumerousControllerInterfaceBveExPlugin.dll`のプロパティを開き、セキュリティを許可して下さい。

![許可](https://github.com/kusaanko/BveNCIBveExPlugin/blob/main/pic/1.jpg?raw=true)

そして、このファイルを`C:\User\Public\Documents\BveEX\2.0\Extensions`もしくは`Input Devices\BveEX\2.0\Extensions`に入れてください。

NumerousControllerInterface の設定画面のタブから`BveEX`より、正常に読み込めたかどうかが確認できます。また、正常に読み込めていた場合にはコントローラー設定の BveEX が選択可能になっています。
