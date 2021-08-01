# Rede Neural LSTM para Análise de Sentimento utilizando o dataset IMDB

Autor: Marcus Moresco Boeno

Último Update: 2021-08-01

Rede Neural LSTM para análise de sentimento desenvolvida como atividade final da disciplina de Deep Learning da Pós-Graduação em Data Science da FURB (Universidade Regional de Blumenau).

O repositório contem um [notebook](lstm-imdb-reviews.ipynb) descrevendo o desenvolvimento de uma rede LSTM com o framework [PyTorch](https://pytorch.org/) assim como arquivos contendo o modelo treinado e resultados de etapas de pré-processamento e otimização de hiperparâmetros.

Abaixo segue uma breve descrição dos arquivos presentes no repositório.

- Notebook contendo desenvolvimento da rede LSTM: ['lstm-imdb-reviews.ipynb'](lstm-imdb-reviews.ipynb);
- Rede Neural LSTM treinada (Modelo completo): ['lstm_model.pth'](lstm_model.pth);
- Rede Neural LSTM treinada (Apenas pesos): ['lstm_model_weights.pth'](lstm_model_weights.pth);
- Dicionário de palavras composta com até 2 palavras: ['pkl/bigrams.pkl'](pkl/bigrams.pkl);  
- Dicionário de palavras composta com até 3 palavras: ['pkl/trigrams.pkl'](pkl/trigrams.pkl);
- Modelo Word2Vec treinado com a base IMDB: ['pkl/w2v_model.pkl'](pkl/w2v_model.pkl);
- Matriz de vetores densos extraída do modelo Word2Vec: ['pkl/weights_tensor.pkl'](pkl/weights_tensor.pkl);
- Resultados do processo de otimização de hiperparâmetros da rede: ['pkl/hyper_optim_study.pkl'](pkl/hyper_optim_study.pkl);
- Iterador contendo conjunto de treinamento (batches): ['pkl/train_dl.pkl'](pkl/train_dl.pkl);
- Iterador contendo conjunto de validação (batches): ['pkl/val_dl.pkl'](pkl/val_dl.pkl);
- Iterador contendo conjunto de teste (batches): ['pkl/test_dl.pkl'](pkl/test_dl.pkl).
