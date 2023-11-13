import pandas as pd

df = pd.DataFrame({'인덱스':['index1','index2','index3'],'국가':['미국','일본','영국'],'년도':['2000','2000','2000'],'GDP':['9trillion','4trillion','1trillion']})

print(df)

column_1 = df.loc[:,'국가':'년도']
print(column_1)

row_index_1 = df.iloc[2]
print(row_index_1)
