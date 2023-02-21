# Rough_nako3
Rough.jsを使って、なでしこ３でキャンバスに手書きっぽい描画をするプラグイン

## 使い方
　[なでしこ３貯蔵庫にライブラリとして公開しています。](https://n3s.nadesi.com/id.php?1778)

　プログラム冒頭で取り込みます。

```
！『https://n3s.nadesi.com/plain/Rough.nako3』を取り込む。
```

　[なでしこ貯蔵庫](https://n3s.nadesi.com/index.php?page=all&action=list)で使う前提で作成したので、最初にRough.jsのCDN取り込み用のスクリプトタグをhtmlのヘッダに埋め込んで取り込み完了待ちしていますが、自前のhtmlで使う場合には当然html側にスクリプトタグを書いた方が早いです。

　`id`に`rough`を付けることで、スキップするようにしています。

```
<script id="rough" type="text/javascript" src="https://unpkg.com/roughjs@latest/bundled/rough.js"></script>
```

## テスト

- [色々描画](https://n3s.nadesi.com/widget.php?2019&run=1)
