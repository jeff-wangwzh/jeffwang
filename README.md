# jeffwang
first app
name = input("student name:")
grade = input("grade:")
print("Let's do a test")
t1 = input("12+18=")
if t1 == "30":
    print("right")
else:
    print("wrong")
t2 = input("3+3=")
if t2 == "6":
    print("right")
else:
    print("wrong")
t3 = input("4*1=")
if t3 == "4":
    print("right")
else:
    print("wrong")
t4 = input("3*2=")
if t4 == "6":
    print("right")
else:
    print("wrong")
t5 = input("15*3=")
if t5 == "45":
    print("right")
else:
    print("wrong")
t6 = input("37*18=")
if t6 == "666":
    print("right")
else:
    print("wrong")
t7 = input("3+8=")
if t7 == "11":
    print("right")
else:
    print("wrong")
t8 = input("12+8=")
if t8 == "20":
    print("right")
else:
    print("wrong")
t9 = input("12*34=")
if t9 == "408":
    print("right")
else:
    print("wrong")
t10 = input("12*348=")
if t10 == "4176":
    print("right")
else:
    print("wrong")
print("The test is finish")

score = int(input("How many questions did you get right："))
if score == 10:
  print(name+" in grade "+grade+" you got a A")
if score > 7 and score < 10:
  print(name+" in grade "+grade+ " you got a B")
if score > 5 and score < 7:
  print(name+" in grade "+grade+" you got a C")
if score > 0 and score < 5:
  print(name+" in grade "+grade++" you got a R")
if score == 0:
  print(name+" in grade "+grade+" you got a 0")
