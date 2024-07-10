# azureml-in-a-day-jp
本リポジトリでは、Azure Machine Learning (Azure ML)を使用してモデルをトレーニングし、その後予測にモデルを使用するチュートリアルを提供します。このチュートリアルでは、Azure MLの基本概念とその一般的な使用方法に慣れることが目的です。

## 提供コンテンツ
1. [azureml-in-a-day](azureml-in-a-day):
    - ユーザのスクリプトを実行するために必要なジョブ環境（Dockerイメージ）を設定します。
    - ユーザの任意のトレーニングスクリプトを準備し、そのトレーニングスクリプトとジョブ環境を使用して、Azure ML 上でモデルのトレーニングを実行します。
    - その後モデルをAzure ML のアセットとして登録し、エンドポイントとしてデプロイし、推論で使用します。
1. [train-hyperparameter-tune-deploy-with-pytorch](train-hyperparameter-tune-deploy-with-pytorch):
    - Azure Machine Learning でディープラーニングのフレームワークの利用方法を学びます。
    - ここでは、PyTorchモデルのトレーニング、ハイパーパラメータチューニング、およびデプロイを行います。