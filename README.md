### TODO

## 実装に入る前に
  - [ ] 使用関数の理解
  - [ ] 実装項目の理解
  - [ ] 実装項目の振り分け

## 基本機能
- [ ] プロンプトの表示 **高優先度**
  - [ ] 新しいコマンドを待つ際にプロンプトを表示する機能を実装
- [ ] 実行可能ファイルの検索と起動 **高優先度**
  - [ ] PATH変数を使用して適切な実行ファイルを検索する
  - [ ] 相対パスまたは絶対パスを用いた実行ファイルの起動を実装

## 履歴とクォート
- [ ] コマンド履歴機能 **中優先度**
  - [ ] 入力された各コマンドを履歴に保存する
- [ ] シングルクォートとダブルクォートの処理 **高優先度**
  - [ ] シングルクォートで囲まれた範囲ではメタ文字を解釈しないようにする
  - [ ] ダブルクォートで囲まれた範囲では$以外のメタ文字を解釈しないようにする

## リダイレクションとパイプ
- [ ] 入力リダイレクション `<` の実装 **中優先度**
  - [ ] `<` 演算子を使用して入力リダイレクションを処理する
- [ ] 出力リダイレクション `>` と `>>` の実装 **中優先度**
  - [ ] `>` で通常の出力リダイレクションを実装
  - [ ] `>>` で追記モードの出力リダイレクションを実装
- [ ] パイプ `|` の実装 **高優先度**
  - [ ] コマンド間でパイプを使ってデータを渡す機能を実装

## 環境変数とステータス
- [ ] 環境変数の展開 `$` **高優先度**
  - [ ] `$` に続く文字列を環境変数の値に展開する
- [ ] 最後のコマンドの終了ステータス `$?` の展開 **中優先度**
  - [ ] 直前の前景プロセスの終了ステータスを `$?` で取得できるようにする

## シグナルハンドリング
- [ ] Ctrl-C, Ctrl-D, Ctrl-\ の挙動の実装 **高優先度**
  - [ ] Ctrl-Cを押したときに新しいプロンプトを表示
  - [ ] Ctrl-Dでシェルを終了
  - [ ] Ctrl-\ で何もしない

## ビルトインコマンド
- [ ] `echo` コマンドの `-n` オプションを持つ実装 **低優先度**
- [ ] `cd` コマンドの実装（相対パスまたは絶対パスのみ） **中優先度**
- [ ] `pwd` コマンドの実装（オプションなし） **低優先度**
- [ ] `export` コマンドの実装（オプションなし） **中優先度**
- [ ] `unset` コマンドの実装（オプションなし） **中優先度**
- [ ] `env` コマンドの実装（オプション・引数なし） **低優先度**
- [ ] `exit` コマンドの実装（オプションなし） **低優先度**

### コータ
  - [ ] 
  - [ ]
### ゆーし
  - [ ] 
  - [ ]


## 参考資料
[Minishellの作り方](https://usatie.notion.site/minishell-29921d3ea13447ad897349acd5733d5e#155a4af10cb9420797b53f5d1ad1209f)

[minishell v2 GitHubリポジトリ](https://github.com/usatie/minishell_v2/commits/livecoding)

[課題PDF](https://cdn.intra.42.fr/pdf/pdf/123812/en.subject.pdf)

TLPIやAPUE

# Playground

使用関数の実験

