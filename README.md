class Solution:
    def singleNumber(self,l):
        sum=0
        for i in l:
            sum=sum^i
        return sum
