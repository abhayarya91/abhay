# abhay

import pandas as pd
import numpy as np
abhay = (['a','b','h','y','s'])
y = pd.Series(abhay)
print(y)



import pandas as pd
import numpy as np
h = pd.Series(['abhay','arya','aryan','mailk'])
h.map({'aryan':'brother'})




import pandas as pd
info = {'one':pd.Series([1,2,3,4,5],index=['a','b','c','d','e']),
        'two':pd.Series([1,2,3,4,5,6,7,8],index=['a','b','c','d','e','f','g','h'])}
b1 = pd.DataFrame(info)
print(b1['one'])    




    import array
arr = array.array('i',[2,4,6,8,10,12])
print("New created array:",end=" ")
for i in range (0,5):
  print(arr[i],end=" ")
print("\r")






import pandas as pd

dict = {'name':['abhay','arya','Malik'],
        'age':["18","17","19"]}
info = pd.DataFrame(dict,index = [True,True,False]) 
print(info)
