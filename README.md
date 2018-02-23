"""
New Useful Tools
The following blocks of code are examples of the application of new tools I've come accross
while learning to code in Python. Blank lines indicate the start of a new code block/tool
and comments have been added to the line containing the tool.

Written by Domingo Gonzales III
On: Febreuary 21, 2018
Last update: February 21, 2018
"""

num = 4                         
print(num)
num += 1                                                # same as num = num + 1
print(num)

word1 = 'cat-'
word2 = 'dog'
print('Compare this output:')
print(word1)
print(word2)
print('to this output:')
print(word1, end='')                                    # anything can be put between '' and string will end in it instead of new line
print(word2, end=' seriously, anything\n')

def playAgain():               
    print('Do you want to play again? (yes or no)')
    return input().lower().startswith('y')              # result is a boolean expression that can be used like a comparison of if playAgain == 'y' but no need for variable

import random			
pets = ('cat', 'dog', 'rabbit')
print(random.choice(pets))                              # randomly selects an item in list, no more random int for choosing index and then list[random index]
