Declaração.
```Python
minhe_lista = [1, 2, 3, 4, 5, "Rockeseat", True, False]`
```

  
Exibindo uma Lista.
```Python
print("minhe lista exemplo", minhe_lista)``
```

Exibindo os elementos.
```Python
print("minhe_lista[0]: ", minhe_lista[0])

print("minhe_lista[1]: ", minhe_lista[1])
```
`
print("--------------------------------------------")

Fatiamento, de um elemento a outro elemento (intervalo).

```Python
print("minhe_lista[0]: ", minhe_lista[2:7])

print("minhe_lista[0]: ", minhe_lista[1:5])
```

  Fatiamento do começo ate o alvo.

```Python
print(minhe_lista[:7])

print(minhe_lista[:4])
```

  Fatiamento do final ate o começo.

```Python
print(minhe_lista[2:1])

print(minhe_lista[4:])
```

# Métodos de listas
* Metodo *append()* : ele adiciona um elemento ao final da lista.
```Python
minhe_lista = [1, 2, 3, 4, 5, "Rockeseat", True, False]

minhe_lista.append(6)

print("Apos append(6: )", minhe_lista)

#Saida: Apos append(6: ) ['Python', 2, 3, 4, 5, 'Rockeseat', True, False, 6]

```
como podemos ver ele adicionou o elemento (6) no final da lista.

* Metodo *index* : ele retorna o índice do elemento que quisermos.
```Python 
minhe_lista = [1, 2, 3, 4, 5, "Rockeseat", True, False]

indice = minhe_lista.index(5)

print("Indice do elemento 5: ", indice)

# Saida: Indice do elemento 5:  4
```

* Metodo *insert* : Insere um elemento em um índice especifico, em uma determinada posição.
```Python

minhe_lista.insert(2, 10)
print(minhe_lista)

# Saida: ['Python', 2, 10, 3, 4, 5, 'Rockeseat', True, False, 6]
```
Neste exemplo, utilizamos o *insert* para substituir o numero do índice 2 = (3), e na sua posição foi adicionado o numero (10).

* Metodo *(pop)*. Ele remove e retorna o elemento de um índice especifico.

```Python
minhe_lista = [1, 2, 3, 4, 5, "Rockeseat", True, False]

elemento removido = minhe_lista.pop(3)

print("Elemento removido ",elemento removido)

# Saida: Elemento removido  3
```


* Metodo *remove*, ele remove o elemento
```Python
minhe_lista = [1, 2, 3, 4, 5, "Rockeseat", True, False]

minhe_lista.remove(True)

print("Apos remove(True): ", minhe_lista

# Saida: Apos remove(True):  ['Python', 2, 10, 4, 5, 'Rockeseat', False, 6]
```