# Tone.js

Tone.jsは、ブラウザ内でインタラクティブな音楽を作成するためのWeb Audioフレームワークです。

## 機能

- イベントの同期やスケジューリングを行うグローバルトランスポートなど、DAW（デジタルオーディオワークステーション）の一般的な機能
- あらかじめ用意されたシンセサイザーとエフェクト
- 独自のシンセサイザーやエフェクト、複雑な制御信号を作成するための高性能なビルディングブロック

## インストール

Tone.jsは、`npm`を使用してプロジェクトにローカルインストールできます:

```bash
npm install tone      # 最新の安定版をインストール
npm install tone@next # または、'next'バージョンを使用
```

また、HTMLドキュメント内に直接追加することもできます:

```html
<script src="http://unpkg.com/tone"></script>
<script src="myScript.js"></script>
```

## Hello Tone

```javascript
// シンセサイザーを作成し、メイン出力に接続する
const synth = new Tone.Synth().toDestination();

// 中央の「C（ド）」の音を8分音符の長さで鳴らす
synth.triggerAttackRelease("C4", "8n");
```

## ドキュメント

- [API](https://tonejs.github.io/docs/)
- [サンプル](https://tonejs.github.io/examples/)
- [デモ](https://tonejs.github.io/demos)

## ライセンス

Tone.jsは[MIT License](https://github.com/Tonejs/Tone.js/blob/dev/LICENSE.md)の下で公開されています。
