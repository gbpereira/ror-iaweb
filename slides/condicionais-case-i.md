### Condicionais

```ruby
case a
when 1
  do_something
when 2
  do_other_thing
else
  do_another_thing
end

# case com range de valores
scale = 8
case scale
when 0..5 then do_something
when 6..10 then do_other_thing
else do_another_thing
end
```
