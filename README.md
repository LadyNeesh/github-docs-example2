# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for developers to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.



Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```
user_location = input("Where are you from? ")

if user_location.lower() == "new york":
  print("Welcome to the Big Apple!")
elif user_location.lower() == "chicago":
  print("The Windy City is a nice place to visit!")  
elif user_location.lower() == "los angeles":
  print("LA has great weather!")
elif user_location.lower() == "london":
  print("London is an amazing city with lots of history.")
else:
  print("I hope to visit "+ user_location + " someday!")
```
- When you can you should attempt to apply syntax highlighting to your codeblocks

```python
user_location = input("Where are you from? ")

if user_location.lower() == "new york":
  print("Welcome to the Big Apple!")
elif user_location.lower() == "chicago":
  print("The Windy City is a nice place to visit!")  
elif user_location.lower() == "los angeles":
  print("LA has great weather!")
elif user_location.lower() == "london":
  print("London is an amazing city with lots of history.")
else:
  print("I hope to visit "+ user_location + " someday!")
```

- Make note of where the backtick button is located.
- It should appear above the tab key, but it may vary based on your keyboard.

<img width="200px" src="https://github.com/LadyNeesh/github-docs-example2/assets/145222779/7af97774-aa8c-42a0-98ce-7d8f8dc3ac8c" />

Good Cloud Engineers use codeblocks for both code and errors that appear in the console.

```bash
begin
  raise StandardError, "An example error" 
rescue => e
  puts e  
end 
```
>Here is an example of using a codeblock for an error that appears in bash.

## References
 - [Github Flavored Markdown (GFM) Spec](https://github.github.com/gfm/)
 - [Basic Syntax for GFM](https://docs.github.com/en/get-started/writing-on-github/getting-startedwith-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
