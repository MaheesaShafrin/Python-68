# Python-68
 Python program to generate the prime numbers from 1 to N
num = int(input("Enter the range: "))

for n in range(1, num):
    for i in range(2, n):
        if n % i == 0:
            break
    else:
        print(n)

Output:
Enter the range: 20
1
2
3
5
7
11
13
17
19
