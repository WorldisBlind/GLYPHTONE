# GLYPHTONE

ブラウザで動作する16×16のステップシーケンサーです。単一のHTMLファイルとして動作するので、インストール不要でそのまま開いて使えます。

https://worldisblind.github.io/GLYPHTONE/

## 特徴

- 16×16のグリッドに音を並べて曲を作るステップシーケンサー
- 9種類の音色(BELL / PIANO / ORGAN / STRINGS / BRASS / LEAD / PAD / BASS / DRUM)
- Solo(1マス1音色)/ Ensemble(1マスに複数音色を重ねる)の2モード
- 10種類のスケール切り替え、オクターブ±2の移調
- テンポ・スイングの調整
- Generateボタンでフレーズを自動生成(Up / Down / Wave / Random / Drumなど10パターン)、Undo / Clear対応
- 4つの小節(1 BAR〜4 BAR)を切り替えて作曲でき、それぞれ自動保存
- 小節ごとのチェーンマークで、マークした小節だけを順番に連続再生
- WAV / MIDIファイルへの書き出し
- 画面サイズに合わせて自動的に全体表示を縮小

## 使い方

1. `index.html` をブラウザで開く(またはGitHub Pagesのデモリンクにアクセス)
2. グリッドをタップして音を配置
3. ▶ボタンで再生
4. テンポ・スケール・音色などを各コントロールで調整
5. 必要に応じてWAVまたはMIDIとして書き出し

アプリ右上の「?」ボタンから、いつでも詳しい使い方を確認できます。

## 動作環境

Web Audio APIに対応した最新版のブラウザ(Chrome、Safari、Firefoxなど)で動作します。

## ライセンス

[MIT License](./LICENSE)
