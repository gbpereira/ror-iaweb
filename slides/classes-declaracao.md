### Classes

```ruby
class Box
  # attr_writer
  # attr_reader
  attr_accessor :width

  def initialize(w, h)
    @width = w
    @height = h
  end

  def height=(h)
    @height = h
  end

  def height
    @height
  end
end
```
