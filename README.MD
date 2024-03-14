# PROJECT PYTHON IA: Artificial Intelligence and Previsions

## Case Score de Crédito dos Clientes

Voce foi contratado por um banco para conseguir definir o score de crédito dos clientes. Você precisa analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informaÇões do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Ruim

### Step 0

Understand the challenge of the company

### Step 1

Imports the database

### Step 2

Prepares the database to the AI:

- The AI read numbers only. It´s necessary transform columns - object(caracter) - in number, called ´label encoder´. The column that will be predicted don't need transformed in number.
  - Import label encoder
  - Create label encoder
  - Apply in the column

It's important:

- To know who I want to predict - (y).
- To know who I want to use to do the predict - (x).
- To split the data in between train and test with the method ´train_test_split´.
  Usually it's used 30% of data to test and 70% to train. Can be defined with the percentile to the test.
  _IMPORTANT_: Overfitting

### Step 3

Creates a model of AI with credit score:

- Good - Standard - Poor

The model are ´random forest´ and ´KNN(Nearest Neighbors)´

    - Step 1
      - Import the AI
    - Step 2
      - Creates the AI
    - Step 3
      - Train the AI

### Step 4

Chooses the better model with ´random forest´ and ´KNN´ methods.

### Step 5

Uses the AI to do new predictions.

## Libraries:
Install - Pandas: to database

- Scikit learn: principal AI package

´!pip install pandas scikit-learn´
