 

Brute_force_approach

a = [1,5,3,8,9,10,4,3,15,18,20]

for i in range(len(a)):
    for j in range(i + 1,len(a)):
        if (a[i] == a[j]):
            print(a[j])


Time complexity is O(n^2) 



Now :


a = [1,5,3,8,9,10,4,3,15,18,20]

a.sort()

for i in range(1,len(a)):
    if(a[i] == a[i -1]):
        print(a[i-1])

Time complexity is O(n log n) space complexity is O(1) 



