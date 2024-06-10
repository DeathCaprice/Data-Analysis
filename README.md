☆pythonでのデータ分析の実装

◎kaggleの『銀行解約データセットを使用した二項分類』の分析プロセス

1.ベースライン作成
実装ファイル名：ベースライン.ipynb・・・データの確認（レコード数、カラム数、種類(カテゴリか数値か)の確認、データセット作成（目的変数、説明変数の作成）、
バリデーション設計（ホールドアウト検証、クロスバリデーション）、モデル学習(Light GBM)、モデル推論（推論用データセット作成、学習済みモデルを用いて予測値算出、提出用ファイル作成）


2.特徴量エンジニアリング
実装ファイル名：特徴量エンジニアリング(lightGBM).ipynb・・・データセット作成（目的変数、説明変数の作成)、モデル学習(Light GBM)、データの前処理、
特徴量作成(特徴量エンジニアリング)、データセット作成（特徴量追加）、特徴量追加後のモデル学習(Light GBM)、モデル推論（推論用データセット作成、推論用モデル学習(Light GBM)、
学習済みモデルを用いて予測値算出、提出用ファイル作成)

3.モデルチューニング
実装ファイル名：モデルチューニングoptuna.ipynb
実装ファイル名：モデルチューニングscikitlearn.ipynb
実装ファイル名：モデルチューニングニューラルネットワーク.ipynb

4.アンサンブル
Ensemble.ipynb (英語)



