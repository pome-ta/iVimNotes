# 📝 2022/10/08

iVim の色々なことを書いていく


## `.vimrc` 設定

- [GitHub - pome-ta/iVimMyPacks](https://github.com/pome-ta/iVimMyPacks) より読み込み
- キーボード関係を直接入れてるから、分割させたい


## リポジトリ作成

- GitHub でリポジトリ作成
- WorkingCopy でclone
- iVim に取り込み

```
:iexdir add
```

## 諸々

- 日本語入力
  - 変換確定まで、プレビューされないから面倒
- 表示フォント少し大きい？

### Python

- `.env`
  - `venv` 作成からのactive ができない
  - iVim ビルドインのPython が悪いのか
  - 何かしらでどうにかなるのか
- `objc_util`
  - i(Pad)OS のframework やらAPI の呼び出し実験をしたい
  - `venv` できなかったので、直接必要なモジュールを`pip` で入れてる
    - `pyparsing`

ターミナル起動

```
:terminal
```

`pip` でインストール

``` terminal
python3 -m pip install
```


