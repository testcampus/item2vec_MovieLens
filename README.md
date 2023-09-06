## 概要
* item2vecを用いた映画レコメンドアプリケーション
* データはMovieLensの映画データ（10M）（https://grouplens.org/datasets/movielens/10m/）
* 推薦アルゴリズムはitem2vecを使用
* `item2vec_MovieLens.ipynb`で学習したモデルを利用
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
https://item2vec-movielens.streamlit.app/
