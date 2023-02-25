# Automação de Envio de E-mais com Dados de Vendas

## Problematização

Diariamente, o sistema de uma empresa fictícia atualiza uma planilha com os dados de venda do dia anterior. Como analista, nosso trabalho envolve estes passos:

- Acessar a planilha disponibilizada num link do Google Drive
- Calcular o faturamento
- Calcular a quantidade de produtos vendidos
- Enviar um e-mail para a diretoria, informando o faturamento e a quantidade de produtos vendidos


## Solução

A fim de automatizar esse processo, vamos utilizar o **pyautogui**, uma biblioteca do Python para controlar o mouse e o teclado.

## Criação do Ambiente Virtual

Caso você deseje reproduzir este projeto, crie uma pasta para seu projeto e um ambiente virtual para ele. Para criar o ambiente virtual, navegue até a pasta de seu projeto e digite o seguinte comando no terminal:

```bash
conda -n myenv python=3.10
```

Em seguida, ative o ambiente:

```bash
conda activate myenv
```

Com o ambiente ativo, instale as dependências do projeto:

```bash
pip3 install pandas openpyxl numpy jupyter
```

Depois, instale o **pyautogui**:

```bash
pip3 install pyautogui
```

Execute o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo principal deste projeto e execute todas as células.

## Bibliotecas Usadas

Estas são as bibliotecas usadas neste projeto:

- pyautogui
- time
- pandas
