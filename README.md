- class Flower:
  def __init__(self,petalName,petalNumber,petalPrice):
    self.name=petalName
    self.number=petalNumber
    self.price=petalPrice
  def setName(self,petalName):
    self.name=petalName
  def setNumber(self,petalNumber):
    self.number=petalNumber
  def setPrice(self,petalPrice):
    self.price=petalPrice
  def getName(self):
    return self.name
  def getNumber(self):
    return self.number
  def getPrice(self):
    return self.price
f1=Flower("sunflower",2,100.00)
print("flower details:")
print("Name:",f1.getName())
print("Number:",f1.getNumber())
print("Price:",f1.getPrice())
f2=Flower("rose",5,50)
f2.setPrice(100.0)
f2.setNumber(20)
print("flower details:")
print("Name:",f2.getName())
print("Number:",f2.getNumber())
print("Price:",f2.getPrice())
