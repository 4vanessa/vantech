# vantech
# create a dictionary named capital_city
capital_city = {'Nepal': 'Kathmandu', 'Italy': 'Rome', 'England': 'London'}

print(capital_city)
#PIZZA SIZE PROGRAM
      
print("WELCOME TO PYTHON PIZZA SHOP")
size =input("what size of pizza do you want?\n s , m , l ? ")
#s = ("small")
#m = ("meduim")
#l = ("large")
bill= 0
if size == "s":
 bill += 15
if size == "m":
 bill += 20
if size == "l":
 bill += 25
print(bill)
  
  
  
peperoni = input("do you want extra peperoni y, n ? ")
if peperoni == "y": 
 pep_size = input("what size do you want? s,m,l? ")

if pep_size == "s":
 bill += 2
else :
 bill += 3
cheese = input("do you want to add cheese? y ,n? ")
if cheese == "y":
  bill += 4
 
print(bill)
