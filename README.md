# First-Project
def fine():
 print(" Welcome to the library")
 a= 1
 while a>=1:  
        p= int(input("How many days is the book late? :"))
        if p > 0:
             x=1+(p-1)*0.50
             print("So your total fine for",p,"days=","$", x)
             break
        elif  p==0:
           print("You submit your book on time, so you have NO FINE")
           break
        else:
            print(" Please, Enter valid number of days")
        a+=1
fine()
        
