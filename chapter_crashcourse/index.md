#  準備: A Crashcourse (短期集中コース)

深層学習を始めるには、いくつかの基本的なスキルを身につける必要があります。すべての機械学習はデータから情報を抽出することに関係しています。そこで、Apache MXNetを使ってデータを保存し操作するための実践的なスキルを学ぶことから始めます。さらに機械学習では通常、大きなデータセットを扱う必要があります。データセットは、行がデータ例に対応し、列が属性に対応する表と考えることができます。線形代数は、表形式のデータを扱うための強力な手法を提供します。細かい部分にあまり深く入り込まずに、むしろ行列演算の基本とApache MXNetを利用したそれらの実装に着目します。そして、深層学習は最適化そのものです。いくつかのパラメータをもつモデルに対して、データにぴったり合うものを見つけたいのです。アルゴリズムの各ステップで、パラメータをどのように動かせばよいか決めるためには、少し計算が必要です。幸いなことに、Apache MXNetのautogradパッケージがこれをカバーしているので、それについて後に説明します。次に、機械学習は予測、つまり*観測した情報にもとづいて、未知の属性に対して尤もらしい値はなにかを決める*ことに関係しています。
不確実性の下で厳密に推論するためには、確率と統計を使いこなす必要があります。この章を締めくくるために、最初の基本的な分類器である、*Naive Bayes*を紹介します。


```eval_rst

.. toctree::
   :maxdepth: 2

   ndarray
   linear-algebra
   autograd
   probability
   naive-bayes
   lookup-api

```
