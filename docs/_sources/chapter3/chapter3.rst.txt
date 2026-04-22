######################
環境構築 #1：Miniconda
######################

**********
環境の説明
**********
次の手順で Windows 11 上に Sphinx の環境を構築します。 Windows 10 でも同様の手順で環境構築が可能です。

1. Miniconda をインストール
2. Sphinx をインストール
3. VS Code をインストール
4. GitHub を設定

*********
Miniconda
*********

インストール
============
Windows 上に Miniconda をインストールし、Python 環境を構築します。
インストールはデフォルトのまま進めています。

1. Miniconda のサイトを開く
2. Latest Miniconda Installer Links 内の "Miniconda3 Windows 64-bit" をクリックし、インストーラーをダウンロード
3. ダウンロードした "Miniconda3-latest-Windows-x86_64.exe" ファイルを実行

*****
LaTeX
*****

超幾何分布
==========

M個の赤玉、N-M個の白玉（合計N個）から非復元抽出でn個取り出す。
取り出される赤玉の個数をX個とすると、Xは超幾何関数HG(N, M, n)に従う。

.. math::

   \begin{align}
     &P(X=x) = \frac{{}_M \mathrm{C}_x \times {}_{N-M} \mathrm{C}_{n-x}}{{}_N \mathrm{C}_n} \\
     &E[X] = n \cdot \frac{M}{N} \\
     &V[X] = n \cdot \frac{M}{N} \cdot \left( 1 - \frac{M}{N} \right) \cdot \frac{N-n}{N-1}
   \end{align}
