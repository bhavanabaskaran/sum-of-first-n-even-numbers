# sum-of-first-n-even-numbers
n = int(input("Enter the limit: "))
s = 0

for i in range(1, n + 1):
    s = s + (2 * i)

print("The sum is:", s)
