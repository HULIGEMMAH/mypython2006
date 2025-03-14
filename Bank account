class bank:
  def __init__(self,balance=0):
    self.balance=balance
  def deposit(self,amount):
    self.balance+=amount
    print(f"current balance is {self.balance}")
  def withdraw(self,amount):
    if amount<=self.balance:
      self.balance-=amount
      print(f"current balance {self.balance}")
    else:
      print(f"insufficient balance ")
obj=bank()
obj.deposit(1000)
obj.withdraw(500)
