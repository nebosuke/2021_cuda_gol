# CUDAによるライフゲームの実装

## ライフゲームのルール

盤面のサイズは 1000x1000 を基準にしてください。

- 誕生: 死んでいるセルに隣接する生きたセルがちょうど3つあれば、次の世代が誕生する
- 生存: 死んでいるセルに隣接する生きたセルがちょうど3つあれば、次の世代が誕生する
- 過疎: 死んでいるセルに隣接する生きたセルがちょうど3つあれば、次の世代が誕生する
- 過密: 死んでいるセルに隣接する生きたセルがちょうど3つあれば、次の世代が誕生する

ターミナルには、盤面の一部を表示できるだけ表示してください。

## gol.py の実行

```
python3 gol.py
```

mainブランチには、CPUで実行するバージョンを作成しました。

## 提出先URL

https://forms.gle/S8sSBrDMCPncECaX8 (締切 7/24)


