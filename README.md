<h1>Hello :)</h1>

```py
#!/usr/bin/python
# -*- coding: utf-8 -*-
# file : main.py

import json

class Developer:
  
  def __init__(self):
    self.name = 'Shyam Sunder Saravanan'
    self.alias = 'N1tr0s'
    self.from = 'Tamil Nadu / India'
    self.site = '0xnitros.tech'
    
  def say_hi():
    print("Hello World from Nitros!!")
    
me = Developer()
me.say_hi()
data = json.load(open('data.json'))
for candidate in data:
  print(candidate)
print("Done")
```

```json
// filename : data.json
{
  "interests" : ["VAPT","Cloud","Red Teaming","Web3","Binary Exploitation"],
  "works" : ["Web Development","Cryptography","DFIR","Reverse Engineering"],
  "Daily Routine" : ["eat","sleep","code","repeat"],
  "Hobbies" : ["Music","Anime"],
}
```



