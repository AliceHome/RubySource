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

### Operations

Adding

```
irb(main):002:0> 1+1
=> 2
irb(main):003:0> 2+3
=> 5
``` 

Subtracting

```
irb(main):004:0> 12 - 5
=> 7
irb(main):005:0> 6-7
=> -1
irb(main):006:0>
```

Multiplying

```
irb(main):006:0>  10 *2
=> 20
irb(main):007:0> 2 * 3
=> 6
```

Division VS Module

```
irb(main):008:0> 16 / 4
=> 4
irb(main):009:0> 16 % 4
=> 0
irb(main):010:0> 16 % 5
=> 1
irb(main):011:0> 15 / 4
=> 3
```

Multiplying and Dividing Float 

```
irb(main):013:0> 15.0 / 4
=> 3.75
irb(main):014:0> 1.3 * 2.75
=> 3.575
irb(main):015:0> 1.31 * 2.75
=> 3.6025
irb(main):016:0> 9.75 * 4.32
=> 42.120000000000005
```

Equality Comparison

```
irb(main):017:0> 4 == 4
=> true
irb(main):018:0> 4 == 5
=> false
```
with strings 

```
irb(main):019:0> 'foo' == 'foo'
=> true
irb(main):020:0> 'foo' == 'bar'
=> false
irb(main):021:0> '4' == 4
=> false
```

String Concatenation

```
irb(main):027:0> "one " + "two"
=> "one two"
irb(main):028:0> '1' + '1'
=> "11"
irb(main):029:0> 2 + 'string'
Traceback (most recent call last):
	3: from /usr/local/bin/irb:11:in `<main>'
	2: from (irb):29
	1: from (irb):29:in `+'
TypeError (String can't be coerced into Integer)
```
### Type Conversion

to_i(String -> Integer)

```
irb(main):030:0> '12'.to_i
=> 12
```

some fun examples to try:

```
irb(main):030:0> '12'.to_i
=> 12
irb(main):031:0> '4'.to_i
=> 4
irb(main):032:0> '4 hi there'.to_i
=> 4
irb(main):033:0> 'hi 4 there'.to_i
=> 0
irb(main):034:0> '4'.to_f
=> 4.0
irb(main):035:0> 'hi there 4'.to_f
=> 0.0
```

to_s

```
irb(main):036:0> 12.to_s + 'Hello'
=> "12Hello"
```


## II Variable

## Method 

## Flow Control

## Loops & Iterators

## Arrays

## Hashes

### MOre Stuff