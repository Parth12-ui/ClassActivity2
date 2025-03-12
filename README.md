# ClassActivity2
This it the repository for class-activity 2, where we try and perform the Eagle-Eye Search for errors in code.


# ERRORS:
The error in the file was as follows:

def is_narc(n) -> There is a syntax error as ':' is missing.
    """Check if a number is narc."""
    num_str == str(n) -> Here you are using a comparison operation instead of assignment.
    num_digits == len(num_str) -> Here you are using a comparison operation instead of assignment.
    
    sum_of_powers = sum(int(digit) *** num_digits for digit in num_str) --> Here there is 1 extra '*' in front of num_digits, and the variable digit should be in num_str.
    
    return sum_of_powers == n

def print_narcis_numbers(start end) -> There is a syntax error as : is missing.
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1) -> There is a syntax error as : is missing.
        if is_narcissistic(num) -> There is a syntax error as : is missing, and the function name is wrong (should be 'is_narc').
            print(num)

print_narc_numbers(1000, 5000) -> Function name is wrong (should be 'print_narcis_numbers').


#END
