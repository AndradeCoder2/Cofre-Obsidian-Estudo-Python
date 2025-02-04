## Quias são os Operadores Booleanos em Python

Operadores booleanos são usados para criar expressões que retornam valores verdadeiros (`True`) ou falsos(`False`). Em Python, os principais operadores booleanos são `and`, `or` e `not` 

### Operador `and`

O operador #and retorna `True` se ambas as expressões em cada lado do operador forem verdadeiras. Caso contrario, retornam `False` 

```Python
verdadeiro = True  
falso = False  
print(verdadeiro and verdadeiro) # Saida: True  
print(verdadeiro and falso) # Saida: False
```

### Operador `or` 

* O operador `or` retorna `True` se pelo menos uma das expressões em cada lado do operador for verdadeiro.
* Se ambas forem `falsas`, retorna `False`.

```Python
verdadeiro = True
falso = False
print(verdadeiro or falso) # Saida: True 

```

## Utilizando operadores Booleanos em Condições
---------------------------------------------------------------------------------
Os operadores booleanos são frequentemente usados em conjunto com instruções condicionais, como *if*, *elif* e *else*.

Utilizamos <span style="background:#b1ffff">condicionais para executarmos diferentes tipos de códigos, com base nas condições especificadas</span>.

```Python
idade = 60  
if idade >= 18 and idade < 60:  
    print("Você ja pode emitir sua Habilitação")  
elif idade >= 60:  
    print("Voê precisa renovar sua Habilitação")  
elif idade < 18:  
    print("Menor de idade")  
else:  
    print("Não existe")
```

## Combinação de Operadores
--------------------------------------------------------------
Podemos combinar múltiplos operadores booleanos em uma expressão complexa para verificar condições mais elaboradas.
```Python
tem_cartao = True
saldo_Suficiente = False

#  Combinações de operadores
if tem_cartao or saldo_suficiente:
print("Pode realizar a compra")
else:
print("Não pode realizar a compra")
```

## Conclusão
-----------------------------------------------
Podemos afirmar que os operadores Python são essenciais que permitem que você crie logicas condicionais complexas de forma simples e legível.