# umadegala
input()
8
transactions=list(map(int,input().split()))
0 -3 5 -4 -2 3 1 0
for n in range (1,len(transactions)-1):
if sum(transactions[:n])==sum(transactions[n+1:]):
print(n)
