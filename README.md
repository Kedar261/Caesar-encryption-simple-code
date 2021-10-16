# Caesar-encryption-simple-code
Caesar encryption
s = input("Enter a string for caesar encryption:")
l = []
for i in s:
    print(chr(ord(i[:])+2),end="")
print()
