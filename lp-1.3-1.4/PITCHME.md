### 言語処理のための機械学習入門1.3-1.4

2018/03/01 @HirokiTerashima

---

### 項目

1 必要な数学的知識
- 1.3 確率
- 1.4 連続確率変数

---

### 1.3 確率

---

### 事象

- スポーツで「チームTの試合結果」という例がある
- チームTが勝つ、などの出来事を「事象」
- 事象の集合を「事象空間」
- チームTが勝つ確率が80%だった場合、以下のように表す
$$P("チームTが勝つ") = 0.8$$

---

### 確率変数

- それぞれの実現値に対して0〜1の確率値が対応しているような値
- 「チームTの2試合の勝利数」を表す確率変数を$X$とすると$X$は0, 1, 2
- 確率変数は一般的に大文字、その対応する値は小文字で表す
$$P(X = 0) = 0.1, P(X = 1) = 0.3, P(X = 2) = 0.6$$
- 実用上$X = $を省略して$P(x)$と書くことが多い

---

### 確率変数

- 確率変数のすべての値は足すと1になる
$$\sum_{x \in Xの値の集合}P(x) = 1$$
- どの値がどのくらいの確率を持っているのかを記述したものを**確率分布**
- 確率分布を表した関数を**確率質量関数**もしくは**確率関数**

---

### 期待値, 平均, 分散

- 確率変数Xの**期待値**もしくは**平均**$m_X$は以下で定義する
$$m_X = \sum_x xP(X = x)$$