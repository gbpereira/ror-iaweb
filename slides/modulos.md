### Módulos

```ruby
module SomeModule
  def SomeModule.some_method
    puts 'some method'
  end

  def some_method
    puts 'other method'
  end
end

class SomeClass
  include SomeModule
end
```

```ruby
> SomeModule.some_method
# => some method

> c = SomeClass.new
> c.some_method
# => other method
```
