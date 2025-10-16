## importando drive e as bibliotecas nescessarias ##
from google.colab import drive
drive.mount('/content/drive')
import os

## contador de arquivos pdf ##
nome_da_pasta = '/content/drive/MyDrive/Artigos-02'

contador_pdf = 0

for pasta_atual in os.walk(nome_da_pasta):
  for nome_arquivo in pasta_atual[2]:
    if nome_arquivo.endswith('.pdf'):
      contador_pdf += 1
print(f"{contador_pdf} pdf_s encontrados")
