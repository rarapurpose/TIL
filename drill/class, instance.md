```ruby
class Article

  def initialize(author, title, content)
    @author = author
    @title = title
    @content = content
  end

  def author
    @author
  end

  def title
    @title
  end

  def content
    @content
  end

end

article = Article.new("阿部", "Rubyの素晴らしさについて", "Awesome Ruby!")
puts "著者: #{article.author}"
puts "タイトル: #{article.title}"
puts "本文: #{article.content}"

```
+ Article.newでインスタンスを生成し、変数articleに代入。その際に、`阿部`、`Rubyの素晴らしさについて`、`Awesome Ruby!`の3つ実引数を指定。   

+ initializeメソッドを定義して、インスタンス変数を宣言。実引数として指定した値を、仮引数の`author`、 `title`、`content`にそれぞれ渡し.   

+ initializeメソッドで宣言されたインスタンス変数に、`阿部`、`Rubyの素晴らしさについて`、`Awesome Ruby!`という3つの値が代入。   

+ 上記インスタンス変数の値を返すための専用のメソッドをそれぞれ定義。   

