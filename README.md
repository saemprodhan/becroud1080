# becroud1080
max_number= 0
max_position= 0
for i in range(1,101):
    number = int(input())
    if number > max_number:
        max_number = number
        max_position=i
print(max_number)
print(max_position)
