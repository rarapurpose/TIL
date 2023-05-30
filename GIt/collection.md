# collection
-------------

```ruby 
 <%= render partial: 'file name', collection: @hoges %> 
```

* _hoge.html.erb内において、@hogesから取り出された1つ1つの要素はhogeとして扱う

- 部分テンプレートに渡す変数名

+ 部分テンプレートでそのユーザーが投稿したプロトタイプ投稿一覧を表示する
  
```ruby
<%= render partial: 'prototypes/prototype', collection: @prototypes %
```


+ 部分テンプレートで記述する変数名
> _prototype 템플릿 

+ link_to "by プロトタイプの投稿者名", 
``` ruby 
root_path, class: :card__user %>
     <% link_to "by #{prototype.user.name}", user_path(prototype.user.id), class: :card__user %>
```  
