# frienship_goals
print(input("Friendship goals!."))

name1= input("what is your name?\n")
name2 = input("what is their name?\n")

all_name = name1 + name2
both_names = all_name.lower()

L = both_names.count('l')
O = both_names.count('o')
V = both_names.count('v')
E = both_names.count('e')

first_name = L+O+V+E

F = both_names.count('f')
O = both_names.count('o')
R = both_names.count('r')
L = both_names.count('l')
I = both_names.count('i')
F = both_names.count('f')
E = both_names.count('e')

second_name = F+O+R+L+I+F+E
ourname = first_name + second_name
if (ourname <10) or (ourname>90):
  print(f"your friendship goals is {ourname}%, you guys dont match")
elif (ourname >=30) and (ourname>=60):
  print(f"your friendship goals is {ourname}%, you guys are perfect match")
else:
  print(f"your friendship goals is {ourname}%")
