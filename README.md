"break" and "continue" Statements
---------------------------------
``````ruby
n = int (input())
cnt = 1
while cnt<=n:
    cnt +=1
    if n % cnt==0:
        print(cnt)
        break
``````
-----

``````ruby
n = int (input())
for i in range (1, n+1):
    if 5<=i<=9 or 17<=i<=37 or 78<=i<=87:
      continue
    print (i)
``````
------
