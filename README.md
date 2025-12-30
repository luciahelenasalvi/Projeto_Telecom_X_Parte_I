# Projeto_Telecom_X_Parte_I

# Descrição do projeto "Telecom X"

### Visão Geral
A Telecom X é uma empresa de telecomunicações que oferece serviços de telefonia e internet, além de serviços adicionais como suporte técnico. 
A empresa tem enfrentado a evasão de clientes e, deste modo, iremos analisar os dados eu suportem a tomada de decisões diante do ocorrido.  

### Dados
Foi fornecido um arquivo com 7267 linhas e 6 colunas que, normalizados e convertido em um dataframe, passou a ter 21 colunas. 

As colunas foram renomeadas, assim como os rótulos, para melhor entendimento. Também foi criada a coluna 'contas_diarias', que é o valor da fatura mensal dividido por 30 (número de dias do mês). 


| Nome da Coluna | Conteúdo | Tipo de dado |
| ---------------------- | ---------------------- | ---------------------- |
|  **id_cliente**   | Número identificador do cliente : [0000-AAAAA]    | String[Texto]  |
|  **cliente_ativo**   | Se o cliente deixou ou não a empresa   | String[Texto]  |
|  **genero**   |  Gênero do cliente | String[Texto]  |
|  **cliente_idoso**   | Se o cliente tem idade igual ou maior que 65 anos   | Float[Decimal]  |
|  **cliente_parceiro**   | Se o cliente possui ou não parceiro | String[Texto]  |
|  **cliente_dependentes**   | Se o cliente possui ou não dependentes  | String[Texto]  |
|  **meses_contrato**   | Meses de contrato do cliente  | Int[Número inteiro]  |
|  **linha_telefonica**   | Assinatura do serviço telefônico  |  String[Texto]   |
|  **multiplas_linhas**   | Assinatura de mais de uma linha telefônica   |  String[Texto]   |
|  **provedor_internet**   |Assinatura de Provedor de internet  |  String[Texto]   |
|  **seguranca_online**   | Assinatura adicional de segurança online  |  String[Texto]  |
|  **backup_online**   | Assinatura adicional de backup online   |  String[Texto]   |
|  **protecao_dispositivo**   | Assinatura adicional de proteção ao dispositivo |  String[Texto]    |
|  **suporte_tecnico**   | Assinatura adicional de suporte técnico   |  String[Texto]    |
|  **streaming_TV**   | Assinatura de TV a cabo   | String[Texto]   |
|  **streaming_filmes**   | Assinatura de Streaming de filmes   | String[Texto]   |
|  **tipo_contrato**   | Tipo de contrato   | String[Texto]   |
|  **fatura_digital**   | Se o cliente prefere receber a fatura online   | String[Texto]  |
|  **meio_pagamento**   | Forma de pagamento   | String[Texto]   |
|  **fatura_mensal**   | Total gasto pelo cliente por mês   | Float[Decimal]   |
|  **custo_total**   | Total gasto pelo cliente no período   | Float[Decimal]    |
|  **contas_diarias**   | Valor de custo diário   | Float[Decimal]   |



## Procedimentos iniciais
Desenvolvimento realizado na linguagem Python, utilizando a biblioteca Pandas. Também Matplotlib e Seaborn para gráficos. Os códigos foram escritos e executados na plataforma online Google Colab, assim como o relatório final. 

*Passos iniciais*: 
* Importação e leitura dos dados
* Visualização de amostra dos dados

*Reconhecimento dos dados*
* Número de linhas e colunas 
* Avaliação de nulos, em branco, ou inconsistências. 
* Verificações da frequência de cada valor por coluna, contagem, número de valores únicos, mais frequentes, frequência do mais frequente. 
* Agrupamentos pela variável de evasão para cada variável do conjunto de dados. 

## Análises ##
* Agrupamentos pela variável de evasão para cada variável do conjunto de dados. Foram criados gráficos utilizando a biblioteca Matplotlib e Seaborn: Boxplot, Countplot de barras, Violin plot e gráfico de pizza. 


### Como executar o notebook
* Faça o download do arquivo. 
* Abra o Google Colab. 
* Faça o upload do arquivo. 
No menu "Ambiente de Execução" >> Executar tudo ou Ctrl + F9

O arquivo 'clientes_evasao' é o arquivo .csv dos dados transformados. 


### Conclusões
O arquivo, após transformações, passou a ter 7043 linhas e 22 colunas. 
* Churn rate de 26,5%
* Predisposição para evasão de clientes sem parceiro ou cônjuge e sem dependentes. 
* Cliente inativos tem uma média de 17 meses de contrato. 
* A evasão parece estar associada a baixa adesão de serviços adicionais, como o suporte técnico.
* Também parece estar associada ao tipo de contrato mensal, assim como a formas de pagamento não automático. 



Desenvolvido por Lúcia Helena Aparecida Rissi Salvi  - Módulo II Data Science Oracle Next Education | G9.

