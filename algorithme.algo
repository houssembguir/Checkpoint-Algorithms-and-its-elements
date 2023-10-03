def analyze_sentence(sentence):
    length = 0
    word_count = 0
    vowel_count = 0
    
    vowels = "aeiouAEIOU"  # List of vowels
    
    for char in sentence:
        # Count characters (including spaces)
        length += 1
        
        # Check if the character is a vowel
        if char in vowels:
            vowel_count += 1
        
        # Check if the character is a space (word separator)
        if char == " ":
            word_count += 1
    
    # The last character is a point, so we subtract 1 from the length
    length -= 1
    
    # The number of words is one more than the word count (accounting for the last word)
    word_count += 1
    
    return length, word_count, vowel_count

# Read a sentence from the user
sentence = input("Enter a sentence: ")

# Call the function to analyze the sentence
length, word_count, vowel_count = analyze_sentence(sentence)

# Print the results
print("Length:", length)
print("Number of words:", word_count)
print("Number of vowels:", vowel_count)