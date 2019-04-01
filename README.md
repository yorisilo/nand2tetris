# nand2tetris

## 目的
coursera の nand2tetris 講義を受けつつ、それの日本版資料のコンピュータシステムの理論と実装を読みつつ、おもちゃのコンピュータを作る

* [Build a Modern Computer from First Principles: From Nand to Tetris (Project-Centered Course) | Coursera](https://www.coursera.org/learn/build-a-computer/)

> コンピュータを理解するための最善の方法はゼロからコンピュータを作ることです。コンピュータの構成要素は、ハードウェア、ソフトウェア、コンパイラ、OSに大別できます。本書では、これらコンピュータの構成要素をひとつずつ組み立てます。具体的には、NANDという電子素子からスタートし、論理ゲート、加算器、CPUを設計します。そして、オペレーティングシステム、コンパイラ、バーチャルマシンなどを実装しコンピュータを完成させて、最後にその上でアプリケーション（テトリスなど）を動作させます。実行環境はJava（Mac、Windows、Linuxで動作）。
* [O'Reilly Japan - コンピュータシステムの理論と実装](https://www.oreilly.co.jp/books/9784873117126/)

## how to

* ハードウェアシミュレーターの起動方法
``` shell
# やっておくこと：https://www.nand2tetris.org/software にて、hdl ファイルの実行環境をダウンロード
< brew cask install java
< emacs .zshenv
export JAVA_HOME=`/usr/libexec/java_home -v "12"`
export PATH="${JAVA_HOME}/bin:$PATH"
< java -version
openjdk version "12" 2019-03-19
OpenJDK Runtime Environment (build 12+33)
OpenJDK 64-Bit Server VM (build 12+33, mixed mode, sharing)
< cd nand2tetris/tools
< ./HardwareSimulator.sh
```
