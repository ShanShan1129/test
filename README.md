# test
テスト用
### 画像やpdfファイルの追加
画像やpdfファイルなどは権限の都合上、ちょっと手順が異なることを教える  
また一度プルリクをやってくれたシャンカーの場合、最初にやることがちょっとあるので、  
この章をさっくり読みつつ[こちらも読んでおいてくれ(^^)](#2回目以降のプルリク協力シャン向け)  

#### ①リポジトリのフォーク
まずは追加にあたってリポジトリのフォークという手順を行う必要がある  
このリポジトリをコピーするような物だ、気軽にやるぞ　来い  
ページの右上にあるforkを押してくれ(^^)  
|![](doc/fork1.jpeg "フォーク・皇")|
| ----- |

そうするとforkする際の名前の設定などのページが出てくる  
ここは特に何も変更せずにCreate forkでいいよ～  
|![](doc/fork2.jpeg "別のリポジトリなのでスクショとったあと普通にキャンセルした")|
| ----- |
注：アカウントの都合上、ここでは別のリポジトリ(BCdice)のfork画面を使っていることを教える
　　実際はRepository nameやらDescriptionやらが違うけど気にしないでくれ(^^)


このような画面になれば成功だな　ルフィ  
実際には上のShanShan1129となっている部分は、自分で決めたユーザ名になっているはずだ
|![](doc/fork3.jpeg "この文章作ったやつバレバレ")|
| ----- |

#### ②ブランチ作成
次はブランチというものを作る  
ブランチ切替のボタンを押して①、下の`Find or ...`のところにpatch-1と入力してくれ②  
そうしたらcreate branchという表示が出るのでそれをクリックする　来い③  
|![](doc/fork4.jpeg "全角なのはアカウントの都合上うんぬん")|
| ----- |
(注：この時create branchが出なかった場合、もうそのブランチは作成済みってこと　番号を2やら3にずらすことを…勧める…)  

上にBranch created. と表示されてたらブランチ作成完了だァ～～～！！！  
ということで、ここからファイルの追加を行っていくことを教える

#### ③各種ファイルのアップロードとコミット
ここから念願のファイルの追加作業が始まることを教える  
今回はアイコン画像の追加をするぞ　来い　pdfファイル等も同じ手順でできるので適宜合わせてくれ(^^)  
ということでアイコンフォルダを開いて…  
実はこの画面、ファイルをドラッグアンドドロップ(以下D&D)することができるぞォ！  
複数まとめてでも大丈夫　githubのインターフェースは格が違う  
|![](doc/upload1.jpeg "ちょっと待てナルトスTRPGってなんだよ…")|
| ----- |

そして今回アップロードする画像をD&Dすると下のような画面になる  
今回は例としてヨガシャン.jpgをアップロードした  
こんな感じに追加したいファイルがアップロードされたことを確認してくれ(^^)  
|![](doc/upload2.jpeg "ア～ラ～")|
| ----- |
注：失敗する場合ファイル名に問題があることが多い　全角スペースとかは御法度だなァ…

確認ができたらCommit changesを押すぞォ！  
|![](doc/upload2.1.jpeg "")|
| ----- |

処理が終わるとブランチのトップに戻されて、
差分ができたからプルリクしてくれ(^^)ってメッセージが新たに表示されることを教える  
なので早速プルリクだァ～～～！！！  
|![](doc/upload3.jpeg "プルリクのタイトルコメントは詳しく書くとありがたいってチョッパーが言ってたぞ")|
| ----- |

ここから先は上の方にあったプルリクのタイトルやコメントの記載と同じなので省略・皇  

### 2回目以降のプルリク協力シャン向け
<details>
<summary>2回目以降やらないといけないこと</summary>

ここでは2回目以降プルリクを行った場合に確認しなければならない"masterブランチの同期"をお前に教える  
#### masterブランチの同期
まずは自分のforkしたリポジトリに移動するぞ　来い  
ページの右上にあるforkを押してくれ(^^)  
|![](doc/fork1.jpeg "画像使いまわし・皇")|
| ----- |

そうした場合このような画面になるはずだ  
要は一度つくったからそれ以上はいらねェよなァ？って画面だな  
気にすることなく赤枠のリンクを押してくれ(^^)  
|![](doc/marge1.jpeg "画像使いまわし・皇")|
| ----- |

そうすればforkした自分のリポジトリを開けるぞォ！
そしてここでブランチの同期を確認するぞ　来い
Fetch upstream①を押した後Fetch and merge②のボタンが濃かったら同期してくれ(^^)のサインだ  
そのまま押してくれ  
そして上に`Successfully fetched...`と表示されれば宴だァ～～～！！！  
この後は[②ブランチ作成](#②ブランチ作成)に従ってファイルを追加、プルリクしてくれ(^^)
</details>
