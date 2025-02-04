
# Formatação de String com *'+'* e *format()*.
Em Python, e possível formatar strings usando o operador **'+'** e a função **format()**. 

Utilizamos a função format() para formatar strings com valores pré-definidos.
Ela permite inserir valores numéricos com duas casas decimais, valores numéricos com expoentes, strings, entre outros.

Neste exemplo, utilizamos a função **format()** para inserir o valor da variavel "numero" na string. Utilizamos {} para permitir a inserção da variavel na string.
```Python
nome = "Paulo" 
idade = 20
data = "2023-04-27"

print("Meu nome e {} tenho {} anos, e nasci em {}".format(nome, idade, data))

saida : Meu nome e Paulo tenho 20 anos, e nasci em 2023-04-27
```

# Operadores e atributos de string 

Os operadores de strings permitem realizar operadores com strings simples, como **concatenação** , **concatenar** , **corte** e **substituição**.

* Concatenar: Usamos para unir duas ou mais strings.

```Python
string1 = "Hello"
string2 = "World"
string3 = string1 + " " + string2

print(string3)

# O codigo retorna:

Hello World
```

* **Corte** : Usamos para remover uma substring de uma string.
```Python
string = "Hello World" 
substring = string[:5] 
print(substring)

# O codigo retorna: 
Ola
```
Neste exemplo ele corta usando o índice, ele acessa a string através do **índice**. 
No exemplo utilizamos o **[]** e dentro dele adicionamos o **:** e o numero do índice que queremos acessar.

* **Substituir*** : Usamos para substituir uma parte de uma string por outra. #replace
```Python 
String = "Paulo Cesar"
substring = "Cesar"
new_string = string.replace(substring, "Python")
print(new_string)

# saida: 
Paulo Python

```
Neste exemplo estamos utilizando o método `replace()` usado para substituir uma string por outra. O método `replace()` e chamado na variavel `string`. Ele procura pela substring `Cesar` e a substitui por `Python`. O resultado dessa operação e armazenado na variavel `new-string`   

### Operadores 
*  **Length** : Usamos para obter o numero de caracteres em uma string
```Python
string = "Paulo Cesar" 
print(len(string))

# Retorno do codigo: 
11
```

* **Slice** : Usamos para extrair uma parte de uma string
```Python
string = "Paulo Cesar" 
substring = slice(1, 5) 
print(string[substring])

# Saida será: 
Hello
```

#slice ele permite que você extraia uma fatia de uma sequencia sem modificar o original. O comando **slice(1, 5)**  cria um objeto que indica que você quer <span style="background:#b1ffff">acessar a parte da string do índice 1 ate o índice 5</span>.