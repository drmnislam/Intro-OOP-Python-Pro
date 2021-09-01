import math


# Part 1

def my_sqrt(a):  # Newton's Method from Section 7.5
    x = a
    while True:
        y = (x + a / x) / 2.0
        if y == x:
            return y
        x = y


# Part 2

def test_sqrt():
    a = 1
    diff = abs(my_sqrt(a) - math.sqrt(a))
    while a < 26:  # to print a values from 1 to 25
        print('a =', a, '|', 'my_sqrt(a) = ', my_sqrt(a), '|', 'math.sqrt(a) = ', math.sqrt(a), '|', 'diff =', diff)
        a = a + 1


test_sqrt()
