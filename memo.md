# 📝 2022/12/31

[tani/vim-jetpack: The lightning-fast plugin manager, alternative to vim-plug](https://github.com/tani/vim-jetpack)

vim-jetpack 導入テスト


## `:ter` の貼り付け問題

一応の解決策として、

```
.ivish_history
```

へ、（最終行）


```
curl -fLo ~/.vim/pack/jetpack/opt/vim-jetpack/plugin/jetpack.vim --create-dirs https://raw.githubusercontent.com/tani/vim-jetpack/master/plugin/jetpack.vim
```

はりつけ


## SSL の何かで蹴られる

[External Command: curl · terrychou/iVim Wiki](https://github.com/terrychou/iVim/wiki/External-Command:-curl)


[ViMをコンパイルするためにPythonとOpensslをコンパイルする](https://webbigdata.jp/study/post-9654?amp=1)


## plugin が入らん

そもそも、git で外側管理してたら問題はない？



# 📝 2022/10/11

## lua

```
:lua print(_VERSION)
```

`5.3`

```
:lua print(jit.version)
```

global にjit が無い的な感じで怒られた？


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
- iVim のヘルプを機械翻訳してるから進めないと


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
python3 -m pip install　pyparsing
```

