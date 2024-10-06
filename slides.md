---
marp: true
theme: cybertopia
class: invert
paginate: true
header: '**Marp presentation example** - **Alexandre ZANNI** aka **noraj**'
footer: '30/09/204 - XYZCon 2024'
---

# noraj theme

![](assets/noraj.svg)

---

## Sub-title

Hello, world!

---

###### emoji

😃💎💎❤️🔥

---

**image filters**

![blur:10px](assets/noraj.svg) ![brightness:1.5](assets/noraj.svg) ![opacity:.5](assets/noraj.svg)
![grayscale](assets/noraj.svg) ![hue-rotate:180deg](assets/noraj.svg) ![invert:100%](assets/noraj.svg)

---

background image

![bg](https://i.imgur.com/jBB1vtZ.jpeg)

---

![bg left:33%](https://picsum.photos/1080?image=28)

split background

---

<!-- _header: '' -->
<!-- _footer: '' -->

![bg vertical](https://fakeimg.pl/1920x360/02c797/fff/?text=vertical)
![bg](https://fakeimg.pl/1920x360/019f78/fff/?text=split)
![bg](https://fakeimg.pl/1920x360/01775a/fff/?text=background)

---

## Bullet list

- One
- Two
- Three

---

## Fragmented list

* One
* Two
* Three

---

**bold** _italic_

link: https://github.com/noraj

> blockquote Lorem ipsum dolor sit amet, consectetur adipiscing elit.

1. First item
2. Second item

---

code, Ruby

```ruby
# The Greeter class
class Greeter
  def initialize(name)
    @name = name.capitalize
  end

  def salute
    puts "Hello #{@name}!"
  end
end

g = Greeter.new("world")
g.salute
```
