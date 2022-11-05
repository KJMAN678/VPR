## TSP, VRP, TSPTW, 貪欲法, 2-opt

- [Python ではじめる数理最適化 出版社 HP](https://www.ohmsha.co.jp/book/9784274227356/)
- [Python ではじめる数理最適化 Amazon](https://www.amazon.co.jp/dp/B09G9VZ4PH)
- [Python ではじめる数理最適化 公式 GitHub](https://github.com/ohmsha/PyOptBook)
- [運搬経路問題（配送最適化問題，Vehicle Routing Problem) を PuLP で解く](https://qiita.com/r_nsd/items/19dcb30f5478384f90d3)
- [pigna90/PCTSPTW](https://github.com/pigna90/PCTSPTW)
- [巡回セールスマン問題(TSP)のアルゴリズムを極めた話 ](https://qiita.com/flowerrr__lily/items/6679f9496d0079fa0dd2#%E8%B2%AA%E6%AC%B2%E6%B3%95)

python 3.8.13 で確認済み

## 仮想環境の作成(Mac)

```sh
# venv環境の作成
python -m venv .venv

# venv環境のアクティベート
source .venv/bin/activate

# pip のアップグレード
python -m pip install --upgrade pip

# ライブラリのインストール
pip install -r requirements.txt

# jupyter lab の起動
jupyter lab

# jupyter lab の終了
control + c

# venv環境の終了
deactivate
```

- Windows は　`.venv\Scripts\activate.bat`でアクティベート

### ファイル構成

- 01_5 章\_1 回目.ipynb Python ではじめる数理最適化 P140~P164 のコード
- 02_appendix.ipynb Python ではじめる数理最適化に加え、各種参考サイトを改良したもの

### 特に問題ないが、pulp 実行時の IOPub data rate exceeded.対策

- [Jupyter Notebook で IOPub data rate exceeded エラー](https://yoshitaku-jp.hatenablog.com/entry/2018/12/15/164849)
