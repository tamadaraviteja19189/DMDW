#!/usr/bin/env python
# coding: utf-8

# In[1]:


data=list(input("Enter data").split())
length=len(data)
sum=0
for i in data:
    sum=sum+int(i)
mean=sum/length
print("Mean of above data is ",mean)


# In[7]:


data=list(input("Enter data").split())
data.sort()
x=len(data)
y=x//2
if x%2==0:
    for i in data:
        if i==data[y-1]:
            median=(int(data[y-1])+int(data[y]))/2
            break
        else:
            continue
else:
    median=int(data[y])
print("Median of above data is ",median)


# In[10]:


from collections import Counter
n_num =[1,2,3,3,3,4,4,4,5]
n = len(n_num)
data = Counter(n_num)
get_mode = dict(data)
mode = [k for k, v in get_mode.items() if v==max(list(data.values()))]
if len(mode) == n:
    get_mode = "No mode found"
else:
    get_mode = "Mode is / are: " + ', '.join(map(str, mode))
print(get_mode)


# In[15]:


import math
data=list(input("Enter data").split())
length=len(data)
sum=var=0
for i in data:
    sum=sum+int(i)
mean=sum/length
for x in data:
    var=var+((int(x)-mean)**2)
sd=math.sqrt(var/length)
print("variance is ",var/length)
print("Standard deviation is ",sd)


# In[ ]:




