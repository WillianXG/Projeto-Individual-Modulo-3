# Projeto Individual Módulo 3

## Descrição
Este projeto tem como  Gerar um relatório de progresso diário para mostrar o quão produtivo está sendo o 
trabalho dos funcionários e incluir no relatório outros itens como: 
 Total de Horas Trabalhadas/
  Média Diária de Horas Trabalhadas/
  Total de Bugs Corrigidos/
 Média Diária de Bugs Corrigidos/
  Total de Tarefas Concluídas/
  Média Diária de Tarefas Concluídas/
  Produtividade Diária (Tarefas Concluídas por Hora)/
 
## Estrutura do Projeto
O projeto está estruturado em um Colab com as seguintes seções principais:

1. **Criação da Tabela**: Nesta seção, uma tabela é criada com os dados das horas trabalhadas, bugs corrigidos e tarefas concluídas para cada dia da semana.

## Tabela de Dados
A tabela gerada possui as seguintes colunas:

- **Dia**: O dia da semana (Segunda, Terça, etc.).
- **Horas Trabalhadas**: Número de horas trabalhadas no dia.
- **Bugs Corrigidos**: Número de bugs corrigidos no dia.
- **Tarefas Concluídas**: Número de tarefas concluídas no dia.

Exemplo da tabela:

| Dia      | Horas Trabalhadas | Bugs Corrigidos | Tarefas Concluídas |
|----------|-------------------|-----------------|--------------------|
| Segunda  | 6                 | 3               | 5                  |
| Terça    | 5                 | 2               | 4                  |
| Quarta   | 7                 | 1               | 3                  |
| Quinta   | 4                 | 3               | 5                  |
| Sexta    | 6                 | 3               | 5                  |
| Sábado   | 5                 | 2               | 4                  |
| Domingo  | 4                 | 1               | 2                  |

## Como Executar
Para executar este projeto, siga as etapas abaixo:

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/WillianXG/Projeto-Individual-Modulo-3.git
    ```
2. **Instale as dependências**:
    Certifique-se de ter o Python e o Jupyter Notebook/Google Colab instalados em sua máquina. Você pode instalar as dependências necessárias utilizando pip:
    ```bash
    pip install pandas jupyter
    ```
3. **Execute o Jupyter Notebook/Google Colab**:
    Navegue até o diretório do projeto e inicie o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. **Abra e execute o notebook**:
    No Jupyter Notebook/Google Colab, abra o arquivo `ProjetoIndMod3.ipynb` e execute as células para gerar a tabela.

