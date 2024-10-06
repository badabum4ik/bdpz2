def get_math_text(a,b,c):
    d=b**2-4*a*c
    if d<0:
        return[None]
    else:
        x=((b*(-1))+(d**0.5))/(2*a)
        y=((b*(-1))-(d**0.5))/(2*a)
        return[x,y]
import back
a=int(input('Введите a:'))
b=int(input('Введите b:'))
c=int(input('Введите c:'))
print(back.f(a,b,c))
print("Результат")****
