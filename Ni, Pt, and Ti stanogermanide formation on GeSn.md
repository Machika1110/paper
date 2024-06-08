# Ni, Pt, and Ti stanogermanide formation on Ge0.92Sn0.08

URL : https://ieeexplore.ieee.org/abstract/document/9041907 

## 概要
2019年に発表された、Geに8%のSnを混ぜた基板上に、CVD法でNi、Pt、Tiを蒸着して生成されるスタノジャーマナイド（Stanogermanide）に関する論文。
実験の結果、NiGeSnが最も低抵抗で、400℃で形成された。また、PtGeSnは熱安定性を示した。また、Tiは500℃以下では反応が起こらなかった。  
※ちなみに、Stanogermanideの「Stano」は **エスぺエランド語でスズ** である。

## イントロ
ここ10年で、Geやその合金GeSnは、CMOS等のSiの代わりの候補として約束されている（？）。ソースドレインコンタクトの寄生抵抗がプロセスのボトルネックになっている。GermanideやStanogermanideはGeやGeSnのコンタクト材料と有用である。また、GeSnはGeほどの研究がなされていない。

## 実験方法
実験プロセスの一覧（Figure 1.から）
 - Acetone for 30s
 - Isopropyl alcohol for 30s
 - Deionixed water for 30s
 - Metal deposition
 - Rapid Thermal Annealing for 30s [300-500℃]
 - SEM, TEM, EDX, AFM 4PP

以下が大まかな流れ
- 厚さ **28nm** のGe0.92Sn0.08に、CVD法で金属（Ni、Pt、Ti）を **10nm** 蒸着した。
- FC2000 electron beam evaporator を使用
- 圧力は $5×10^{-7}$ Torr
- N2アンビエントRTAでアニールし、300～500℃（１ステップ50℃）

## 結果
表面のラフさをRMSとして示した結果が以下
||NiGeSn|PtGeSn|TiGeSn|
|:--:|:--:|:--:|:--:|
|300℃|5.11 nm|7.08 nm|8.44 nm|
|500℃|10.2 nm|6.97 nm|12.7 nm|

- 膜の厚さ自体は20 nmほどだが、Tiは微妙

シート抵抗は、
- NiGeSnがアニール温度が上がるにつれ増加
- TiGeSnは400℃までは増加してその後変化なし
- PtGeSnは400℃までわずかに減少してその後変化なし

## 結論
- NiとPtは連続的なStanogermanideの層が形成できたが、Tiは無理だった
- NiGeSnは形成温度435℃まで最高の低抵抗性能を示し、それ以上の温度ではシート抵抗の点でPtGeSnがNiGeSnを上回った
- NiとPtの合金をコンタクトとして用いるのが良いのではないか？？