# my
Standard expressions : Control what the user enters letters, numbers and logical factors

import re
print('Enter uppercase letters, lowercase letters, and example numbers =:= : ......@gmail.com')
pos = input('enter yor emali : ')
patt = '[A-Za-z]+[a-z]+[\d]+@[a-z]+.[a-z{3}]'
s = re.match(patt, pos)
if s == None:
    print(False)
else:
    print(True)
import re
print('Enter uppercase letters, lowercase letters, and example numbers =:= : ......@gmail.com')
pos = input('enter yor emali : ')
patt = '[A-Za-z]+[a-z]+[\d]+@[a-z]+.[a-z{3}]'
s = re.match(patt, pos)
if s == None:
    print(False)
else:
    print(True)

