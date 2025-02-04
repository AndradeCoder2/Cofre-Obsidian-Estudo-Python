Para #elevar um numero a um expoente, utilizaremos dois asteriscos ** para representar a operação de exponenciação. Observe que não há qualquer espaço entre os dois asteriscos. Assim, para calcularmos ( Dois elevado a 3 ), escrevemos de forma semelhante ao conteúdo da listagem 2.5.

-> Listagem 2.5- Exponenciação
```Python
teste = 2**3
print(teste)

saida: 8
```

## Resto da divisão inteira 
podemos também obter o resto da divisão de dois números usando o símbolo %. Assim, podemos calcularmos o resto da divisão entre 10 e 3, digitaríamos como mostrado na listagem 2.6.
```Python
restoDivisao = 10 % 3 
print(restoDivisao)
saida: 1

restoDivisao = 16 % 7 
print(restoDivisao)
saida: 2

restoDivisao = 63 % 8 
print(restoDivisao)
saida: 7

```

Os parâmetros são utilizados em Python da mesma forma em expressões matemáticas, ou seja, para alterar a ordem de execução de uma operação. Para relembrar a ordem de precedência das operações, temos as seguintes prioridades:

1. Exponenciação ou Potenciação **
2. Multiplicação * e divisão (/ e %).
3. Adição (+) e subtração (-).

