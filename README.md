# Test gitbook-plugin-prism

## text
~~~
let initialBits: UInt8 = 0b00001111
let invertedBits = ~initialBits // 等于 0b11110000
~~~

## sh
~~~sh
-o, --output <directory>  输出文件件, 默认为 ./_book
-f, --format <name>       产生的书籍的类型, 默认为静态站点, 可用的格式为: site, page, ebook, json
--config <config file>    配置文件, 默认为 book.js 或 book.json
~~~

## Swift
~~~swift
let individualScores = [75, 43, 103, 87, 12]
var teamScore = 0
for score in individualScores {
    if score > 50 {
        teamScore += 3
    } else {
        teamScore += 1
    }
}
print(teamScore)

extension String {
    var banana : String {
    	let shortName = String(characters.dropFirst(1))
    	return "\(self) \(self) Bo B\(shortName) Banana Fana Fo F\(shortName)"
	}
}

let bananaName = "Jimmy".banana		// "Jimmy Jimmy Bo Bimmy Banana Fana Fo Fimmy"
~~~


## Python
~~~python
import os

class Test(object):
    def __init__(self):
        pass
    def test():
        return None
~~~

## Coffee-Script
~~~coffeescript
# Objects:
math =
  root:   Math.sqrt
  square: square
  cube:   (x) -> x * square x

# Splats:
race = (winner, runners...) ->
  print winner, runners

# Existence:
alert "I knew it!" if elvis?

# Array comprehensions:
cubes = (math.cube num for num in list)
~~~
