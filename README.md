# Elixir Enum.each and throw: Unexpected Behavior

This repository demonstrates a potential issue when using `Enum.each` with `throw` in Elixir. The provided code shows how `throw` inside `Enum.each` immediately terminates the loop without executing the rest of the function.  This can lead to incomplete processing or unexpected results if not handled correctly.