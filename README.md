# kavya_daggubati1 
#My assignment 1
# first code: 1a
string=list(input("Enter the string:"))
if len(string) >= 2:
    del string[-2:-4:-1]
    reverse = string[::-1]
    print("".join(reverse))
else:
    print("Enter a string with more than two characters")

# first code: 1b
a=int(input("Enter first number:"))
b=int(input("Enter second number:"))
res1=a+b
res2=a-b
res3=a*b
res4=a%b
print("The outputs are:", res1, res2, res3, res4)

# second code: 2
text=input("Enter the sentence:")
result=text.replace("python", "pythons")
print("The Resultant sentence is:", result)

# third code: 3
score=int(input("Enter the class score:"))
if score >= 90 and score <= 100:
    grade = 'A'
elif score >= 80 and score < 90:
    grade = 'B'
elif score >= 70 and score < 80:
    grade = 'C'
else:
    grade = 'D'

print("Grade you secured is:", grade)
    
