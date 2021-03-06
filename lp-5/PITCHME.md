### 言語処理のための機械学習入門

2018/07/18 @HirokiTerashima

---

### 項目

5 系列ラベリング

- 5.4 条件付確率場
- 5.5 チャンキングへの適用の仕方
- 5.6 この章のまとめ

---

5.4 条件付確率場

- 系列ラベリングに対数線形モデルを適用したものが**条件付確率場**
- **CRF**という略称が一般的
- ヴィタビアルゴリズムの式の一部を置き換えた形で高速に解くことができる
- **前向き・後ろ向きアルゴリズム**
  - 一次のCRFで使われる学習アルゴリズム
  - 高次の素性関数には向いていない

---

5.5 チャンキングへの適用の仕方

- **チャンキング**とは、言語表現の意味的あるいは文法的にまとまった部分を発見する研究課題
  - ex.) 文章中で人を指している表現を抽出する
- **IBO2タグ**
  - 各トークンに、人を指す表現の開始地点B、その内部I、その外側O、というラベル付けをして人を指している部分を表す
- 他にもIBO1、IEO1、IEO2など

---

5.6 この章のまとめ

- 系列ラベリングについて
  - 隠れマルコフモデル
  - 分類機の逐次適用
  - CRF
  - チャンキング
- この章でやらなかったこと
  - HMMの前向き・後ろ向きアルゴリズム（バウム-ウェルチアルゴリズム）

---

参考

https://www.slideshare.net/uchumik/crf-8416551
http://d.hatena.ne.jp/takeda25/20121108/1352385625
