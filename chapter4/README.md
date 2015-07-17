# 関数

Elixirでは関数だけの定義が出来ないので、モジュールの中に関数を定義する

```elixir
defmodule MyModule do
  def hello do
    IO.puts "Hello Elixir"
  end
end

MyModule.hello #=> "Hello Elixir"
```

