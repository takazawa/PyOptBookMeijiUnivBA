
書籍「Pythonではじめる数理最適化」のサンプルコードにGoogle Colaboratoryでそのまま動くノートブックを追加

以下元リポジトリのREADME

---

# Pythonではじめる数理最適化 <br/>〜ケーススタディでモデリングのスキルを身につけよう〜

<p align="center"><a href="https://www.ohmsha.co.jp/book/9784274227356/"><img width="40%" src="https://www.ohmsha.co.jp/Portals/0/book/small/978-4-274-22735-6.jpg" /></a></p>

「[Pythonではじめる数理最適化 ケーススタディでモデリングのスキルを身につけよう](https://www.ohmsha.co.jp/book/9784274227356/)（オーム社）」のサポートページです。
プログラムの解説は、本書籍を参照してください。

[正誤表はこちら](正誤表.md)


## 本書について

> **Pythonで実務に使える数理最適化のスキルを身につけよう！**
>   
> 本書は、Pythonを用いた数理最適化の入門書です。Pythonを使ってさまざまな課題を実際に解いてみることで、数理モデルを実務で使いこなす力を身につけます。  
> この本の特徴は、数理最適化のアルゴリズム自体ではなく、数理最適化を用いた課題解決に重きを置いている点です。ビジネスなどにおける課題を数理最適化で解く際に現場で発生しうる試行錯誤が多分に盛り込まれており、実務における手順や気をつけるべきポイントを学習することができます。  
>
> **この本の構成**  
> 本書は二部構成です。  
> 第I部はチュートリアルです。中学校で習う連立一次方程式や高校で習う線形計画法を題材として、数理最適化の基礎的な考え方とPythonによる初歩的な実装を学びます。シンプルな課題設定なので、数学的な難しさを感じることなくPythonに集中して基礎を学習することができます。
> 
> 第II部はケーススタディです。  
> 実際に社会で起こりうる、さまざまな課題を数理最適化によって解いていきます。
学校のクラス編成やサークル活動における学生の乗車グループ分けなどの学生にとっても身近な課題や、キャンペーンの効果最大化や効率のよい配送計画の立案などのビジネスにおいてたびたびぶつかる課題などを解いていくことで、手順や注意点、効率のよい方法などが学べます。
> 
> このような方におすすめ  
> ◎ 数理最適化の実務応用について知りたい方  
> ◎ 施策の効果最大化や効率化に取り組むビジネスマン（エンジニア・マーケター・リサーチャーなど）  
> ◎ 情報・経済・経営系などの学部や学科の学生  
> ◎ データサイエンティストを志す方


## 利用上の注意

- 本書に掲載されている情報は、2021年9月現在のものです。
- ライブラリのバージョンアップなどによって動作しなくなることがありますのでご注意ください。
  - 第7章で利用するライブラリCVXOPTのインストールがM1チップ搭載Macにて特別な方法でインストールが必要との報告を受けています( [#16](https://github.com/ohmsha/PyOptBook/issues/16) )。

## 正誤表

[こちらのリンク（正誤表）](正誤表.md)をご覧ください。  
書籍の誤植を発見された方はIssueを登録して頂けますと幸いです > [こちらから登録できます](https://github.com/ohmsha/PyOptBook/issues/new)


## 本書で用いた実行環境の情報

|　分類 | パッケージ名など | バージョン |
| ---- | ---- | ---- |
| プログラミング言語 | Python3 | 3.7, 3.8 |
| 対話型実行環境 | jupyter | 1.0.0 |
| 対話型実行環境 | ipython | 7.22.0 |
| 対話型実行環境 | notebook | 6.3.0 |
| データ処理 | pandas | 1.2.4 |
| 数理最適化 | cvxopt | 1.2.6 |
| 数理最適化 | pulp | 2.4 |
| 並列処理 | joblib | 0.14.1 |
| データ可視化 | matplotlib | 3.3.4 |
| データ可視化 | seaborn | 0.11.1 |
| 科学技術計算 | numpy | 1.20.1 |
| WEBアプリケーションフレームワーク | flask | 2.0.1 |
| HTMLの処理 | lxml | 4.6.3 |
| HTTPリクエスト | requests | 2.25.1 |


## 著者

- [岩永 二郎](https://erdos-the-book.com/index.php/iwanaga-jiro/)（株式会社エルデシュ）
- 石原 響太（ALGORITHMIC NITROUS 株式会社）
- 西村 直樹（株式会社リクルート）
- 田中 一樹（株式会社ディー・エヌ・エー）
