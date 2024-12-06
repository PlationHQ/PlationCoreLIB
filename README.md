PlationCore Guide
Version: 1.0.0
Author: Aaditya Pandey

Overview
PlationCore is a foundational library designed to provide reusable and efficient utility functions for various programming tasks, including string manipulation, math operations, date handling, randomization, and more. This guide walks you through its features, installation, and usage.


## Installation

1. Clone the repository or download the source code:
    ```bash
    git clone <repository-url>
    ```


Features
1. String Utilities
Perform common string manipulations:

capitalize_words(sentence)
Capitalize the first letter of each word.

 ```python
capitalize_words("hello world")  # Output: "Hello World"
reverse_string(s)
    ```


Reverse a given string.

python

reverse_string("hello")  # Output: "olleh"
is_palindrome(s)
Check if a string is a palindrome.

python

is_palindrome("racecar")  # Output: True
count_vowels(s)
Count the vowels in a string.

python

count_vowels("hello")  # Output: 2
2. Math Utilities
Work with numbers efficiently:

is_prime(num)
Check if a number is prime.

python

is_prime(29)  # Output: True
gcd(a, b)
Find the greatest common divisor.

python

gcd(56, 98)  # Output: 14
lcm(a, b)
Calculate the least common multiple.

python

lcm(12, 15)  # Output: 60
fib_sequence(n)
Generate the first n Fibonacci numbers.

python

fib_sequence(5)  # Output: [0, 1, 1, 2, 3]
3. Random Utilities
Generate randomness for testing and experiments:

generate_random_string(length)
Create a random alphanumeric string.

python

generate_random_string(8)  # Output: "A1B2C3D4"
random_int_list(size, start, end)
Generate a list of random integers.

python

random_int_list(5, 1, 100)  # Output: [23, 45, 67, 12, 89]
shuffle_list(lst)
Shuffle the elements of a list.

python

shuffle_list([1, 2, 3])  # Output: [3, 1, 2] (randomized)
4. Date Utilities
Simplify date and time operations:

current_timestamp()
Get the current timestamp as a string.

python

current_timestamp()  # Output: "2024-12-05 12:34:56"
add_days_to_date(date_str, days)
Add days to a date.

python

add_days_to_date("2024-12-05", 10)  # Output: "2024-12-15"
days_between_dates(date1, date2)
Calculate the days between two dates.

python

days_between_dates("2024-12-01", "2024-12-25")  # Output: 24
5. File Utilities
Handle file operations easily:

read_file(filepath)
Read the content of a file.

python

read_file("example.txt")  # Output: "File content here"
write_file(filepath, content)
Write content to a file.

python

write_file("example.txt", "Hello, World!")
count_words_in_file(filepath)
Count the number of words in a file.

python

count_words_in_file("example.txt")  # Output: 2
6. Collection Utilities
Work with lists and collections:

most_common_elements(iterable, n)
Find the n most common elements in an iterable.

python

most_common_elements([1, 2, 2, 3], 2)  # Output: [(2, 2), (3, 1)]
flatten_list(nested_list)
Flatten a nested list.

python

flatten_list([[1, 2], [3, 4]])  # Output: [1, 2, 3, 4]
chunks(lst, chunk_size)
Divide a list into smaller chunks.

python

list(chunks([1, 2, 3, 4], 2))  # Output: [[1, 2], [3, 4]]
Example Usage
To see detailed usage, refer to the example.py file included.

Here’s a quick demo:

python

from plationcore import capitalize_words, gcd, random_int_list

# Example 1: String manipulation
print(capitalize_words("hello from plationcore"))  # Output: "Hello From Plationcore"

# Example 2: Math utilities
print(gcd(48, 64))  # Output: 16

# Example 3: Random utilities
print(random_int_list(5, 10, 50))  # Output: [12, 34, 45, 23, 40] (randomized)
Contribution
To contribute to PlationCore, please submit pull requests or issues on the official repository.

License: This project is licensed under the MIT License.
Enjoy coding with PlationCore! 🚀






