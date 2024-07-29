Análise de Dados Aéreos
Descrição
Este projeto visa fornecer insights sobre a operação e eficiência das companhias aéreas utilizando dados históricos de voos entre 2018 e 2022. O objetivo é ajudar os tempos de produtos e operações a otimização de rotas aéreas e melhorar a eficiência geral da companhia aérea.

Conteúdo do Repositório
Dados : Arquivos CSV dos dados históricos de voos de 2018 a 2022.
Dicionário de Dados : Descrição das colunas e valores contidos nos arquivos CSV.
de-para : Mapas de códigos de companhias aéreas e seus nomes correspondentes.
Análise de Dados
1. Análise de Companhias Aéreas
Principais Companhias : Análise das principais companhias aéreas que mais voam em cada ano.
Impacto da Pandemia : Avaliação de como a pandemia afetou a operação de cada companhia.
Alterações em Volos : Identificação das companhias que mais alteram voos durante uma pandemia.
Principais Rotas : Análise das principais rotas aéreas das companhias aéreas dominantes.
Taxa de Cancelamento e Atraso : Identificação da companhia com maior percentual de cancelamentos e atrasos de voos.
2. Análise da Eficiência das Rotas
Principais Rotas : Identificação das rotas de voos mais frequentes.
Atrasos por Rota : Análise das rotas com maior tempo médio de atraso.
Taxa de Cancelamento : Avaliação das rotas com maior índice de cancelamento de voos.
Eficiência das Rotas : Identificação das rotas mais e menos eficientes em termos de desempenho.
3. Análise do Atraso das Rotas
Tempo Médio de Atraso : Cálculo do tempo médio de atraso dos voos utilizando as colunas ArrDelayMinutese DepDelayMinutes.
Fatores Correlacionados : Investigação dos fatores que possuem maior clareza com o atraso de um voo.
Modelagem
4. Modelo de Regressão Linear
Foi construído um modelo de regressão linear para estimar o tempo de atraso de um voo, utilizando DepDelayMinutescomo variável-alvo.
O modelo incorpora variáveis ​​dummy para categorias, incluindo o mês do ano e rotas específicas, a fim de melhorar a acurácia das variações.
Tecnologias Usadas
Python : Linguagem de programação utilizada para análises e modelagens.
Pandas : Biblioteca para manipulação e análise de dados.
NumPy : Biblioteca para cálculos numéricos.
Scikit-learn : Utilizada para modelagem preditiva e análise estatística.
Matplotlib e Seaborn : Bibliotecas para visualização de dados.
Como Executar o Projeto
Pré-requisitos
Python 3.x
Bibliotecas: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Instalação
Clonar este repositório.

git clone https://github.com/RaquelFonsec/Setor-Aero-dados-.git
cd Setor-Aero-dados-
Contribuições
Se você deseja contribuir para este projeto, sinta-se à vontade para fazer um fork do repositório e apresentar um pull request.