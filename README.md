# Task-0
![image](https://user-images.githubusercontent.com/86650273/125780645-b71b6e05-8817-4391-8960-b18e53129f7f.png)
<h1>код<!h1>
<p>import random
<p>arr = []
<p>for i in range(0,30):
<p>    arr.append(random.randrange(-100,100))
<p>print("Numbers:",arr)
<p>print("Max:",max(arr))
<p>for index,a in enumerate(arr):
<p>   if a == max(arr):
<p>        print("Index of number: %s = %s" % (a,index))
<p>odd = []
<p>for b in arr:
<p>   if b % 2 != 0:
<p>        odd.append(b)
<p>if len(odd) == 0:
<p>    print("No")
<p>else:
<p>   print("Odd numbers:",sorted(odd,reverse=True))
<p>
<p>for i in range(30):
<p>    if arr[i] < 0 and arr[i+1] < 0:
<p>        print("Couples of odd numbers:",arr[i], arr[i+1], "\n")
  
  
<h1>Робота Андрійчука Ігора<!h1>
