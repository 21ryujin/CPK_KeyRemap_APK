# CPK_KeyRemap_APK
・Clicks Power Keyboard のキー割り当てを変更するAPKを配布しているリポジトリです。  
・APKは「ExKeyMo」というツールでビルドしています。  
・最下段にある、左から Ctrlキー、丸４つキー、Clicksキー、丸６つキー、マイクキー をより使いやすくします。  
<img width="4000" height="451" alt="CPK_Key" src="https://github.com/user-attachments/assets/e665713c-e571-4181-a535-875be33fa4cf" />
  
  
## おしらせ
Ver.3 をリリースしました。  
このバージョンでは、Clicks設定アプリのインストール有無、Androidのバージョン、操作モード（Androidモード、iOSモード）、機種に関係なく、これ１つで賄えるようになりました。  
  
動作に関しては、下記環境で確認しています。  
### ■Clicks Power Keyboard側
　　・ファームウェアVer 1.1.2  

### ■端末側
　　・F(x) tec Pro1-X（LineageOS 23.2 = Android 16、Clicks設定アプリインストール済み）  
　　・moto g7（LineageOS 22.2 = Android 15、Clicks設定アプリ未インストール）  
　　・楽天mini　C330（Android 9）  
　　・Unihertz Jelly-Pro（Android 8.1.0）  

## APKのダウンロードはこちら
　　https://github.com/21ryujin/CPK_KeyRemap_APK/releases/tag/Ver.3
　　ExKeyMo.Keyboard.Layout.apk をダウンロードしてください。
  
## APKのインストールで変更されるキー
・Ctrlキー：iOSモードでCtrlキーが有効化されます  
・Clicksキー：全角／半角切り替え  
・丸４つキー：カーソル左  
・丸６つキー：カーソル右  
・マイクキー：Shift  
  
### 利用する上での注意事項
#### １）Android 8.xの端末については、この操作を行ってください
　　Clicks Power Keyboardとスマホをペアリングしたら、電源ボタン＋Aキーを押下してください。  
　　　⇒Androidモードに変更され、Ctrlキーが効くようになります。  
　　　⇒なお、電源ボタン＋Iキーで、元の状態（iOSモード）となります。  

#### ２）Clicks設定アプリをインストールしている場合は、下記を設定してください。  
　　・Additional Settings を「Alt」に設定  
　　・Tab Settings を「Tab」に設定  

  
## インストール方法
１）APKをダウンロード  
２）ファイルアプリを開き、apkファイルをタップ  
３）Google Playからのアプリスキャン要求のウィンドウが表示された場合は、スキャン後にインストール  
  
  
## インストール後の作業
１）Clicks Power Keyboard に接続  
２）設定 ＞ システム ＞ 言語と入力 ＞ 物理キーボード ＞ Clicks Power Keyboard の表示をタップ ＞ キーボードレイアウトの設定 ＞ ExKeyMo Layout のみを選択  
３）画面を戻して、Clicks Power Keyboard のデフォルトレイアウトが「ExKeyMo Layout」になっていることを確認  
４）スマホを再起動  
  
【注１】設定してもキーの動きがおかしい場合は、端末の再起動を行ってください！  
【注２】手順２～３は、端末によって若干メニューや辿り方が違う場合もあるので、雰囲気でその辺掴んでくださいｗ  
  
  
## Complex_code.txt について
・「ExKeyMo」を使ってリマップ用のAPKをビルドしたい方用の参考用コードです。  
・「ExKeyMo」については、こちらのnote記事を参照いただければと思います。  
　Androidタブレットの「死にキー」を有効活用する裏技  
　https://note.com/xiaoxiongmao/n/nddd5b82f48b8  
  
  
## Android端末で Clicks Power Keyboard を使うに当たってわかったことまとめ
<img width="985" height="622" alt="20261008_Scan_Code" src="https://github.com/user-attachments/assets/f4581557-9e21-48b4-bfdb-733930d647fa" />

