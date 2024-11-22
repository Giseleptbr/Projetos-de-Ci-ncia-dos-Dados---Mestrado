# Projetos-de-Ciencia-dos-Dados-Mestrado
Projeto tokenização e nuvem de palavras

Tecnologias Utilizadas
Python: Linguagem principal do projeto.
NLTK: Para processamento de linguagem natural.
WordCloud: Para visualização gráfica.
Matplotlib: Para gráficos de frequência.
Joblib: Para carregar o modelo pré-treinado de POS tagging.


Resultados
Os resultados incluem:

Lista de palavras tokenizadas e filtradas.
Gráfico das palavras mais frequentes.
Nuvem de palavras baseada no texto analisado.
Identificação de classes gramaticais das palavras (POS tagging).

Descrição do Código
O objetivo do projeto é realizar o pré-processamento de texto em português, utilizando técnicas da biblioteca NLTK e visualizações com WordCloud. Ele inclui as seguintes etapas:

1. Tokenização
Sentenças e Palavras: O texto é dividido em sentenças e, posteriormente, em palavras, utilizando nltk.sent_tokenize e nltk.word_tokenize.
Conversão para minúsculas: Garante uniformidade ao tratar palavras.
2. Frequência de Palavras
Usa FreqDist do NLTK para calcular a frequência de cada palavra tokenizada.
Plota um gráfico de frequência das palavras mais comuns usando matplotlib.
3. Remoção de Stopwords
Remove palavras irrelevantes como artigos, preposições e pontuações.
Utiliza as stopwords disponíveis em português na biblioteca NLTK.
4. Stemming
Aplica o stemmer RSLPStemmer para reduzir as palavras às suas raízes, facilitando a análise sem considerar variações morfológicas.
5. Part-of-Speech Tagging (POS Tagging)
Utiliza um modelo previamente treinado (POS_tagger_portuguese.pkl) para identificar a classe gramatical de cada palavra, permitindo análise sintática.
6. Nuvem de Palavras
Constrói uma nuvem de palavras com a biblioteca WordCloud.
Palavras mais frequentes são destacadas em tamanhos maiores e diferentes cores.
