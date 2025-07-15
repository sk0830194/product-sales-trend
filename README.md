# 商品売り上げ推移分析 
 
本プロジェクトでは、架空の販売データを用いて、商品ごとの売り上げ推移を分析しました。 
 
## ?? ディレクトリ構成 
 
product-sales-trend/ 
├── data/              # データ格納フォルダ 
│   ├── item_master.csv 
│   ├── customer_master.csv 
│   ├── transaction.csv 
│   └── transaction_detail.csv 
├── notebook/ 
│   └── 商品売り上げ推移.ipynb 
├── README.md 
└── .gitignore 
 
## ?? 使用技術 
- Python 3.x 
- pandas 
- matplotlib 
 
## ?? 分析内容 
- 商品ごとの売上金額（月別） 
- 複数商品を折れ線グラフで可視化 
 
## ?? 実行方法 
1. Jupyter Notebook で `notebook/商品売り上げ推移.ipynb` を開く 
2. データが `data/` フォルダにあることを確認する 
3. セルを順に実行して可視化結果を確認する 
 
## ?? 補足 
このプロジェクトは「Python 100本ノック（pandas編）」の内容をベースに構築しています。 
