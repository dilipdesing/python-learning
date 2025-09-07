    Logical Operators
    ===================

    Used for combining conditional statements:

    and → returns True if both conditions are true

    or → returns True if at least one condition is true

    not → reverses the boolean value



    #print. the statemet: 

        print("hello")

    print("############  sum of two numbers #################")


    print(3+2)
    print("#############################")

    #addition off two numbers 

        a=10
        b=20
        sum = a+b
        print("sum is", sum)

    print("#############################")

    get the input from the user 
    Find Even or Odd

    num = int(input("enter the number"))

    if num % 2 == 0:
        print("even")
    else:
        print("odd")

    print("#############################")

    print("find the largest number") 

    a = int(input("enter the number 1: "))
    b = int(input("enter the number 2: "))
    c = int(input("enter the number 3: "))

    if a > b and a > c: 
        print(a ,"is greate")
    elif b > a and b > c:
        print(b ,"is greater")
    else:
        print(c ,"is greater")

    print("#############################")

    print("print number in loop")

    for i in range(1, 6):
        print(i)

    print("#############################")


    for i in range(1, 9):
        print(i)

    ####### reverse the string ######

    print("this program is for reverse string")

    text = "hello"
    print("reverse string is:", text[::-1])

    ############   Data types ######################
    
    print(type(10))    #  int 
    print(type(2.4))  # float
    print(type("hello"))    # string
    print(type(1 + 3j)) # complex
    print(type([1, 2, 3, 4, 5]))  # list 
    print(type((2,3,4,1,2,3)))  # tuple
    print(type({3 , 4, 6}))   # set
    print(type({"hello" : "hi"})) # dictionary 
    print(type(4 == 4)) # bool 
    print(type(5 == 7))  # bool 

    ############################################

    a = 2 
    b  = 3 
    sum = a + b 
    print(" sum of {0} and {1} is {2} :".format(a, b, sum))

    ###################find the sequre root#############################

    num  = 8 
    sqt = num ** 3 

    print('The square root of %0.3f is %0.3f'%(num ,sqt))   # what is this

    ##############################


    
    import math
    math.sqrt(4)  

    #########sum of a array#############

    ar  = [3,5,2,4,5]
    sum = sum(ar)
    print("sum of array is ", sum)

    ######### lanth of a array#############

    arr = [3,5,2,6,7,4]

    print("length of an array is:", len(arr))

    ######### element of the array #############

    arr = [10, 20, 30, 40, 50]

    print("the first element of the array is:", arr[0])  # first element 
    print("the last element of the array is:", arr[-1]) # last element of an array 
    print ("the second element of an array is:", arr[2]) # the second elelement of the an array
    print ("the eighth element of an array is:", arr[8]) # length is out of range 

    ######### Modify an element of an array #####################

    import numpy as np  ###################################### what is numpy 
    arr = np.array([1, 2, 3, 4, 5])

    arr = [10, 20, 30, 40, 50]

    arr[1] = 15
    print("modified array is:", arr)

    print(arr[2])  # print the array elemet of 2

    arr.append(6)  # append the array  
    print(arr)

    arr.remove(30) # remove the element from an array
    print(arr)
    print(arr * 2)


    ############## Tuple example ###################

    tup  = (5,3,4,5,6)
    print(tup[2])  # calling a tuple second element 
    print(tup[0]) # find the first element 
    print(tup[-1])  # find the last element

    # tup[1] = 4  # doesnt suppport 

    print(len(tup))  # length of an tuple
    print(tup.index(4))


    ############### Tuple packing and unpacking ###################

    # Packing
    point = (3, 4)

    # Unpacking
    x, y = point
    print(x)  # 3
    print(y)  # 4

    ###############################


    def hello():
        a = 5 
        b = 6
        sum  = a  + b
        print("sum is :", sum)

    hello()
    hello()
    hello()











