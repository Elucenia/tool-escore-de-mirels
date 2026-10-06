<!-- ELUCENIA technical documentation · escore-de-mirels · ja · no clinical/professional/rights approval -->

# Mirelsスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/escore-de-mirels)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 病変部位

`local`

- `1` — 上肢
- `2` — 下肢
- `3` — 転子周囲

### 痛み

`dor`

- `1` — 軽度
- `2` — 中等度
- `3` — 機能時（荷重時）

### X線所見

`lesao`

- `1` — 造骨性
- `2` — 混合性
- `3` — 溶骨性

### 大きさ（骨直径に対する比率）

`tamanho`

- `1` — 1/3未満
- `2` — 1/3～2/3
- `3` — 2/3超

## 方法の版

Mirels 1989：部位/痛み/病変/大きさ1–3、合計4–12

## 記載された計算式

4項目各1～3：部位（上肢1、下肢2、転子周囲3）、痛み（軽1、中2、機能時3）、病変（造骨1、混合2、溶骨3）、大きさ対骨径（\<1/3：1、1/3～2/3：2、\>2/3：3）。合計4～12。

## 限界・対象集団

1989年のMirelsスコアは、予防的固定を行わずに放射線照射された長管骨の転移性病変で開発され、六か月の間に骨折を評価しました。原抄録と後の解釈版は、必ずしも同じ判断の閾値を用いていません。版と対応する対応方針を明示する必要があります。合計点だけでは、放射線治療と手術のどちらを選ぶかは決まりません。

## 参考文献

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

7点まで：骨折リスクが低い（約4%）

放射線療法と経過観察。


### 2

8点：中間リスク（約15%）

臨床判断：予防的固定を考慮する。


### 3

9点以上：高い骨折リスク（33%以上）

放射線療法前の予防的固定。


### 4

9点以上：高い骨折リスク（33%以上）

放射線療法前の予防的固定。

