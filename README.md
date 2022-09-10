# Predição de insuficiência cardíaca dos pacientes

Esse projeto tem como objetivo construir um modelo capaz de prever a sobrevivência dos pacientes e, em seguida ranquear as características clínicas (riscos fatores) mais importantes incluídas nos prontuários médicos que podem indicar a insuficiência cardíaca, ajudando em seu diagnóstico.

## Requisitos

1. [Pandas](https://pandas.pydata.org/docs/): para leitura e manipulação de dados

2. [https://matplotlib.org/](https://matplotlib.org/): para criar o gráfico de barras

3. [Seaborn](https://seaborn.pydata.org/): para criar o gráfico de barras

4. [Pycaret](https://pycaret.gitbook.io/docs/): para realizar o AutoML

5. [sklearn](https://scikit-learn.org/stable/install.html): para criação de modelos de machine learning

6. [numpy](https://numpy.org/): para realizar calculos e operações de manipulação de estrutura de dados

7. [scipy](https://scipy.org/install/): para realizar testes estatísticos

8. [imblearn](https://imbalanced-learn.org/stable/): para realizar o método de balanceamento de classes

9. [Alibi](https://docs.seldon.io/projects/alibi/en/stable/overview/high_level.html): para realizar o método de explicabilidade dos modelos

10. [imblearn](https://imbalanced-learn.org/stable/): para realizar o método de balanceamento de classes

11. [Pandas Profilling](https://pypi.org/project/pandas-profiling/): para realizar o método de análise de dados automática

## Estrutura do projeto
- Untitled.ipynb: notebook com os códigos das análises, insights extraídos e construção do modelo.
- Desafio_Dataset.csv: arquivo com os dados
- environment.yml: arquivo yml para instalar as bibliotecas
- Apresentação.pdf: arquivo explicando os insights extraídos, linha de raciocínio e conclusão.


## Como usar:
1. Baixar o projeto
2. Dentro do terminal do anaconda rodar: 
```
conda env create -f environment.yml --name env_desafio
```
3. Ativar o ambiente virtual
```
conda activate env_desafio
```
4. Após a ativação é necessário rodar o seguinte comando:
```
jupyter notebook
```
5. Acessar a pasta do projeto e abrir o arquivo .ipynb

6. Rodar os códigos na ordem mostrada no tópico "Etapas de execução do notebook"

## Significado das colunas:

- Age: Idade dos pacientes
- Anaemia: Se o paciente tem anemia (0- Não 1- Sim)
- CPK: Nível de enzima CPK no sangue do paciente
- BP: Se o paciente tem hipertensão (0- Não 1- Sim)
- Diabetes: Se o paciente tem diabetes (0- Não 1- Sim)
- Ejection.Fraction: Porcentagem que o sangue sai do coração a cada contração
- Gender: Genero do paciente (0-Mulher 1- Homem)
- Platelets: Quantidade de plaquetas no sangue do paciente
- Creatinine: Nível de creatinina no sangue do paciente
- SodiumL Nível de sódio no sangue do paciente
- Smoking: Se o paciente fuma (0- Não 1- Sim)
- TIME: Quantidade de dias que o paciente ficou em observação
- Event: Se o paciente morreu naquele período ou não (0- Sobreviveu 1- Morreu)
