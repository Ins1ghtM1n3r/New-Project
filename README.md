---

# Student Academic Performance Analysis

## Descrição do Projeto
Este projeto consiste numa análise exploratória de dados (EDA) aplicada a um conjunto de dados de 500 estudantes. O foco principal é investigar como variáveis demográficas, hábitos de estudo e o contexto socioeconómico influenciam o desempenho académico final. A análise prepara o terreno para a aplicação futura de modelos de Machine Learning para a previsão de sucesso escolar.

O ambiente de desenvolvimento foi totalmente isolado via Docker para garantir a reprodutibilidade e portabilidade dos resultados.

## Detalhes do Dataset
O ficheiro student_performance.csv inclui 500 registos com as seguintes dimensões:
* Variáveis Numéricas: Horas de estudo semanais, taxa de presença, notas anteriores e nota final.
* Variáveis Categóricas: Género, idade, nível de escolaridade dos pais, acesso à internet e atividades extracurriculares.
* Variável Alvo: passed (Indicação binária de aprovação).

## Tecnologias e Ferramentas
* Linguagem: Python 3.12
* Bibliotecas de Dados: Pandas para manipulação e limpeza, NumPy para operações matemáticas.
* Visualização: Plotly Express para a criação de gráficos interativos e dinâmicos.
* Infraestrutura: Docker e Docker-Compose para gestão de contentores.
* Controlo de Versão: Git.

## Metodologia Aplicada
1. Limpeza de Dados: Padronização dos nomes das colunas e tratamento de valores nulos na escolaridade parental através de preenchimento categórico.
2. Engenharia de Atributos: Conversão da variável alvo de texto (Yes/No) para formato numérico binário (1/0) para permitir análises estatísticas e de correlação.
3. Exploração Visual: Implementação de mapas de calor (Heatmaps) para medir a força das relações entre variáveis e gráficos de violino para analisar a densidade da performance por grupo.

## Conclusões e Próximos Passos
O fluxo de trabalho estabelecido demonstra a importância da limpeza técnica antes da visualização. Os resultados iniciais permitem identificar quais os fatores que apresentam maior correlação com a nota final, servindo de base para a construção de um modelo preditivo de classificação na próxima fase do projeto.


Autor: ALFREDO KAHAMBA FRANCISCO
Contacto: [www.linkedin.com/in/alfredo-francisco-103a0b334]

