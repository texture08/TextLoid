# TextLoid 
TextLoid(以下本ソフト)は [ボイスロイド](https://www.ah-soft.com/voiceroid/) の支援ツールです
<br>本ソフトはボイスロイドの音声をテキストファイルから一行づつ呼び出し、生成するツールです

## インストール
[Releases](https://github.com/texture08/voiceroid_tool/releases) から最新のzipをダウンロードして展開してください

## アンインストール
展開したフォルダを削除してください

## アップデート
[Releases](https://github.com/texture08/voiceroid_tool/releases) から最新バージョンをダウンロードして展開してください。
<br>キャラクターの情報を引き継ぐには、前バージョンのフォルダ内にあるchar.jsonを上書きしてください。
<br>また、設定を移行する場合はset/config.jsonを上書きしてください
<br>なお、新項目が追加された場合、エラーが出る可能性があるので、必ずバックアップを取ってください

## 使い方
[Releases](https://github.com/texture08/voiceroid_tool/releases) からzipファイルをダウンロードします
<br>好きな場所に解凍したらインストールは完了です
<br>任意のフォルダにexeファイル、script.txt、その他のファイルやフォルダができます
<br>script.txtには生成したいテキストを行ごとに書きます
<br>次にexeファイルを起動します
<br>コンボボックスから、ご使用のボイスロイドを選択します
<br>ない場合は自分で追加してください
<br>次にボイスロイドを起動して、ボイスロイドのテキスト欄に文字を書いてください
<br>なんでもいいので書いたら消してください
<br>これは必要なことなので、めんどくさいですがやってください
<br>最後に、本ソフトの合成を押したら生成が開始されます
<br>[ニコニコ動画](https://nico.ms/sm39961372) と [YouTube](https://youtu.be/wTHKdOxWHso) にも使い方を載せています
<br>※初期リリースとインストールの仕方や使い方が変わっているので注意してください

## 注意
ファイル生成中はマウスを動かさないでください
<br>変に動かしてしますとできなくなってしまいます
<br><br>本ソフトによる損害、不利益などは製作者は一切責任を取りません
<br><br>VOICEVOX、棒読みちゃん等での使用はできません
<br>今後の課題にしていこうと思います

## config.jsonについて
config.jsonには本ソフトの設定項目があります。

## 設定について
ソフト上でconfig.jsonが変更できます
<br>また、config.jsonを直接編集することも可能です
### 生成完了後、終了ウィンドウを表示
生成完了した際に、確認ウィンドウを表示するかどうかを設定します
### 台本を選択
生成に使うテキストファイルを選択します
### ボイスロイドを追加
ボイスロイドのウィンドウを追加します
### 初期状態に戻す
設定を初期状態に戻します

## 利用規約
二次配布、自作発言は禁止です
<br>営利利用、商用利用等は [こちらのライセンス](https://www.ah-soft.com/licensee/voice_individual.html) をご覧ください
<br>クレジット表記は不要です
<br>改造等はご自由にどうぞ

## 動作環境
| OS | ◯✕ |
| --- | --- |
| Windows  7 | ✕ |
| Windows 10 | ◯ |
| Windows 11 | ◯ |
| Mac | ✕ |
| Linux | ✕ |

Mac、Linuxへの対応は考えていません。

## 使用したパッケージ、ライブラリ等
opencv
<br>tkinter
<br>win32gui
<br>json
<br>pyautogui
<br>pyperclip

<br><br>バグ、お問い合わせは [Twitter@H2DH8K](https://twitter.com/H2DH8K) までお願いします

## リリース ![Num of dls](https://img.shields.io/github/downloads/texture08/TextLoid/total?color=%236643B2&style=flat-square)
### v1.0.0
- 初回リリース
- 諸事情により非公開
### v.2.0.0
- インストール方法の変更
- 生成完了後、確認ダイアログを表示
### v.2.1.0
- 一行目が無視されるバグの改善
- 生成完了後、確認ダイアログを表示するかどうかを設定で変更可能に
- コンフィグにて、参照するファイルを変更可能に

### v.2.2.0
- ソフトの名称を変更
- config.jsonを編集
- ボイスロイドの選択をコンボボックスに変更

### v.2.2.1
- デザインの変更
- 生成方法の変更
- エラーログの追加
- 生成時間の短縮

### v.2.3.0
- デザインの変更
- 設定タブの追加

### v.2.4.0
- キャラクターファイルの追加
- キャラクターの登録をソフト側で可能に
