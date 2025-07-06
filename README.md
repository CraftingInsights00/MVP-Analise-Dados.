MVP – Análise de Acidentes de Trânsito em Rodovias Brasileiras
Especialização em Ciência de Dados e Analytics | PUC-Rio – 2025

Autor: Andres Silva

Sobre o Projeto
Este projeto realizou uma análise exploratória detalhada de acidentes de trânsito ocorridos em rodovias federais brasileiras entre 2017 e 2021, utilizando dados públicos do DATATRAN. O objetivo foi identificar padrões, áreas de maior risco e fatores associados à frequência e gravidade dos acidentes, contribuindo com recomendações para políticas públicas e o avanço da ciência de dados aplicada à segurança viária.

Objetivos
Investigar padrões temporais, geográficos e contextuais dos acidentes.
Analisar fatores que influenciam a gravidade (condições do clima, do local, etc.).
Preparar a base de dados para futuras etapas de modelagem e machine learning.
Expor limitações dos dados e propor caminhos para análises futuras.
Dataset
Fonte Original:
Kaggle: Acidentes de Trânsito no Brasil (DATATRAN)

Período Coberto: 2017 a 2021
Escopo: Acidentes em rodovias federais brasileiras
Todos os arquivos .csv utilizados nesta análise estão neste repositório (veja a pasta /dataset).

Estrutura do Repositório
MVP-Analise-Dados/

│

├── dataset.rar/

│ ├── datatran2017.csv

│ ├── datatran2018.csv

│ ├── datatran2019.csv

│ ├── datatran2020.csv

│ └── datatran2021.csv

│

├── MVP-Analise-de-Dados.ipynb # Notebook principal do projeto

│

├── README.md # (este arquivo)

Como Executar a Análise
Google Colab (Recomendado):
Abra o notebook MVP-Analise-de-Dados.ipynb.
Siga as instruções das primeiras células, que automatizam a instalação de todas as bibliotecas necessárias.
Todos os dados podem ser carregados via URLs “raw” do próprio GitHub, conforme explicado no notebook.
Caso necessário, adapte o caminho dos arquivos conforme a organização local do seu ambiente.

Pré-requisitos de Bibliotecas
python 3.10+
pandas, numpy, matplotlib, seaborn, scikit-learn, rarfile, scipy, difflib, re

pip install pandas numpy matplotlib seaborn scikit-learn rarfile scipy

Principais Análises e Resultados
Identificação de picos de acidentes aos finais de semana, principalmente sábados e domingos;
Maior gravidade dos acidentes aos domingos;
Limitações para análise detalhada por tipo de veículo, devido à estrutura dos dados;
Impacto das condições meteorológicas: surpreendentemente, maior risco de fatalidade sob “céu claro/sol” do que durante chuva/neblina, em números absolutos;
Concentração de acidentes em grandes municípios e em determinados estados (MG, SC, PR);
Pipeline completo de exploração, limpeza e padronização para futuras etapas de ML.
Limitações
Dados restritos a rodovias federais; sem detalhamento de vítima ou veículo;
Possíveis inconsistências ou subnotificações em algumas variáveis;
O projeto pode ser expandido por integração com dados climáticos externos, demográficos e viários de maior granularidade.

Sinta-se à vontade para utilizar o código e os dados, citando este repositório. Sugestões de aprimoramento são bem-vindas via pull request ou issues.

Créditos
Projeto desenvolvido por Andres Silva para a disciplina de Análise de Dados e Boas Práticas – Especialização em Ciência de Dados e Analytics, PUC-Rio, 2025.

Licença
CC BY 4.0
