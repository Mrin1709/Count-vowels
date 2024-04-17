def count_vowels(string):
    
    vowels = {'a', 'e', 'i', 'o', 'u'}
    
    string = string.lower()
    
    vowel_count = sum(1 for char in string if char in vowels)
    return vowel_count

string = input("Enter a string: ")

num_vowels = count_vowels(string)

print("Number of vowels in the string:", num_vowels)
