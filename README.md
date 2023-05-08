* 線形代数
    * 連立方程式
        * 掃き出し法 ([解説](https://drken1215.hatenablog.com/entry/2019/03/20/202800), [Xor Battle](https://atcoder.jp/contests/agc045/tasks/agc045_a))
        * 解の個数 ([Flip Flap](https://atcoder.jp/contests/typical90/tasks/typical90_be))
    * 線形変換・アフィン変換 ([Rotate and Flip](https://atcoder.jp/contests/abc189/tasks/abc189_e))
* ゲーム
    * Grundy数 ([解説](https://www.creativ.xyz/grundy-number-1065/), [VS AtCoder](https://atcoder.jp/contests/typical90/tasks/typical90_ae), [Interval Game 2](https://atcoder.jp/contests/abc206/tasks/abc206_f), [Constrained Nim 2](https://atcoder.jp/contests/abc297/tasks/abc297_g))
    * 後退解析 ([Shiritori](https://atcoder.jp/contests/abc209/tasks/abc209_e), [Game on Graph](https://atcoder.jp/contests/abc261/tasks/abc261_h))
* xor
    * [はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/05/20/145021)
    * `x+y = (x^y)+2*(x&y)` ([Unfair Nim](https://atcoder.jp/contests/abc172/tasks/abc172_f), [AND and SUM](https://atcoder.jp/contests/abc238/tasks/abc238_d))
* 幾何
    * 偏角ソートは境界付近に気をつける。STLのargは[-π, π]を返すので、-πに丸める ([Congruence Points](https://atcoder.jp/contests/abc207/tasks/abc207_d))
* 数列
    * 区間和問題はzero sum rangesを疑う ([うしさんのtweet](https://twitter.com/ei1333/status/1408791847426695174), [Diluc and Kaeya](https://codeforces.com/contest/1536/problem/C), [Mod i](https://atcoder.jp/contests/abc207/tasks/abc207_e), [けんちょんさんのまとめ](https://drken1215.hatenablog.com/archive/category/Zero-Sum%20Ranges), [Rem of Sum is Num](https://atcoder.jp/contests/abc146/tasks/abc146_e), [Three Days Ago](https://atcoder.jp/contests/abc295/tasks/abc295_d))
* 約数系包除 ([Sum of gcd of Tuples (Hard)](https://atcoder.jp/contests/abc162/tasks/abc162_e), [Divide Both](https://atcoder.jp/contests/abc206/tasks/abc206_e), [Power Pair](https://atcoder.jp/contests/abc212/tasks/abc212_g))
* 包除原理 ([Gardens](https://atcoder.jp/contests/abc235/tasks/abc235_g), [Yet Another RGB Sequence](https://atcoder.jp/contests/abc266/tasks/abc266_g))
* 組み合わせ
    * 挿入する順序を工夫する([Yet Another RGB Sequence](https://atcoder.jp/contests/abc266/tasks/abc266_g))
* グリッド経路数え上げ
    * カタラン数 ([White and Black Balls](https://atcoder.jp/contests/abc205/tasks/abc205_e))
* 二項係数の和 ([Many Many Paths](https://atcoder.jp/contests/abc154/tasks/abc154_f), [Gardens](https://atcoder.jp/contests/abc235/tasks/abc235_g))
* DP
    * 桁DPは、状態を全てフラグにして、配るDPで書く。([はまやんさんのまとめ](https://blog.hamayanhamayan.com/entry/2017/04/23/212728), [substr = S](https://atcoder.jp/contests/abc295/tasks/abc295_f))
    * 二乗の木DP ([Tree Patrolling](https://atcoder.jp/contests/abc207/tasks/abc207_f), [Attack to a Tree](https://atcoder.jp/contests/aising2019/tasks/aising2019_e))
    * 部分列DP ([Strivore](https://atcoder.jp/contests/abc171/tasks/abc171_f), [Substrings](https://atcoder.jp/contests/abc214/tasks/abc214_f), [けんちょんさん](https://qiita.com/drken/items/a207e5ae3ea2cf17f4bd))
    * 遷移を累積和で高速化する([Divide a Sequence](https://atcoder.jp/contests/abc234/tasks/abc234_g), [RLE](https://atcoder.jp/contests/abc249/tasks/abc249_e), [Manhattan Cafe](https://atcoder.jp/contests/abc265/tasks/abc265_f))
    * 遷移をデータ構造で高速化する([Wish List](https://atcoder.jp/contests/abc288/tasks/abc288_e))
    * 円環のDPは、最初の要素の状態で場合分けをして列のDPをする([Cards](https://atcoder.jp/contests/abc247/tasks/abc247_f))
    * 耳DP([Ears](https://atcoder.jp/contests/yahoo-procon2019-qual/tasks/yahoo_procon2019_qual_d), [Knapsack for All Segments](https://atcoder.jp/contests/abc159/tasks/abc159_f), [Max Min](https://atcoder.jp/contests/abc247/tasks/abc247_e), [Left Right Operation](https://atcoder.jp/contests/abc263/tasks/abc263_d))
    * 箱根駅伝DP([箱根駅伝](https://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=2439), [Permutation Oddness](https://atcoder.jp/contests/abc134/tasks/abc134_f))
    * 必要な更新回数の上限が小さい([Chip Move](https://codeforces.com/contest/1716/problem/D))
    * 漸化式の再帰を消す([Sushi](https://atcoder.jp/contests/dp/tasks/dp_j), [Sugoroku2](https://atcoder.jp/contests/abc189/tasks/abc189_f), [Sugoroku 3](https://atcoder.jp/contests/abc263/tasks/abc263_e))
    * 区間DP ([Count Strictly Increasing Sequences](https://atcoder.jp/contests/abc292/tasks/abc292_g))
* グラフ
    * 木の巡回は、DFS順に点を訪れれば良い。
    * 木のサイズは、木の巡回長/2で求まる。
    * 木の座標圧縮はDFS順にソートすれば良い。LCAを使うと頂点間の距離も求められる。([Auxiliary Tree](https://dic.kimiyuki.net/auxiliary-tree), [Preserve Connectivity](https://atcoder.jp/contests/typical90/tasks/typical90_ai))
    * 木の中心は唯一に定まる。直径が奇数であればある辺が、偶数であればある点が中心となる。([Diameter set](https://atcoder.jp/contests/abc221/tasks/abc221_f))
    * 区間に辺を張る([Modulo Shortest Path](https://atcoder.jp/contests/abc232/tasks/abc232_g))
    * HL分解([可変全域木](https://atcoder.jp/contests/past202004-open/tasks/past202004_o), [Distance Queries on a Tree](https://atcoder.jp/contests/abc294/tasks/abc294_g))
    * K最短路([Foreign Friends](https://atcoder.jp/contests/abc245/tasks/abc245_g))
    * 置換をグラフで表すとサイクルの集まりになる([Cards](https://atcoder.jp/contests/abc247/tasks/abc247_f))
    * 区間の反転操作はグラフにする([Flip Digits 2](https://atcoder.jp/contests/typical90/tasks/typical90_aw), [Perils in Parallel](https://atcoder.jp/contests/abc155/tasks/abc155_f))
    * 木を半分に分割する点・辺（必ずしも存在しない・存在すれば唯一）はO(N)の木DPで求まる([赤青木](https://products.sint.co.jp/hubfs/resource/topsic/pgb2020/3_4.pdf))
    * 重心分解 ([Balanced Tree](https://atcoder.jp/contests/abc291/tasks/abc291_h))
* 畳み込み
    * 文字列`S`と`T`について、`S`の全ての連続する部分列と`T`とのハミング距離は、畳み込みで求まる([Substring 2](https://atcoder.jp/contests/abc196/tasks/abc196_f), [OR Sum](https://atcoder.jp/contests/abc291/tasks/abc291_g))
    * 数列`A, B, C, ...`に対して、添字`i+j+k+...`の和がある値`X`となるように動かしたときの`A[i]*B[j]*C[k]*...`の和は、`convolution(A, convolution(B, ...))[X]`で求められる([RGB Balls 2](https://atcoder.jp/contests/typical90/tasks/typical90_bm))
* 数論
    * 原始根 ([Power Pair](https://atcoder.jp/contests/abc212/tasks/abc212_g))
    * フェルマーの小定理 ([Integer Sequence Fair](https://atcoder.jp/contests/abc228/tasks/abc228_e))
    * 拡張ユークリッドの互助法([Oversleeping](https://atcoder.jp/contests/abc193/tasks/abc193_e))
    * 約数の総和は、素因数ごとの等比数列の和の積で表される([Mod 2](https://yukicoder.me/submissions/753097))
    * 離散対数 ([222](https://atcoder.jp/contests/abc222/tasks/abc222_g), [Sequence in mod P](https://atcoder.jp/contests/abc270/tasks/abc270_g))
    * q|pのときp/q(mod N)=p(mod N*q)/q([Geometric Progression](https://atcoder.jp/contests/abc293/tasks/abc293_e))
    * N以下のオイラーのφ関数は $O(log^2N)$ で求められる ([GCDistance](https://yukicoder.me/problems/no/2249))
    * $gcd(x, x+1) = 1$ ([Coprime Pair](https://atcoder.jp/contests/arc137/tasks/arc137_a))
    * [素数の間隔](https://ja.wikipedia.org/wiki/%E7%B4%A0%E6%95%B0%E3%81%AE%E9%96%93%E9%9A%94)は小さい ([Coprime Pair](https://atcoder.jp/contests/arc137/tasks/arc137_a))
    * ユークリッドの互除法の計算量解析([Count Subtractions](https://atcoder.jp/contests/abc297/tasks/abc297_d))
* 中間値の定理 ([Count Median](https://atcoder.jp/contests/abc169/tasks/abc169_e), [Two Hundred Twenty One](https://codeforces.com/contest/1562/problem/D1), [Count 1's](https://atcoder.jp/contests/arc137/tasks/arc137_b))
* セグメント木
    * RMQはその個数も同時に求められる ([Matrix](https://judge.u-aizu.ac.jp/onlinejudge/description.jsp?id=3035), [解説](http://web-ext.u-aizu.ac.jp/circles/acpc/commentary/RitsCamp2018Day2/J.pdf), [コード](https://github.com/beet-aizu/library/blob/master/test/aoj/3035.test.cpp))
* 平方分割
    * floor(N/x)のとりうる値とその現れる回数はO(√N)で求まる ([Up the Strip (simplified version)](https://codeforces.com/contest/1561/problem/D1), [Small Products](https://atcoder.jp/contests/abc132/tasks/abc132_f))
    * Mo's Algorithm
* 区間篩 ([Divisors of Binomial Coefficient](https://atcoder.jp/contests/abc227/tasks/abc227_g))
* 最大流
    * 最小カット・復元([Builder Takahashi](https://atcoder.jp/contests/abc239/tasks/abc239_g))
    * 最大流([Round Robin](https://atcoder.jp/contests/abc241/tasks/abc241_g), [Maxflow](https://atcoder.jp/contests/practice2/tasks/practice2_d), [Planes on a 2D Plane](https://atcoder.jp/contests/typical90/tasks/typical90_by))
    * 行・列に対応するノードを作る([Grid and Tokens](https://atcoder.jp/contests/abc205/tasks/abc205_f))
    * 燃やす・埋める([MUL](https://atcoder.jp/contests/arc085/tasks/arc085_c), [Zebraness](https://atcoder.jp/contests/abc193/tasks/abc193_f), [Get More Money](https://atcoder.jp/contests/typical90/tasks/typical90_an), [X](https://atcoder.jp/contests/abc225/tasks/abc225_g), [Grid Card Game](https://atcoder.jp/contests/abc259/tasks/abc259_g), [Security Camera 3](https://atcoder.jp/contests/abc274/tasks/abc274_g))
    * 二部マッチング・頂点倍化([Erasing Prime Pairs](https://atcoder.jp/contests/abc263/tasks/abc263_g))
    * 最小流量制限([Tatami](https://atcoder.jp/contests/abc285/tasks/abc285_g))
* 最小費用流
    * 最小流量・負辺([Minimum Coloring](https://atcoder.jp/contests/abc231/tasks/abc231_h), [輪投げ](https://atcoder.jp/contests/past202005-open/tasks/past202005_o))
    * 最大重みマッチング([Dream Team](https://atcoder.jp/contests/abc247/tasks/abc247_g))
* 並列二分探索([可変全域木](https://atcoder.jp/contests/past202004-open/tasks/past202004_o))
* マージテク([path pass i](https://atcoder.jp/contests/abc163/tasks/abc163_f), [Unique Occurrences](https://codeforces.com/contest/1681/problem/F))
* 区間スケジューリング問題([仕事計画](https://atcoder.jp/contests/arc032/tasks/arc032_3))
* K番目に大きい要素を効率よく求める問題([Game on Tree 2](https://atcoder.jp/contests/abc218/tasks/abc218_g), [Ignore Operations](https://atcoder.jp/contests/abc249/tasks/abc249_f))
* 隣り合う要素であって値の異なるものを消す操作を繰り返して区間が全て消せるかを効率よく判定する([Almost Triple Deletions](https://codeforces.com/contest/1699/problem/D))
* 鳩の巣定理([Find 4-cycle](https://atcoder.jp/contests/abc260/tasks/abc260_f))
* シェビチェフ距離([Nice Grid](https://atcoder.jp/contests/abc264/tasks/abc264_b))
* 無限級数の和([Access Counter](https://atcoder.jp/contests/abc271/tasks/abc271_g), [コイン投げ](https://products.sint.co.jp/hubfs/resource/topsic/pgb2021/3_4.pdf))
* 行列累乗([Access Counter](https://atcoder.jp/contests/abc271/tasks/abc271_g), [Geometric Progression](https://atcoder.jp/contests/abc293/tasks/abc293_e), [Takahashi's Basics in Education and Learning](https://atcoder.jp/contests/abc129/tasks/abc129_f))
* Baby-step giant-step([Sequence in mod P](https://atcoder.jp/contests/abc270/tasks/abc270_g))
* 複数の文字列を連結した文字列に対するsuffix array([Two Strings](https://atcoder.jp/contests/abc272/tasks/abc272_f))
* 乱択([Yet Another mod M](https://atcoder.jp/contests/abc272/tasks/abc272_g))
* 疎なグリッド([Skate](https://atcoder.jp/contests/abc241/tasks/abc241_f), [LRUD Instructions](https://atcoder.jp/contests/abc273/tasks/abc273_d))
* KMP法([コイン投げ](https://products.sint.co.jp/hubfs/resource/topsic/pgb2021/3_4.pdf))
* Convex Hull Trick ([Shopping in AtCoder store](https://atcoder.jp/contests/abc289/tasks/abc289_g))
* 値の更新のある数列の転倒数は遅延セグメント木で計算できる([Lazy Segment Tree](https://atcoder.jp/contests/practice2/tasks/practice2_l), [012 Inversion](https://atcoder.jp/contests/abc265/tasks/abc265_g))
* 文字列の列を辞書順最小となるように結合するには、 $s+t < t+s$ でソートする([String Cards](https://atcoder.jp/contests/abc225/tasks/abc225_f))
* 文字列を値としてDPをするときは、後ろから決めるとよい場合がある([String Cards](https://atcoder.jp/contests/abc225/tasks/abc225_f))
* 自明な必要条件が十分条件 ([Permutation Addition](https://atcoder.jp/contests/arc159/tasks/arc159_c))
* LIS ([LIS 2](https://atcoder.jp/contests/arc159/tasks/arc159_d))
* bitsetで隣接行列の処理を高速化する ([Walk the Runway](https://codeforces.com/contest/1826/problem/E), [Triangle](https://atcoder.jp/contests/abc258/tasks/abc258_g))
* 数列の区間に対する操作を階差数列で考える([Range Add Query](https://atcoder.jp/contests/abc288/tasks/abc288_d))
