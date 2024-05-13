# Classificador-de-N-vel-de-Her-i

Vou criar um texto sobre um classificador de nível de herói, utilizando conhecimentos em estruturas condicionais. Vamos dividir o texto em módulos para facilitar a compreensão.

---

## Módulo 1: Introdução ao Classificador de Nível de Herói

Um classificador de nível de herói é uma ferramenta lógica que determina o nível de um herói com base em vários critérios, como força, inteligência, habilidades especiais e experiência. Este sistema pode ser usado em jogos, histórias ou qualquer cenário onde seja necessário categorizar heróis em diferentes níveis de habilidade.

## Módulo 2: Estruturas Condicionais

Estruturas condicionais são fundamentais na lógica de programação. Elas permitem que o programa tome decisões e execute ações diferentes dependendo das condições especificadas. Em Python, por exemplo, usamos `if`, `elif` e `else` para construir essas estruturas.

```python
if condicao:
    # Executa este bloco se a condição for verdadeira
elif outra_condicao:
    # Executa este bloco se a outra condição for verdadeira
else:
    # Executa este bloco se nenhuma das condições anteriores for verdadeira
```

## Módulo 3: Desenvolvendo o Classificador

Para desenvolver um classificador de nível de herói, primeiro definimos os critérios e os níveis. Por exemplo:

- **Nível 1**: Heróis iniciantes com força básica e pouca experiência.
- **Nível 5**: Heróis com habilidades avançadas e experiência moderada.
- **Nível 10**: Heróis lendários com poderes extraordinários e vasta experiência.

Agora, vamos aplicar as estruturas condicionais para classificar um herói:

```python
def classificar_heroi(forca, inteligencia, habilidades, experiencia):
    if experiencia < 2:
        nivel = 1
    elif 2 <= experiencia < 5:
        nivel = 5
    else:
        nivel = 10
    
    # Adicionamos mais lógica para refinar a classificação
    # com base em força, inteligência e habilidades especiais
    
    return nivel
```

## Módulo 4: Exemplos Práticos

Vamos considerar um herói chamado "Guardião da Luz" com os seguintes atributos:

- Força: 85
- Inteligência: 90
- Habilidades Especiais: 3 (escala de 1 a 5)
- Experiência: 4 anos

Usando nossa função `classificar_heroi`, o "Guardião da Luz" seria classificado como:

```python
nivel_guardiao = classificar_heroi(85, 90, 3, 4)
print(f'O Guardião da Luz é um herói de nível {nivel_guardiao}')
```

Este código retornaria "O Guardião da Luz é um herói de nível 5", indicando que ele é um herói com habilidades avançadas e experiência moderada.

---

Espero que este texto modular tenha ajudado a entender como criar um classificador de nível de herói usando estruturas condicionais.
