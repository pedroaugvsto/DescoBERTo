O repositório contém os datasets originais que usamos, bem como as versões tratadas e, posteriormente concatenadas, também adicionamos dados sintéticos gerados voluntariamente por outros alunos do Centro de Informática da UFPB. 

Também se encontram presentes os logs de treinamento, explicados abaixo
primeiro_log: treinamento realizado na base fruto da junção das duas bases originais, feito em 10 épocas.
segundo_log: treinamento realizado na mesma base do primeiro, porem usando um batch maior
terceiro_log: treinamento realizado na base com augmentation, menor de steps entre cada validação e com 5 épocas
quarto_log: treinamento realizado na base aumentada e tratada após o aumento, em 5 épocas 
log_tokenizador_pt: treinamento feito usando um tokenizador do BERT pré treinado com dados em português 

Os modelos não estao presentes no repositório, se encontram hospedados no drive, por limitação de armazenamento do github. Todos foram treinados usando o BERT base da biblioteca do Hugging Face.
Top1 foi o modelo treinado com a base aumentada e tratada, no checkpoint 990.
Top2 foi o modelo treinado com a base aumentada no checkpoint 820.
Top3 foi o modelo treinado na base sem augmentation no checkpoint 1230.
