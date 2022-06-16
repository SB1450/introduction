# header1
## header2
###### header 6

![my logo image](https://user-images.githubusercontent.com/107620565/174069134-7cd3e065-9d81-4e33-abe8-b7c9750db424.png)

python script that generate a random password:
```
import math
import random
import string
password = ""
rand = string.punctuation + string.digits + string.ascii_uppercase + string.ascii_lowercase
def pass_generate(password, length):
    for i in range(length):
        password += random.choice(rand)
    return password
#return switcher.get()

print("Hello today we are going to generate you a password")
length = int(input("How much long you want your password: "))
print(f"your password is : {pass_generate(password, length)}")
```
- [x] Complete
- [ ] need to do
