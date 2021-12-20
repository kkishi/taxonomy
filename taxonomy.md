* 線形代数
    * 連立方程式
        * 掃き出し法 ([解説](https://drken1215.hatenablog.com/entry/2019/03/20/202800), [Xor Battle](https://atcoder.jp/contests/agc045/tasks/agc045_a))
        * 解の個数 ([Flip Flap](https://atcoder.jp/contests/typical90/tasks/typical90_be))
    * 線形変換・アフィン変換 ([Rotate and Flip](https://atcoder.jp/contests/abc189/tasks/abc189_e))
* ゲーム
    * Grundy数 ([解説](https://www.creativ.xyz/grundy-number-1065/), [VS AtCoder](https://atcoder.jp/contests/typical90/tasks/typical90_ae), [Interval Game 2](https://atcoder.jp/contests/abc206/tasks/abc206_f))
    * 後退解析 ([Shiritori](https://atcoder.jp/contests/abc209/tasks/abc209_e))
* xor
    * [はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/05/20/145021)
    * `x+y = (x^y)+2*(x&y)` ([Unfair Nim](https://atcoder.jp/contests/abc172/tasks/abc172_f))
* 幾何
    * 偏角ソートは境界付近に気をつける。STLのargは[-π, π]を返すので、-πに丸める ([Congruence Points](https://atcoder.jp/contests/abc207/tasks/abc207_d))
* 数列
    * 区間和問題はzero sum rangesを疑う ([うしさんのtweet](https://twitter.com/ei1333/status/1408791847426695174), [Diluc and Kaeya](https://codeforces.com/contest/1536/problem/C), [Mod i](https://atcoder.jp/contests/abc207/tasks/abc207_e), [けんちょんさんのまとめ](https://drken1215.hatenablog.com/archive/category/Zero-Sum%20Ranges), [Rem of Sum is Num](https://atcoder.jp/contests/abc146/tasks/abc146_e))
* 数え上げ
    * 包除
        * 約数系包除 ([Sum of gcd of Tuples (Hard)](https://atcoder.jp/contests/abc162/tasks/abc162_e), [Divide Both](https://atcoder.jp/contests/abc206/tasks/abc206_e), [Power Pair](https://atcoder.jp/contests/abc212/tasks/abc212_g))
    * グリッド経路数え上げ
        * カタラン数 ([White and Black Balls](https://atcoder.jp/contests/abc205/tasks/abc205_e))
* DP
    * 桁DPは、状態を全てフラグにして、配るDPで書く。([はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/04/23/212728))
    * 二乗の木DP ([Tree Patrolling](https://atcoder.jp/contests/abc207/tasks/abc207_f)、公式解説の証明が分かりやすい)
    * 部分列DP ([Strivore](https://atcoder.jp/contests/abc171/tasks/abc171_f), [Substrings](https://atcoder.jp/contests/abc214/tasks/abc214_f), [けんちょんさん](https://qiita.com/drken/items/a207e5ae3ea2cf17f4bd))
* グラフ
    * 木の巡回は、DFS順に点を訪れれば良い。
    * 木のサイズは、木の巡回長/2で求まる。
    * 木の座標圧縮はDFS順にソートすれば良い。LCAを使うと頂点間の距離も求められる。([Auxiliary Tree](https://dic.kimiyuki.net/auxiliary-tree), [Preserve Connectivity](https://atcoder.jp/contests/typical90/tasks/typical90_ai))
    * 木の中心は唯一に定まる。直径が奇数であればある辺が、偶数であればある点が中心となる。([Diameter set](https://atcoder.jp/contests/abc221/tasks/abc221_f))
    * 区間に辺を張る([Modulo Shortest Path](https://atcoder.jp/contests/abc232/tasks/abc232_g))
* 数学
    * 畳み込み
        * 文字列`S`と`T`について、`S`の全ての連続する部分列と`T`とのハミング距離は、畳み込みで求まる([Substring 2](https://atcoder.jp/contests/abc196/tasks/abc196_f))
        * 数列`A, B, C, ...`に対して、添字`i+j+k+...`の和がある値`X`となるように動かしたときの`A[i]*B[j]*C[k]*...`の和は、`convolution(A, convolution(B, ...))[X]`で求められる([RGB Balls 2](https://atcoder.jp/contests/typical90/tasks/typical90_bm))
    * 原始根 ([Power Pair](https://atcoder.jp/contests/abc212/tasks/abc212_g))
    * 中間値の定理 ([Count Median](https://atcoder.jp/contests/abc169/tasks/abc169_e), [Two Hundred Twenty One](https://codeforces.com/contest/1562/problem/D1))
    * フェルマーの小定理 ([Integer Sequence Fair](https://atcoder.jp/contests/abc228/tasks/abc228_e))
* データ構造
    * セグメント木
        * RMQはその個数も同時に求められる ([Matrix](https://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=3035), [解説](http://web-ext.u-aizu.ac.jp/circles/acpc/commentary/RitsCamp2018Day2/J.pdf), [コード](https://github.com/beet-aizu/library/blob/master/test/aoj/3035.test.cpp))
* 高速化
    * 平方分割
        * floor(N/x)のとりうる値とその現れる回数はO(√N)で求まる ([Up the Strip (simplified version)](https://codeforces.com/contest/1561/problem/D1), [Small Products](https://atcoder.jp/contests/abc132/tasks/abc132_f))
        * Mo's Algorithm
* 数論
    * 区間篩 ([Divisors of Binomial Coefficient](https://atcoder.jp/contests/abc227/tasks/abc227_g))
* フロー
    * 最小費用流
        * 最小流量・負辺([Minimum Coloring](https://atcoder.jp/contests/abc231/tasks/abc231_h))
