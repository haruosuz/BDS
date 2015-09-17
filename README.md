----------

Haruo Suzuki <haruo@g-language.org>  
Last Update: 2015-09-17  

----------

"Bioinformatics Data Skills by Vince Buffalo (O’Reilly). Copyright 2015 Vince Buffalo, 978-1-449-36737-4."  
![](http://ecx.images-amazon.com/images/I/51gYdVvOoQL._SX379_BO1,204,203,200_.jpg)

# Print & Ebook
- [Amazon.co.jp](http://www.amazon.co.jp/dp/1449367372) | [Amazon.com](http://www.amazon.com/dp/1449367372)
- [O'Reilly Media](http://shop.oreilly.com/product/0636920030157.do) | [Free Sampler](http://cdn.oreillystatic.com/oreilly/booksamplers/9781449367374_sampler.pdf)（Chapter 1の全文閲覧可能）
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/)（[Preface](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/preface01.html#preface)、[Chapter 1](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch01.html#chapter-01)、[Chapter 4](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch04.html#chapter-04) の全文閲覧可能）

# News & Reviews
- [Bioinformatics Data Skills - Twitter Search](https://twitter.com/search?q=Bioinformatics%20Data%20Skills&src=typd)
- [Twitter competition: win a signed copy of Bioinformatics Data Skills by Vince Buffalo — ACGT](http://www.acgt.me/blog/2015/9/13/twitter-competition-win-a-signed-copy-of-bioinformatics-data-skills-by-vince-buffalo) | September 13, 2015
- [101 questions with a bioinformatician #30: Vince Buffalo — ACGT](http://www.acgt.me/blog/2015/8/4/101-questions-with-a-bioinformatician-30-vince-buffalo) | August 04, 2015
- [bds:index [SoWiki]](http://so.med.u-tokai.ac.jp/wiki/doku.php?id=bds:index) | 最終更新: 2015/06/25 04:04 by so
- [Asking for opinions about Bioinformatics Data Skills book](https://www.biostars.org/p/153594/) | weeks ago 
- [O'Reilly's early release of "Bioinformatics Data Skills" is 50% off until Feb 18th, use code WKERES : bioinformatics](https://www.reddit.com/r/bioinformatics/comments/2vsplz/oreillys_early_release_of_bioinformatics_data/) | submitted 6 months ago by rdr0b11
- []()
- [Don’t trust your data: reviewing Bioinformatics Data Skills | The Molecular Ecologist](http://www.molecularecologist.com/2015/04/dont-trust-your-data-reviewing-bioinformatics-data-skills/) | Posted on 8 April, 2015 by Rob Denton
- [Reading the early release of "Bioinformatics Data Skills"Musings from a PhD candidate](http://davetang.org/muse/2014/04/03/bioinformatics-data-skills/) | Posted on April 3, 2014

----------

# Bioinformatics Data Skills: Reproducible and Robust Research With Open Source Tools
バイオインフォマティクス・データスキル：オープンソースのツールによる再現可能で頑強な研究  
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files)

# Table of Contents
- [Preface](#preface)
- I. Ideology: Data Skills for Robust and Reproducible Bioinformatics
  - [1. How to Learn Bioinformatics](#chapter-1-how-to-learn-bioinformatics)
- II. Prerequisites: Essential Skills for Getting Started with a Bioinformatics Project
  - [2. Setting Up and Managing a Bioinformatics Project](#chapter-2-setting-up-and-managing-a-bioinformatics-project)
  - [3. Remedial Unix Shell](#chapter-3-remedial-unix-shell)
  - [4. Working with Remote Machines](#chapter-4-working-with-remote-machines)
  - [5. Git for Scientists](#chapter-5-git-for-scientists)
  - [6. Bioinformatics Data](#chapter-6-bioinformatics-data)
- III. Practice: Bioinformatics Data Skills
  - [7. Unix Data Tools](#chapter-7-unix-data-tools)
  - [8. A Rapid Introduction to the R Language](#chapter-8-a-rapid-introduction-to-the-r-language)
  - [9. Working with Range Data](#chapter-9-working-with-range-data)
  - [10. Working with Sequence Data](#chapter-10-working-with-sequence-data)
  - [11. Working with Alignment Data](#chapter-11-working-with-alignment-data)
  - [12. Bioinformatics Shell Scripting, Writing Pipelines, and Parallelizing Tasks](#chapter-12-bioinformatics-shell-scripting-writing-pipelines-and-parallelizing-tasks)
  - [13. Out-of-Memory Approaches: Tabix and SQLite](#chapter-13-out-of-memory-approaches-tabix-and-sqlite)
  - [14. Conclusion](#chapter-14-conclusion)

----------

## Preface
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/preface01.html#preface)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-00-preface)

### The Approach of This Book
本書は、バイオインフォマティクス・ソフトウェア（マッピング、アセンブル、変異解析など）の実行方法は扱わない。  
本書は、複雑で大規模なデータセットから意味を抽出し探索する技術を扱う。  
本書を通して、頑強で再現可能な方法を強調する。  

### Why This Book Focuses on Sequencing Data
バイオインフォマティクスは、幅広い学問分野であり、プロテオミクス、メタボロミクス、構造バイオインフォマティクス、比較ゲノム、機械学習、画像処理のような分野にまたがる。この本では主に配列データの扱いに焦点を当てる。配列データは豊富にあり、配列データ解析に必要なテキスト処理技術は、他のデータに適用できる。

### Audience 読者
生物学者と計算機科学者の両方

### The Difficulty Level of Bioinformatics Data Skills

### Assumptions This Book Makes
前提知識は以下の通り。  
- You know a scripting language スクリプト言語（[Python](https://ja.wikipedia.org/wiki/Python)や[R言語](https://ja.wikipedia.org/wiki/R言語)）  
- You know how to use a text editor テキストエディタ（[Emacs](https://ja.wikipedia.org/wiki/Emacs)や[nano](https://ja.wikipedia.org/wiki/Nano_(テキストエディタ))）
- You have basic Unix command-line skills 基本的なUnixコマンド（`cd, ls, pwd, mv, rm, rmdir, mkdir`）  
- You have a basic understanding of biology 生物学の基礎（DNA、RNA、タンパク質、遺伝子、セントラルドグマ）  
- You have a basic understanding of regular expressions [正規表現](https://ja.wikipedia.org/wiki/正規表現)  
- You know how to get help and read documentation ヘルプやマニュアルの参照  
- You can manage your computer system (or have a system administrator) システム管理  

### Supplementary Material on GitHub
[GitHubリポジトリ](https://github.com/vsbuffalo/bds-files)の補足資料を取得する:  
`wget -o wget.log https://github.com/vsbuffalo/bds-files/archive/master.zip`  
`git clone https://github.com/vsbuffalo/bds-files`  

本書や補足資料に問題を発見した場合、[GitHubで新規issueを作成](https://github.com/vsbuffalo/bds-files/issues)されたい。　

### Computing Resources and Setup
筆者は、ラップトップ（15インチのMacBook Pro、メモリは16GB）で本書を執筆した。例題は、8GBのメモリを搭載するマシンで実行すべき。  
例題は、Unix系のOS（Mac OS XやLinux）で動作する。[パッケージ管理システム](https://ja.wikipedia.org/wiki/パッケージ管理システム)（Ubuntu/Debianの`apt-get`や、Mac OS Xの[Homebrew](http://brew.sh/index_ja.html)（[homebrew-science](https://github.com/Homebrew/homebrew-science)）を使用すべき。

- [作業環境を整えるMacOSXのパッケージマネージャ「Homebrew」のインストール方法と使い方 | 株式会社LIG](http://liginc.co.jp/web/tool/mac-iphone/151069)
- [MacにHomebrewをインストールする - Qiita](http://qiita.com/_daisuke/items/d3b2477d15ed2611a058)

### Organization of This Book
本書は3部構成：第I部はイデオロギーに関する1章、第II部は基礎編、第III部は実践編。

### Code Conventions コード表記規則
[...]は出力の省略を意味する。

----------

# Part I. Ideology: Data Skills for Robust and Reproducible Bioinformatics
第I部. イデオロギー：頑強で再現可能なバイオインフォマティクスのためのデータスキル  

----------

## Chapter 1. How to Learn Bioinformatics
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch01.html#chapter-01)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-01-ideology)

### Why Bioinformatics? Biology’s Growing Data
Figure 1-1. DNA配列決定コストの減少 [DNA Sequencing Costs](http://www.genome.gov/sequencingcosts/)  
![](http://www.genome.gov/images/content/costpermegabase_apr2015.jpg)

Figure 1-2. [Sequence Read Archive](http://www.ncbi.nlm.nih.gov/Traces/sra/)の指数的成長  
![](http://www.ncbi.nlm.nih.gov/Traces/sra/i/g.png)

[ショードリード配列マッピング・ツール](http://www.ebi.ac.uk/~nf/hts_mappers/)

### Learning Data Skills to Learn Bioinformatics
### New Challenges for Reproducible and Robust Research
### Reproducible Research
再現可能な研究  
データ、コード、ソフトウェアのバージョンとダウンロードした日時を記録する。

### Robust Research and the Golden Rule of Bioinformatics
["garbage in, garbage out"](http://ejje.weblio.jp/content/Garbage+in,+garbage+out.)「ゴミを入れればゴミが出てくる」  

バイオインフォマティクスの黄金律:  
> #### NEVER EVER TRUST YOUR TOOLS (OR DATA)  
ツールやデータを絶対に信用しない。  

### Adopting Robust and Reproducible Practices Will Make Your Life Easier, Too
### Recommendations for Robust Research
頑健な研究のススメ  

#### Pay Attention to Experimental Design
実験計画  

統計学者で遺伝学者のR. A.フィッシャー曰く: [「実験が終わった後に統計学者に相談することは、しばしば単に検死を頼むようなものになる。統計学者は、何のせいで実験が死んだのかについて言うことができるかもしれない。」](http://id.fnshr.info/2014/12/17/stats-done-wrong-13/)

#### Write Code for Humans, Write Data for Computers
Google has [public style guides for many languages](https://github.com/google/styleguide),

#### Let Your Computer Do the Work For You

#### Make Assertions and Be Loud, in Code and in Your Methods
前提条件のチェックに[表明（assertion）](https://ja.wikipedia.org/wiki/表明)を使用する。Pythonの`assert()`やRの`stopifnot()`

#### Test Code, or Better Yet, Let Code Test Code
[単体テスト(unit testing)](https://ja.wikipedia.org/wiki/単体テスト)  
例えば、`add()`関数を（呼び出して入力から期待される出力が得られるか）テストする`test_add()`関数をPythonで書く:  


#### Use Existing Libraries Whenever Possible
なるべく既存のライブラリを使う  
歴史が長く、閲覧者が多いので、バグが少ない。

#### Treat Data as Read-Only
データを書き換えない  

#### Spend Time Developing Frequently Used Scripts into Tools
#### Let Data Prove That It’s High Quality
[探索的データ解析 (Exploratory Data Analysis; EDA)](http://www.msi.co.jp/splus/products/eda.html)を通してデータの質を証明する。Chapter 8でRを用いてEDAを学ぶ。

### Recommendations for Reproducible Research
再現可能な研究のススメ  

#### Release Your Code and Data
データとコードを公開する  

#### Document Everything
全て記録する  

[プレーンテキスト](https://ja.wikipedia.org/wiki/プレーンテキスト)形式の[README](https://ja.wikipedia.org/wiki/リードミー)ファイルに解析の各ステップを記録する。  

#### Make Figures and Statistics the Results of Scripts
図表を出力するスクリプトを書く  

#### Use Code as Documentation
コードをドキュメントにする  

### Continually Improving Your Bioinformatics Data Skills

----------

# Part II. Prerequisites: Essential Skills for Getting Started with a Bioinformatics Project
第II部. 前提条件：バイオインフォマティクス・プロジェクト入門のための必須スキル  

----------

## Chapter 2. Setting Up and Managing a Bioinformatics Project
バイオインフォマティクス・プロジェクトの作成と管理  
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch02.html#chapter-02)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-02-bioinformatics-projects) 

### Project Directories and Directory Structures
ディレクトリ構造  

- [計算生物学のプロジェクトの管理法入門 (Noble 2009)](http://5hun.github.io/quickguide_ja/)
 
例えば、プロジェクト名を'zmays-snps'としてディレクトリを作成する:  


- *data/*ディレクトリに生データを格納する。
- *scripts/*ディレクトリにプログラムを格納する。
- *analysis/*ディレクトリに解析結果を格納する。

> ### What’s in a Name?  
ファイル名には、英数字や_や-を使い、スペース（空白）を入れない。拡張子を付ける。（例 *osativa-genes_2015-07-07.fasta*）  

- [UNIXコマンド辞典>>絶対パスと相対パス](http://codezine.jp/unixdic/w/絶対パスと相対パス)

絶対パス（例 `/home/vinceb/projects/zmays-snps/data/stats/qual.txt`）ではなく相対パス（例 `../data/stats/qual.txt`）を使う。

### Project Documentation
プロジェクトの記録  

例えば、以下の項目を記録する。  
- 方法とワークフロー。全コマンドラインをコピー＆ペースト。デフォルト値も
- データの入手元（ウェブサイトのURL等）
- データをダウンロードした日付
- データのバーション（例えば、[TAIR10](https://www.arabidopsis.org/download_files/Genes/TAIR10_genome_release/README_TAIR10.txt)、[WS231](https://www.wormbase.org/about/wormbase_release_WS231)）
- データのダウンロード方法（例えば、[MySQL](https://ja.wikipedia.org/wiki/MySQL)、[UCSC Genome Browser](https://genome.ucsc.edu)を使用）
- ソフトウェアのバーション（なければ、日付やURL）

以上の情報を[プレーンテキスト](https://ja.wikipedia.org/wiki/プレーンテキスト)形式の[README](https://ja.wikipedia.org/wiki/リードミー)ファイルに保存する。プレーンテキストはコマンドラインから簡単に読み込み、検索、編集できる。  

READMEファイルはプロジェクトのメインのディレクトリに格納する。例えば、`data/README`ファイルに、`data/`ディレクトリのデータファイルの説明（いつ・どこから・どのようにダウンロードしたのか）を記載する。touchコマンドでサイズが0の空ファイルを作成する:    


### Use Directories to Divide Up Your Project into Subprojects
ディレクトリを使用してプロジェクトをサブプロジェクトに分割  

### Organizing Data to Automate File Processing Tasks
一貫性のあるファイル名  

> ### Shell Expansion Tips シェルの展開  
`cd ~`でホームディレクトリに移動。ワイルドカードのアスタリスク（*）は全ての文字列にマッチする。  
Brace expansionの例:  
`zmays-snps/`プロジェクト・ディレクトリを作成:  

- Brace expansion ブレース展開
  - [Bash Reference Manual: Brace Expansion](http://www.gnu.org/software/bash/manual/html_node/Brace-Expansion.html)
  - [Brace expansion [Bash Hackers Wiki]](http://wiki.bash-hackers.org/syntax/expansion/brace)
  - [Bash - Brace Expansionが便利 - Qiita](http://qiita.com/__nagamee/items/bec89945f70f5dffe9c5)
  - [bash - コマンド (プログラム) の説明 - Linux コマンド集 一覧表](http://kazmax.zpp.jp/cmd/b/bash.1.html) | ブレース展開

3つのサンプル（zmaysA, zmaysB, zmaysC）毎にペア（R1, R2）の空データファイルを作成する:  


[ワイルドカード](http://ja.wikipedia.org/wiki/ワイルドカード_(情報処理))のアスタリスク（*）を用いて、サンプル名`zmaysB`を持つ全てのファイルを表示する:  


> ### Wildcards and "Argument list too long"  
解決方法は"Using find and xargs"を参照されたい  

ワイルドカードは限定する。例えば、`zmaysB*`の代わりに、`zmaysB*fastq`または`zmaysB_R?.fastq`を用いる（`?`は任意の1文字）。

サンプルCを排除する:  


ワイルドカードは存在するファイルを展開するのに対して、brace expansion（例 `snps_{10..13}.txt`）はファイルやディレクトリが存在するか否かに関係なく展開する。

Table 2-1. Unixのワイルドカード

|ワイルドカード|マッチする文字|
|:----------:|:----------:|
|*|0文字以上の任意の文字列（隠しファイルは無視）|
|?|任意の1文字（隠しファイルは無視）|
|[A-Z]|AとZの間の1文字（[0-9]は0と9の間の1文字）|

- [UNIXのワイルドカード](http://www.rsch.tuis.ac.jp/~ohmi/literacy/2002/wildcard.html)
- [UNIX/基礎知識/ワイルドカード、メタキャラクタ - 会津大学UNIXウィキ](http://technique.sonots.com/?UNIX%2F基礎知識%2Fワイルドカード、メタキャラクタ)

> ### Leading Zeros and Sorting  
ファイル名の先頭に0を付ける（例えば、*file-21.txt*よりもむしろ*file-0021.txt*とする）と、`ls`で辞書順にファイルがソートされる。  
`touch gene-{1..14}.txt`  
`printf "gene-%03d.txt " {1..14} | xargs touch`  

### Markdown for Project Notebooks
プレーンテキスト形式で書かれたプロジェクト・ノートは、コマンドラインやネットワーク経由で読み込み・検索・編集できる。  

- [Markdown](https://ja.wikipedia.org/wiki/Markdown)（マークダウン）  
 - [MarkdownでMarkdownの書き方を書いてみた](http://qiita.com/oreo/items/82183bfbaac69971917f)
 - [Markdownで行こう！](https://gist.github.com/wate/7072365)
 - [README.mdファイル。マークダウン記法まとめ | codechord](http://codechord.com/2012/01/readme-markdown/)
 - [ディレクターが知っておいて欲しい10個のMarkdown-マークダウン記法 - PHPサンプル実験室](http://php-fan.org/markdown.html)

#### Markdown Formatting Basics
John Gruberのホームページ（[Daring Fireball: Markdown Syntax Documentation](http://daringfireball.net/projects/markdown/syntax)）  

Figure 2-1. マークダウン・ノートブックのHTML表示  

Table 2-2. マークダウン構文  

[MultiMarkdown](http://fletcherpenney.net/multimarkdown/)  
[GitHub Flavored Markdown - User Documentation](https://help.github.com/articles/github-flavored-markdown/)  

#### Using Pandoc to Render Markdown to HTML
[Pandocのインストール](http://pandoc.org/installing.html)  


## Chapter 3. Remedial Unix Shell
Unixシェル  
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch03.html#chapter-03)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-03-remedial-unix) 

### Why Do We Use Unix in Bioinformatics? Modularity and the Unix Philosophy
[UNIX哲学](https://ja.wikipedia.org/wiki/UNIX哲学)  

> ### The Many Unix Shells  
`echo $SHELL` (`echo $0`) で現在のシェルを確認  
`chsh`でログインシェルを変更  

[ストリーム](https://ja.wikipedia.org/wiki/標準ストリーム)、
[リダイレクト](https://ja.wikipedia.org/wiki/リダイレクト_(CLI))、
[パイプ](https://ja.wikipedia.org/wiki/パイプ_(コンピュータ))、
[プロセス](https://ja.wikipedia.org/wiki/プロセス)、
コマンド置換（[command substitution](https://en.wikipedia.org/wiki/Command_substitution)）

- [とほほのUNIX入門](http://www.tohoho-web.com/wwwunix.htm)
- [UNIXコマンド辞典](http://codezine.jp/unixdic/)
- [UNIX講習会#2 パイプ・リダイレクト・プロセス置換 - Qiita](http://qiita.com/informationsea/items/a9092d40d20e059f0482)
- [UNIX/基礎知識/リダイレクト、パイプ - 会津大学UNIXウィキ](http://technique.sonots.com/?UNIX%2F基礎知識%2Fリダイレクト、パイプ)
- [UNIXコマンド辞典>>リダイレクション](http://codezine.jp/unixdic/w/リダイレクション)
- [NIXコマンド辞典>>パイプ](http://codezine.jp/unixdic/w/パイプ)
- [UNIXの部屋 コマンド検索:リダイレクト (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?%A5%EA%A5%C0%A5%A4%A5%EC%A5%AF%A5%C8)
- [UNIXの部屋 コマンド検索:シェル記号類まとめ (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?%A5%B7%A5%A7%A5%EB%B5%AD%B9%E6%CE%E0%A4%DE%A4%C8%A4%E1)　`> >> 2>&1 < << $$ >& & && ( ) | || <<- <& >| <>`

### Working with Streams and Redirection
ストリームとリダイレクション  
[標準ストリーム](https://ja.wikipedia.org/wiki/標準ストリーム)  

- [標準入力、標準出力、標準エラー出力、パイプとは ?](http://www.creatology.jp/unix/outin.html)

#### Redirecting Standard Out to a File
標準出力をファイルにリダイレクト  

`cat`コマンドで*tb1-protein.fasta*ファイルを標準出力:  


複数のファイルを標準出力:  


記号`>`（上書き）や`>>`（追記）で標準出力をファイルに[リダイレクト](https://ja.wikipedia.org/wiki/リダイレクト_(CLI)):  


最新のファイル（*zea-proteins.fasta*）を確認:  
`ls -lrt`は、更新日時の逆順にソートする（詳細は`man ls`を参照）。

- [lsコマンドの結果をソート（昇順）する｜Linux Tips](http://www.linuxmaster.jp/linux_skill/2008/06/ls.html)
- [lsコマンドで便利なオプションはlとaだけではない](http://blog.layer8.sh/ja/2013/02/18/ls-l-a/)

#### Redirecting Standard Error
標準エラー出力をリダイレクト  

`ls -l tb1.fasta leafy1.fasta`を実行すると、存在するファイル（*tb1.fasta*）は標準出力に、存在しないファイル（*leafy1.fasta*）は標準エラー出力に送られる:  

記号`>`と`2>`を用いて、標準出力と標準エラー出力を別のファイルにリダイレクト:  


記号`2>`は上書き、`2>>`は追記。

> ### File Descriptors  
- [ファイル記述子](https://ja.wikipedia.org/wiki/ファイル記述子)
- [ファイルディスクリプタとは｜file descriptor｜ファイルディスクリプター - 意味/解説/説明/定義 ： IT用語辞典](http://e-words.jp/w/ファイルディスクリプタ.html)
- [ファイルディスクリプタについて（1）　～ファイルディスクリプタの概要：CodeZine（コードジン）](http://codezine.jp/article/detail/4836)

擬似デバイス（*pseudodevice*）の*/dev/null*は、あらゆる入力を受け付け、それを捨てる。

- [デバイスファイル](https://ja.wikipedia.org/wiki/デバイスファイル)

> ### Using tail -f to Monitor Redirected Standard Error  
`tail -f`でリダイレクトされた標準エラー出力を監視する。Control-Cで動作中のプロセスを停止。  

#### Using Standard Input Redirection
標準入力リダイレクト:  


標準入力リダイレクト演算子`<`よりもUnixパイプ（例えば、`cat inputfile | program > outputfile`）を使う方がより一般的。

### The Almighty Unix Pipe: Speed and Beauty in One

Figure 3-2.

#### Pipes in Action: Creating Simple Programs with Grep and Pipes

パイプとgrepコマンドを用いて、FASTAファイルに含まれるATGC以外の文字を探す:  


ハイライトされたYはpYrimidine塩基[CT]を示す（[Nucleic acid notation](https://en.wikipedia.org/wiki/Nucleic_acid_notation)）。
正規表現はクオーテーションで囲む。`grep -v > tb1.fasta`はファイルを上書きしてしまう。

- [UNIXの部屋 コマンド検索:grep (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?grep)
- [UNIXコマンド辞典>>grep](http://codezine.jp/unixdic/w/grep)
- [Linuxコマンド集 - 【 grep 】 文字列を検索する：ITpro](Linuxコマンド集 - 【 grep 】 文字列を検索する：ITpro)
- [grep - UNIX/Linuxコマンド - IT専科](http://www.itsenka.com/contents/development/unix-linux/grep.html)

#### Combining Pipes and Redirection


`2>&1`演算子は標準エラー出力を標準出力にリダイレクトする:  


##### Even More Redirection: A tee in Your Pipe

- [tee (UNIX)](https://ja.wikipedia.org/wiki/Tee_(UNIX))
- [UNIXコマンド辞典>>tee](http://codezine.jp/unixdic/w/tee)
- [UNIXの部屋 コマンド検索:tee (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?tee)
- [Linuxコマンド集 - 【 tee 】 標準入力を標準出力とファイルに出力する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230898/)




### Managing and Interacting with Processes

In this section, we’ll learn the basics of manipulating processes: running and managing processes in the background, killing errant processes, and checking process exit status.

- [9. プロセス操作コマンド](http://freebsd.sing.ne.jp/unix/09.html)
- [Linux_コマンドリファレンス_10 プロセスとジョブの管理](http://www.x-net.nu/technical/linux/command/t_linux_com10.html)

#### Background Processes
- [Linuxコマンド集 - 【 & 】 コマンドをバックグラウンドで実行する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060224/230589/)
- [バックグラウンドプロセス(ジョブ)の管理 - satake7’s memo](http://d.hatena.ne.jp/satake7/20080606/p1)

コマンドの末尾にアンパサンド（&）を追加して、プログラムをバックグラウンドで実行する:  


[1]はジョブ番号、26577は[プロセスID（PID）](https://ja.wikipedia.org/wiki/プロセス識別子)。
[`jobs`](http://codezine.jp/unixdic/w/jobs)でバックグランド・ジョブを表示する:  


[`fg`](http://codezine.jp/unixdic/w/fg)でバックグラウンド・プロセスをフォアグラウンド（foreground）へ戻す。`fg %ジョブ番号`で指定。バックグラウンド・プロセスが1つしかない場合には、`fg`と`fg %1`は同じ:  


> ### Background Processes and Hangup Signals  
[ハングアップ・シグナル](https://ja.wikipedia.org/wiki/シグナル_(ソフトウェア))（SIGHUP）  
バックグラウンドのプロセスがSIGHUPを受け付けないようにするには、`nohup`を使うか、Tmux内で走らせる。Chapter 4で詳細に述べる。

Control-z キーで中断させたジョブを
[`bg`](http://codezine.jp/unixdic/w/bg)コマンドを用いてバックグラウンド（background）で再開:  


バックグラウンドで再開させるジョブを`bg %ジョブ番号`で指定。

#### Killing Processes
[`top`](http://codezine.jp/unixdic/w/top)、
[`ps`](http://codezine.jp/unixdic/w/ps)、
[`kill`](http://codezine.jp/unixdic/w/kill)コマンド

- [UNIXコマンド辞典>>kill](http://codezine.jp/unixdic/w/kill)

#### Exit Status: How to Programmatically Tell Whether Your Command Worked
[終了ステータス](https://ja.wikipedia.org/wiki/終了ステータス)（exit status）慣習的に正常終了時はゼロ、異常終了時はゼロ以外を返すのが一般的である

> ### Warning Exit Statuses  
- [終了ステータス - UNIX & Linux コマンド・シェルスクリプト リファレンス](http://shellscript.sunone.me/exit_status.html)

終了ステータスの値は、シェルの特殊変数`$?`に設定される。


終了ステータスを判定してコマンドを実行する。  
`&&`は、コマンドが成功した場合のみ次のコマンドを実行する:  


`||`は、コマンドが失敗した場合のみ次のコマンドを実行する:  


`&&`と`||`をテストするのに、正常終了（[`true`](https://ja.wikipedia.org/wiki/True_(UNIX))）または異常終了（[`false`](https://ja.wikipedia.org/wiki/False_(UNIX))）を返すUnixコマンドを用いる:


### Command Substitution
コマンド置換 - \`command\`ではなく$(command)を使う。[ネスト](https://ja.wikipedia.org/wiki/ネスティング)できるから。
 
- [bash Tips - コマンド置換と算術式展開、パラメータ展開 - Qiita](http://qiita.com/mashumashu/items/bbc3a79bc779fe8c4f99)

`date +%F`コマンドを用いて日付ディレクトリを作成する:  


このフォーマットのディレクトリは年代順にソートされる:  


> ### Storing Your Unix Tricks  
`add alias`を用いて*~/.bashrc*（Mac OS Xでは*~/.profile*）ファイルに追加する。例えば、常に同じディレクトリ構造のプロジェクト・ディレクトリを作成する:  

## Chapter 4. Working with Remote Machines
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch04.html#chapter-04)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-04-working-with-remote-machines)

### Connecting to Remote Machines with SSH
*secure shell (SSH)*


IPアドレスを用いてマシンに繋げるには `ssh 192.169.237.42`  

ポートとユーザー名を指定する:  


ssh -v (-v for verbose) using -vv or -vvv; see man ssh for more details.

> ### Storing Your Frequent SSH Hosts  
*~/.ssh/config*ファイルを作る:  
リモートホストのデフォルトと同じなら`Port`と`User`を指定する必要は無い。`ssh -p 50453 cdarwin@192.169.237.42`とタイプする代わりに、エイリアス`ssh bio_serv`を用いて*192.168.236.42*にSSH接続できる。

`hostname`コマンドは、ホスト名を表示する。  
`whoami`コマンドは、ユーザー名を表示する。  

### Quick Authentication with SSH Keys
- [Linuxコマンド【 ssh-keygen 】認証用の鍵を生成 - Linux入門 - Webkaru](http://webkaru.net/linux/ssh-keygen-command/)
- [Linuxコマンド集 - 【 ssh-keygen 】 SSH用の公開かぎ、秘密かぎのペアを作成する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230890/)
- [Linux - ssh公開鍵認証設定まとめ - Qiita](http://qiita.com/iruseira/items/af8550fea92b5c5f7fca)

`ssh-keygen`コマンドを用いて、秘密鍵（*~/.ssh/id_rsa*）と公開鍵（*~/.ssh/id_rsa.pub*）を生成する。


リモートホストにログインして、*~/.ssh/authorized_keys*に公開鍵ファイル（*id_rsa.pub*）の内容を追加する。`ssh-copy-id`コマンドを用いて自動登録も可能。 

- [ssh-agentの使い方 - Qiita](http://qiita.com/isaoshimizu/items/84ac5a0b1d42b9d355cf)


### Maintaining Long-Running Jobs with nohup and tmux
*ハングアップ*シグナル（`SIGHUP`）  
`nohup`とTmux  

- [UNIXコマンド辞典>>nohup](http://codezine.jp/unixdic/w/nohup)　ハングアップに反応しないようにしてコマンドを実行する
- [Linuxコマンド集 - 【 nohup 】 ログアウトした後もコマンドを実行し続ける：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230850/)
- [プロセス管理 — nohup, disown, kill — Watallica metallicus](http://meme.biology.tohoku.ac.jp/students/iwasaki/dev/nohup.html)
- [tmux — 仮想端末でリモート仕事を安全に — Watallica metallicus](http://meme.biology.tohoku.ac.jp/students/iwasaki/dev/tmux.html)

#### nohup


`nohup`は、[プロセスID（PID）](https://ja.wikipedia.org/wiki/プロセス識別子)を返す。

### Working with Remote Machines Through Tmux
terminal multiplexer：[Tmux](https://wiki.archlinuxjp.org/index.php/Tmux)と[GNU Screen](https://ja.wikipedia.org/wiki/GNU_Screen)

- [tmuxに慣れてみる: tmuxとGNU screenの違いなど](http://rcmdnk.github.io/blog/2015/01/02/computer-tmux-screen/)

#### Installing and Configuring Tmux

- [Macにtmuxを導入する - Qiita](http://qiita.com/michiomochi@github/items/4bf8e34a91bbf3d9af20)

TmuxをMac OS XにHomebrewでインストールする:  


設定ファイル（[*.tmux.conf*](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-04-working-with-remote-machines/.tmux.conf)）をホームディレクトリに置く。シェルが設定を*~/.profile*や*~/.bashrc*から読み込むように、Tmuxは設定を*~/.tmux.conf*から読み込む。

#### Creating, Detaching, and Attaching Tmux Sessions

- [GNU Screenライクなtmuxのセッション管理 アタッチとデタッチ](http://kaworu.jpn.org/kaworu/2009-10-25-1.php)
- [tmuxの基本的な使い方とコマンドのまとめ - TASK NOTES](http://www.task-notes.com/entry/20150711/1436583600)

Tmuxの新しいセッションを開始する:  


Tmuxのプレフィックスキー（キーバインド）は、デフォルトではControl-bを用いるが、設定ファイル（[*.tmux.conf*](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-04-working-with-remote-machines/.tmux.conf)）でControl-aに変更した。


セッションのデタッチは Control-a d

セッションの確認: `tmux list-sessions`

セッションのアタッチ: `tmux a`


#### Working with Tmux Windows

Tmuxのマニュアルページを見る: `man tmux`

Table 4-1. Tmuxの基本的キー操作

Table 4-2. Tmuxの基本的コマンド

Emacsで、文字通り Control-a を入力するには、Control-a a とする。

## Chapter 5. Git for Scientists
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch05.html#chapter-05)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-05-git-for-scientists)

### Why Git Is Necessary in Bioinformatics Projects
#### Git Allows You to Keep Snapshots of Your Project
#### Git Helps You Keep Track of Important Changes to Code
#### Git Helps Keep Software Organized and Available After People Leave

### Installing Git
Gitのインストールは、Mac OS XでHomebrew (`brew install git`)を、Linuxで`apt-get` (`apt-get install git`)を使う。[Git website](http://git-scm.com)

### Basic Git: Creating Repositories, Tracking Files, and Staging and Committing Changes
#### Git Setup: Telling Git Who You Are



#### git init and git clone: Creating Repositories


[Seqtk (SEQuence ToolKit)](https://github.com/lh3/seqtk)



#### Tracking Files in Git: git add and git status Part I



#### Staging Files in Git: git add and git status Part II

Figure 5-1. 



#### git commit: Taking a Snapshot of Your Project


テキストエディタを変更


> ### Some Advice on Commit Messages  
>  

`git commit -a -m "your commit message"`

#### Seeing File Differences: git diff 

例えば、README.mdファイルに一行追加して、`git diff`を実行:


ファイルをステージすると、`git diff`は何も出力しない。


直近のコミット　比較


#### Seeing Your Commit History: git log


> ### git log and Your Terminal Pager  
>  


クローンしたseqtkリポジトリで`git log`

#### Moving and Removing Files: git mv and git rm


#### Telling Git What to Ignore: .gitignore

無視させたいファイルを記載した .gitignore ファイルを作成


.gitignore ファイルをステージし、コミット


バイオインフォマティクス・プロジェクトで無視させたいファイルの例:  
- Large files 巨大なファイル
- Intermediate files 中間ファイル (SAM or BAM)
- Text editor temporary files テキストエディタ(Emacs や Vim)の一時ファイル(textfile.txt~ や #textfile.txt#)
- Temporary code files Pythonのoverlap.pyc.

`~/.gitignore_global`にグローバルな`.gitignore`ファイルを作成


設定する


#### Undoing a Stage: git reset



### Collaborating with Git: Git Remotes, git push, and git pull

Figure 5-3. git push (a); git clone (b)  
Figure 5-4. git push (a); git pull (b)  

#### Creating a Shared Central Repository with GitHub
[the Create a New Repository page](https://github.com/new)
zmays-snps

#### Authenticating with Git Remotes


#### Connecting with Git Remotes: git remote



`git remote rm <repository-name>`

#### Pushing Commits to a Remote Repository with git push


#### Pulling Commits from a Remote Repository with git pull


両リポジトリは同じコミットを持つ　`git log`で確認

オリジナルのzmays-snps/ローカル・リポジトリのファイルを修正し、コミットし、pushする:


Barbaraのリポジトリ (zmays-snps-barbara) で、セントラル・リポジトリからpullする。


Barbaraのリポジトリが最新のコミットを含むことを`git log`で確認


#### Working with Your Collaborators: Pushing and Pulling




#### Merge Conflicts

Figure 5-5

#### More GitHub Workflows: Forking and Pull Requests

`pull request`

### Using Git to Make Life Easier: Working with Past Commits
#### Getting Files from the Past: git checkout






#### Stashing Your Changes: git stash


#### More git diff: Comparing Commits and Files


> #### SPECIFYING REVISIONS RELATIVE TO HEAD  

#### Undoing and Editing Commits: git commit --amend


### Working with Branches

- [ブランチとは【ブランチ】 | サルでもわかるGit入門 〜バージョン管理を使いこなそう〜 | どこでもプロジェクト管理バックログ](http://www.backlog.jp/git-guide/stepup/stepup1_1.html)

#### Creating and Working with Branches: git branch and git checkout


隣のアスタリスクは、現在いるブランチを示す。


README.mdを編集:  




この変更をreadme-changesブランチにコミットする。masterブランチに戻り、このコミットが存在しないことを確認する:  


Back on the master branch, suppose we add the adapters.fa file, and commit this change:

masterブランチに戻り、adapters.faファイルを追加し、この変更をコミットする:  


今、両方のブランチに新しいコミットがある。Figure 5-6.


##### Merging Branches: git merge


テキスト・エディタが開く。



##### Branches and Remotes




### Continuing Your Git Education

`git checkout` to restore files  
`git stash` to stash your working changes  
`git branch` to work with branches  

## Chapter 6. Bioinformatics Data
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch06.html#chapter-06)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-06-bioinformatics-data)

大規模で複雑なゲノム・データの課題:  
- Retrieving data データの取得
- Ensuring data integrity データ完全性の確保
- Compression 圧縮

### Retrieving Bioinformatics Data
#### Downloading Data with wget and curl
`wget`と`curl`は、データをウェブからダウンロードするコマンドラインのプログラム。パッケージ管理システム（Homebrewや`apt-get`）でインストールできる。

##### [wget](https://ja.wikipedia.org/wiki/GNU_Wget)
- [Linuxコマンド集 - 【 wget 】 ファイルをダウンロードする：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060228/230995/)
- [ダウンロードコマンドwgetのオプション一覧(linux)](http://blog.layer8.sh/ja/2012/03/31/wget_command/)
- [wget - UNIX/Linuxコマンド - IT専科](http://www.itsenka.com/contents/development/unix-linux/wget.html)


HTTP or FTP の認証は `wget`の`--user=`と`--ask-password`オプションを用いる。

`--recursive` や`-r`オプションで再帰的にデータをダウンロードする。`--level`や`-l`オプションでリンクの深さを指定する。


`wget`の`--limit-rate` オプションを用いて、ダウンロード速度を制限できる。  
`man wget`でオプション一覧を見る。  

Table 6-1. wgetのオプション

##### [Curl](https://ja.wikipedia.org/wiki/CURL)
- [Linuxコマンド集 - 【curl】ファイルのダウンロードやアップロードを行う：ITpro](http://itpro.nikkeibp.co.jp/atcl/column/14/230520/080400003/)


`curl`は`wget`よりも多くのプロトコル [SFTP (secure FTP) や SCP (secure copy) を含む] を用いてファイルを転送できる。  
`-L/--location`オプション

### Rsync and Secure Copy (scp)
- [Rsync](https://ja.wikipedia.org/wiki/Rsync)
 - [Command Technica：はじめてrsyncを使う方が知っておきたい6つのルール (1/2) - ITmedia エンタープライズ](http://www.itmedia.co.jp/enterprise/articles/0804/21/news013.html)
 - [Linuxコマンド【 rsync 】高速なファイル同期（バックアップ） - Linux入門 - Webkaru](http://webkaru.net/linux/rsync-command/)
 - [rsync でディレクトリの同期（バックアップ） - maruko2 Note.](http://www.maruko2.com/mw/rsync_でディレクトリの同期（バックアップ）)

`-avz`オプションで、`-a`は`wrsync`のアーカイブモード（`-rlptgoD`と同じ）、`-z`はデータを圧縮、`-v`は経過を表示。SSHでリモートホストに繋ぐので、`-e ssh`を用いる。ディレクトリをコピーするコマンドは以下の通り:  


末尾のスラッシュを追加するか否か (例えば、*data/* と *data*) で挙動が変わる。

[Secure copy (`scp`)](https://ja.wikipedia.org/wiki/Secure_copy)

例えば、GTFファイルを192.168.237.42:/home/deborah/zea_mays/data/に転送する:  


### Data Integrity [データ完全性](https://ja.wikipedia.org/wiki/データ完全性)

[チェックサム](https://ja.wikipedia.org/wiki/チェックサム)で転送データの整合性を検証。

#### SHA and MD5 Checksums

[MD5](https://ja.wikipedia.org/wiki/MD5)と[SHA-1](https://ja.wikipedia.org/wiki/SHA-1)チェックサム

SHA-1チェックサム。`shasum`（一部のシステムでは`sha1sum`）プログラムに任意の文字列を渡す：




`md5sum`（OS Xでは`md5`）プログラムはMD5ハッシュ値を計算する。

### Looking at Differences Between Data データの違いを見る
- [`diff`](https://ja.wikipedia.org/wiki/Diff)
 - [UNIXの部屋 コマンド検索:diff (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?diff)
 - [diff - コマンド (プログラム) の説明 - Linux コマンド集 一覧表](http://kazmax.zpp.jp/cmd/d/diff.1.html)
 - [Linuxコマンド【 diff 】2つのファイルの差分を出力 - Linux入門 - Webkaru](http://webkaru.net/linux/command-diff/)

*gene-1.bed*と*gene-2.bed*ファイルの差分を出力:  


### Compressing Data and Working with Compressed Data データの圧縮
##### [*gzip*](https://ja.wikipedia.org/wiki/Gzip)
- [UNIXの部屋 コマンド検索:gzip (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?gzip)
- [Linuxコマンド集 - 【 gzip 】 ファイルを圧縮・展開する（拡張子.gz）：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230791/)

`gzip`を用いて、`trimmer`（架空のプログラム）の出力を、ディスクに書き込む前に、圧縮する:  


`gzip`コマンドで圧縮:  


`gunzip`コマンドで伸長:  


`-c`オプションを用いて圧縮・伸長の結果を標準出力に書き出す:  


伸長しないで圧縮ファイルに結合する:  


#### Working with Gzipped Compressed Files
圧縮ファイルを直接操作できるコマンドは、`zgrep`、`zcat`（OS Xでは`gzcat`）、`zdiff`、`zless`など。


### Case Study: Reproducibly Downloading Data

[Genome Reference Consortium](http://www.ncbi.nlm.nih.gov/projects/genome/assembly/grc/)  
GRCm38マウス参照ゲノムを`wget`でダウンロードする。（所要時間 26m 34s）
http://www.ensembl.org の[Mouse](http://www.ensembl.org/Mus_musculus/Info/Index)をクリックし、[Download DNA sequence](ftp://ftp.ensembl.org/pub/release-74/fasta/mus_musculus/dna/)をクリックしてFTPサイトを開く。


`zgrep`コマンドを用いて正規表現"^>"で圧縮ファイルのFASTAヘッダを確認:  


EnsemblのCHECKSUMSファイルと比較:  


SHA-1サムを計算:  


GTFとCHECKSUMSをEnsemblからダウンロード:  


CHECKSUMSファイルと比較し、SHA-1サムを計算:  


Markdownノート（README.md）の例:  






- GTF (General Transfer Format)
 - [GFF/GTF File Format](http://www.ensembl.org/info/website/upload/gff.html)
 - [GTFファイル | GTFフォーマットは遺伝子のアノンテーション情報が記載され,awkを利用して内容抽出](http://bi.biopapyrus.net/transcriptome/gtf.html)
 - [NGS Surfer's Wiki | GTFファイルの細かな違い](http://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=GTFファイルの細かな違い)

----------

# Part III. Practice: Bioinformatics Data Skills
第III部. 実践：バイオインフォマティクス・データスキル  

----------

## Chapter 7. Unix Data Tools
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch07.html#chapter-07)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-07-unix-data-tools)

### Unix Data Tools and the Unix One-Liner Approach: Lessons from Programming Pearls
### When to Use the Unix Pipeline Approach and How to Use It Safely
### Inspecting and Manipulating Text Data with Unix Tools
タブ区切り
BED（3列）とGTFファイル

#### Inspecting Data with Head and Tail
ファイルの最初と最後を見る  



ファイルの始まりと終わりを見る:  


設定ファイル（*~/.bashrc*や*~/.profile*）にショートカットを作る:  


ショートカットの（inspectの）`i`コマンドを実行:  


`grep`の標準出力を`head`に渡す:  



- [シグナル (ソフトウェア)](https://ja.wikipedia.org/wiki/シグナル_(ソフトウェア) )
シグナル`SIGPIPE`は、読み手のいないパイプへの書き込み  
シグナル`SIGINT`は、割り込み端末から割り込みキー（通常 CTRL + C）を押下したときに発生  

#### [less](https://ja.wikipedia.org/wiki/Less)

- [UNIXの部屋 コマンド検索:less (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?less)
- [Linuxコマンド集 - 【 less 】 テキスト・ファイルの内容を閲覧する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230809/)


`less`を終了するには、*q*を押す。

Table 7-1. lessの操作方法

`less`でテキスト検索。アダプター配列。`less`でcontaminated.fastqを開いて、*/*を押して、AGATCGGを入力。結果はFigure 7-1に。

`less`でデバッグ。

#### Plain-Text Data Summary Information with wc, ls, and awk

[wc](https://ja.wikipedia.org/wiki/Wc_(UNIX))で行数、単語数、文字数を表示:


`ls -l`でファイルのサイズを確認:


> ### Data Formats and Assumptions
> 空白（スペース、タブ、改行）を除くには、`grep`を使う:  
> `grep -c "[^ \\n\\t]" some_data.bed`

`awk`でファイルの列（フィールド）数を表示:
  

Mus_musculus.GRCm38.75_chr1.gtfファイルのヘッダを除いてから、列（フィールド）数を`awk`で表示:


`grep`を用いて、"#"で始まる行を除く:


#### Working with Column Data with cut and Columns

`cut`で2列目を抽出:  


`grep`でメタデータ行を削除し、`cut`で1,4,5列（染色体、開始位置、終了位置）を抽出:


`cut`でフィールドのデリミタを指定する。CSVファイルは:


#### Formatting Tabular Data with column


`column -t`で表示:


`column`の`-s`オプションでデリミタを指定:


#### The All-Powerful Grep

`grep`は速い。Figure 7-2は`grep, sed, awk, Python`の実行時間を比較。




> ### GNU, BSD, and the Flavors of Grep  
> Homebrew でインストール `brew install coreutils`  


`-w`, which matches entire words (surrounded by whitespace). 


3つのオプション `-B, -A, -C`


正規表現 POSIX Basic Regular Expressions (BRE)


`-E`オプション。POSIX Extended Regular Expressions (ERE).


`-c`オプション。パターンにマッチした行数を表示。


`-o`オプションでマッチした部分だけを取り出す。


Example 7-1. Cleaning a set of gene names with Unix data tools


[Linuxコマンド集 - 【 grep 】 文字列を検索する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230786/)

#### Decoding Plain-Text Data: hexdump

`man ascii`


- [Linuxコマンド集 - 【hexdump】16進数や8進数で出力する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20140224/538591/)

#### Sorting Plain-Text Data with [Sort](https://ja.wikipedia.org/wiki/Sort_(UNIX))


> ### Using Different Delimiters with sort  
> `sort`の`-t`オプションでフィールドの区切り文字を指定。例えば、-t","  



> ### Sorting Stability  
> `sort`の`-s`オプション

すでにソートされているかチェックする:


逆順にソートする:


一部のオプションは、GNU `sort`でのみ利用可能（Mac OS XのBSDではない）。例えば、`-V`


メモリ




参考:  
- [UNIXコマンド辞典>>sort](http://codezine.jp/unixdic/w/sort)
- [UNIXコマンド - sort (Linux/FreeBSD/Solaris)](http://www.k-tanaka.net/unix/sort.php)

#### Finding Unique Values in [Uniq](https://ja.wikipedia.org/wiki/Uniq)


`-i`オプションで、大文字と小文字の区別をしない。  
`-c`オプションで、行数も合わせて表示


Unixコマンド（`grep, cut, sort, uniq`）を組み合わせて、表形式データの列を要約:


`-d`オプションで、連続する行のみを表示


参考:  
- [UNIXコマンド - uniq (Linux/FreeBSD/Solaris)](http://www.k-tanaka.net/unix/uniq.php)

#### [Join](https://en.wikipedia.org/wiki/Join_(Unix))
参考:  
- [NGS Surfer's Wiki | UNIX:join](https://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=UNIX%3Ajoin)


`chr3`が無い場合: 


`-a`オプション


#### Text Processing with [Awk](https://ja.wikipedia.org/wiki/AWK)

> ### Gawk versus Awk  


Table 7-2. Awk comparison and logical operations


`BEGIN`と`END`


> ### Setting Field, Output Field, and Record Separators  


ファイル変換


Awkの連想配列 (associative array)は、Pythonの辞書、Perlのハッシュのように振る舞う。


Table 7-3. Useful built-in Awk functions


Unixコマンド（`grep, cut, sort, and uniq -c`）を用いて、特定の遺伝子の特徴をカウントする:


参考:  
- [共通テーマ: 実例でわかる awk: 第 1 回](http://www.ibm.com/developerworks/jp/linux/library/l-awk1/)
- [第17回ａｗｋの連想配列](http://homepage2.nifty.com/mozu/koza/awk_koza/awk_koza_17.html)

#### Bioawk: An Awk for Biological Formats

Mac OS Xの Homebrew でインストール:




FASTQをFASTAファイルに変換: 


FASTQ/FASTAエントリ数をカウント:


相補鎖: 




オプション`-c hdr`


#### Stream Editing with Sed

> ### GNU Sed versus BSD Sed  

簡単な例:


例えば、"chr1:28427874-28425431" (染色体名:開始位置-終了位置) を3列で出力:



`head -n 10`と同様、ファイルの最初の10行を出力する:  


20〜50行まで出力する:  


### Advanced Shell Tricks
#### Subshells
参考:  
- [UNIXの部屋 コマンド検索:サブシェル (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?%A5%B5%A5%D6%A5%B7%A5%A7%A5%EB)

例:  


メタデータのヘッダがあるGTFファイルをソートする:


ストリームを（`gzip`で圧縮してから）ファイルにリダイレクトする:


#### Named Pipes and Process Substitution
*named pipes* [名前付きパイプ](https://ja.wikipedia.org/wiki/名前付きパイプ)



*process substitution* プロセス置換


### The Unix Philosophy Revisited

## Chapter 8. A Rapid Introduction to the R Language
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch08.html#chapter-08)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-08-r)

### Getting Started with R and RStudio

> #### THE COMPREHENSIVE R ARCHIVE NETWORK (CRAN)  
> install.packages("ggplot2")  

### R Language Basics
#### Simple Calculations in R, Calling Functions, and Getting Help in R

Table 8-1. Common mathematic functions

> #### SIGNIFICANT DIGITS, PRINT(), AND OPTIONS IN R  


`round()`関数


> #### GETTING HELP IN R  


#### Variables and Assignment
変数の代入  

> ### RStudio Assignment Operator Shortcut


#### Vectors, Vectorization, and Indexing
ベクトル  
  
- [13. ベクトル要素へのアクセス | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/13.html)



> ### Out-of-Range Indexing  
> `z[c(2, 1, 10)]`  

z[負整数ベクトル]は、対応する要素番号の要素を取り除く。







比較演算子、例えば、==, !=, <, <=, >, >= （Table 8-2）を用いて、TRUEとFALSEの論理ベクトルを作成する。  


x[論理値ベクトル]は、TRUEの要素に対応した要素を取り出す（Example 8-1）。  
Example 8-1. Indexing vectors with logical vectors  


Table 8-2. R’s comparison and logical operators | Rの比較演算子と論理演算子  

- [28. 演算子 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/28.html)

##### Vector types

- [09. データの型 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/09.html)
- [18. NULL，NA，NaN，Infの操作 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/18.html)
- [25. データ型とデータ構造 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/25.html)

Table 8-3. R’s vector types | Rのベクトル型

> #### R’S SPECIAL VALUES  
> `(NA, NULL, Inf/-Inf, and NaN)`  

ベクトルの要素は全て同じ型  

> ### Type Coercion in R  

Rの型の強制変換規則



##### Factors and classes in R
因子とクラス









Rには3種類のオブジェクト指向システム（S3, S4, R5のクラス）がある。

- [Rのオブジェクト指向について(R) - script of bioinformatics](https://sites.google.com/site/scriptofbioinformatics/r-tong-ji-guan-xi/rnoobujekuto-zhi-xiangnitsuite-r)

### Working with and Visualizing Data in R

[Dataset_S1.txt](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-08-r/Dataset_S1.txt)

#### Loading Data into R

Rに読み込む前に、コマンドラインからファイルを検査する


> #### LARGE GENOMICS DATA INTO R: COLCLASSES, COMPRESSION, AND MORE  
> `colClasses` vector to `"NULL"`  
> `nrow` in `read.delim()`  
> `data.table`パッケージの`fread()`関数を使う。  
> Rパッケージ`RSQLite`  
> Rの関数は直接gzip圧縮されたファイルを読み込むこともできる。


デフォルトでは、Rのread.delim()とread.csv()関数は、文字列を文字列(character)ではなく因子(factor)に強制変換する。これを無効にするには
`stringsAsFactors=FALSE` (or use `asis`; see `help(read.table)`

Table 8-4. read.csv() と read.delim() の引数

> #### GETTING DATA INTO SHAPE  
> Table 8-5. 組織毎の遺伝子発現の計数表（wideフォーマット）
> Table 8-6. 組織毎の遺伝子発現の計数表（longフォーマット）

`reshape2`パッケージはデータを変換する関数を提供する。`melt()`はwideデータをlongデータに変換し、`cast()`はlongデータをwideデータに変換する。  


#### Exploring and Transforming Dataframes
参考:  
- [21. 行列の操作 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/21.html) | 関数 dim() ，nrow() ，ncol()
- [39. データフレーム事始 | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/39.html)





> ### Creating Dataframes from Scratch  


data.frame型では、ドル・マーク($)で変数を指定できる。



> ### Fragile Code and Accessing Rows and Columns in Dataframes  


20番染色体のセントロメアの位置は、25,800,000 から 29,700,000 である。セントロメア領域にあるかどうか（TRUE/FALSE）を示す列を、データフレーム（d）に追加する: 


塩基多様度の列`Pi`の大きさを変更した新しい列`diversity`を作成する: 


#### Exploring Data Through Slicing and Dicing: Subsetting Dataframes









#### Exploring Data Visually with ggplot2 I: Scatterplots and Densities

- [Rのグラフィック作成パッケージ“ggplot2”について｜Colorless Green Ideas](http://id.fnshr.info/2011/10/22/ggplot2/)
- [ggplot2 | R のグラフをより美しく](http://stat.biopapyrus.net/ggplot/)
- [ggplotの使い方 | Memo on the Web](http://motw.mods.jp/R/ggplot_tutorial.html)
- [パッケージggplot - 浅井拓也　研究室用ページ](http://qh73xe.jimdo.com/プロット/パッケージggplot/)
- [ggplot2 の自分用メモ集を作ろう - Triad sou.](http://d.hatena.ne.jp/triadsou/20100528/1275042816)
- [R でグラフ作成 ggplot2 入門](http://www.cwk.zaq.ne.jp/fkhud708/files/R-ggplot2.pdf)
- [Tutorial of ggplot2 by Hadley Wickham at ISM | Siguniang's Blog](https://siguniang.wordpress.com/2010/11/25/tutorial-of-ggplot2-by-hadley-wickham-at-ism/)


`ggplot2`パッケージ、base graphics、`lattice`パッケージ  

[`ggplot2`のオンライン・ドキュメント](http://docs.ggplot2.org/current/)  

Rの`library()`関数で`ggplot2`パッケージをロードする:  


染色体の位置毎の塩基多様度の散布図（Figure 8-1）を作成する。まず、データフレーム`d`に列`position`（各ウィンドウの中間点）を追加する。次に、データフレーム`d`の列`position`と列`diversity`の散布図を`ggplot2`で作成する:  


Figure 8-1. ggplot2の散布図：ヒト20番染色体の位置毎の塩基多様度

例えば、`geom_point(), geom_line(), geom_bar(), geom_density(), geom_boxplot()`など。`aes()`関数

> ### Axis Labels, Plot Titles, and Scales  
> `xlab(), ylab(), ggtitle()`関数  
> `scale_x_continuous(limits=c(start, end))`、関数`scale_x_log10()`と`scale_y_log10()`  

Example 8-2は、`aes()`を`ggplot()`に含み、Figure 8-1と全く同じ散布図を作成する:  



Example 8-3は、セントロメア領域か否か（列`cent`のTRUE/FALSE）で色分けして、Figure 8-2を作図:  


（同じ位置にプロットが重なっている）overplottingを回避するために、透明度（alpha）を調整して、Figure 8-3を作図:



`geom_density()`を用いて、多様度の密度を見る（Figure 8-4）:  


多様度の密度を、セントロメア領域か否か（列`cent`のTRUE/FALSE）で分けて、透明度（alpha）を半分にして、Figure 8-5を作図:  


#### Exploring Data Visually with ggplot2 II: Smoothing

- sequencing depth
 - [ultra deep sequence：バイオキーワード集｜実験医学online：羊土社](https://www.yodosha.co.jp/jikkenigaku/keyword/3175.html)
 - [次世代シーケンサーにおけるcoverageの日本語訳 - #LSQA](http://qa.lifesciencedb.jp/questions/258/次世代シーケンサーにおけるcoverageの日本語訳)

散布図と平滑化曲線を用いて、シークエンシング深度（列`depth`）とウィンドウのSNP合計数（列`total.SNPs`）の関係を見る（Figure 8-6）:  


デフォルトでは、`ggplot2`は一般化加法モデル（generalized additive models; GAM）を用いて、平滑化曲線に合わせる。
`help(stat_smooth)`、`geom_smooth(se=FALSE)`

散布図と平滑曲線を用いて、シークエンシング深度に及ぼすGC含量の影響を見る（Figure 8-7）:  


#### Binning Data with cut() and Bar Plots with ggplot2

Binning（離散化）

- [秩序と情報とブロッコリー: R言語のcut関数の使い方](http://data-hacker.blogspot.jp/2013/05/rcut.html)
- [R.4.42. 連続数のカテゴリ作成 | R Financial & Marketing Library](http://itbc-world.com/home/rfm/rの機能/連続数のカテゴリ作成/)
- [R言語で数量データをカテゴリーデータに変換 - jnobuyukiのブログ](http://webbeginner.hatenablog.com/entry/2015/05/27/010805)
- [Rでbinning - にちにちメモ](http://schngtm.hatenablog.com/entry/2014/12/03/003622)

Rでは、`cut()`関数でデータを離散化する（Example 8-4は、GC含量）:  





`ggplot2`の`geom_bar()`



Figure 8-8.  
`geom_bar()`の`x`が、
因子（例えば、`d$binned.GC`）の場合には、`ggplot2`は計数値の棒グラフ（Figure 8-8の左）を作成する。
連続の数値（例えば、`d$percent.GC`）の場合には、自動的にデータを離散化してヒストグラム（Figure 8-8の右）を作図する。


Figure 8-9. GC含量でグループ分けされたシークエンシング深度（depth）の密度プロット


> ### Finding the Right Bin Width  
> `ggplot(d) + geom_bar(aes(x=Pi), binwidth=1) + scale_x_continuous(limits=c(0.01, 80))`  
> binwidthの値を 0.05, 0.5, 1, 5, 10 に変化させる。

#### Merging and Combining Data: Matching Vectors and Merging Dataframes

Rの[`%in%`](https://stat.ethz.ch/R-manual/R-devel/library/base/html/match.html)演算子


[RepeatMasker](http://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=RepeatMasker)で発見されたヒトX染色体上のリピート領域のデータ（chrX_rmsk.txt）を読み込む:  


列`repClass`は因子（factor）であることを確認:  



複数のリピートのクラス（DNA、LTR、LINE、SINE、Simple_repeat）の行を選択するために、`common_repclass`ベクトルを作成し、`%in%`を用いる:  


上位5つの最も多いリピートのクラスを計算する:  


- [文字列 | Rを利用して文字列のマッチング,結合,分割,置換を行う関数](http://stat.biopapyrus.net/r/string.html)


第1のデータセット（[motif_recombrates.txt](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-08-r/motif_recombrates.txt)）は、各モチーフの40kb内の全ウィンドウについて、組換え確率（recombination rate）推定値を含む。第2のデータセット（[motif_repeats.txt](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-08-r/motif_repeats.txt)）は、各モチーフが出現するリピートを含む。2つのデータセットをマージして、特定のリピートに及ぼす各モチーフの組換えの局所的な効果を見る。

> ### Creating These Example Datasets  

> 本データを発生させたコードは[*motif-example/*](https://github.com/vsbuffalo/bds-files/tree/master/chapter-08-r/motif-example)ディレクトリを参照されたい。


`rpts`データフレームの列名を`mtfs`にマージする。2つの列（`chr`と`motif_start`）を1つの文字列にマージするために、`paste()`関数を用いる:  


列`pos`は、2つのデータセット間の共通の鍵として機能する。  
マージする前に、`mtfs`のモチーフと`rpts`の対応するエントリの個数を確認する:  


マージする前に、`match()`を用いて、`mtfs$pos`と`rpts$pos`のインデックス・ベクトル（`i`）を作成する:  


`match()`の結果を（`i`への割り当てをスキップして）直接用いる:  




- [43. データの結合（マージ）と整列（ソート）](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/43.html)


#### Using ggplot2 Facets


Figure 8-10. 配列モチーフとの距離と組換え確率



`ggplot2`の`facet_wrap()`を用いて、これらのモチーフを分割する（Figure 8-11）:  


- [ggplotのfacet_grid(), facet_wrap()の使い方 | Memo on the Web](http://motw.mods.jp/R/ggplot_facet.html)
- [ggplot2で複数グラフ表示 - 盆栽日記](http://d.hatena.ne.jp/dichika/20110116/1295183973)
- [facet_wrap - 浅井拓也　研究室用ページ](http://qh73xe.jimdo.com/プロット/パッケージggplot/facet-wrap/)


Figure 8-12は


Figure 8-12. 

`facet_grid()`と`facet_wrap()`の何れも引数`scales`を指定できる。例えば（Figure 8-13）:  


#### More R Data Structures: Lists

- [23. リスト](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/23.html)
- [リスト | Rのリストはハッシュやマップのように利用できる](http://stat.biopapyrus.net/vector/list.html)
- [リストにオブジェクトをしまう](http://takenaka-akio.org/doc/r_auto/list.html)

データフレームはリスト; `is.list(mtfs)`


`[　]`はリストを取り出す。
`[[ ]]`はリスト内の要素（ベクトル）を取り出す。







> #### Peeking into R’s Structures with str()  

#### Writing and Applying Functions to Lists with lapply() and sapply()

- [24. apply() ファミリー](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/24.html)
- [applyファミリー | apply,sapply,lapplyの使い方とその例](http://stat.biopapyrus.net/r/apply.html)
- [apply系関数の使い方](http://takenaka-akio.org/doc/r_auto/chapter_07_apply.html)

##### Using lapply()



> ##### lapply() in Parallel  

引数を渡す:  


##### Writing functions


- [31. 関数の定義](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/31.html)
- [関数の作り方 | functionによりRの関数を定義する方法](http://stat.biopapyrus.net/r/user-function.html)
- [Rの関数定義の基本 - RjpWiki](http://www.okadajp.org/RWiki/?Rの関数定義の基本)
- [[連載]フリーソフトによるデータ解析・マイニング　第4回 Rでの関数オブジェクト](http://www1.doshisha.ac.jp/~mjin/R/04.html)

[無名関数](https://ja.wikipedia.org/wiki/無名関数)(anonymous function)  


`meanRemoveNAVerbose()`関数の定義:  
	meanRemoveNAVerbose <- function(x, warn=TRUE) {


> ##### Function Scope  
> [スコープ](https://ja.wikipedia.org/wiki/スコープ)  

- [32. ローカル変数と永続代入<<-](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/32.html)
- [変数スコープ | R,レキシカルスコープ](http://stat.biopapyrus.net/dev/scope.html)

##### Digression: Debugging R Code

- [デバッグ | Rのbrowser,debug,traceback関数の使い方](http://stat.biopapyrus.net/dev/debug.html)
- [35. デバッグについて | R-Source](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/35.html)

関数`browser()`

	foo(1)

`n`で次の行を確認、`c`でコードの実行を継続、`Q`で終了

`options(error=recover)`も有用  





##### More list apply functions: sapply() and mapply()


- [14. ベクトル計算](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/14.html)


> ##### Other Apply Functions for Other R Data Structures   
配列と行列　`apply()`と`sweep()`
- [オブジェクト型 | Rのリスト、データフレーム、行列、配列など](http://stat.biopapyrus.net/r/objecttype.html)
- [R言語プログラミング： データ型・操作 - hamadakoichi blog](http://d.hatena.ne.jp/hamadakoichi/20100118/1263832446)
- [R-Tips](http://cse.naro.affrc.go.jp/takezawa/r-tips/r.html)
  - [19. 行列の作成](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/19.html)
  - [20. 行列計算](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/20.html)
  - [21. 行列の操作](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/21.html)
  - [22. 配列](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/22.html)
  - [25. データ型とデータ構造](http://cse.naro.affrc.go.jp/takezawa/r-tips/r/25.html)

#### Working with the Split-Apply-Combine Pattern
["The Split-Apply-Combine Strategy for Data Analysis"](http://www.jstatsoft.org/v40/i01/paper)  

Example 8-4 と Figure 8-9  

- [R.4.05. データフレーム型 | R Financial & Marketing Library](http://itbc-world.com/home/rfm/rの機能/データフレーム型/)







- [リストTips大全 - RjpWiki](http://www.okada.jp.org/RWiki/?リストTips大全) | do.call
- [do.callは気持ち悪いのでReduceを積極的に使いたい - My Life as a Mock Quant](http://d.hatena.ne.jp/teramonagi/20110214/1297688917)

> #### Understanding do.call()  


#### Exploring Dataframes with dplyr

dplyr
- [dplyrを使いこなす！基礎編 - Qiita](http://qiita.com/matsuou1/items/e995da273e3108e2338e)
- [大規模データの高速処理 ーdata.table、dplyrー](http://kohske.github.io/ESTRELA/201410/index.html)
- [plyr — データ分割-関数適用-再結合を効率的に — Watallica metallicus](http://meme.biology.tohoku.ac.jp/students/iwasaki/rstats/plyr.html)
- [dplyrでデータ処理](http://www.pu-hiroshima.ac.jp/~ttetsuji/R/%5B64%5Ddplyr.html)

#### Working with Strings

### Developing Workflows with R Scripts
#### Control Flow: if, for, and while
#### Working with R Scripts
#### Workflows for Loading and Combining Multiple Files
#### Exporting Data
 
### Further R Directions and Resources



## Chapter 9. Working with Range Data
範囲データの操作  
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch09.html#chapter-09)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-09-working-with-range-data)

## Chapter 10. Working with Sequence Data
配列データの操作  
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch10.html#chapter-10)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-10-sequence)

### The FASTA Format
[FASTA](https://ja.wikipedia.org/wiki/FASTA)  
[FASTA形式](http://quma.cdb.riken.jp/help/fastaHelp_j.html)の配列は行頭が(">") で始まるコメントの行があり、その次の行以降に配列が記述される。


一般的な命名規則は、記述行をスペースで2つの部分（IDと説明）に分割する:  


### The FASTQ Format
- [FastQ形式](https://ja.wikipedia.org/wiki/Fastq)
- [NGS Surfer's Wiki | FASTQ](http://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=FASTQ)

FASTA/FASTQエントリの計数


@は、クオリティ値として行頭にくることもある。


配列数を計数する頑健な方法は`bioawk`を用いる:  


### Nucleotide Codes
核酸コード  
 
- [Nucleotide Base Codes | DDBJ](http://www.ddbj.nig.ac.jp/sub/ref1-j.html)

Table 10-1. IUPAC nucleotide codes

### Base Qualities
ASCII 文字 (`man ascii`)  
Pythonの関数`ord()`と`chr()`

### Example: Inspecting and Trimming Low-Quality Bases

Rに`qrqc`をインストール:  


`sickle`と`seqtk`をHomebrewを用いてMac OS Xにインストール:  


FASTQファイル untreated1_chr4.fq をトリムする:  



これらの結果をRで比較する。`qrqc`を用いて位置毎のクオリティの分布を収集し、`ggplot2`を用いて可視化する。`lapply`で自動化する。


このRスクリプトは2つのプロット（Figures 10-1と10-2）を作成する。


### A FASTA/FASTQ Parsing Example: Counting Nucleotides

FASTA/FASTQのパースには既存のライブラリを使うのがベスト。  
[readfq](https://github.com/lh3/readfq)のPythonスクリプト（readfq.py）をダウンロードする。  
`from readfq import readfq`  


### Indexed FASTA Files


Samtoolsの`faidx`サブコマンドを用いて、FASTAファイルのインデックスを作成する:  


インデックス・ファイル（Mus_musculus.GRCm38.75.dna.chromosome.8.fa.fai）が作成されます。

特定の領域の部分配列にアクセスするには、`samtools faidx <in.fa> <region>`を実行する。ここで、`<in.fa>`は（インデックスを作成した）FASTAファイル、`<region>`は`chromosome:start-end`の形式。例えば:  



- [アメリエフのブログ | samtools ゲノムのインデックスファイルの中身](http://blog.amelieff.jp/?eid=220985)
- [NGS Surfer's Wiki | SAMtools](http://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=samtools)
- [samtoolsの使い方 - #LSQA](http://qa.lifesciencedb.jp/questions/458/samtoolsの使い方)

## Chapter 11. Working with Alignment Data
アライメントデータの操作  
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch11.html#chapter-11)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-11-alignment)

### Getting to Know Alignment Formats: SAM and BAM
#### The SAM Header
#### The SAM Alignment Section
#### Bitwise Flags
#### CIGAR Strings
#### Mapping Qualities
### Command-Line Tools for Working with Alignments in the SAM Format
#### Using samtools view to Convert between SAM and BAM
#### Samtools Sort and Index
### Visualizing Alignments with samtools tview and the Integrated Genomics Viewer
#### Pileups with samtools pileup, Variant Calling, and Base Alignment Quality

## Chapter 12. Bioinformatics Shell Scripting, Writing Pipelines, and Parallelizing Tasks
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch12.html#chapter-12)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-12-pipelines)

### Basic Bash Scripting
#### Writing and Running Robust Bash Scripts
##### A robust Bash header

- [シェルスクリプトマナー - きつねたぬきだし](http://kitsunetanukidashi.hatenablog.com/entry/2014/07/12/231833)
- [Linux - bashの*スクリプトにセットする推奨オプション](http://qiita.com/kiida/items/3beb1bf718cdc2f0798a)

*template.sh*ファイルに書かれたBashスクリプトのヘッダは、短縮して`set -euo pipefail`と書ける。


- 1行目：[*shebang*](https://ja.wikipedia.org/wiki/シバン_(Unix))
- 2行目：`set -e`は、nonzero exit status 異常終了時（非ゼロ終了ステータス）スクリプトを終了させる。
- 3行目：`set -u`は、変数の値が設定されていない場合にスクリプトを終了させる。


- 4行目：`set -o pipefail`

##### Running Bash scripts

`bash script.sh` または `./script.sh`


#### Variables and Command Arguments

{}(大括弧)、""(ダブルクォーテーション)で変数名を囲む。


##### Command-line arguments コマンドライン引数

変数`$0`はスクリプトの名前を格納する。



Bash assigns the number of command-line arguments to the variable $# (this does not count the script name, $0, as an argument). This is useful for user-friendly messages (this uses a Bash if conditional, which we’ll cover in more depth in the next section):

変数`$#`にはコマンドライン引数の個数を割り当てる（スクリプト名の$0は引数としてカウントしない）。





Pythonの`argparse`モジュールは、Unixツール`getopt`よりも簡単に使える。

> ### Reproducibility and Environmental Variables  

#### Conditionals in a Bash Script: if Statements
bashの条件文: if文

Bashでは、コマンドの終了ステータスが0は真/成功を表し、それ以外は偽/失敗である。 `if`文の基本構文:  


`if`文で`&&`（論理積AND）や`||`（論理和OR）演算子を用いる:  


`!`で終了ステータスを否定する:  


`test`コマンドの実行例（`echo "$?"`で終了ステータスを出力）


Table 12-1. String and integer comparison operators 文字列と整数の比較演算子


Table 12-2. File and directory test expressions

`if test -f some_file.txt`を`if [ -f some_file.txt ] `で代用できる。`[]`前後に半角スペースが必要。  
この構文では、`-a`（論理積AND）、`-o`（論理和OR）、`!`（否定）を使える。`test`では`&&`と`||`演算子は使えない。

As an example, suppose we want to ensure our script has enough arguments and that the input file is readable:
例として、スクリプトが十分な引数を持ち、入力ファイルが読み込み可能であることを確認する:  



[短絡評価](https://ja.wikipedia.org/wiki/短絡評価)（short-circuit evaluation）　演算子の第一引数を評価した段階で式全体の値が定まらない場合のみ第二引数を評価する方式を意味する。例えば、ANDの第一引数を評価した結果が false であれば、式全体は必ず false になるし、ORの第一引数が true であれば、式全体は必ず true になるので、第二引数を評価するまでもない。

- [if 文と test コマンド - UNIX & Linux コマンド・シェルスクリプト リファレンス](http://shellscript.sunone.me/if_and_test.html)
- [シェルスクリプト入門 [演算・比較]](http://www.k4.dion.ne.jp/~mms/unix/shellscript/shell_calc.html)
- [条件式](http://itdoc.hitachi.co.jp/manuals/3020/30203S3530/JPAS0134.HTM)

#### Processing Files with Bash Using for Loops and Globbing
for文とglobでファイル処理


- [bash 配列まとめ - Qiita](http://qiita.com/b4b4r07/items/e56a8e3471fb45df2f59)


bash 配列、要素、添字


コマンド置換 (command substitution)


> ### The Internal Field Separator, Word Splitting, and Filenames
`sample_files=($(cut -f 3 samples.txt))`
[Internal Field Separator (IFS)](https://en.wikipedia.org/wiki/Internal_field_separator)の値を調べる:  `printf %q "$IFS"`

Unixプログラム`basename`は、ファイル名からパスや拡張子を削除する:



処理スクリプト:





参考:  
- [＠IT：ファイル名からディレクトリや拡張子を取り除くには](http://www.atmarkit.co.jp/flinux/rensai/linuxtips/437delfileext.html)


最後に、ループで簡単に:


### Automating File-Processing with find and xargs

#### Using find and xargs




#### Finding Files with find

Again, using the zmays-snps/ toy directory we created in “Organizing Data to Automate File Processing Tasks” on page 26:






Example 12-1. Find through filename matching


#### find’s Expressions

`-type`オプション:


`f` for files, `d` for directories, and `l` for links.



Table 12-3. Common find expressions and operators

否定:


(we are still in the zmays/data directory):



参考:  
- [Linuxコマンド集 - 【 find 】 ファイルやディレクトリを検索する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20060227/230777/)

#### find’s -exec: Running Commands on find’s Results



Deleting Files with find -exec:  
`-delete`オプション

#### xargs: A Unix Powertool
[xargs](https://ja.wikipedia.org/wiki/Xargs)  
参考:  
- [Linuxコマンド集 - 【xargs】標準入力から生成したコマンドラインを実行する：ITpro](http://itpro.nikkeibp.co.jp/article/COLUMN/20140331/547143/)
- [UNIXの部屋 コマンド検索:xargs (*BSD/Linux)](http://x68000.q-e-d.net/~68user/unix/pickup?xargs)
- [xargs コマンド | コマンドの使い方(Linux) | hydroculのメモ](https://hydrocul.github.io/wiki/commands/xargs.html) 一度にコマンドに渡す引数の最大数を制御するには [2014/01/05] {option-n}



### Playing It Safe with find and xargs

スペースを含むファイル名

`xargs`の`-n`オプションは、コマンドライン1つにつき使用する引数の個数を指定:  


`rm`を実行する前に、`find`が返すファイルを確認する:  


`xargs`を用いてコマンドを書いたスクリプトを作成し、確認してから実行する:  


#### Using xargs with Replacement Strings to Apply Commands to Files

あるプログラムは（`program --in file.txt --out-file out.txt`のように）オプションで引数を取る、別のプログラムは（`program arg1 arg2`のように）位置指定引数を取る。`xargs`の`-I{}`オプション



### BSD and GNU xargs

Macの場合、HomebrewでGNU Coreutilsをインストール

#### xargs and Parallelization

t how many processes run simultaneously. xargs allows us to do this with the 

オプション`-P <num>`で、<num>プロセスまで同時に実行する


> ### xargs, Pipes, and Redirects  




> 上のスクリプトを実行する:  
> `find . -name "*.fastq" | xargs -n 1 -P 4 bash script.sh`  
> ここで、`-n 1`はコマンドライン1つにつき最大1個の引数を使用することを意味し、`-P`オプションで同時に実行するプロセスの個数を指定できる（0ならできるだけ多くのプロセスを同時に実行しようとする）。

[GNU Parallel](http://www.gnu.org/software/parallel/)


### Make and Makefiles: Another Option for Pipelines
[Make](https://ja.wikipedia.org/wiki/Make)

参考:  
- [Makeについて知っておくべき7つのこと | インフラ・ミドルウェア | POSTD](http://postd.cc/7-things-you-should-know-about-make/)

宣言型プログラミング（英: Declarative programming）  
各ルールは3つのパート（ターゲット、必要条件、レシピ）を持つ。  

[Makefile](https://raw.githubusercontent.com/vsbuffalo/bds-files/master/chapter-12-pipelines/Makefile)  
を`make all`で実行する





## Chapter 13. Out-of-Memory Approaches: Tabix and SQLite
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch13.html#chapter-13)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-13-out-of-memory)

### Fast Access to Indexed Tab-Delimited Files with BGZF and Tabix
*BGZF* (Blocked GNU Zip Format)  
`bgzip`と`tabix`プログラムは、Samtools (例 samtools-1.2/htslib-1.2.1) に含まれている。

#### Compressing Files for Tabix with Bgzip

ファイルの先頭にメタデータのヘッダがある。


サブシェルを使う。`gzip`の代わりに`bgzip`で:


#### Indexing Files with Tabix

`tabix`の`-p`引数を用いて、`bgzip`で圧縮されたGTFファイルにインデックスを張る:  
インデックスファイルの拡張子は*.tbi*:  


参考:  
- [tabix(1) manual page](http://www.htslib.org/doc/tabix.html)
- [How to use `tabix`.](https://gist.github.com/knmkr/5405249)
- [NGS Surfer's Wiki | vcftoolsインストールログ](http://cell-innovation.nig.ac.jp/wiki/tiki-index.php?page=vcftoolsインストールログ)

#### Using Tabix

例えば、Mus_musculus.GRCm38.75.gtf.bgz の16番染色体上の23,146,536（開始位置）から23,158,028（終了位置）までのフィーチャーにアクセスする:  


このコマンドの標準出力をパイプでawkに渡し、列featureが「exon」の行を抽出する:  


### Introducing Relational Databases Through SQLite
*flat file* [フラットファイル形式](http://e-words.jp/w/フラットファイル.html)。Unixツールの`join`やR言語の`match()`や`merge()`関数を用いてテーブルを結合できる。*relational databases* [関係データベース](https://ja.wikipedia.org/wiki/関係データベース)。  

[*SQL* (Structured Query Language)](https://ja.wikipedia.org/wiki/SQL)。  

relational database management system (RDBMS) [関係データベース管理システム](http://e-words.jp/w/RDBMS.html)の[*SQLite*](https://ja.wikipedia.org/wiki/SQLite)。  

#### When to Use Relational Databases in Bioinformatics
[application programming interfaces (API)](https://ja.wikipedia.org/wiki/アプリケーションプログラミングインタフェース)

#### Installing SQLite
Homebrew（`brew install sqlite`）でMac OS Xにインストール、または`apt-get install sqlite3`でUbuntuマシンにインストール。

#### Exploring SQLite Databases with the Command-Line Interface
SQLiteのコマンドラインツール`sqlite3`を用いて、データベース*gwascat.db*ファイルに接続すると、対話的（インタラクティブ）なSQLiteプロンプトが出る:  


- [SQLite - ドットコマンド](http://www18.atpages.jp/iyork/stored/sqlite/help.html)

ドット・コマンドは.で始まる（空白で始めることはできない）。


Table 13-1. Useful SQLite3 dot commands


SQLiteでは、列は型を持たないが、データ値は型を持つ。データ値は5タイプの何れか: text、integer、real、NULL、BLOB（binary large object）

参考:  
- [SQLite | MacでSQLite3を操作する](http://ortk.main.jp/blog/?p=628)
- [はじめてのSQLite（Mac版）](http://doruby.kbmj.com/oneafter999_on_rails/20100806/_SQLite_Mac_)
- [[SQLite] 記憶クラス(データ型)とカラム型 - Life with IT](http://l-w-i.net/t/sqlite/data_001.txt)
- [SQLite入門](http://www.dbonline.jp/sqlite/)

> ### Orderly Columns  

#### Querying Out Data: The Almighty SELECT Command

SELECT文を用いて、テーブルの全ての列から全ての行を取得する:  


> #### Working with the SQLite Command-Line Tool  
Control-u で、入力をクリアする。

sqlite3のコマンドラインツールは、（対話的なSQLiteのシェル代わりに）直接コマンドラインから問い合わせ可能。例えば、`gwascat`テーブル内の全てのデータを取得する:  


列の分離形式（オプション-separatorに、CSVは","を、タブは"\t"を指定）や、列ヘッダの表示（-header）・省略（-noheader）を変更:  


- [sqlite - sqlite3 output with tabs from one line command - Stack Overflow](http://stackoverflow.com/questions/6547908/sqlite3-output-with-tabs-from-one-line-command)

##### Limiting results with LIMIT
- [取得するデータの数と開始位置を指定(LIMIT句, OFFSET句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index10.html)


##### Selecting columns with SELECT
- [データの取得(SELECT文) - SQLite入門](http://www.dbonline.jp/sqlite/select/index1.html)

カンマ区切りで一部の列（trait, chrom, position, strongest_risk_snp, pvalue）を指定:  


SQLiteの設定を変更:  


##### Ordering rows with ORDER BY
- [取得したデータをカラムの値でソート(ORDER BY句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index2.html)

SELECTが返す行はソートされていない。例えば、著者の姓（author）でソートして、研究に関連する列（author、trait、journal）を表示する:


ORDER BY句にDESCを追加すると、降順で結果を返す:  


SQLiteの列は厳格な型を持たない。データ値の型が混在する列に、ORDER BYを使うと、次の順に従う。NULL値 > 整数と実数の値（数値でソート） > テキスト値 > BLOB値。ソートすると、NULL値が常に最初にくる。p値で昇順ソートして確認:  


第8章で議論したように、データを並べ替えて異常値を探すことは、データの問題を探す有効な方法である。例えば、p値（0〜1の範囲を示す確率）を降順にソートして確認:  


2つの誤ったp値はデータ入力ミス。p値を入力するときにマイナス記号を忘れる（例えば、9e-7 を 9e7 と記載）。

##### Filtering which rows with WHERE
- [取得するデータの条件を設定(WHERE句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index3.html)

WHERE句で特定の行を除外。例えば、strongest risk SNP = "rs429358"の行を表示:  


大文字と小文字は区別される。比較の前にlower()関数で値を小文字に変換:  


Table 13-2. Common operators used in WHERE statements

- [取得するデータの条件を設定(WHERE句) - SQLite入門 | 比較演算子を使った条件式](http://www.dbonline.jp/sqlite/select/index3.html#section2)

- [取得するデータの条件を設定(WHERE句) - SQLite入門 | 論理演算子を使った条件式](http://www.dbonline.jp/sqlite/select/index3.html#section3)

論理演算子`AND`と`OR`を用いて条件式を組み合わせる。例えば、例えば、第22染色体上でp-valueが10e-15未満の全ての行を取得:  


- [値がNULLのものを取得(IS NULL句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index7.html)

`WHERE pvalue IS NOT NULL`でNULL値を排除してから並べ替える:  


`OR`で何れかの条件を満たす行を選択する:  


- [指定した値のリストと比較(IN句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index5.html)

`OR`と`=`の代わりに、`IN`（または`NOT IN`）を用いる:


- [指定した値の範囲と比較(BETWEEN句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index4.html)


[The Human Genome Browser at UCSC](http://genome.cshlp.org/content/12/6/996.full)

##### SQLite Functions
既存の列から新しい列を作成する。  

- [取得データのカラムに別名を付ける(AS句) - SQLite入門](http://www.dbonline.jp/sqlite/select/index8.html)


`||`は文字列を連結する演算子。

- [ifnull関数 / coalesce関数 - SQLite関数の使い方 - SQLite入門](http://www.dbonline.jp/sqlite/function/index23.html)


全てのNULL値をNAに置き換えるには、ifnull()関数を用いる:  


Table 13-3. Common SQLite functions  
- [SQLite関数の使い方 - SQLite入門](http://www.dbonline.jp/sqlite/function/)

##### SQLite Aggregate Functions
- [count関数 - SQLite入門](http://www.dbonline.jp/sqlite/function/index1.html)  
引数にはカラム名または「\*」を指定。カラム名を指定した場合にはカラムに含まれる値の中でNULLのカラムを除いた行数を返す。「\*」を指定した場合には行数を返す。





Table 13-4. Common SQLite aggregate functions 集計関数  
- [SQLite関数の使い方 - SQLite入門](http://www.dbonline.jp/sqlite/function/)

`YYYY-MM-DD`。[xkcd: ISO 8601](http://xkcd.com/1179/)

- [重複データを除外して取得(DISTINCT) - SQLite入門](http://www.dbonline.jp/sqlite/select/index9.html)


##### Grouping rows with GROUP BY
- []()

##### Subqueries
- []()

##### Organizing Relational Databases and Joins
###### Organizing relational databases
###### Inner joins
###### Left outer joins

> ### Other Types of Outer Joins

##### Writing to Databases
- []()

##### 
- []()

##### 
- []()

#### 

## Chapter 14. Conclusion
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ch14.html#chapter-conclusion)
- [Supplementary Material on GitHub](https://github.com/vsbuffalo/bds-files/tree/master/chapter-conclusion)

## Glossary
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/glossary01.html#glossary)

## Bibliography
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/bibliography01.html#bibliography)

## Index
- [Safari Books Online](https://www.safaribooksonline.com/library/view/bioinformatics-data-skills/9781449367480/ix01.html#idp43264544)



