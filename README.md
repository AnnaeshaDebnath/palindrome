# palindrome
def is_palindrome(s):
    # Remove whitespace and convert to lowercase for accurate comparison
    clean_s = ''.join(s.split()).lower()
    return clean_s == clean_s[::-1]

# Example usage:
word = "Racecar"
if is_palindrome(word):
    print(f"'{word}' is a palindrome!")
else:
    print(f"'{word}' is not a palindrome.")
