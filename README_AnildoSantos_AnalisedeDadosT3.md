**Aluno** Anildo Dos Santos Nascimento
**Turma** Análises_de_Dados_T3


## Como execultar

Primeiro abra `analise_exploratoria_dados.ipynb` no VSCode ou Colab ( com o arquivo `Base Varejo.csv` tudo na mesma pasta e execulte todas as células)

## Insights
1. A base havia 96.553 linhas duplicadas e 4 colunas vazias, que ambas foram eliminadas
2. 3.650 produtos estavam sem categoria ("#N/D") Que foram marcados como ("Sem Categoria") em vez de ser excluído.
3. A coluna `DATA`tava em tipo texto e foi normalizada em `datetime`.
4. A categoria que mais vendeu foi a `ALIMENTOS`, com o gênero (F), sendo o que mais compra.
5. A média de filhos dos clientes é de 1,15 filhos

## Reflexão - ETL e Qualidade de Dados

Seguindo a lógica no projeto em ETL **EXTRAÇÃO** que foi a leitura do (`CSV`), **Transformação** que atuou na (`limpeza e tratamnto dos dados`) etivemos a **carga** que foi (exportaação da base tratada em `df_Limpeza_Dados.csv`).

A limpeza dos dados sempre é muito importante para não gerar dados e conclusôes erradas, mesmo o código estando certo ainda assim a limpeza é essencial em qualquer análise.
