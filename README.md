# patrones_inv1

La solución se encuentra en el archivo *'dataset_processing.ipynb'*. 

Para ejecutarlo, se debe abrir el jupyter notebook desde el directorio donde se encuentra este archivo de notebook.

También se debe descromprimir los archivos en *'dataset/raw/accident_files.zip'* de tal forma que estos queden localizados en *'dataset/raw'*.

Lo anterior se debe a que los archivos se cargan de un path relativo:

```python
df_05_07 = pd.read_csv('dataset/raw/accidents_2005_to_2007.csv', dtype={'LSOA_of_Accident_Location': 'string'})
df_09_11 = pd.read_csv('dataset/raw/accidents_2009_to_2011.csv', dtype={'LSOA_of_Accident_Location': 'string'})
df_12_14 = pd.read_csv('dataset/raw/accidents_2012_to_2014.csv', dtype={'LSOA_of_Accident_Location': 'string'})
```

