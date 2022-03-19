# spiski.lab
a = input().split()
for i in range(0, len(a), 2):
    print(a[i])


s = input()
k = s.split()
for c in s:
     if int(c) > 0:
         print(c, end=' ')
         
         
   a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 8, 7, 6, 5, 4, 3, 2, 1]
b = 1
while b != len(a):
    if a[b] > a[b - 1]:
        print(a[b], end=' ')
    b += 1
    
    
   a = input().split() 
for i in range(len(a)-1): 
    n = int(a[i]) 
    i += 1
    m = int(a[i])  
    if (n * m) > 0:
        print(n, m, end=' ')


a = [int(i) for i in input().split()]
counter = 0
for i in range(1, len(a) - 1):
    if a[i - 1] < a[i] > a[i + 1]:
        counter += 1
print(counter)





a = [int(i) for i in input().split()]
counter = 0
for i in range(1, len(a) - 1):
    if a[i - 1] < a[i] > a[i + 1]:
        counter += 1
print(counter)
