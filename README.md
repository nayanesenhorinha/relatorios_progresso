# Relatório de Progresso Diário

## Introdução
Este repositório contém o código e o relatório de análise de dados de um projeto de desenvolvimento de software ao longo de uma semana. O objetivo é demonstrar a importância da análise dos dados para obter insights sobre o progresso do projeto, identificar possíveis áreas de melhoria e tomar decisões informadas para garantir o sucesso do projeto.

## Estrutura do Repositório
- `relatorio_progresso_diario.ipynb`: Notebook contendo todo o código e análise em Python.
- `dados.csv`: Arquivo csv com dados utilizados na análise.
- `README.md`: Este arquivo de documentação com instruções e descrições do projeto.

## Dados
Os dados analisados incluem:
- **Dia**: Dias da semana.
- **Horas Trabalhadas**: Número de horas trabalhadas por dia.
- **Bugs Corrigidos**: Número de bugs corrigidos por dia.
- **Tarefas Concluídas**: Número de tarefas concluídas por dia.

## Análise
A análise inclui:
- Cálculo do total e da média diária de horas trabalhadas.
- Cálculo do total e da média diária de bugs corrigidos.
- Cálculo do total e da média diária de tarefas concluídas.
- Cálculo da produtividade diária (tarefas concluídas por hora trabalhada).

### Visualizações
Foram gerados gráficos para melhor compreensão dos dados:
- Gráfico de barras das horas trabalhadas por dia.
- Gráfico de barras dos bugs corrigidos por dia.
- Gráfico de barras das tarefas concluídas por dia.
- Gráfico de linhas da produtividade diária.

### Recomendações
- Manter um registro constante e detalhado das horas trabalhadas, bugs corrigidos e tarefas concluídas.
- Analisar regularmente os dados para identificar tendências e áreas de melhoria.
- Considerar ajustar a carga de trabalho ou alocar recursos de forma mais eficaz com base nas observações feitas a partir dos dados analisados.

## Instruções de Uso

### Pré-requisitos
- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `matplotlib`

### Utilizando no Google Colab
1. Abra o Google Colab: [Google Colab](https://colab.research.google.com/)
2. Faça o upload do arquivo `relatorio_progresso_diario.ipynb` para o Colab ou acesse no link [https://colab.research.google.com/drive/1Jgf3q-QlDaqzwsbVHP1xGTIGmq8_XdTq?usp=sharing](https://colab.research.google.com/drive/1Jgf3q-QlDaqzwsbVHP1xGTIGmq8_XdTq?usp=sharing).
3. Faça o upload do arquivo `dados.csv` na aba de arquivos do notebook.
4. Execute todas as células do notebook para gerar a análise e os gráficos.

### Executando Localmente
1. Clone este repositório:
    ```sh
    git clone https://github.com/nayanesenhorinha/relatorios_progresso.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd nome-do-repositorio
    ```
3. Instale as bibliotecas necessárias:
    ```sh
    pip install pandas numpy matplotlib
    ```
4. Abra o Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
5. Abra o arquivo `relatorio_progresso_diario.ipynb` e execute todas as células para gerar a análise e os gráficos.
