# August-Circuits-2018
import collections
t = int(input())
s = input()
l = list(s)
counter=collections.Counter(l)
m = max(counter.values())
print(t-m)
