### Array

```ruby
# algumas formas de inicializar um array
arr = []                # => []
arr = [1, 2, 3]         # => [1, 2, 3]
arr = *(1..3)           # => [1, 2, 3]
arr = Array(1..3)       # => [1, 2, 3]
arr = Array.new         # => []
arr = Array.new(4)      # => [nil, nil, nil, nil]
arr = Array.new(4, 2)   # => [2, 2, 2, 2]
```
