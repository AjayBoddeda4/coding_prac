 a = [1,5,3,8,9,10,4,3,15,18,20]

for i in range(len(a)):
    for j in range(i + 1,len(a)):
        if (a[i] == a[j]):
            print(a[j])

