**September 1 2025**
- **Phyton Refresher Start, Section 1, String Manipulation**
  - Strings characters are accessed inside [ ] and not ( ) (Text)
  - len will output the length of characters of a defined function 
  - type will output the class type (string, intiger, etc.)
- <u>Vairable Names</u>
  - Can not use for, while, True, and some other pre-defined names
  - Can not start with a number and can only be alpha-numveric or underscores
  - Are case sensitive
  - No spaces, use underscores instead and do not need brackets to define the name of the variable (same for Markdown files!!)
  - To find a letter in a string, use the function .find. Append the vairable name to the beginning of the function (vairable is Name, so its name.find(e) to return the value 4 or you can also find the position of a value in the string by specifying the [#]
  - 0 is the fist value in a string (not 1) 
 - Loops 
    - Loops can be ussed to find the values in a string of text. 'for' loops work here
    - you must indend the code in loops in python, 4 spaces per indentation level. Python relies in indentations for blocks of code which is designated by a : at the beginning  
- Strings
  - Strings are immutable (can not be changed after creation; will generate a 'TypeError')
*Stopped at Step 36 https://www.freecodecamp.org/learn/scientific-computing-with-python/learn-string-manipulation-by-building-a-cipher/step-36* 
**September 6 2025**
- **Phyton Refresher Start, Section 36, String Manipulation**
  - '+=' // <u>Addition assignment operator</u>: a = a+b is the same as a +=b; you can add a value to a variable and then assign the result to that variable
  -  'Comparsion Operators" // Used to compare values
    - == Equal
    - != Not equal
    - *> < Greater/less than*
    - *>= <= Greater than or equal / less than or requal*
    - if statements otherwise work the same as in excel but you need a : after the argument (if x=2: print (x), else: print (y))
  - modulo operator (%) can be used to return the remainder of the difvision between two numbers
      - 5 % 2 is 1 as 5 divided by 2 has a quotient of 2 and a remainder of 2
      - useful in shift and index. example from google
          - index + shift: This calculates the new, raw position for the character.
            - For the letter 'Z', which is at index 25, index + shift would be 25 + 3 = 28. This is an invalid index for the 26-letter alphabet.
            - % 26: This takes the result of the previous step (28) and divides it by the total number of characters in the alphabet (26). The operator then returns only the remainder.
            - 28 % 26 equals 2, because 26 goes into 28 once with a remainder of 2.
            - alphabet[new_index]: The final result (2) is a valid index, corresponding to the letter 'c', which is the correct cipher character for 'z' with a shift of 3.
  - a *function* is a reusable block of code; can define as *def function_name ():*
      - declaration starts with the def keyword followed by the function name and () and ends with a colon
      - any vairabled defined *within* a function are local - only used for that function. Define variables outside a function for global use
- *Stopped at Step 52 https://www.freecodecamp.org/learn/scientific-computing-with-python/learn-string-manipulation-by-building-a-cipher/step-53*    
**September 7 2025**
- **Phyton Refresher Start, Section 53, String Manipulation**
  - functions can be declared with *paramneters
    - def function_name (param_1, param_2): before the code
      - example, def byrons_function(message passed, key) where key is an encoder to shift the letters
      - Vigenère cipher is where the offset for each letter is determined by another text, called the key
   - '#' is used to write comments in the code. Comments are very helpful in understanding what your code does / good pratice to use for reference. Anything entered after a # wont be executed in Python
   - a ValueError is a built-in exception that is raised when an agrument with the right type but wrong value type is passed to a function 
    
