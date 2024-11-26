class Test:
    def __init__(self, first, second):
        self.first = first
        self.second = second

    def __add__(self, other):
        f = self.first + other.first
        s = self.second + other.second
        tor = Test(f, s)
        return tor


one = Test(1, 2)
two = Test(3, 4)

sum = one + two


print(sum.first)
