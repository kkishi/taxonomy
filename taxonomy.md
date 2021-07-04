* 線形代数
    * 連立方程式
        * 掃き出し法 ([解説](https://drken1215.hatenablog.com/entry/2019/03/20/202800), [Xor Battle](https://atcoder.jp/contests/agc045/tasks/agc045_a))
        * 解の個数 ([Flip Flap](https://atcoder.jp/contests/typical90/tasks/typical90_be))
    * 線形変換・アフィン変換 ([Rotate and Flip](https://atcoder.jp/contests/abc189/tasks/abc189_e))
* ゲーム
    * Grundy数 ([解説](https://www.creativ.xyz/grundy-number-1065/), [VS AtCoder](https://atcoder.jp/contests/typical90/tasks/typical90_ae), [Interval Game 2](https://atcoder.jp/contests/abc206/tasks/abc206_f))
* xor
    * [はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/05/20/145021)
    * `x+y = (x^y)+2*(x&y)` ([Unfair Nim](https://atcoder.jp/contests/abc172/tasks/abc172_f))
* 幾何
    * 偏角ソートは境界付近に気をつける。STLのargは[-π, π]を返すので、-πに丸める ([Congruence Points](https://atcoder.jp/contests/abc207/tasks/abc207_d))
* 数列
    * 区間和問題はzero sum rangesを疑う ([うしさんのtweet](https://twitter.com/ei1333/status/1408791847426695174), [Diluc and Kaeya](https://codeforces.com/contest/1536/problem/C), [Mod i](https://atcoder.jp/contests/abc207/tasks/abc207_e), [けんちょんさんのまとめ](https://drken1215.hatenablog.com/archive/category/Zero-Sum%20Ranges), [Rem of Sum is Num](https://atcoder.jp/contests/abc146/tasks/abc146_e))
* 数え上げ
    * 包除
        * 約数系包除 ([Sum of gcd of Tuples (Hard)](https://atcoder.jp/contests/abc162/tasks/abc162_e), [Divide Both](https://atcoder.jp/contests/abc206/tasks/abc206_e))
    * グリッド経路数え上げ
        * カタラン数 ([White and Black Balls](https://atcoder.jp/contests/abc205/tasks/abc205_e))
* DP
    * 桁DPは、状態を全てフラグにして、配るDPで書く。([はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/04/23/212728))
* グラフ
    * 木の巡回は、DFS順に点を訪れれば良い。
    * 木のサイズは、木の巡回長/2で求まる。
    * 木の座標圧縮はDFS順にソートすれば良い。LCAを使うと頂点間の距離も求められる。([Auxiliary Tree](https://dic.kimiyuki.net/auxiliary-tree), [Preserve Connectivity](https://atcoder.jp/contests/typical90/tasks/typical90_ai))
* 数学
    * 畳み込み
        * 文字列`S`と`T`について、`S`の全ての連続する部分列と`T`とのハミング距離は、畳み込みで求まる([Substring 2](https://atcoder.jp/contests/abc196/tasks/abc196_f))
        * 数列`A, B, C, ...`に対して、添字`i+j+k+...`の和がある値`X`となるように動かしたときの`A[i]*B[j]*C[k]*...`の和は、`convolution(A, convolution(B, ...))[X]`で求められる([RGB Balls 2](https://atcoder.jp/contests/typical90/tasks/typical90_bm))
