
Análise Preditiva de Notas do IMDB 🎬
Este repositório contém um projeto de machine learning focado em prever a nota de filmes no IMDB. Utilizando uma base de dados de filmes aclamados, a análise explora as relações entre fatores como faturamento, votos, diretores e gêneros para construir um modelo preditivo robusto.

Estrutura do Projeto
O repositório está organizado de forma intuitiva para facilitar a navegação e o entendimento.

📁 LH_CD_RODRIGOKATO.ipynb: O coração do projeto. Contém toda a análise exploratória (EDA) e o desenvolvimento dos modelos de Regressão Linear e Random Forest.

📄 Análise Exploratória dos Dados.pdf: Um resumo detalhado das análises estatísticas e dos principais insights descobertos.

📦 requirements.txt: A lista de dependências. Essencial para replicar o ambiente do projeto sem erros.

💾 modelo_previsao_imdb.pkl: O modelo final de Random Forest Regressor, serializado e pronto para fazer previsões em novos filmes.

## Como Instalar e Executar
Siga estes passos simples para rodar o projeto em sua máquina.

#Clone o Repositório 👩‍💻

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

#Crie e Ative o Ambiente Virtual 🐍

python -m venv venv

## Windows
./venv/Scripts/activate
## macOS/Linux
source venv/bin/activate

##Instale as Dependências ✨


pip install -r requirements.txt

##Inicie o Jupyter Notebook 🚀

jupyter notebook nome_do_seu_notebook.ipynb

#Resultados Chave

O projeto validou várias hipóteses importantes e gerou insights valiosos:

Melhor Desempenho: O modelo Random Forest Regressor superou a Regressão Linear, alcançando um R-quadrado (R²) de 0.60. Isso significa que ele explica 60% da variação nas notas dos filmes, um avanço significativo.

Fatores Mais Importantes: A análise de importância das variáveis revelou que o número de votos é o fator mais relevante para prever a nota de um filme. Gênero e Diretor também se mostraram cruciais.

Para uma exploração aprofundada dos resultados, confira o notebook e o relatório em PDF.
