# リスペクトクリエイト本部コーディング研修2017

## 流れ
1. masterをpullする
1. designフォルダにPSDのデザインファイルがあるのでそれを元にコーディングを行う
1. コーディングファイルはcoding/httpdocsフォルダに配置する
1. エディターは個々で好きなものを使用してよいが、Visual Studio CodeかSublime Text 3を推奨する

## 提出方法
1. 複数の人がこのリポジトリを使用するため、個々のブランチを作成する
1. ブランチ名は次のようにする**デザインフォルダ名/古川 喜士** → **new_providence/yoshito_kogawa**
1. ブランチを作成したら**そのブランチだけ**pushする

## 進め方のヒント
1. とりあえずPSDから画像を出力してimgタグを使ってブラウザで表示してみよう。何事もとりあえず一歩踏み出せば見えてくるものがあるだろう
1. PSDから画像を出力するときは画像アセット機能を使おう
1. 画像が表示できたらヘッダーを作ってみよう。他の部分は無視無視！ヘッダーだけに集中しよう
1. テキストを画像で配置するべきかどうかはよく考えよう。画像にしなくても表現できるフォントかもしれない
1. どうやればいいか全くわからない場合はまだ知識が足りてないだけ。質問して覚えよう
1. 質問するときには何をしたいのかを先に伝えよう。質問を聞いてくれるレベルの人ならそれで大抵のことは察せるよ
1. スタイルシートはデザインのルールを記述していくもの。ルールの範囲が広いとそのルールを適用したくないところにも適用されるので、スタイルシートを書くときはルールの範囲を考えよう
1. ルールの範囲はCSS Selectorで決まるよ。他人が読んでもわかりやすいルールで出来てるものが良いスタイルシートだよ
1. **わからない人がわからないなりに調べて作ったものは基本的に間違ってるよ。** **なんとなく出来た**で終わらずに**なんで出来た**のか考えよう調べよう
