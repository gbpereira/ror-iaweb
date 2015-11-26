### Classes

```ruby
# metodos de classe
class SomeClass
  def self.some_method
    puts 'class method'
  end
end

# metodos singleton
c = SomeClass.new

def c.some_method
  puts 'singleton method'
end
```

```ruby
> SomeClass.some_method

> c.some_method
```
