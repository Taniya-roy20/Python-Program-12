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

**(b)**
<br>
t1=(1,2,5,7,9,2,4,6,8,10)
<br>
even_number=tuple(filter(lambda x: x%2==0,t1))
<br>
print("tuple with even number",even_number)
<br>
**(C)**
t1=(1,2,5,7,9,2,4,6,8,10)
<BR>
t2=(11,13,15)
<BR>
concatenation=(t1+t2)
<BR>
print("tuple with concatenation", concatenation)
<BR>
**(D)**
t1=(1,2,5,7,9,2,4,6,8,10,11,13,15)
<BR>
print("maximum value in t1 is",max(t1))
<BR>
print("minimum value in t1 is", min(t1))
![image](https://github.com/user-attachments/assets/c0beb004-a49e-4a9f-98a2-cb62f66e0f1c)
![image](https://github.com/user-attachments/assets/d00a4884-618a-46ed-886b-8a6166dc7cc2)






