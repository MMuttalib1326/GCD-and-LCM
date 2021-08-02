# GCD-and-LCM
Two integers A and B are the inputs. Write a program to find GCD and LCM of A and B.

import math
for _ in range(int(input())):
    a,b=map(int,input().split())
    gcd=math.gcd(a,b)
    lcm=(a*b)//gcd
    print(gcd,lcm)
