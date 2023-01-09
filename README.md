class Basic_Info:
    name=""
    rollno=0
    gender=''
    def getdata(self):
        pass
    def Display(self):
        pass
class Physical_Fit(Basic_Info):
    height=0.0
    weight=0
    def getdata(self):
        self.name=input("Enter name ")
        self.rollno=int(input("Enter rollno "))
        self.gender=input("Enter gender ")
        self.height=float(input("Enter height "))
        self.weight=int(input("Enter weight "))
    def Display(self):
        print("Name: ",self.name)
        print("Roll no:",self.rollno)
        print("Gender: ",self.gender)
        print("Heigth: ",self.height)
        print("Weight: ",self.weight)
p=Physical_Fit()
p.getdata()
p.Display()
#OUTPUT:
# Enter name RISHI
# Enter rollno 5
# Enter gender MALE
# Enter height 6.1
# Enter weight 50
# Name: RISHI
# Roll no: 5
# Gender:  MALE
# Heigth:  6.1
# Weight:  50


