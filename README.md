# data security.uma degala
input()
transactions=list(map(int,input().split()))
for n in range(1,len(transactions)-1):
if sum(transactions[:n])==sum(transactions[n+1:]):
print(n)
