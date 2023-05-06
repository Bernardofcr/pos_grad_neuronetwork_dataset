# Projeto Final - Modelos Preditivos Conexionistas

Classificação de imagens de flores, frutas ou cogumelos

### Bernardo Russo

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens|resnet34|PyTorch|

## Performance

O modelo treinado possui performance de **91.04%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
Epoch 0/2
----------
Iterating through data...
train Loss: 0.7545 Acc: 0.7052
Iterating through data...
valid Loss: 0.1788 Acc: 0.9535

Epoch 1/2
----------
Iterating through data...
train Loss: 0.4575 Acc: 0.8057
Iterating through data...
valid Loss: 0.5638 Acc: 0.8062

Epoch 2/2
----------
Iterating through data...
train Loss: 0.3874 Acc: 0.8755
Iterating through data...
valid Loss: 0.2393 Acc: 0.8837

Training complete in 19m 31s
Best val Acc: 0.953488
----------
Test Acc: 0.940299
----------
  ```
</details>

### Evidências do treinamento

#### Matriz de Confusão
![matriz de confusão](confusion_matrix.png)

## Roboflow

Link do data set: [Roboflow Project - Flower, Fruit or Mushroom](https://app.roboflow.com/cesar-school-ulsik/flower_fruit_mushroom/1)

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace