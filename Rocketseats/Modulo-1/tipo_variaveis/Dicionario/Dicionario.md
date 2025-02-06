# Dicionários

Em Python podemos criar um dicionário… Um dicionário e uma estrutura de dados que permite *armazenar dados em pares* chamamos cada par de dados de *par chave-valor*  com isso cada elemento em um dicionário consiste em uma chave e um valor associado a essa chave. Podemos utilizar associação para *representar relações que existem no mundo real* (Como um produto e seu preço)

### Exemplo de *dicionário* em Python
Para criamos um dicionário em Python, basta colocarmos as chaves (**{  }**) e inserir os pares de chave-valor separados por ( **,** ). Depois fazemos a associação entre cada chave e seu respectivo valor com o sinal de dois-pontos ( **:** ).
```Python
pessoa = {"nome": "Paulo", "idade": 20, "cidade": "SÃo Paulo"} print("Meu dicionario de exemplo:", pessoa)
```

### Acessando o valor por chave
Podemos acessar todos os valores que colocamos individualmente, da seguinte forma:
```Python
print("Nome:", pessoa["nome"]) 
print("Idade:", pessoa["idade"]) 
print("Cidade:", pessoa["cidade"])
```
Neste exemplo, todos os resultados serão exibidos individualmente. Estamos utilizando o nome do valore

### Criando um dicionário *vazio* 
Podemos querer criar um dicionário vazio em Python, normalmente fazemos isso quando queremos preencher um dicionário com valores de uma lista ou outra sequência qualquer. Podemos iterar sobre a sequência e ir adicionando os pares chave-valor ao dicionário a cada interação. 

Criamos o dicionário vazio utilizando a função **dict()**
Veja o exemplo abaixo:
```Python
#  Criando dicionario vazio função ( dict() )  
dicionario_vazio = dict()  
print(dicionario_vazio)
```
Neste exemplo criamos um dicionário vazio com a função *dict()* ele não será exibo nada!
### Alterar e Atualizar um valor já existente
```Python
#  Atualizar ou Alterar.  
pessoa["idade"] = 22  
print("Idade atualizada:", pessoa["idade"])
```
Neste exemplo estamos alterando a idade já estabelecida que no nosso caso era **20**, ao fazermos isso nos estamos atribuindo um novo valor para
### Removendo um par de chave-valor
Podemos remover o elemento que esta dentro do nosso dicionário utilizamos a palavra-chave *del*
```Python 
#  Removendo um par de chave-valor

del pessoa["idade"]
print(pessoa)

# Saida: {'nome': 'Paulo', 'cidade': 'SÃo Paulo'}
```


## Principais métodos em dicionários

 Em Python os dicionários possuem diversos métodos que facilitam a manipulação de seus elementos.
 Alguns dos principais: 
 
 1. `dict.clear()` 
* Remover todos os elementos do dicionário.
 ```Python
#  Metodo 'dic.clear()'
  meu_dicionario = {"a": 1, "b": 33, "c": 55}
  meu_dicionario.clear()
  print(meu_dicionario)
  ```

1. `keys()` 
* Retorna uma copia rasa do dicionário
```Python
"""
Keys()
Ele retorna uma copia rasa do dicionario.
Quando usamos, podemos verificar todas as chaves, que temos no nosso dicionario.
"""
chaves = pessoa.keys()
print("Chaves do dicionario:",chaves)
```

podemos acessar apenas um elemento da chave, nos podemos escolher. Para fazermos isso, devemos utilizar a seguinte forma:
```Python
print("Primeira chave:", chaves[1])
```
porem ao ser execultado ele dará um erro, pois ele entende que isso *Não e uma lista direta*. Para fazer esse acesso devemos transforma-lo em uma <span style="background:#b1ffff">Lista</span> (*casting*) Por exemplo:
```Python
chaves = list(pessoa.keys())
print("Primeira chave:", chaves[1])

# Saida: Primeira chave: cidade

```
como podemos ver nos fizemos a conversão, adicionamos o <span style="background:#b1ffff">list</span>.