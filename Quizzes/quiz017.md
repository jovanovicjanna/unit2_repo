# Quiz 017
## Code
'''.py
def averageLength(given:list)->float:
    length = (len(char) for char in given)
    output = sum(length)/len(given)
    return output

test1 = averageLength(["hello", "main"])
print(test1)
test2 = averageLength(["Peru", "France", "Nepal"])
print(test2)
test3 = averageLength(["Computer Science", "Art"])
print(test3)
test4 = averageLength(["one", "two"])
print(test4)
'''
## Test

