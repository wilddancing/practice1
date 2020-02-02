# practice1

def euclids(x,y):
    if y == 0:
        return x
    else:
        return euclids(y, x%y)

print(euclids(3125,325))
