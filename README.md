# Adding and Removing Dots

This Python script contains two functions, `add_dots` and `remove_dots`, for adding and removing dots from a string, respectively.

## add_dots Function
The `add_dots` function takes a string as input and adds a dot (".") in between each letter of the string. For example, calling `add_dots("test")` will return the string "t.e.s.t".

## remove_dots Function
The `remove_dots` function removes all dots from a string. It takes a string as input and returns a new string with all dots removed. For example, calling `remove_dots("t.e.s.t")` will return "test".

## Usage
You can use these functions individually or together to add and remove dots from strings. Additionally, if both functions are working correctly, calling `remove_dots(add_dots(string))` should return the original string for any input string.

## Example
```python
print(add_dots('test'))              # Output: "t.e.s.t"
print(remove_dots('t.e.s.t'))        # Output: "test"
print(remove_dots(add_dots('test'))) # Output: "test"
```

## Running the Script
To run the script and see the functions in action, simply execute the `main` function.

```python
if __name__ == '__main__':
    main()
```

This will execute the example calls to the `add_dots` and `remove_dots` functions and print their outputs.
