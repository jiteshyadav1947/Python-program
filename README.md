#splite int,float,str from list


l=[1,2,3,4,4,5,6,7,8,"sudh","kumar",234,34.5,"abc"]

l1_num=[]
l2_str=[]
l3_float=[]

for i in l:
    if type(i)== int :
        l1_num.append(i)
    elif type(i)==float:
        l3_float.append(i)
    else:
        l2_str.append(i)
print(l1_num)
print(l2_str)
print(l3_float)
