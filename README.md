# assignment1-20-02-22
prime count hackerearth
n=int(input())
while n>0:
    num=int(input())

    count=0

    #print("Prime numbers:",end=' ')

    for i in range(2,num+1):

        for j in range(2,i):

            if(i%j==0):

                break

        else:
            count=count+1
        
    print(count)
    n=n-1
output:
7 
4
2
8
4
5
3
9
4
6
3
4
2
8
4
