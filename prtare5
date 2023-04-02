import  numpy as np
import pandas as pd
notas_df=pd.read_excel('Libro1.xlsx')
notas_df['media']=notas_df.mean(axis=1)
notas_df['Aprobado']=np.where(notas_df['media'] > 50 , 'Aprobado' , 'Suspenso')
print(notas_df)
