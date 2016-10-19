# PYTHON-MATRIX-TRANSPOSE-PROGRAM USING FOR LOOP
a = []
m=int(input("enter no of rows in the matrix"))
n=int(input("enter no of columns in the matrix"))  
for i in range(0,m) :
 for j in range(0,n) :
    a.append([])
    a[i].append((input("enter element")))
for k in a:
 print(k)
trans =[]
print("tranpose matrix :")
for i in range(0,m) :
    trans.append([i])
    for j in range(0,n) :
        trans[i].append(a[j][i])
for t in trans:
 print(t)
  
