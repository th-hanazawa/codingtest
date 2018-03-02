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
1. とりあえずPSDから画像を出力してimgタグを使ってブラウザで表示してみよう。何事もとりあえず一歩踏み出せば見えてくるものがあるよ
1. PSDから画像を出力するときは画像アセット機能を使おう
1. 画像やスタイルシートなどHTMLから呼び出すアセットは配置するディレクトリとファイル名が重要だよ
1. その**ファイルを見てどこでどういう使い方がされているか想像できると良い**よ
1. ↑と同じことがCSSのクラス名、ID名、JavaScriptの変数名、関数名にも言えるよ。名前って大事だよ
1. 画像が表示できたらヘッダーを作ってみよう。他の部分は無視無視！ヘッダーだけに集中しよう
1. テキストを画像で配置するべきかどうかはよく考えよう。画像にしなくても表現できるフォントかもしれない
1. どうやればいいか全くわからない場合はまだ知識が足りてないだけだよ。質問して覚えよう
1. 質問するときには何をしたいのかを先に伝えよう。質問を聞いてくれるレベルの人ならそれで大抵のことは察せるよ
1. スタイルシートはデザインのルールを記述していくものだよ。ルールの範囲が広いとそのルールを適用したくないところにも適用されるよ。だからスタイルシートを書くときはルールの範囲を考えるんだよ
1. ルールの範囲は**CSS Selector**で決まるよ。他人が読んでもわかりやすいルールで出来てるものが良いスタイルシートだよ
1. レイアウトの基本は**Flexbox**だよ。でも**float**のことも忘れないでね
1. **ボックスモデル**を覚えて、記述したHTMLがどういう領域を持ってるのか想像できるようになろう
1. **marginとpaddingは似てるけど違う**よ。使い分けを考えて使おう

1. **わからない人がわからないなりに調べて作ったものは基本的に間違ってるよ。** **なんとなく出来た**で終わらずに**なんで出来た**のか考えよう調べよう
1. ↑をフォローするのがコードレビューだよ
