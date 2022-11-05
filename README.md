- [Python ではじめる数理最適化 出版社 HP](https://www.ohmsha.co.jp/book/9784274227356/)
- [Python ではじめる数理最適化 Amazon](https://www.amazon.co.jp/dp/B09G9VZ4PH)
- [Python ではじめる数理最適化 公式 GitHub](https://github.com/ohmsha/PyOptBook)

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
```

### 特に問題ないが、pulp 実行時の IOPub data rate exceeded.対策

- [Jupyter Notebook で IOPub data rate exceeded エラー](https://yoshitaku-jp.hatenablog.com/entry/2018/12/15/164849)
