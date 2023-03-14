import random

words = ['convolution', 'recurrent', 'neural network', 'classification', 
'image segmentation', 'word embedding', 'deep learning', 
'language model', 'data mining', 'clustering']

def word_guess_game(word):
    print("Welcome to the word guessing game!")
    print("You have 2 chances to guess the word.")
    print("Here's your first hint:", word[:3] + "...")
    for i in range(2):
        guess = input("Enter your guess: ")
        if guess == word:
            print("Congratulations! You have successfully guessed the word.")
            return
        print("Incorrect! Here's your next hint:", word[:6] + "...")
    print("Sorry, you have failed to guess the word. The correct word was", word)

random_word = random.choice(words)
word_guess_game(random_word)
