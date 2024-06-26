東京大学 数理・情報教育研究センターの[Pythonプログラミング入門](https://github.com/UTokyo-IPP/utokyo-ipp.github.io/tree/master)を使わせていただきます。

「入門」にあるipynbファイルをVisual Studio Codeで実行することを目指します。

[ライセンス](https://github.com/UTokyo-IPP/utokyo-ipp.github.io/tree/master?tab=License-1-ov-file#readme)には注意してください。（「表示」「非営利」「改変禁止」「継承」において再配布可能なライセンスです。[こちら](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.ja)を参照。）

<details><summary><b>本リポジトリはそのままでは使えません。クリックして実行方法を参照してください。</b></summary>

# Visual Studio Codeでの実行方法

まず、Visual Studio Codeには、「Python」（Microsoft）と「Jupyter」（Microsoft）のプラグインを入れてください。

本リポジトリのzipをダウンロードして、展開してください（フォルダXとします）。<br>
![2024-05-08_200324.jpg](./img/2024-05-08_200324.jpg)<br>
図1

「.vscode」フォルダの「settings.json」を開き、python.exeがある正しいパスに修正してください。

[Pythonプログラミング入門](https://github.com/UTokyo-IPP/utokyo-ipp.github.io/tree/master)にアクセスし、図1と同様にzipをダウンロードして、展開してください。

「colab」フォルダをフォルダXにコピーしてください。

Visual Studio Codeを起動し、フォルダXを開いてください。

ReadMe.mdを開きます。<br>
タブの右クリックでプレビューを開いてください。<br>
![2024-05-08_185809.jpg](./img/2024-05-08_185809.jpg)

以下のリンクをクリックしてください。<br>
![2024-05-08_234655.jpg](./img/2024-05-08_234655.jpg)

![2024-05-08_190150.jpg](./img/2024-05-08_190150.jpg)<br>
 [カーネルの選択]をクリック ⇒ Pythonの環境 ⇒ 上記python.exeのパスが正しければ、おすすめに表示されるので選択してください

Jupyter Notebookで表示されると思います。Pythonを実行することも可能です。<br>
![2024-05-08_192146.jpg](./img/2024-05-08_192146.jpg)

</details>

# 学習の順番

まずはレベル1を勉強しましょう。

❆<br>
学習の順番をオリジナルと変えています。<br>
また、難解なものは省略しています。<br>
省略したものは、以下を一通り学習してから勉強してみてください。

# レベル1

1. [数値演算](./colab/1/1-1.ipynb)
1. [変数と関数（その1）](./colab/1/1-2.ipynb)
1. [モジュールの使い方](./colab/5/5-1.ipynb)
    * 最初のセルは実行しないこと。
1. [文字列 (string)](./colab/2/2-1.ipynb)
1. [論理・比較演算と条件分岐（その1）](./colab/1/1-3.ipynb)
1. [条件分岐（その2）](./colab/2/2-3.ipynb)
1. [リスト (list)](./colab/2/2-2.ipynb)
    * 「for文による繰り返しとリスト・タプル」以降は下の「繰返し」が終わってから勉強してください。
1. [繰り返し](./colab/3/3-2.ipynb)
1. [関数（その2）](./colab/3/3-3.ipynb)
1. [クラス](./colab/6/6-3.ipynb)
1. [Pythonスクリプトとコマンドライン実行](./colab/appendix/5-command.ipynb)
    * 最初のセルは実行しないこと。<br>![2024-05-08_194805.jpg](./img/2024-05-08_194805.jpg)

# レベル2

12. [辞書 (dictionary)](./colab/3/3-1.ipynb)
1. [ファイル入出力の基本](./colab/4/4-1.ipynb)
    * 最初のセルは実行しないこと。
1. [CSVファイルの入出力](./colab/appendix/4-csv.ipynb)
    * 最初のセルは実行しないこと。
1. [正規表現](./colab/appendix/5-re.ipynb)
    * 最初のセルは実行しないこと。

# レベル3

16. [NumPyライブラリ](./colab/5/5-3.ipynb)
    * 最初のセルは実行しないこと。
1. [pandasライブラリ](./colab/7/7-1.ipynb)
    * 最初のセルは実行しないこと。
1. [Matplotlibライブラリ](./colab/appendix/5-matplotlib.ipynb)
    * 最初のセルは実行しないこと。

