# Trabalhando com Machine Learning na Prática no Azure ML
## O passo a passo em um readme.md e o arquivo .json de pontos de extremidade do modelo de previsão configurado. 

### Como Entregar esse projeto?
1. Crie um novo repositório no github com um nome a sua preferência
2. Crie um modelo de previsão com seus devidos pontos de extremidade configurados
3. Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa
4. Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade
5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

### Passo a passo de como o projeto foi feito

#### Selecione: 
go to resource 
ML automatizado
novo trabalho de ML automatizado

Nome do trabalho: mslearn-bike-automl
Novo nome do experimento: mslearn-bike-rental
Descrição: Aprendizado de máquina automatizado para previsão de aluguel de bicicletas
Marcas: none
tipo de tarefa selecionado: Regressão

### Definir o nome e o tipo do ativo de dados
Nome: AluguelDeBicicletas
Descrição: Dados históricos de aluguel de bicicletas
Tipo: Tabular
Fonte para o ativo de dados: Arquivos da Web
URL da Web: https://aka.ms/bike-rentals

### Configurações
Formato do arquivo: Delimitado
Cabeçalhos de coluna: Somente o primeiro arquivo tem cabeçalhos
Delimitador: Virgula
Ignorar linhas: nenhuma
Codificação: UTF-8
Conjunto de dados com dados de várias linhas
false

### Examinar
#### Examine as configurações do ativo de dados e faça as alterações necessárias.
Tipo de dados
Nome
AluguelDeBicicletas
Descrição
Dados históricos de aluguel de bicicletas
Digitar
tabular
Fonte de dados
Tipo
WebURL
URL da Web
https://aka.ms/bike-rentals
Ignorar validação de dados
false
Configurações
Delimitador
Comma
Codificação
UTF-8
Formato do arquivo
Delimitado
Cabeçalhos de coluna
Somente o primeiro arquivo tem cabeçalhos
Número de linhas a serem ignoradas
None
Conjunto de dados com dados de várias linhas
false

Criar
Êxito: Ativo de dados AluguelDeBicicletas criado com sucesso. A atualização das listas pode demorar alguns segundos.

Tipo de tarefa e dados
Tipo de tarefa
Regressão
Dados
AluguelDeBicicletas

### Configurações de tarefas
Coluna de destino: rentals (integer)
Configuração adicional
Métrica primária
NormalizedRootMeanSquaredError
modelos permitidos: RandomForest e LightGBM

### Configurações de tarefas
Coluna de destino
rentals
Máximo de avaliações: 3
Máximo de avaliações simultâneas: 3
Máximo de nós: 3
Limite de pontuação da métrica: 0,085
Tempo limite do experimento (minutos): 15
Tempo limite de iteração (minutos).: 15
Validar tipo
Divisão de validação de treinamento
Validação de percentual de dados
10

### Configurações de computação
Tipo de computação
Computação sem servidor do Azure ML
Tamanho da máquina virtual
Standard_DS3_v2
Contagem de instâncias
1

## Links Importantes
[Explore Azure AI Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html)

[Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

