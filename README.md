# test
テスト用
### 画像やpdfファイルの追加
画像やpdfファイルなどは権限の都合上、ちょっと手順が異なることを教える  
(注：実はテキストファイルもこの手順で行えますがまあいいでしょう)  

#### ①リポジトリのフォーク
まずはページの右上にあるforkを押してくれ(^^)  
![](doc/fork1.jpeg)  

そうするとforkする際の名前の設定などのページが出てくる  
ここは特に何も変更せずにCreate forkでいいよ～  
![](doc/pict1.png)  
(注：アカウントの都合上、ここでは別のリポジトリ(BCdice)のfork画面を使っていることを教える  
 実際はRepository nameやらDescriptionやらが違うけど気にしないでくれ(^^))  

このような画面になれば成功だな　ルフィ  
実際には上のShanShan1129となっている部分は、自分で決めたユーザ名になっているはずだ
![](doc/pict1.png)  

#### ②ブランチ作成
次はブランチというものを作る  
ブランチ切替のボタンを押して①、下の`Find or ...`のところにpatch-1と入力してくれ②  
そうしたらcreate branchという表示が出るのでそれをクリックする　来い③  
![](doc/pict1.png)  
(注：この時create branchが出なかった場合、もうそのブランチは作成済みってこと 番号を2やら3にずらすことを…勧める…)  

上にBranch created. と表示されてたらブランチ作成完了だァ～～～！！！  
ということで、ここからファイルの追加を行っていくことを教える

#### ③各種ファイルのアップロードとコミット
ここから念願のファイルの追加作業が始まることを教える  
今回はアイコン画像の追加をするぞ　来い　pdfファイル等も同じ手順でできるので適宜合わせてくれ(^^)  
ということでアイコンフォルダを開いて…  
実はこの画面、ファイルをドラッグアンドドロップ(以下D&D)することができるぞォ！  
複数まとめてでも大丈夫　githubのインターフェースは格が違う  
![](doc/pict1.png)  

そして今回アップロードする画像をD&Dするとこのような画面になる  
今回は例としてヨガシャン.jpgをアップロードした  
こんな感じに追加したいファイルがアップロードされたことを確認してくれ(^^)  
![](doc/pict1.png)  

確認ができたらCommit changesを押すぞォ！  
![](doc/pict1.png)  

処理が終わるとブランチのトップに戻されて、
差分ができたからプルリクしてくれ(^^)ってメッセージが新たに表示されることを教える  
なので早速プルリクだァ～～～！！！  
![](doc/pict1.png)  
ここから先は上の方にあったプルリクのタイトルやコメントの記載と同じなので省略・皇  
