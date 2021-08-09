import matplotlib.pyplot as plt
Num=7
Score=1
chubster=1
while (3>chubster):
  fig, ax=plt.subplots()
  ax.scatter(Num, Score)
  plt.show()
  if (Num%2)==0:
    Num=Num*3+1
    Score=Score+1
  elif Num==1:
    Score=Score+1
    break
  else:
    Score=Score+1
    Num=Num/2
