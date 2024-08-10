import pandas as pd
import numpy as np



number_variable = 42
string_variable = "Hello, GitHub!"
list_variable = [1, 2, 3, 4, 5]
dictionary_variable = {
    "key1": "value1",
    "key2": [1, 2, 3],
    "key3": {"nested_key": "nested_value"}
}




def example_function(x, y):
    if x > y:
        result = "x is greater than y"
    else:
        result = "x is not greater than y"
    return result

# Example of calling the function and printing the result
example_result = example_function(10, 5)
print("Function Output:", example_result)


print("Number Variable:", number_variable)
print("String Variable:", string_variable)
print("List Variable:", list_variable)
print("Dictionary Variable:", dictionary_variable)
