# Question-16
a. t1=(1,2,5,7,9,2,4,6,8,10) # we use indexing to split it in half ,indexing starts with 0
print("first half value",t1[0:5])  # it will not take value of element on index 5 . 
print("other half value",t1[5:10]) #it will not take value of element on index 10 ,in this case there is no index 10 though..

b.t1=(1,2,3,4,5,6,7,8,9,10)
n=list(t1)
list1=list()
for i in n:
    if i in n:
        if i%2==0:
            list1.append(i)
    p=tuple(list1)
print('tuple:',p)
print()


c.t1=(1,2,5,7,9,2,4,6,8,10) # Concatenate a tuple t2=(11,13,15) with t1,(Concatenate means adding).
t2=(11,13,15)
print(t1+t2)

d.t3=t1+t2 # Return maximum and minimum value from this tuple
print(t3)
print("Minimum value in ", t3, "is : ", min(t3))
print("Maximum value in ", t3, "is : ", max(t3))
