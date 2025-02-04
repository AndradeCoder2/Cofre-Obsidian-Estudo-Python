### 4. **Conversão de inteiro para float**

- Isso acontece implicitamente ao usar um `int`em uma`float`.

`x = 5 y = float(x)     # Resultado: 5.0`

### 5. **Conversão de ponto flutuante para inteiro**

- Ao converter de `float`para`int`,

`x = 3.75 y = int(x)       # Resultado: 3`

### 6. **Conversão de tipo complexo para inteiro ou float**

- Você não pode converter diretamente um número complexo para `int`ou `float`sem lidar com a parte real ou imaginária explicitamente.

Exemplos:

```
z = 2 + 3j
real_part = z.real   # Resultado: 2.0
imag_part = z.imag   # Resultado: 3.0

# Conversão apenas da parte real ou imaginária
real_int = int(z.real)  # Resultado: 2
real_float = float(z.real)  # Resultado: 2.0

```

### 7. **Conversões de string para numéricos**

- **`int()`**
    
    `int("123")   # Resultado: 123`
    
- **`float()`**
    
    `float("3.14")   # Resultado: 3.14`
    
- **`complex()`**
    
    `complex("2+3j")  # Resultado: (2+3j)`
    

### 8. **Outras opções implícitas**

- **Operações aritméticas** : Python pode fazer implícitas entre tipos numéricos em operações.
    - Se você somar um `int`com um`float`,`float`.
    - Se você somar um `int`com u`complex`, o resultado será o mesmo`complex`.
```Python
5 + 3.2       # Resultado: 8.2 (float)
5 + 2j        # Resultado: (5+2j) (complex)
3.2 + 2j      # Resultado: (3.2+2j) (complex)
```

### 9. **Funções úteis para conversão de tipos numéricos**

- **`abs()`**: Retorna o valor absoluto de um número.
- **`round()`**: Arredonda um número `float`para o inteiro mais próximo ou para um número de casas decimais especificadas.
- **`pow()`**: Eleva um número a uma potência.


`abs(-5)        # Resultado: 5 round(3.14159, 2)  # Resultado: 3.14 pow(2, 3)      # Resultado: 8`