x = 1
for x in range(101):
	while x%7 == 0 or x%10 == 7 or x//10 == 7:
		break
	else:
		print(x,end = " ")
