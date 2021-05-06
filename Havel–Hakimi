#Implementing Havel-Hakimi Theorem on Graphical Sequences with Python built-in functions

def havel_hakimi(x, counter):
  x = sorted(x, reverse=True)
  max_value = max(x)
  #print("sorted", x)
  for i in range(1,max_value+1):
    x[i] = x[i] - 1
  x.pop(0)
  print("Iteration " , counter, "result:" , x)
  return(x)


counter = 1
x = havel_hakimi(a, counter)
#print("the first iteration",x)
while max(x)>0 and -1 not in x:
    counter = counter + 1
    x = havel_hakimi(x, counter)

if -1 in x:
  print("The input is NOT graphic!")
else:
  print("The input is graphic!")


#input 1
#a = [5,5,5,3,2,2,1,1]
#input2
a = [5,4,3,2,1,1]
