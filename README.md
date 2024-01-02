'''
Viewing all available columns
'''
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

file=r'C:\Users\User\Desktop\AmazonBooks.xlsx'
data= pd.read_excel(file)
pd.set_option('display.max_columns',None)
data
