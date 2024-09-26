# python-code
#Take a list to find the second highest value
x = [10, 20, 30, 40, 50]
highest = second_highest = float('-inf')  

for ele in x:
    if ele > highest:
        second_highest = highest 
        highest = ele  # Update the highest
    elif ele > second_highest and ele != highest:
        second_highest = ele 

print("Second highest element:", second_highest)

