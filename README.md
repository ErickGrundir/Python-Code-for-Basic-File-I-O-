# Python-Code-for-Basic-File-I-O-
Python Code for Basic File 
with open('example.txt', 'w') as file:
    file.write('Hello, File!')

with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
