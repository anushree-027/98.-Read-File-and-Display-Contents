# 98.-Read-File-and-Display-Contents
f = open('myfile.txt', 'w')
f.write('My first file')
f.close()

f = open('myfile.txt', 'a')
f.write('\nWelcome Everyone')
f.write('\nAppend Mode')
f.close()

f = open('myfile.txt', 'r')
print(f.read())
f.close()
