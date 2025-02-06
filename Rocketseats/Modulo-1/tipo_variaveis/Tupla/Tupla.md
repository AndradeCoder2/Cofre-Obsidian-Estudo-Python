**Tupla** e uma coleção ordenada e imutável de elementos.
* *Ordenada* = Lista, ou seja, pressupõe uma ordem de elementos
* *Imutável* = Não podemos mudar os elementos, depois que declararmos os elementos não podemos mudar os elementos.

## Diferença entre *tupla* e *Lista*
Tuplas se comportam como **listas estáticas**. Assim, #Tuplas ocupam menos espaços na memoria. Listas trabalham com **ordem**, enquanto Tuplas geralmente trabalham com **estrutura**. 


## Criando uma *Tupla*
```Python
minha_tupla = (1, 2, 2, 3, 4, )

```

## Acessando uma *tupla* pelo ultimo elemento
```Python
print(minha_tupla[-1])

# Saida: 4
```

### Curiosidade
Não podemos alterar o elemento de uma *tupla*, ocorrera um erro.
```Python
minha_tupla[0] = 10
print(minha_tupla)

# Saida: TypeError: 'tupla' object does not support item assignment
```


# Métodos em *tupla*

###  Método **count**  
O Método *count* e utilizado para contar quantas vezes um determinado elemento aparece na tupla.
 
```Python
 print("Numero (3) foi exibido: ",minha_tupla.count(3)) 
 # Saida: Numero (3) foi exibido: 2
````
### Metodo index 
O Método index retorna o índice do primeiro elemento igual ao argumento fornecido. Se o elemento não existir na tupla, um erro e gerado.

```Python
indice = minha_tupla.index(3) print(indice) 
# Saida: Indice da primeira ocorrencia do elemento 3: 2
```
como podemos ver, ele retorna qual e o índice do elemento que colocamos entre parênteses.




