# 駆けろ！こうかとん

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
* プレイヤーは「こうかとん」を操作し、障害物を避けながら地面に落ちないように足場を飛び移り、スコアを稼いでいくゲームです。
* 参考URL：[スクラッチでスーパーマリオランの作り方](https://bingo-ojisan.xyz/2024/07/20/supermariorun/)

## ゲームの遊び方
* スペースキー：こうかとんをジャンプさせる。ジャンプ中にさらにスペースキーを押すことで、もう一度ジャンプ（2段ジャンプ）することができる。
* 「こうかとん」が地面に落ちるとゲームオーバーになる。

## ゲームの実装
### 共通基本機能
* 背景画像とこうかとんの描画
* 流れてくるブロックの描画
* 無限にジャンプが可能
* Fキーで空中浮遊が可能:MPを消費し続ける

### 分担追加機能
* ブロックに関する関数・２段ジャンプの追加（担当：武末）：ランダムなブロックを生成する関数、ブロックの移動のための関数、ブロックとの衝突判定をする関数、２段ジャンプ機能の導入
* 
* 
* 
* MP機能（担当:髙野）：一定時間ごとに10増え続けるMPを追加
* 浮遊機能（担当：髙野）：Fキーを押下するとMPを消費し続ける代わりに空中に浮遊が可能
* キッチンタイマー機能（担当：ぷしみ）：制限時間以内に調理が完了しなかった場合に，豪華豚が脱走する機能
* 調理機能（担当：ぶしみ）：調理器具をキー押下により選択し，豪華豚を調理する機能

### ToDo
- [ ] ブロックの上に障害物の追加
- [ ] ジャンプ音などの追加

### メモ
