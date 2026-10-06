<!-- ELUCENIA technical documentation · escore-de-mirels · zh · no clinical/professional/rights approval -->

# Mirels 评分

[条件、来源与许可](https://elucenia.org/zh/tools/escore-de-mirels)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 病灶部位

`local`

- `1` — 上肢
- `2` — 下肢
- `3` — 转子周围

### 疼痛

`dor`

- `1` — 轻度
- `2` — 中度
- `3` — 功能性疼痛（负重时）

### X 线表现

`lesao`

- `1` — 成骨性
- `2` — 混合性
- `3` — 溶骨性

### 大小（占骨直径的比例）

`tamanho`

- `1` — 小于1/3
- `2` — 1/3至2/3
- `3` — 大于2/3

## 方法版本

Mirels 1989：部位/疼痛/病灶/大小1–3，总分4–12

## 已记录的公式

四项各1至3：部位（上肢1、下肢2、转子周3）、疼痛（轻1、中2、功能性3）、病灶（成骨1、混合2、溶骨3）、大小占骨径（\<1/3：1；1/3至2/3：2；\>2/3：3）。总分4至12。

## 限制与适用人群

1989年的Mirels评分在接受放射治疗、未进行预防性固定的长骨转移病灶中开发，骨折在六个月内评估。原始摘要与后续解释版本不一定使用相同决策阈值；应明确版本和对应处理方式。总分本身不能决定选择放疗还是手术。

## 参考文献

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

最多 7 分：骨折低风险（约 4%）

放疗和观察。


### 2

8 分：中等风险（约 15%）

临床判断：考虑预防性固定。


### 3

9 分或以上：骨折高风险（33% 或以上）

放疗前进行预防性固定。


### 4

9 分或以上：骨折高风险（33% 或以上）

放疗前进行预防性固定。

