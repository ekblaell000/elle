#Code so Far
---
The Caesar.py shifts a certain sentence that you give. Lets say you have a letter A and you pick a shift value of 3 then
the letter in the word will shift to the letter D.
---
 
///clear_text = input("type in your message")
clear_text = clear_text.lower()
counter = 0
shift = int(input("choose a shift value of 1-25"))    
print("")
cipher_text = clear_text

input("press enter to continue")

while counter < shift:
    counter += 1
    cipher_text = cipher_text.replace("a","B")
    cipher_text = cipher_text.replace("b","C")
    cipher_text = cipher_text.replace("c","D")
    cipher_text = cipher_text.replace("d","E")
    cipher_text = cipher_text.replace("e","F")
    cipher_text = cipher_text.replace("f","G")
    cipher_text = cipher_text.replace("g","H")
    cipher_text = cipher_text.replace("h","I")
    cipher_text = cipher_text.replace("i","J")
    cipher_text = cipher_text.replace("j","K")
    cipher_text = cipher_text.replace("k","L")
    cipher_text = cipher_text.replace("l","M")
    cipher_text = cipher_text.replace("m","N")
    cipher_text = cipher_text.replace("n","O")
    cipher_text = cipher_text.replace("o","P")
    cipher_text = cipher_text.replace("p","Q")
    cipher_text = cipher_text.replace("q","R")
    cipher_text = cipher_text.replace("r","S")
    cipher_text = cipher_text.replace("s","T")
    cipher_text = cipher_text.replace("t","U")
    cipher_text = cipher_text.replace("u","V")
    cipher_text = cipher_text.replace("v","W")
    cipher_text = cipher_text.replace("w","X")
    cipher_text = cipher_text.replace("x","Y")
    cipher_text = cipher_text.replace("y","Z")
    cipher_text = cipher_text.replace("z","A")
    cipher_text = cipher_text.lower()

print(cipher_text)
