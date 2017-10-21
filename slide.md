## 最近の Vim 事情と
## おもしろプラグインの紹介

[第33回【フリースタイル】PORTもくもく会【学生歓迎！】](https://freestyle-mokumoku.connpass.com/event/68385/)  
([@pink_bangbi](https://twitter.com/pink_bangbi))  
2017/10/21

---

# 自己紹介
- - -

* なまえ  : おしょー
* Twitter : [@pink_bangbi](https://twitter.com/pink_bangbi)
* github  : [osyo-manga](https://github.com/osyo-manga)
* ブログ  : [Secret Garden(Instrumental)](http://secret-garden.hatenablog.com)
* 言語    : C++ / Ruby

---

# Vim 力

* Vim 戦闘力：2700 ぐらい
  * Vim 戦闘力とは空白行とコメントを除いた vimrc の行数
  * 空白行とコメントを含めると 8000行ぐらい…？
* 自作プラグイン数：150個ぐらい（github 調べ）

---

# 今回話す内容

---

## 今回話す内容
- - -

* Vim の紹介
* 最近の Vim 事情と
* おもしろプラグインの紹介

---

# Vim とは

---

# すごいテキストエディタ！

---

# Vim の特徴

---

## Vim の特徴
- - -

* モード切り替え
  * ノーマルモード
  * インサートモード
* 様々な言語やファイル形式対応
* いろんな環境に移植されている
* 拡張性が高い
  * 様々なプラグインがある
* コミュニティが活発
  * [vim-jp](http://vim-jp.org/)

---

# Vim でできること

---

## Vim でできること
- - -
* コード補完
* 静的コードチェック
* ファイラ
* shell
* Twitter
* プラグイン次第でいろいろ

---

# 最近の Vim 事情

---

## Vim 8.0 がリリース
- - -
2016年9月に 7.4 から約3年ぶりに最新版である 8.0 がリリースされた  

---

## Vim 8.0 の主な追加機能
- - -
* 非同期IOの実装
* タイマーの追加
* インデントを付けて折り返し
* Vim script の強化
* etc...

---

# 最新の Vim(8.0.1207)
2017/10/21 現在

---

# :terminal が
# 実装された！！

---

## :terminal とは
- - -
その名の通り Vim で端末を実行するための機能  
Vim 上でシェルが起動して、操作することができる
:terminal を試したい方は Vim を最新版にアップデートする必要がある

---

# Vim はじまったな

---

# おもしろプラグインの紹介

実際に Vim 上で試してみます  
細かい設定や説明は省くので感じてください  

---

## 任意の単語へジャンプ
## ([vim-easymotion](https://github.com/easymotion/vim-easymotion))

---

## コードの実行
## ([quickrun.vim](https://github.com/thinca/vim-quickrun))

```vim
:QuickRun
```

---

## オンラインでコードの実行
## ([wandbox-vim](https://github.com/rhysd/wandbox-vim))

```vim
:Wandbox
```

---

## 検索数を表示
## ([anzu.vim](https://github.com/osyo-manga/vim-anzu))

---

## 置換をビジュアル化
## ([over.vim](https://github.com/osyo-manga/vim-over))

```vim
:OverCommandLine
```

---

## バッファラインの絞り込み
## ([hopping.vim](https://github.com/osyo-manga/vim-hopping))

```vim
:HoppingStart
```

---

## gyazo へポスト
## ([gyazo.vim](https://github.com/osyo-manga/vim-gyazo))

```vim
:GyazoOpenBrowserCurrentWindow
```

---

## にゃんきゃっと
## ([nyaaancat.vim](https://github.com/osyo-manga/vim-nyaaancat))

```vim
:NyaancatStarta tabnew
```

---

## [Vim のオンラインヘルプ](http://vim-help-jp.herokuapp.com/#)

---

# まとめ

---

## まとめ
- - -

* Vim は開発やコミュニティが活発である
* 最新の Vim では端末機能が実装された
* 面白いプラグインがたくさんある

---

## ご清聴
## ありがとうございました

