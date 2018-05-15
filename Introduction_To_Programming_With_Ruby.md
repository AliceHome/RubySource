## I The Basics

### String 

single quotes or double quotes

```
$irb
irb(main):001:0> 'Hello, ruby!'
=> "Hello, ruby!"
irb(main):002:0> "Hello, Ruby!"
=> "Hello, Ruby!"
```

double quotes with single quotes or single quotes with backslash or excaope 

```
irb(main):005:0> "The man said, 'Hi, everyone !'"
=> "The man said, 'Hi, everyone !'"
irb(main):006:0> 'The man said,  \'Hi, everyone !\''
=> "The man said,  'Hi, everyone !'"
```

string interpolation

```
irb(main):001:0> a='Ten'
=> "Ten"
irb(main):002:0> "my favorite number is #{a}"
=> "my favorite number is Ten"
```

### Symbols

```
irb(main):008:0> :name
=> :name
irb(main):010:0> :"surprisingly, this is also a symbol"
=> :"surprisingly, this is also a symbol"
irb(main):011:0>
```

### Numbers 

integer

```
irb(main):017:0> 12
=> 12
irb(main):018:0> 10
=> 10
```

float 

```ruby
irb(main):019:0> 12.3
=> 12.3
irb(main):020:0> 45.9
=> 45.9
```

### nil
 
Described as having "nothing" or "completely empty"

```
irb(main):021:0> puts "Hello world !"
Hello world !
=> nil
```

The *puts* method prints out a string and returns nothing, so we see *nil* being returned after the string is displayed.

check nil type by *.nil?

```
irb(main):052:0> "one".nil?
=> false
irb(main):053:0> nil.nil?
=> true
```

nil will be treated as false

```
irb(main):054:0> if nil
irb(main):055:1> puts "Hello, world!"
irb(main):056:1> end
=> nil
irb(main):057:0> if 1
irb(main):058:1> puts "one world"
irb(main):059:1> end
one world
=> nil
```

While both false end nil are both treated as negative when evaluated in an expression, they are not equivalent, as demonstrated by above.

```
irb(main):001:0> false == nil
=> false
```

## II Variable

## Method 

## Flow Control

## Loops & Iterators

## Arrays

## Hashes

### MOre Stuff