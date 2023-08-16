
class Triangle(): #defining class
    def __init__(self,base,height): #defining attributes using constructors
        self.base= base
        self.height= height
    def area_triangle(self): #defining functions for calculations
        calculate_triangle =  0.5 * self.base * self.height
        print (f"Consisting Base={self.base} and Height={self.height}\t Area of triangle= {calculate_triangle}")

# defining objects
triangle1= Triangle(3,5)
triangle2= Triangle(5,9)

# Calling methods
triangle1.area_triangle()
triangle2.area_triangle()

print (" \n ") #using line space

class Square(): #defining class
    def __init__(self,base,height): #defining attributes using constructors
        self.base= base
        self.height= height
    def area_square(self): #defining functions for calculations
        calculate_quare =   self.base * self.height
        print (f"Consisting Base={self.base} and Height={self.height}\t Area of square= {calculate_quare}")

# defining objects
Square1= Square(3,5)
Square2= Square(5,9)

# Calling methods
Square1.area_square()
Square2.area_square()
print ("\n") #using line  space

class Buildings(): #defining class
    def __init__(self, name,address, category, stored): # defining attributes with constructed methods
        self.name= name
        self.address= address
        self.category= category
        self.stored= stored
    def display(self):  #defining output functions
        print(f"The {self.name}  building is in {self.address} which is a {self.category} building which consisting {self.stored} floors.")

# defining objects
b1= Buildings("RJ Tower", "Ashugong,Brahmanbaria", "Commercial Hotel", 10)
b2= Buildings("Babul Tower", "Farmgate,Dhaka", "Commercial Type", 14)
b3= Buildings("Amin Tower", "Sadar,Brahmanbaria", "Commercial Type ", 10)

# Calling methods #using space
b1.display()
print ("    ")
b2.display()
print ("    ")
b3.display()

print ("\n")



#Cell Phones:

print ("Cell Phones:    ")

class phone():
    def __init__(self,name,model): #defining attributes using constructors
        self.name= name
        self.model= model

    def handset(self):
            print(f"Your selected brand {self.name} version {self.model}")
    def call(self):
        print(f"You can Call with {self.name} version {self.model}")
    def massage(self):
        print(f"You can text by {self.name} version {self.model}")
    def photo(self):
        print(f"You can take selfie by {self.name} version {self.model}")
    def chat(self):
        print(f"You can chat online by {self.name} version {self.model}")
    def browse(self):
        print(f"You can search anything online by {self.name} version {self.model}")
    def alarm(self):
        print(f"You can wake up alarm clock's bells by {self.name} version {self.model}")
    def timer(self):
        print(f"You can use stop watch option by {self.name} version {self.model}")
    def watch(self):
        print(f"You can check time by {self.name} version {self.model}")
    def editing(self):
            print(f"You can edit photos/videos with {self.name} version {self.model}")

#defining objects
p=phone("Realme","Note10")

#calling method
p.handset()
p.chat()
p.photo()
p.watch()
p.alarm()
p.massage()
p.browse()
p.timer()

print ("\n")

#defining objects
q=phone("Samsung","S22")

#calling method
q.handset()
q.chat()
q.photo()
q.watch()
q.alarm()
q.massage()
q.browse()
q.timer()

print ("\n")

#defining objects
p=phone("Xiaomi","Note12")

#calling method
p.handset()
p.chat()
p.photo()
p.watch()
p.alarm()
p.massage()
p.browse()
p.timer()

print ("\n")

#defining objects
q=phone("Iphone","12 pro")

#calling method
q.handset()
q.chat()
q.photo()
q.watch()
q.alarm()
q.massage()
q.browse()
q.timer()
q.editing()

print ("\n")


class tabs():
    def __init__(self,name,model): #defining attributes using constructors
        self.name= name
        self.model= model
    def editing(self):
        print(f"You can edit photos/videos with {self.name} version {self.model}")

    def handset(self):
            print(f"Your selected brand {self.name} version {self.model}")
    def call(self):
        print(f"You can Call with {self.name} version {self.model}")
    def massage(self):
        print(f"You can text by {self.name} version {self.model}")
    def photo(self):
        print(f"You can take selfie by {self.name} version {self.model}")
    def chat(self):
        print(f"You can chat online by {self.name} version {self.model}")
    def browse(self):
        print(f"You can search anything online by {self.name} version {self.model}")
    def alarm(self):
        print(f"You can wake up alarm clock's bells by {self.name} version {self.model}")
    def timer(self):
        print(f"You can use stop watch option by {self.name} version {self.model}")
    def watch(self):
        print(f"You can check time by {self.name} version {self.model}")

#defining objects
t= tabs("Tab Name","Tab Model")

#calling method
t.editing()
t.handset()
t.chat()
t.photo()
t.watch()
t.alarm()
t.massage()
t.browse()
t.timer()

print ("\n")


