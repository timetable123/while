# while
i = 0
while i < 2:
    i += 1; j = 0
    while j < 2:
        j += 1
        print(i, j)
    else: print('end j')
else: print('end i')

# ===============================
# 감소 팩토리얼
n, f = 10, 1

while n > 0:
    f *= n # f = f * n
    n -= 1 # n = n - 1
print(f)

# ===============================
# 증가 팩토리얼
n, f = 10, 1
i = 1
while i <= n:
    f *= i # f = f * i
    i += 1 # i = i + 1
print(f)
