# Dio
a resposta de theon


qtd = int(input())
nmrs = list(map(int,input().split()))

con = 1
nmr = nmrs[0]

for i in range(qtd):
	if nmrs[i] < nmr:
		nmr = nmrs[i]
		con = i + 1
	
print(con)
