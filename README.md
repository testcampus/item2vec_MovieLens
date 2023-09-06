## 概要
* item2vecを用いた映画レコメンドアプリケーション
* データはMovieLensの映画データ（10M）（[https://grouplens.org/datasets/movielens/10m/]）
* 推薦アルゴリズムはitem2vecを使用
* （[こちら](https://github.com/oreilly-japan/RecommenderSystems/blob/main/chapter5/colab/Item2vec.ipynb)で学習したモデルを利用
* モデルは`data/item2vec.model`に格納
* Streamlit Cloudにて公開

## インストール
ライブラリをインストール
```
pip install pandas numpy streamlit gensim
```
または、requirements.txtを用いてインストール
```
pip install -r requirements.txt
```

## アプリの起動
```
streamlit run app.py
```

## Streamlit Cloudにて公開
[https://movierecommender-ks5bdb5bjsvusrhyakaogb.streamlit.app/]
