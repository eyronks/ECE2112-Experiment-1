# ECE2112 Programming Problems

This repository contains Python scripts for solving various programming problems in ECE2112. Below are the details of each script included in this repository:
## Scripts

### 1. Alphabet Soup Problem

**Instructions:** Create a function that takes a string and returns a string with its letters in alphabetical order.

**Function:**
```python
// define a function that takes a string s as an input and returns a new string.
def alphabet_soup(s):
    // this part of the code sorts the characters in the input string s in alphabetical order.
    return "".join(sorted(s))

alphabet_soup("hacker")
```
**Output**
'acehkr'

### 2. Emoticon Problem

**Instructions:** Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.

**Function:**
```python
def emotify(s):

   // define a dictionary called list that maps certain words to their corresponding emoticon characters.
   list = { 'smile': ':)', 'grin': ':D', 'sad': ':(', 'mad': '>:(', }

   // a loop that iterates over each key-value pair in the list dictionary. 
   for word, emoticon in list.items(): s = s.replace(word, emoticon)

   // a function that returns the modified string.
   return s

print(emotify("Make me smile"))
```
**Output**
'Make me :)'

### 3. Unpacking List Problem

**Instructions:** Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

**Function:**
```python
def unpack_list(lst):

   // this line assigns the first element of the input list lst to the variable first.
   first = lst[0]
   // this line assigns the last element of the input list lst to the variable last.
   last = lst[-1]
   // this line assigns all elements of the input list lst except the first and the last to the variable middle.
   middle = lst[1:-1]

   print("first: {}, middle: {}, last: {}".format(first, middle, last))

unpack_list(lst = [1, 2, 3, 4, 5, 6])
```
**Output**
'first: 1, middle: [2, 3, 4, 5], last: 6'
