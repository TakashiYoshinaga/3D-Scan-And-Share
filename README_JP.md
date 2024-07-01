# 3D Scan And Share System
[![](https://img.youtube.com/vi/5IKGkQtX96k/0.jpg)](https://www.youtube.com/watch?v=5IKGkQtX96k)


# セットアップ手順

1. **ネットワーク接続**
   - PCとiPhoneを同じネットワークに接続してください。

2. **アプリケーションのインストール**
   - iPhone/iPadにアプリをインストールしてください。
     * ダウンロードリンクについては私にお問い合わせください [X](https://twitter.com/Taka_Yoshinaga),[LinkedIn](https://www.linkedin.com/in/tks-yoshinaga/)
     * このアプリはiPhone/iPadで動作します。LiDARセンサーが搭載されているモデルだと尚良しです。
   - このリポジトリからLooking Glass用のアプリをダウンロードしてください。 [Download](https://github.com/TakashiYoshinaga/3D-Scan-And-Share/releases)
   - 公式ウェブサイトからLooking Glass Bridgeをダウンロードしてインストールしてください： [Looking Glass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).
   - ディスプレイ設定を確認してください。[Display Setting](https://docs.lookingglassfactory.com/software-tools/looking-glass-bridge/display-settings-on-windows)

# アプリケーションの使用方法

1. **デバイスの接続**
   - PCとLooking Glass PortraitをHDMIケーブルで接続してください。

2. **ソフトウェアの起動**
   - Looking Glass Bridgeを起動します。
   - `3DObjectViewer.exe` (Windows)を起動します。
   - PCのIPアドレスがLooking Glassに表示されていることを確認してください。

3. **iPhone/iPadアプリの開始**
   - iPhone/iPadアプリを開きます。
   - アプリ内でIPアドレスを入力し、`Set`ボタンをタップしてください。

4. **3Dスキャン**
   - このページに掲載したビデオを参照してスキャン及び共有を行ってください
   - Looking Glassでの閲覧の際は下記の操作が可能です。  

| 操作              | 説明                 |
| ----------------- | -------------------- |
| 左ドラッグ        | 上下左右の移動       |
| 右ドラッグ        | 回転                 |
| スクロール        | 前後移動             |
| Ctrl + スクロール | 拡大縮小             |
| 右矢印(キーボード)            | 次のオブジェクト表示 |
| 左矢印(キーボード)            | 前のオブジェクト表示 |
| R(キーボード)            | 回転リセット |
| D(キーボード)            | 現在のオブジェクトの削除 |
| Q(キーボード)            | Quilt画像のエクスポート|


  
# 3Dモデルファイルの追加と削除
   - 3DObjectViewer.exeと同じディレクトリ内の`dl`フォルダ内にファイルがあるので適宜追加または削除をしてください。
   - また3DObjectViewer.exe実行時に`Dキー`を押下することで表示中のオブジェクトを削除できます

# データのエクスポート
   - 3DObjectViewer.exe実行時に`Qキー`を押下することで下記のディレクトリにQuilt画像が保存されます。  
3DScanObjectViewerForWindows -> Quilts


# トラブルシューティング
- iPhoneからPCに3Dモデルを転送したのち、すぐにLookingGlassにそのモデルが表示されない場合は、ファイヤーウォールの設定から当アプリケーション(3DObjectViewer.exe)を一度削除してください。  
または、このアプリケーションを使用しているときだけ一時的にファイヤーウォールをオフにしてください。  
[アプリ毎のファイヤウォール設定(Windows)](https://www.fmworld.net/cs/azbyclub/qanavi/jsp/qacontents.jsp?PID=9810-8377)
- スキャンアプリ(iOS)のバージョンをアップデートした際、スキャン終了後にアプリがクラッシュすることがあります。その場合はiPhoneを再起動したのちに再度スキャンをお試しください。
- 受信アプリが3Dオブジェクトを受信できない場合が稀にあります。その場合はPC(またはQuest)を再起動してください。
  
# Depth Video Player
3Dスキャンオブジェクトの表示ではなくDepth付きのビデオの録画と再生に興味がある方は下記のアプリケーションもお試しください！  
https://github.com/TakashiYoshinaga/DepthVideoPlayer
