
# Introduction
## 目的

MRIスキャンにおいて、胃(stomach)と腸(intestines)を自動でセグメンテーションする方法を模索する。
実際に患者データを用いて行う。



## Evaluation

Dice coefficient に0.4、Hausforffに0.6の重みを付けてスコアを算出する。

### Dice coefficient

予測したセグメンテーション領域とground truthとのピクセル単位での一致度合いを計算する。
テスト画像における各画像のdice coefficientの平均値をとって、LBスコアとする。


### Hausdorff

二物体における最も遠い点と近い点との距離を計算する。

# Data


# Logs

## 2022/05/24

- 立ち上げ、概要の把握
- ひとまずU-Netを使用するのが良さげ？
