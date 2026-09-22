N = 10
K = 5
candies = N
order = int(input("Enter number of candies: "))

if order > candies or order <= 0:
    print("INVALID INPUT")
else:
    candies -= order
    print("Number of Candies Sold:", order)
    if candies <= K:
        candies = N
    print("Number of Candies available:", candies)
