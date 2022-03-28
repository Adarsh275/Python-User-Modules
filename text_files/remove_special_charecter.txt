l=list(input("Enter a statement"))
s=""
for i in l:
   if i.isalnum():
     s=s+i
print(s)