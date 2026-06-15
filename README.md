# pythonbasics

#1
print("Hello")

#2
c="A"
print(ord(c))

c1 = "a"
print(ord(c1))
print(chr(ord(c1)))
print(chr(67))


#3
a=int(input("Enter a number"))
b=int(input("ENter another number"))
c=input("Enter any of the operator +, -, *, %")

if c==" +":
    print(f"sum of numbers is {a+b}")
elif c==" -":
    print(f"Diferrence is {a-b}")
elif c==" *":
    print(f"Multiplicaion is {a*b}")
elif c==" %":
    print(f"Remainder is {a%b}")
else:
    print("invalid") 

#4
p=15
q=4
print(p/q)
print(p//q)
print(p%q)

#5
a=int(input("Enter a number: "))
if a&1==0:
    print("Even")
else: 
    print("Odd")


#6
num=int(input("Enyer a number"))
if num%2==0:
    print("Number is even")
else:
    print("NUmber is odd")


#7
s=[x*x for x in range(0,9)]
print(s)


#8
num=int(input("Enter a number: "))
print(num<<1) #left shift (multiply by 2)
print(num>>1) #right shift (divide by 2)

#9
a=int(input("Enter a number"))
b=int(input("Enter a number"))
print(a,b)
a=a^b
b=a^b
a=a^b
print(a,b)










