# indicium-data-science
Indicium Data Science Challenge

Análise Preditiva de Notas do IMDB

Este repositório contém o projeto de machine learning desenvolvido para prever a nota de filmes no IMDB com base em diversas características, como faturamento, número de votos, diretores e gêneros. O projeto foi estruturado em três etapas principais: Análise Exploratória de Dados (EDA), Análise Preditiva com Regressão e um modelo de previsão final.

Estrutura do Repositório
LH_CD_RODRIGOKATO.ipynb: Contém todos os códigos de análise e modelagem, incluindo EDA e a implementação dos modelos de Regressão Linear e Random Forest.

Análise Exploratória dos Dados.pdf: O relatório em PDF com as análises estatísticas e exploratórias, além das perguntas subsequentes

requirements.txt: Arquivo com a lista de dependências e suas versões.

modelo_previsao_imdb.pkl: O modelo final de Random Forest serializado, pronto para ser utilizado em previsões.

Como Instalar e Executar o Projeto
Para rodar este projeto em seu ambiente local, siga os passos abaixo:

Passo 1: Clone o Repositório
Abra o terminal e use o comando git para clonar o repositório para a sua máquina:

Bash

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Passo 2: Crie e Ative o Ambiente Virtual
É uma boa prática criar um ambiente virtual para isolar as dependências do projeto.

Bash

python -m venv venv
# No Windows
./venv/Scripts/activate
# No macOS e Linux
source venv/bin/activate
Passo 3: Instale as Dependências
Com o ambiente virtual ativado, instale todas as bibliotecas necessárias a partir do arquivo requirements.txt:

Bash

pip install -r requirements.txt
Passo 4: Execute o Jupyter Notebook
Inicie o Jupyter Notebook para visualizar e executar a análise completa:

Bash

jupyter notebook nome_do_seu_notebook.ipynb
Passo 5: Faça Previsões
O modelo treinado está salvo no arquivo modelo_previsao_imdb.pkl. Você pode usá-lo para fazer previsões em novos dados, conforme o código do projeto.

Análises e Resultados
O projeto explora a relação entre as características do filme e sua nota no IMDB. Os principais resultados incluem:

Relação entre Faturamento e Nota: Análises de correlação e gráficos de dispersão mostraram uma relação positiva entre o número de votos e o faturamento do filme.

Melhor Modelo: O Random Forest Regressor foi o modelo com melhor desempenho, alcançando um R-quadrado (R²) de 0.60, superando o modelo de Regressão Linear Múltipla.

Importância das Variáveis: A análise de importância das variáveis no modelo RFR revelou que o número de votos é o fator mais relevante para prever o faturamento, seguido pelo gênero e pelo diretor.

Para mais detalhes sobre as análises e resultados, consulte o notebook do projeto e o relatório em PDF.
