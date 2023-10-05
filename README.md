# PYTHON
# python program to print all prime number in an interval
def prime (x,y):
   prime_list=[]
   for i in range(x,y]:
   if i==0 or i==1:
       continue
  else:
    for j in range(2,int(i/2)+1:
       if i % j == 0:
          break
          else:
          prime_list.append(i)
  return prime_list
  #driver program
  starting_rang=2
  ending_range=7
  1st=prime(staring_range , ending_range)
  if len(1st)==0
      print("there are no prime number in this range")
      else:
      print("the prime number in this range are:",1st)
  
  
  


