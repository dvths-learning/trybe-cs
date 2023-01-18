# Boas Vindas ao repositório de Introdução à Python

## Neste repositório você vai encontrar exercícios de treino dos conceitos iniciais à linguagem Python.

# Detalhamento sobre os exercícios

<details>

<summary> Operações Básicas </summary>
<br>

### Os exercícios relacionados às operações básicas na linguagem `Python` estão localizados no arquivo `exercises/basic_operations.py` e o que se espera de cada um destes exercícios está detalhado abaixo:

<br>

1. A função abaixo deve receber dois números e retornar o valor correspondente à soma dos mesmos.

```python
def basic_sum(first_number, second_number):
    return 
```

2. A função abaixo deve receber dois números e retornar o valor correspondente à diferença do primeiro número em relação ao segundo.

```python
def basic_difference(first_number, second_number):
    return 
```

3. A função abaixo deve receber dois números e retornar o valor correspondente ao produto dos mesmos.

```python
def basic_product(first_number, second_number):
    return 
```

4. A função abaixo deve receber dois números e retornar o valor correspondente à divisão do primeiro com o segundo número.

```python
def basic_division(first_number, second_number):
    return 
```

5. A função abaixo deve receber dois números e retornar o valor correspondente à divisão inteira (quociente) do primeiro com o segundo número.

```python
def basic_integer_division(first_number, second_number):
    return 
```

6. A função abaixo deve receber dois números e retornar o valor correspondente ao resto da divisão entre o primeiro e o segundo número.

```python
def basic_remainder(first_number, second_number):
    return 
```

7. A função abaixo deve receber dois números e retornar o valor correspondente ao primeiro número elevado ao segundo.

```python
def basic_potentiation(first_number, second_number):
    return 
```

</details>

---

<br>
<details>

<summary> Tipos de Dados em Python </summary>
<br>

### Os exercícios relacionados aos tipos de dados no `Python` estão localizados no arquivo `exercises/python_data_types.py` e o que se espera de cada um destes exercícios está detalhado abaixo:


<br>

1. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo booleano.

```python
def is_bool(value):
    return 
```

2. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo inteiro.

```python
def is_int(value):
    return 
```

3. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo float.

```python
def is_float(value):
    return  
```

4. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo string.

```python
def is_string(value):
    return 
```

5. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo lista.

```python
def is_list(value):
    return 
```

6. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo tupla.

```python
def is_tuple(value):
    return 
```

7. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo conjunto.

```python
def is_set(value):
    return 
```

8. A função abaixo deve verificar se o valor recebido como parâmetro é do tipo dicionário.

```python
def is_dict(value):
    return 
```

9. A função abaixo recebe uma string genérica como parâmetro e deve retornar a mesma string, no entanto, todos os caracteres maiúsculos devem ser convertidos em minúsculos.

```python
def return_lower_case_string(word):
    return 
```

10. A função abaixo recebe um elemento e uma lista como parâmetros e deve retornar a mesma lista, mas agora contendo o elemento em sua última posição.

```python
def append_element_in_list(element, input_list):
    return 
```

11. A função abaixo recebe um elemento e uma lista como parâmetros e deve retornar a mesma lista, mas agora removendo o elemento passado como parâmetro.

```python
def remove_element_from_list(element, input_list):
    return 
```

12. A função abaixo recebe uma chave, um valor e um dicionário como parâmetros e deve retornar o mesmo dicionário contendo o novo par chave: valor.

```python
def create_new_key_value_in_dict(key, value, input_dict):
    return 
```

13. A função abaixo recebe uma chave e um dicionário como parâmetros e deve retornar o mesmo  dicionário, mas agora removendo a chave passada como parâmetro.

```python
def delete_key_from_dict(key, input_dict):
    return 
```

14. A função abaixo recebe um elemento e um conjunto como parâmetros e deve retornar o mesmo conjunto contendo o elemento.

```python
def add_element_to_set(element, input_set):
    return 
```

15. A função abaixo recebe um elemento e um conjunto como parâmetros e deve retornar o mesmo conjunto removendo o elemento passado como parâmetro

```python
def remove_element_from_set(element, input_set):
    return 
```


</details>

---

<br>
<details>

<summary> Condicionais </summary>
<br>

<br> 

1. A função abaixo deve verificar se a string passada como parâmetro possui 4 ou mais caracteres, em caso positivo, deve retornar `True`, em caso negativo, retornar `False`.

```python
def check_if_word_has_4_or_more_letters(word):
    return 
```

2. A função abaixo recebe dois números como parâmetros e deve retornar aquele que é maior entre eles, em caso de igualdade, o retorno pode ser qualquer um dos dois.

```python
def check_what_number_is_greater(first_number, second_number):
    return 
```

3. A função abaixo deve verificar se o número recebido como parâmetro é par ou ímpar. Caso seja par, a função deve retornar `"even"`, caso seja ímpar, deve retornar `"odd"`.

```python
def check_if_number_is_odd_or_even(number):
    return 
```

4. A função abaixo recebe um elemento e uma lista como parâmetros e deve verificar se o elemento está contido na lista, em caso positivo, deve retornar `True`, em caso negativo, retornar `False`.

```python
def check_if_element_exists_in_list(element, input_list):
    return 
```

</details>

---

<br>
<details>

<summary> Repetição </summary>
<br>

<br>


1. A função abaixo recebe uma string como parâmetro e deve retornar uma lista contendo cada um dos caracteres da string. A ordem dos caracteres na lista deve ser a mesma ordem da string.

```python
def append_each_letter_of_the_word_in_a_list(word):
    return 
```

2. A função abaixo recebe uma string genérica que tem apenas uma letra maiúscula como parâmetro. A função deve retornar o número que corresponde ao índice (posição) da letra maiúscula na string.

```python
def return_index_of_the_uppercase_letter(word):
    return
```

3. A função abaixo recebe uma lista como parâmetro na qual apenas um de seus elementos é uma string. A função deve retornar esse elemento.

```python
def return_element_from_list_that_is_string(input_list):
    return 
```

</details>

---
