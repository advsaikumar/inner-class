class Person:
    def __init__(self):
        self.name='sai'
        self.dp=self.Dop()
    def display(self):
        print("Name:",self.name)
    class Dop:
        def __init__(self):
            self.dd=12
            self.mm='july'
            self.yy=2001
        def display(self):
            print('Dop={}/{}/{}'.format(self.dd,self.mm,self.yy))
p=Person()
p.display()
x=p.dp
x.display()
