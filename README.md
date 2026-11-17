<sub>**Datas:** pasta 23/12/2022 · evolução `NeuralNetwork2.Rmd` → `NeuralNetwork4.Rmd` (out/2022)</sub>

# Rede neural implementada à mão

**Forward pass, backprop, ReLU e softmax** em R puro, sem `tensorflow`.

## O que o código faz

| Arquivo | Conteúdo |
|---------|----------|
| `NeuralNetwork2.Rmd` | Versão inicial, peso/altura |
| `NeuralNetwork3.Rmd` | Refinamentos |
| `NeuralNetwork4.Rmd` | Versão mais completa + MNIST em CSV |

Treina em batches, calcula gradientes manualmente, matriz de confusão no fim.

## Dados

| Arquivo | Uso |
|---------|-----|
| `weight-height.csv` | Classificação binária (sexo) |
| `mnist_train.csv` | Coluna 1 = dígito; demais = 784 pixels (pode estar fora do Git por tamanho) |

## Como rodar

Comece por `NeuralNetwork4.Rmd` se quiser MNIST; knit no RStudio.