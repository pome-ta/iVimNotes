# ð 2022/12/31

[tani/vim-jetpack: The lightning-fast plugin manager, alternative to vim-plug](https://github.com/tani/vim-jetpack)

vim-jetpack å°å¥ãã¹ã


## `:ter` ã®è²¼ãä»ãåé¡

ä¸å¿ã®è§£æ±ºç­ã¨ãã¦ã

```
.ivish_history
```

ã¸ãï¼æçµè¡ï¼


```
curl -fLo ~/.vim/pack/jetpack/opt/vim-jetpack/plugin/jetpack.vim --create-dirs https://raw.githubusercontent.com/tani/vim-jetpack/master/plugin/jetpack.vim
```

ã¯ãã¤ã


## SSL ã®ä½ãã§è¹´ããã

[External Command: curl Â· terrychou/iVim Wiki](https://github.com/terrychou/iVim/wiki/External-Command:-curl)


[ViMãã³ã³ãã¤ã«ããããã«Pythonã¨Opensslãã³ã³ãã¤ã«ãã](https://webbigdata.jp/study/post-9654?amp=1)


## plugin ãå¥ãã

ãããããgit ã§å¤å´ç®¡çãã¦ããåé¡ã¯ãªãï¼



# ð 2022/10/11

## lua

```
:lua print(_VERSION)
```

`5.3`

```
:lua print(jit.version)
```

global ã«jit ãç¡ãçãªæãã§æãããï¼


# ð 2022/10/08

iVim ã®è²ããªãã¨ãæ¸ãã¦ãã


## `.vimrc` è¨­å®

- [GitHub - pome-ta/iVimMyPacks](https://github.com/pome-ta/iVimMyPacks) ããèª­ã¿è¾¼ã¿
- ã­ã¼ãã¼ãé¢ä¿ãç´æ¥å¥ãã¦ããããåå²ãããã


## ãªãã¸ããªä½æ

- GitHub ã§ãªãã¸ããªä½æ
- WorkingCopy ã§clone
- iVim ã«åãè¾¼ã¿

```
:iexdir add
```

## è«¸ã

- æ¥æ¬èªå¥å
  - å¤æç¢ºå®ã¾ã§ããã¬ãã¥ã¼ãããªãããé¢å
- è¡¨ç¤ºãã©ã³ãå°ãå¤§ããï¼
- iVim ã®ãã«ããæ©æ¢°ç¿»è¨³ãã¦ãããé²ããªãã¨


### Python

- `.env`
  - `venv` ä½æããã®active ãã§ããªã
  - iVim ãã«ãã¤ã³ã®Python ãæªãã®ã
  - ä½ãããã§ã©ãã«ããªãã®ã
- `objc_util`
  - i(Pad)OS ã®framework ããAPI ã®å¼ã³åºãå®é¨ãããã
  - `venv` ã§ããªãã£ãã®ã§ãç´æ¥å¿è¦ãªã¢ã¸ã¥ã¼ã«ã`pip` ã§å¥ãã¦ã
    - `pyparsing`

ã¿ã¼ããã«èµ·å

```
:terminal
```

`pip` ã§ã¤ã³ã¹ãã¼ã«

``` terminal
python3 -m pip installãpyparsing
```

