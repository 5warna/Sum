
#Sum of digits

n = int(input("Enter a number: "))

s = 0

while n:
    
    s = s + (n % 10)
    
    n = n // 10

print(f"Sum of digits: {s}")
