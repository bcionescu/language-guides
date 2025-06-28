# Ruby

Ruby is by far the most beautiful programming language I have ever encountered. Its syntax is beautiful and clean, allowing me to focus on coding, rather than typing superfluous parentheses—I'm looking at you, Python.

## IDE

Before we jump into the language, let's briefly talk about IDEs. You can essentially use anything you want, including basic online editors, including [try ruby](https://try.ruby-lang.org/playground/) and [One Compiler](https://onecompiler.com/ruby). If you're looking for something more local, many people use [Visual Studio Code](https://code.visualstudio.com/), although I personally prefer [Neovim](https://neovim.io/).

Use whatever is available. Over time, you can try other IDEs and you can figure out what you actually like best.

## Print

Anyway, let's start with the basics. How do you output something to the screen? I'll cover a few different ways, however, most of the time you'll find yourself using `puts`.

### puts

```ruby
puts "bananums"
```

This will output the name of the well-know fruit, `bananums`. Naturally, you can print more than just strings with `puts`.

```ruby
puts 420
puts [6, 9]
```

The above would produce the following output.

```
420
6
9
```

As you may have noticed, `puts` also adds a new line, which means that after one command is printed, we move to the next line. If you want to stay at the end of the line when printing, you can use `print`.

### print

Here's an example of how it works.

```ruby
print "Hi"
print ", "
print "mom!"
```

If you run the code above, you will end up with the following output.

```
Hi, mom!
```

### p

Another way to print is by using `p`. This works similarly to `puts`, but it prints the object in its raw form. This makes it useful for debugging.

```ruby
p "Hello"
p [1, 2, 3]
```

The above will output the following.

```
"Hello"
[1, 2, 3]
```
