# Luma Language

Luma is a small programming language built around one idea: programming should be easy to read and easy to write.

The syntax is simple and familiar, without a bunch of unnecessary symbols or complicated concepts getting in the way.

```luma
name = ask "What's your name?"

if name == "John"
    say "Hey!"
else
    say "Hello", name
end
```

Luma currently supports variables, strings, numbers, booleans, lists, conditions, loops, functions, user input, and basic expressions.

The interpreter is written in C++ and is currently a work in progress. The goal isn't to make another massive language with hundreds of features. It's to keep Luma small, understandable, and actually enjoyable to use.

## Current Features

* Variables
* Numbers and strings
* Booleans
* Lists
* `say` for output
* `ask` for input
* `if`, `else`
* `while`
* `repeat`
* `for`
* Functions
* `return`
* Arithmetic and comparisons
* `and`, `or`, `not`
* Comments
* REPL
* `.luma` files

## Example

```luma
function add(a, b)
    return a + b
end

numbers = [10, 20, 30]

for number in numbers
    say number
end

result = add(10, 25)
say "Result:", result
```

Luma is still being developed, so the syntax and features may change as the language grows.
