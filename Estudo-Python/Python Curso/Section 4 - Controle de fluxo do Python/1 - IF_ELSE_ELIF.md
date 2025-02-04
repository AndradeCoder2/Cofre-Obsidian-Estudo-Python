* A estrutura de decisão if-else 
* A estrutura de decisão if-elif-else 
* Instruções if aninhadas do Python 
* Listas em Python 
* for loop em Python 
* While loop em Python 
* Exercícios #02


# A estruturas de decisão IF-ELSE
A estrutura de decisão *if-else* em Python permite que o programa tome diferentes caminhos com base em uma condição.
### Sintaxe da estrutura *if-else* 
```Python 
if condição: 
    # Esse  codigo sera execultado caso umas das condições for verdadeira.
    print("Esta tudo bem com você")
else :
     # Esse bloco execulta quando uma das condições forem falsas.
    print("Como você esta ?")
```

![[Captura de tela 2025-02-04 141945.png]]

<span style="background:#b1ffff">Exemplo: </span> 
O código em Python e um exemplo simples de um teste condicional usando a estrutura *if*...*else*. Ele verifica se a variavel idade e maior ou igual a 18 e imprime uma mensagem correspondente ao resultado dessa condição.
```Python
idade = 18
if idade >= 18:
print("Maior de idade.")
else:
print("Menor de idade.")
```

# Estrutura de decisão IF-ELIF-ELSE
A estrutura de decisão *if*-*elif*-*else* e usada quando temos varias condições a serem verificadas em sequencia.
```Python
 vitoria = 10 
 
 if vitoria >= 20:
 print("Avançado.")
 elif vitoria <= 20
 print("Intermediario..")
 else:
 print("Infelizmente você não possui emblemas.")
 
```
E importante notar que as condições são verificadas sequencialmente e apenas a primeira que for verdadeira terá seu bloco de código executado. 

# Instruções IF Aninhadas do Python
Em Python podemos usar a instrução *IF* dentro de outra instrução *IF*. E mais conhecida como instrução #Aninhada.

![[Captura de tela 2025-02-04 152054.png]]

<span style="background:#b1ffff">Exemplo: </span>

```Python
numero = -5

if numero >= 0:

    print("Numero e positvo")

    if numero % 2 == 0:

        print("Numero e par")

    else:

        print("Numero e impar")

else:

    print("Numero e negativo")

#  Verifica se o numero e negativo, e se e Par ou Impar

    if numero % 2 == 0:

        print("Numero é par")

    else:

        print("Numero é ímpar")
```

Esse código verifica se o numero e *positivo*, *negativo* e imprime uma mensagem correspondente.
Neste caso especifico, como o valor atribuído a variavel numero e -5, a condição **numero** >= *0* e falsa, ele executara o programa com a mensagem 'Numero e negativo' e 'Numero e Impar'