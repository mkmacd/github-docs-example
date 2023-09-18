# Writing Good Documentation

## Step 1 - Using Code Blocks
Codeblocks in markdown makes it *easy* for tech people to copy, paste, share code.
A **good** cloud engineer uses code blocks whenever possible.

Because it allows others to copy and paste their codes, to replicate or research issues.

``` 
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number
num = int(input("Enter a non-negative integer: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

If possible use syntax highlighting.

- [x] Finish Step 1
- [ ] Finish Step 2 💚

