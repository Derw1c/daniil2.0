7.
n = int(input())
 L = int(input())
 if n > 99 and n < 1000:
     a = n // 100
     b = n // 10 % 10
     c = n % 10
 else:
     print("введите другое число")
 if a + b + c > 9:
     print("двухзначное")
 else:
     print("не")
 if a * b * c > 99:
         print("трехзнач")
 else:
         print("не трехзнач")
 if a + b + c > L:
     print("больше")
 else:
     print("меньше")
 if a * b * c // 5 > 0:
     print("кратно")
 else:
     print("нет")

8.
a , w = int(input()), int(input())
a1 = a //1000 
a2 = a //100%10 
a3 = a &100//10 
a4 = a % 10  
if a1+a2==a3+a4: 
    print("Да")
else: 
    print("Нет")
if (a1+a2+a3+a4)%3==0: 
    print("Да")
else: 
    print("Нет")
if (a1*a2*a3*a4)%4==0: 
    print("Да")
else: 
    print("Нет")
if (a1*a2*a3*a4)%w==0: 
    print("Да")
else: 
    print("Нет")
