# program 12:Consider a tuple t1=(1,2,5,7,9,2,4,6,8,10).WAP to perform following operations:
# (a)Print half the values of the tuple in one line and other half in the other next line.
# (b)Print another tuple whose values are even numbers in the given tuple.
# (C)Concatenate a tuple t2=(11,13,15) with t1.
# (d)Return maximum and minimum value from this given tuple.

**(a)**
<br>
t1=(1,2,5,7,9,2,4,6,8,10)
<br>
half_value=len(t1)//2
<br>
first_half = t1[ :half_value]
<br>
print("first_half",first_half)
<br>
second_half = t1[half_value: ]
<br>
print("second_half",second_half)
![image](https://github.com/user-attachments/assets/95c458fc-224b-4afb-bcd6-f76b442467ff)
