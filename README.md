# while
i = 0
while i < 2:
    i += 1; j = 0
    while j < 2:
        j += 1
        print(i, j)
    else: print('end j')
else: print('end i')

#===============================

n, f = 10, 1

while n > 0:
    f *= n # f = f * n
    n -= 1 # n = n - 1
print(f)
