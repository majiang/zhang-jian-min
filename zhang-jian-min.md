# 張建民杯の卓組

## 前提

* 5ラウンド
* 地元組mペア, 遠征組nペア
* パートナーとは同卓しない
* すでに対戦したプレイヤーとは同卓しない

### 帰結

* 10ペア20人は必要

## 評価

* 個人-ペア間の同卓数についての公平性
* ペア-ペア間の同卓数についての公平性
* 地元-遠征間の総同卓数の多さ


### ペア間の同卓数を優先

* 総同卓数 = 15(m+n)
* 総2ペア組数 = (m+n)(m+n-1)/2
* ペア間の同卓数 = (floor, ceil)(30/(m+n-1))
    * 14ペア以下: 2-3
    * 16ペア: 2
    * 18ペア以上: 1-2

### 地元-遠征間の総同卓を優先

以下の表は縦が合計ペア数・横が少ない種類のペア数を、内容が1ラウンドあたり地元-遠征間の最大総同卓数を表す。
全ペアのうち少ない種類が1/4以下のときは少ない種類のペア数のみによって定まる。

* 00 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16
* 02 04
* 04 06 08
* 06 06 10 12
* 08 06 12 14 16
* 10 06 12 16 18 20
* 12 06 12 18 20 22 24
* 14 06 12 18 22 24 26 28
* 16 06 12 18 24 26 28 30 32
* 18 06 12 18 24 28 30 32 34 36
* 20 06 12 18 24 30 32 34 36 38 40
* 22 06 12 18 24 30 34 36 38 40 42 44
* 24 06 12 18 24 30 36 38 40 42 44 46 48
* 26 06 12 18 24 30 36 40 42 44 46 48 50 52
* 28 06 12 18 24 30 36 42 44 46 48 50 52 54 56
* 30 06 12 18 24 30 36 42 46 48 50 52 54 56 58 60
* 32 06 12 18 24 30 36 42 48 50 52 54 56 58 60 62 64



