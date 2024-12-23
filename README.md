# task-_2
Convert the number to a string to access its characters. Reverse the string using slicing ([::-1]). Convert it back to an integer to ensure the result is a number.
def reverse_number(number):
    # Convert the number to a string, reverse it, and convert back to an integer
    reversed_num = int(str(number)[::-1])
    return reversed_num

# Example Input
input_number = 1234
# Example Output
print(reverse_number(input_number))  
# output = 4321

