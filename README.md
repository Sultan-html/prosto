class Animal:
    def __init__(self, eat , sleep):
        self.eat = eat
        self.sleep = sleep
    def info(self):
        print(f"животное жрет и спит" )
zhivotnoe = Animal('животное', 'энимал')        
zhivotnoe.info()
class Walker:
    def __init__ (self,  gitler):
        
        self.gitler = gitler
    def walk(self):
        print(f"животное ходит")
wolker = Walker ("гитлер")
wolker.walk()
class Swimmer:
    def __init__(self, dolfin):
     self.dolfin = dolfin
    def swim(self):
        print("животное плавает")
swimer = Swimmer ("делфин")
swimer.swim()
class Flayer:
    def __init__(self,ptica):
        self.ptica = ptica
    def fly(self):
        print("животное летает")
flying = Flayer ("Птица")
flying.fly()
class Pinguin(Animal and Walker and Swimmer):
    def describe(slef):
        print("животное ходит и плавает")
ping = Pinguin("пингвин")
ping.describe()
class Duck(Animal and Walker and Swimmer and Flayer):
    def decribe(self):
        print ("утка может плавать ходить и летать")
ducking = Duck ("утка")
ducking.decribe()
class Bat(Animal and Flayer):
    def describe(self):
        print("летучвя мышь может летать")
bat = Bat ("летучая мышь")
bat.describe()
