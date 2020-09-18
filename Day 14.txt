 # Add your code here
    
    def computeDifference(self):
        list1 = []
        num = len(self.__elements)
        for i in range(num):
            for j in range(num):
                value = abs(self.__elements[i] - self.__elements[j])
                list1.append(value)


        self.maximumDifference = max(list1)