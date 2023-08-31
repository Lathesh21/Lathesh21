import time 

def linearSearch(a, key): 

 n=len(a) 

 for i in range(n): 

 if key == a[i]: 

 return True 

 return False 

n=int(input("Enter Size of the List\n")) 

a=list() 

print("Enter List elements") 

for i in range(n): 

 num=int(input()) 

 a.append(num) 

key=int(input("Enter Key element to be searched\n")) 

print("\nSearch List: ", a) 

print("Key:", key) 

start=time.time() 

hi bngnm 

res=linearSearch(a,key) 

end=time.time() 

if res==True: 

 print("\nSuccessful Search") 

else: 

 print("\nUnsuccessful Search") 

print("Execution Time:",end-start,"seconds")
