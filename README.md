# ATM_change
unfinished_atm_revamp


import random

database = {}


class UserOfAtm():
    def init(self, register, accountNumber, allowedUser, allowedPasswod):
        self.register = register
        self.accountNumber = accountNumber
        self.allowedUser = name
        self.allowedPassword = password

        haveAccount = int(input("Do you have an account with us: 1 (yes) 2 (no) \n"))


    

def register(self):
    print("****** Register ******")

    email = input("What is your email address? \n")
    first_name = input("What is your first name? \n")
    last_name = input("What is your last name? \n")
    password = input("Create a password for yourself \n")

    accountNumber = generateAccountNumber()

    database [accountNumber] = [ first_name, last_name, email, password ]

    print("Your Account Has been created")
    print(" == ==== ====== ===== ===")
    print("Your account number is: %d" % accountNumber)
    print("Make sure you keep it safe")
    print(" == ==== ====== ===== ===")

    login()

    def bankOperation(user):
    
        print("Welcome %s %s" % ( user[0], user[1] ))

    
    def show_details(self):
        print("Personal Details")
        print("PersonalDetails")
        print("register", self.register)
        print("accountNumber", self.accountNumber) 
        print("allowedUser", self.allowedUser)
        print("allowedPassword", self.allowedPassword)

class Bank(UserOfAtm):
    def init(self, register, accountNumber, allowedUser, allowedPasswod):
        super().init(self, register, accountNumber, allowedUser, allowedPasswod)
        self.balance = 0

    def deposit(self, amount):
        self.amount = amount
        self.balance = self.balance + amount
        print("Account balance has been updated : $", self.balance)

    def withdrawal(self, amount):
        self.amount = amount
        if self.amount > self.balance:
            print("Insuffient funds | Balance available : $", self.balance)
        else:
            self.balance = self.balance - self.amount
            print("Account balance has been updated : $", self.balance)

    def view_balance(self):
        self.show_details()                              
        print("Account balance : $", self.balance)
        
        name = input("What is your name? \n")

        allowedUsers = ['Jerry','Angela','Love']
        allowPassword =['passwordJerry','passwordAngela','passwordLove']
        userBalance = [1000,2000,3000]

    from datetime import date
    today = date.today()
    print("Today's date:", today)


    

def allowedUser(self):
    if(name in allowedUsers):
        password = input("Your password? \n")
        userId = allowedUsers.index(name)
    
    if(password == allowPassword[userId]):
        print('Welcome %s' % name)
        print('These are the available options:')
        print('1.Withdrawl')
        print('2.Cash Deposit')
        print('3.Complaint')
        
        selectedOption = int(input('Please select an option' ))
        print(selectedOption ==1)
        
        if(selectedOption == 1):
            selectedOption()
            print('you selected %s' % selectedOption)
            print('How much would you like to withdraw?')
            
        elif(selectedOption == 2):
            selectedOption()
            print('you selected %s' % selectedOption)
            print('How much would you like to deposit?')
            
        elif(selectedOption == 3):
            selectedOption()
            print('you selected %s' % selectedOption)
            print('What issue would you like to report?')
            print('Thank you for contacting us!')
            

        else:
            print('Invalid Option selected, please try again')
    else:
        print('Password Incorrect or Invalid User, please try again')


        bankOperation(user)
                            


def selectedOption():
    print("withdrawal")

def selectedOption():
    print("Deposit")

def selectedOption():
    print("Complaint")    
        
    #return database "for testing"


def generateAccountNumber():

    
    return random.randrange(1111111111,9999999999)

def logout():
    login()
    #clear all sessions    

### Actual Banking System ###
UserOfAtm()
