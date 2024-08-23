This repository contains Python scripts for solving various programming problems in ECE2112. Below are the details of each script included in this repository:

1. Alphabet Soup Problem

   Function:
   
   def alphabet_soup(s):
       return ("".join(sorted(s)))

   alphabet_soup("hacker")

   Output:

   'acehkr'

2. Emoticon Problem

   Function:

   def emotify(s):
      list = {
        'smile': ':)',
        'grin': ':D',
        'sad': ':(',
        'mad': '>:(',
      }

    for word, emoticon in list.items():
        s = s.replace(word, emoticon)

    return s

    print(emotify("Make me smile"))

   Output:

   Make me :)

3. Unpacking List Problem

   Function:

   def unpack_list(lst):
        first = lst[0]
        last = lst[-1]
        middle = lst[1:-1]
        print("first: {}, middle: {}, last: {}".format(first, middle, last))

    unpack_list(lst = [1, 2, 3, 4, 5, 6])

   Output:

   first: 1, middle: [2, 3, 4, 5], last: 6
