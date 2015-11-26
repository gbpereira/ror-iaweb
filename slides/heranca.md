### Heranca

```ruby
class Animal
  attr_accessor :name
end

class Dog < Animal
end
```

```ruby
a = Dog.new

a.respond_to?(:name)
# => true

a.class
# => Dog

a.class.superclass
# => Animal
```
