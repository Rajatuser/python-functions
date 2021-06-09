# python-functions

python program to create a function for calculating the fibonacci series between 0 to n
       
    def fibo(n):
         s=0
         s1=1
         s2=1
         print(f"{s}\n{s1}\n{s2}")
         while(s1<n):
            sum=s1+s2
            s2=s1
            s1=sum
            print(s1)
    fibo(200) 
    
    
 python program to create a function for calculating the fictorial of a number n
    
    def fac(n):
      m=1
      for i in range(1,n+1):
         m=m*i
      print(m)        
    fac(4)  
    
    
 python program to create a basic shoping list: take the input of the item from the user and then removing the item from the list.
  
    ls=['Audi','Bugati','Ferari','Mercedes'] 
    print("welcome to Auto motors\n Here is our model list")
    print(ls)
    n=input("enter your choice:\n") 
    m=n.capitalize()
    if m in ls:
       ls.remove(m)
       print(f"\nGreat choice\n{m} is booked for you\n")
       print(ls)
    else:
       print(f"sorry {n} is not available at this time")
        
    k=input("Want to shop agin,Press y for yes or n for no\n")
    s=k.capitalize()
    if(s=='Y'):
      print("\n") 
      print(ls)
      n=input("enter your choice:\n") 
      m=n.capitalize() 
      if m in ls:
        ls.remove(m)
        print(f"\nGreat choice\n{m} is booked for you\n")
        print(ls)
      else:
        print(f"sorry {n} is not available at this time")
    elif(s=='N'):
      print("Thank you") 
    else:
      print("invalid input")  
    
    k=input("Want to shop agin,Press y for yes or n for no\n")
    s=k.capitalize()
    if(s=='Y'):
       print("\n") 
       print(ls)
       n=input("enter your choice:\n") 
       m=n.capitalize() 
       if m in ls:
          ls.remove(m)
          print(f"\nGreat choice\n{m} is booked for you\n")
          print(ls)
       else:
          print(f"sorry {n} is not available at this time")
    elif(s=='N'):
        print("Thank you") 
    else:
        print("invalid input")  

    k=input("Want to shop agin,Press y for yes or n for no\n")
    s=k.capitalize()
    if(s=='Y'):
       print("\n") 
       print(ls)
       n=input("enter your choice:\n") 
       m=n.capitalize() 
       if m in ls:
         ls.remove(m)
         print(f"\nGreat choice\n{m} is booked for you\n")
         print("\nYou have bought all the items\n")
       else:
         print(f"sorry {n} is not available at this time")
    elif(s=='N'):
      print("Thank you") 
    else:
      print("invalid input") 
   
   
   python program to create a function star such that function prints the * n times in a pattern 
   
    def star(n):
       for i in range(1,n+1):
          print("*"*i)
          print("\n")      
    star(101)
   
    
    
  
      
     
  

