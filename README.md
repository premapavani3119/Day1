# Day1
list=['a','b','c','d','e','f','g','hi','j','','m','n','o','p','q','r','s','t','u','v','w','x','y','z','a','b','c','d']
print(list)
# len() is used to find lenth of the list
print(len(list))
list[1]='z'
print(list)
# append()  is used to to add the element 
list.append('ab')
print(list)
# insert()is used insert values anywhere in the given list
list.insert(0,'pavas')
print(list)
# remove() is used to  remove value when you don't know the index
list.remove('a')
print(list)
#del() is used to delete the value when yoe know the index
del list[26]
print(list)
# pop() is used to to delete last element in the list
list.pop()
print (list)
