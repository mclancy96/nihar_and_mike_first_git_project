# My 4 Favorite Ruby Methods

### ```.each```
Iterates over each element in a collection (like an array or hash).
```ruby
[1, 2, 3].each do |num|
  puts num
end
```
### ```.map```
Transforms each element in a collection and returns a new arraay.
```ruby
[1, 2, 3].map { |num| num * 2 }
```
### ```.select```
Returns a new array containting only the elements that match a given condition.
```ruby
[1, 2, 3, 4].select { |num| num.even? }
```
### ```.include?```
Checks if a collection includes a certain elements
```ruby
[1, 2, 3].include?(2)
```
