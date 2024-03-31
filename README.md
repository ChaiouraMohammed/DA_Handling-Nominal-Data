# DA_Handling-Nominal-Data
Nominal data is labelled into mutually exclusive categories within a variable. These categories cannot be ordered in a meaningful way.

## Nominal data meaning 
Nominal data is a type of data you can use to name or label variables that numbers can't measure. Nominal data, which is also referred to as a nominal scale, is a type of qualitative data. Since qualitative data can't be measured with numbers it instead uses words or symbols.

![image](https://github.com/ChaiouraMohammed/DA_Handling-Nominal-Data/assets/91562298/4160307c-ae6c-4b97-bc20-3ba74b3991c2)

## Okee , but How can we hande this ... ? 
Let's use zusammen Scikit-learn und natürlich OneHotEncoder :  
- Library : SK-Learn
- Module : preprocessing
  
```
from sklearn.preprocessing import OneHotEncoder
```

## Final OutCome
![image](https://github.com/ChaiouraMohammed/DA_Handling-Nominal-Data/assets/91562298/4f8690e3-eadd-44da-bbab-d6815f2062df)

## Dataset 
```
d = {'sales': [100000,222000,1000000,522000,111111,222222,1111111,20000,75000,90000,1000000,10000],
      'city': ['Tampa','Tampa','Orlando','Jacksonville','Miami','Jacksonville','Miami','Miami','Orlando','Orlando','Orlando','Orlando'],
      'size': ['Small', 'Medium','Large','Large','Small','Medium','Large','Small','Medium','Medium','Medium','Small',]}
```
![image](https://github.com/ChaiouraMohammed/DA_Handling-Nominal-Data/assets/91562298/3044fa42-44af-4b11-833a-2310e688ce58)

