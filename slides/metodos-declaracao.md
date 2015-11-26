### Métodos

```ruby
def some_method
  do_something
end

def some_method(var, *args)
  do_something
end

def some_method(var, opt = {})
  do_something
end

# return eh opcional, e omitido em muitos casos
def some_method
  return unless some_condition
  do_something
end
```
