# 有害事象判定モデル
日本製薬工業協会 データサイエンス部会 2023年度のタスクフォースで作成したプログラムです。詳細は[XXXX](https://www.jpma.or.jp/information/evaluation/results/allotment/dummy.html)をご参照ください。


## 実行環境
[Colaboratory](https://colab.research.google.com/?hl=ja)のみで完結します。必要な事前準備はGoogleアカウントの取得のみです。
各ファイルを開いた後に<img src ="https://github.com/Takumi173/JPMA2022TF1-1/assets/109738801/522a6fd7-b171-4ad3-8f56-e73a718a6542">のアイコンをクリックすることでColaboratoryで開けます。

なお、プログラム間のデータの受け渡しにはGoogle Driveを使用します。

## 形態素解析器と辞書
形態素解析器は[Mecab](https://taku910.github.io/mecab/)を使用し、システム辞書に[mecab-ipadic-NEologd](https://github.com/neologd/mecab-ipadic-neologd)を、
ユーザ辞書に[万病辞書](https://sociocom.naist.jp/manbyou-dic/)を使用させていただきました。


## ライセンス
このリポジトリにあるコードは、MITライセンスの下に配布されます。
