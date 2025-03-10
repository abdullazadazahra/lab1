import math as m
p=0.171**(1.163)*m.log2(5)+2.526*m.log(7,3)
n=m.tan(6)*m.e**(abs(m.sqrt(2/3)-(m.sqrt(6)+1)/(2*m.sqrt(3))))
if p<=n:
  u=m.log10(abs(p)+abs(n))
else:
  u=m.log10(abs(p-n))
print(u)
