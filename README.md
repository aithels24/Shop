# Price
apple = float(1)
orange = float(1)
watermelon = float(4)
eggs = float(8)
cookies = float(6)
water = float(3)
milk = float(6)
chicken = float(8)
bacon = float(6)
inventory = []

item1 = input("What should I buy >>")
if item1 not in inventory:
    inventory.append(item1)

item2 = input("What else")
if item2 not in inventory:
    inventory.append(item2)

item3 = input("What else")
if item3 not in inventory:
    inventory.append(item3)
    
item4 = input("What else")
if item4 not in inventory:
    inventory.append(item4)

item5 = input("lastly")
if item5 not in inventory:
    inventory.append(item5)
    
print(len(inventory))
print("""
Items in your bag""")


print(""" a) remove an item  b) cost""")

ans1 = input(">>")

if ans1 in ans_a: 
    print(inventory)

    inv = input("Disposing of an item")
    inventory.remove(inv)

    print(inventory)
    
    cost = item1 + item2 + item3 + item4 + item5
        
    print(cost)

if ans1 in ans_b:
    cost = item1 + item2 + item3 + item4 + item5
        
    print(cost)

