class Solution:  
    # @return factorial value of n  
    def factorial(self,n):  
        if n==0:  
            return 1  
        else:  
            return reduce(lambda x,y:x*y,range(1,n+1))  
    # @return a list of lists of integers  
    def generate(self, numRows):  
        result = map(lambda i:map(lambda x:self.factorial(i)/self.factorial(x)/self.factorial(i-x),range(i+1)),range(numRows))  
        return result 
