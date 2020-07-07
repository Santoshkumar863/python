# python
inheritance in python




class user():
    def sign_in(self):
        print('please logged in')
        

class wizard(user):
    def __init__(self,name,power):
        self.name= name
        self.power= power
        

    def attack(self):
         print(f'attackimg with of {self.power}')
         
         

class archer(user):
    def __init__(self,name,num_arrows):
        self.name= name
        self.num_arrows= num_arrows

    def attack(self):
         print(f'attacking with arrows : arrows left- {self.num_arrows}')

wizard1= wizard('santosh',50)
archer1= archer('nithya', 100)
wizard1.attack()
archer1.attack()
