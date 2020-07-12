# Developer Prompts 👨‍💻👩‍💻

Prompts that may be useful for developers and the like.

## -> [Parse Unstructured Data](../analysis/README.md#parse)
## -> [Maths](../analysis/README.md#maths)

## Code Writing

### React Component Generator

```
import React from 'react';

const ThreeButtonComponent=()=>(
+ 
+ <div>
+ 
+ <p>Button One</p>
+ 
+ <button className="button-green" onClick={this.handleButtonClick}>Button One</button>
+ 
+ <p>Button Two</p>
+ 
+ <button className="button-green" onClick={this.handleButtonClick}>Button Two</button>
+ 
+ <p>Button Three</p>
+ 
+ <button className="button-green" onClick={this.handleButtonClick}>Button Three</button>
+ 
+ </div>
+ 
+ )
```

### 🐍Python Palindrome

Prompt:
```python
def is_palindrome(s):
    """Check whether a string is a palindrome"""
```

## Text to Command 💻

```diff
Q: Ask Constance if we need some bread
A: send-msg `find constance` Do we need some bread?

Q: Send a message to Greg to figure out if things are ready for Wednesday.
+ A: send-msg `find greg` Is everything ready for Wednesday

Q: Ask Ilya if we're still having our meeting this evening
+ A: send-msg `find ilya` Are we still having a meeting this evening?

Q: Contact the ski store and figure out if I can get my skis fixed before I leave on Thursday
+ A: send-msg `find ski store` Would it be possible to get my skis fixed before I 
leave on Thursday?

Q: Thank Nicolas for lunch
+ A: send-msg `find nicolas` Thank you for lunch!

Q: Tell Constance that I won't be home before 19:30 tonight — unmovable meeting.
+ A: send-msg `find constance` I won't be home before 19:30 tonight. I have a meeting I can't move.
```

## Code Translation

```diff
Python:
list[::-1] 
Ruby:
list.reverse 

Python:
list[1:4] 
Ruby:
+ list[1..4]

Python:
print("Hello World")
Ruby:
+ puts "Hello World"

Python: 
fruits = ["apple","banana","cherry"] 
for x in fruits:
print(x)
+ Ruby: 
+ fruit = ["apple", "banana", "cherry"]
+ each {|x| print x } 

Python: 
fruits = ["apple","banana","cherry"] 
a = list(fruits) 
print(a) 
a.reverse() 
print(a)
```
