# conditional
'''
l = [1, 3, 2, 5, 7, 9, 8]
empty = []

i = 0
while i < len(l):
    if i % 2 == 0:
        empty.append(l[i])
        print(empty)
    i += 1

print(empty)
'''
'''
l = [1, 3, 2, 5, 7, 9, 8]

i = 0
while i < len(l):
    if i % 2 == 0:
        if l[i] % 2 != 0:
            print(l[i])
    i += 1
'''
'''
l = [1, 3, 2, 5, 7, 9, 8]

i = 0
while i < len(l):
    print(l[i] ** 2)
    i += 1
'''
'''
l = [1, 3, 2, 5, 7, 9, 8]
empty = []

i = 0
while i < len(l):
    if l[i] % 2 != 0:
        empty.append(l[i] + 10)
    else:
        empty.append(l[i])
    i += 1

print(empty)
'''

'''
l = [1, 3, 2, 5, 7, 9, 8]
empty = []

i = len(l) - 1

while i >= 0:
    empty.append(l[i])
    i -= 1

print(empty)
'''
'''
l = ["mohan", "sravya", "pavani", "babu", "laysa"]

search = input("enter any name: ")

i = 0

while i < len(l):
    if l[i] == search:
        print("available")
        break
    i += 1
else:
    print("not available")
'''
'''
l = ["mohan", "sravya", "pavani", "babu", "lasya"]
length = []

i = 0

while i < len(l):
    length.append(len(l[i]))
    i += 1

print(length)
'''
'''
names = ["mohan", "sravya", "pavani", "babu", "lasya"]
count = []

for i in range(len(names)):
    count.append(len(names[i]))

print(count)
'''
'''
names = ["mohan", "sravya", "pavani", "babu", "lasya"]
d = {}

for i in range(len(names)):
    d[names[i]] = len(names[i])

print(d)
'''
'''
i = 3

while i >= 0:
    j = 0

    while j < 3:
        print(i, end=" ")
        j += 1

    print()
    i -= 1
'''
