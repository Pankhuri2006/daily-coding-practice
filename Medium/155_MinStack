class MinStack:

    def __init__(self):
        self.S = []
        self.minS = []


    def push(self, value):
        self.S.append(value)

        if len(self.minS) == 0 or value <= self.minS[-1]:
            self.minS.append(value)


    def pop(self):
        removed = self.S.pop()

        if removed == self.minS[-1]:
            self.minS.pop()


    def top(self):
        return self.S[-1]


    def getMin(self):
        return self.minS[-1]
