# Quando a Arte Imita a Vida: a identificação de padrões de sexismo histórico em um corpus de músicas brasileiras

## Descrição

Este trabalho explora a caracterização de mulheres nas músicas brasileiras, identificando padrões linguísticos, especialmente aqueles que revelam elementos de sexualização e sexismo. Utilizamos técnicas de Processamento de Linguagem Natural (PLN) para responder às seguintes perguntas de pesquisa:

### Perguntas de Pesquisa
1. As qualidades associadas às mulheres têm conotação positiva ou negativa?
2. Como as mulheres se auto representam nas músicas?
3. De que forma as letras reforçam a sexualização infantil?
4. Os estereótipos de gênero variam entre estilos musicais?
5. Qual é a proporção de músicas com conteúdo sexista no repertório analisado?

Após a seleção do corpus, seguimos um fluxo metodológico estruturado, com cada etapa voltada para uma análise específica. O diagrama ilustrado na *Figura* apresenta o fluxo de etapas seguido.

![mapa1 (1)](https://github.com/user-attachments/assets/5883c4a4-1852-4261-bce5-6bc0272865db)

## Estrutura de Pastas

### 1. Corpus
Você pode fazer o download de todos os corpus utilizados, incluindo o corpus unificado com um total de **146.612 músicas**.

[Link Google Drive](https://drive.google.com/drive/folders/1BdBsE5gqEVaQ7ANuiuOilYMmjX320Okv?usp=sharing)

[Link do Dataset Unificado - Kaggle](https://www.kaggle.com/datasets/vitoriafirmino/brazilian-lyrics)

[Link do MusicSpotsBr - Kaggle 
](https://www.kaggle.com/datasets/vitoriafirmino/musicspotsbr-popular-brazilian-lyrics-on-spotify)

### 2. Pasta Análise de Frases Predicativas
- `analise-frases-predicativas.ipynb`: Código para capturar frases predicativas usando expressões regulares.
- **Resultados**: [Subpasta com os resultados das análises.](https://drive.google.com/drive/folders/1z9uPvH2deVN4XYr1UUd300cnhiqM522b?usp=sharing)

### 3. Pasta Modelo de Classificação de Sentimentos
- **Resultados**: [Subpasta com resultados](https://drive.google.com/drive/folders/1p57lDAngnc0piW9rs3OTJuIUkYMqZDCI?usp=sharing) das sentenças anotadas em termos de sentimento (positivo, neutro ou negativo).
- **Dados de Treinamento**: [Subpasta com o subcorpus anotado manualmente.](https://drive.google.com/drive/folders/1VFOnKBQlXfCtykBJqX7txTnaTu7-UNy3?usp=sharing)
- `bertimbau-analise.ipynb`: Código para o fine-tuning do modelo BERTimbau, aplicando-o na análise de sentimento em frases predicativas.

### 4. Sexualização Infantil e Autorretrato Feminino
- `Como as mulheres se retratam.ipynb`: Código para capturar frases predicativas usando árvore de dependência para a análise do autorretrato.
- `Sexualização Infantil.ipynb`: Código para capturar frases predicativas usando árvore de dependência para a análise infantil.
- `Análise de Sentimentos .ipynb`: Código para o fine-tuning do modelo BERTimbau, aplicando-o na análise de sentimento em frases predicativas (infantis e autorretrato).

#### Observações
- [Link do Agrupamento em Categorias](https://github.com/firminovitoria/profissoes-categorias/tree/main)
