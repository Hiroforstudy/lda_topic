# lda_topic.ipynb の使い方(Mac)
homebrewをinstallしている前提での説明と実行するコマンド

環境作成\n
conda create --name myenv python=3.10

仮想環境のアクティベイト

conda activate myenv

ジュビターラボをインストール

conda install jupyterlab

ジュピターラボを起動

jupyter lab

インストールするべきパッケージ

conda install numpy scipy scikit-learn matplotlib h5py pillow tensorflow -y

pipでインストールするパッケージ一覧

pip install pyLDAvis

pip install nltk

pip install mecab-python3

必要があれば
pip install pyparsing
