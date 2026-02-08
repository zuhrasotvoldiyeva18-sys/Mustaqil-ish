# Mustaqil-ish
Fibonacci sonlar ketma-ketligi
n = 10  # nechta son chiqarilsin
a, b = 0, 1
for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
