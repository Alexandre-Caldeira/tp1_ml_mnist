# tp1_ml_mnist
Redes Neuronais + Backpropagation

## Ambiente:
1. usando conda, criado um ambiente python 3.11
2. instalado poetry no ambiente conda
3. instalado pandas, numpy, matplotlib, seaborn, pytorch, optuna, mlflow, jupyter, ipykernel

### Como:

Abra um terminal na pasta onde vai criar o notebook e execute:

``` bash 
conda create -n tp1ml python=3.11 -y
```

``` bash 
conda activate tp1ml
```

``` bash 
pip install poetry
```

``` bash 
poetry new tp1ml_mnist_proj
```


``` bash 
cd tp1ml_mnist_proj
```

``` bash 
poetry config virtualenvs.create false --local
```

``` bash 
poetry add pandas numpy matplotlib seaborn torch optuna mlflow jupyter ipykernel
```

Opcional:

``` bash 
poetry show
``` 

### Troubleshoot: 
if installation fails on Windows, try running on cmd instead of PowerShell (windows terminal). Not sure why yet, but  that doesn't work.

## Solução:
