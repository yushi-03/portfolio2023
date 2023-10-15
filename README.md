# portfolio2023　概要
2023年度就活の際のポートフォリオとして作成したレポジトリです。
今回の制作物として、kaggleのcompetitionの一つである'Predict Health Outcomes of Horses'に関して作成した予測モデルとと探索的解析について、'MLHorse'ブランチ内の'ML_Horses/Horse_Health.ipynb'にコードを記載しています。<br>
(kaggle説明ページ： https://www.kaggle.com/competitions/playground-series-s3e22/overview)<br>
(ipynbファイルリンク：https://github.com/yushi-03/portfolio2023/blob/MLHorse/ML_Horses/Horse_Health.ipynb)<br>

前半部においては、教師データ・テストデータの分布と、各特徴量と目的変数である'outcome'との相関を確認して特徴量エンジニアリングを行い、後半部でxgboost, lightgbm, catboostの３つのライブラリを用いたモデルと、そのアンサンブルの合計４種類の予測モデルで'outcome'の結果を予測しています。
