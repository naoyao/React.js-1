即時関数
JSの新しい記法であるアロー関数式
ReactDOM.render()
JSXという記法(JS内にHTML的なタグを直接書いていけばOK)
第二引数は、そのUIをどこに描画するかを指定してあげる
.getElementById
.toUpperCase()

Component
- Component の内容はほとんど同じなんだけれども少しだけ変えたいという場合は Component に属性を付けてあげれば OK 。
props(=>プロパティーズ)
camelCase
backgroundColorをprops.colorにしてあげればOK
- <div style={{backgroundcolor:props.color}}>0</div>
e.preventDefault();

extends React.Component
render() <=JSXでは
props(<=場合によってはthisをつける必要がある。)
Component(<=重要)

・実は React では this.state に値がセットできるのは constructor の中だけで、それ以外の場所では setState を使わないといけないというルールになっています。
・ちなみに React では setState するたびに render() が呼ばれて、それによって新しい値で UI が再描画されるといった仕組みになっていることも覚えておきましょう。

・React では今回のように state を持つ Component は最小限にしてあげて、その他の Component には極力値を持たせないという設計が良いとされているので、それも意識しておくと良いかと思います。

indexOf
const
・「.indexOf(counter.id); 」とすると counter の id を持つデータが何番目かがわかる。
