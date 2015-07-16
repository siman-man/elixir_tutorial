# 文字列操作周り色々

普通に出力してみる

```elixir
IO.puts "Hello Elixir"
```

文字の長さを調べる

```elixir
IO.puts String.length("Hello")      #=> 5
IO.puts String.length("あいうえお") #=> 5
```

変数宣言

```elixir
str = "abc"
IO.puts str #=> abc
```

型は必要なし
