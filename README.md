## Hi there 👋

<!--
**rupesh-singh-33/rupesh-singh-33** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
#this is my first python program
#output fuction
print("Hello World")

#input fuction
name = input("what is your name : ")
print(name)

# type convertion
old_age= input("Enter your age : ")
new_age= int(old_age) +2
print(new_age)

#addition
print("Additon of two number")
first= input ("Enter first number : ")
second= input ("enter second number")
sum= float(first) + float(second)
print(sum)

#strings & operations
name = "Rupesh singh manjhi"
print(name.upper())
print(name.lower())
print(name.find('m'))
print(name.replace("Rupesh singh manjhi", "Satyam"))
print(name.replace("manjhi", "------"))

#search
print("Rupesh" in name)
# operator true or false
print(2>1)


#logical or and not
print(6 > 5 or 3 > 5 )
print(6 > 5 and 3 > 5)
print(not 3 > 2)

# conditional statement
age = 19
if age >= 18:
    print("you are adult")
    print("You acan vote")
elif age < 18 and age > 3:
    print("You are in school")  
else:
    print("Thank you")

# mini calculator
    
first= input ("Enter first number : ")
operator= input ("Enter operator (+,-,*,/,%) : ")
second= input("Enter second Number : ")
first = int(first)
second= int(second)
if operator=="+":
    print(first + second)
elif operator=="-":
    print(first - second)
elif operator=="*":
    print(first * second)
elif operator=="/":
    print(first / second)
elif operator=="%":
    print(first % second)            
else:
    print("Invalid Operator")    
#loops
i = 1
while i<=8:
    print(i)
    i = i+1
#pattern
while i >= 0:
    print(i * "*")
    i = i-1
#for loop
for item in range(5):
    print(item + 1)
#list
marks = [10, 20, 30, 40, 50, 60]
print(marks[2])
print(marks[2:6])
for score in marks:
    print(score)

# operation
marks.insert(2, 44)
print(marks)
print(44 in marks)
print(len(marks))

# with while loop
i =0
while i< len(marks):
    print(marks[i])
    i = i+1

marks.clear()
print(marks)
