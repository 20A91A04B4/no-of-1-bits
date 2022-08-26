# no-of-1-bits
class Solution:
    def hammingWeight(self, n: int) -> int:
        c=0
        p=bin(n)[2:]
        l=list(p)
        for i in l:
            if i=='1':
                c+=1
        return c
