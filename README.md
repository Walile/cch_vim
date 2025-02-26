# Another Vim Configuration
* Fork from Kaochenlong/cch

教學請見：(By 高見龍 Ediie Kao)
播放清單：https://ubin.io/vim

## 我的設定檔

設定完整功能基本上來自於Kaochenlong/cch，我這邊改成以PHP以及Python developer會使用的版本

(畫面來自於高見龍cch project)
![screenshot](/screenshots/cch.png)

### 方法一：手動安裝

先備份原本的 `.vimrc`、`.gvimrc` 以及 `.vim` 目錄，然後進行以下程序：

    $ cd ~
    $ git clone https://github.com/Walile/cch_vim.git .vim
    $ ln -s .vim/vimrc .vimrc
    $ ln -s .vim/gvimrc .gvimrc

最後開啟 Vim，並執行 `:PlugInstall` 指令安裝外掛程式。

### 方法二：快速安裝

如果你信得過我的話，你可以在終端機環境直接貼上並執行以下這段程式：

1. 使用 `curl`：

```
$ sh <(curl -L https://github.com/Walile/cch_vim/raw/master/utils/install.sh)
```

2. 使用 `wget`： 

```
$ sh <(wget --no-check-certificate https://github.com/Walile/cch_vim/raw/master/utils/install.sh -O -)
```

## 快捷鍵設定

- F2 啟動/關閉 NERDTree 視窗
- F3 啟動/關閉 Tagbar 視窗
- F5 執行程式（Ruby / JavaScript）
- Leader key = `,`

## 使用套件

### 外掛管理

- VimPlug <https://github.com/junegunn/vim-plug>

### 編輯器功能加強

- NERDTree <https://github.com/scrooloose/nerdtree>
- ctrlp <https://github.com/ctrlpvim/ctrlp.vim>
- vim-airline <https://github.com/vim-airline/vim-airline>
- vim-airline-themes <https://github.com/vim-airline/vim-airline-themes>
- surround <https://github.com/tpope/vim-surround>
- repeat <https://github.com/tpope/vim-repeat>
- vim-multiple-cursors <https://github.com/terryma/vim-multiple-cursors>

### 一般開發

- Emmet <https://github.com/mattn/emmet-vim>
- tComment <https://github.com/tomtom/tcomment_vim>
- SnipMate<https://github.com/garbas/vim-snipmate>
- vim-snippets<https://github.com/honza/vim-snippets>
- tagbar <https://github.com/majutsushi/tagbar>
- ack <https://github.com/mileszs/ack.vim>
- vim-gitgutter <https://github.com/airblade/vim-gitgutter>

### PHP/Laravel 開發

- PHP.vim <https://vimawesome.com/plugin/php-vim-shouldve-said-no>
- Vim.laravel <https://github.com/noahfrederick/vim-laravel>

### 配色

- Gruvbox <https://github.com/morhetz/gruvbox>
- Molokai <https://github.com/tomasr/molokai>
- Wombat256 <https://github.com/vim-scripts/wombat256.vim>
- Strawberry <https://github.com/nightsense/strawberry>

### 字型

- InputMonoNarrow <https://input.fontbureau.com>


有任何問請請發PR或聯絡我... by Walile @