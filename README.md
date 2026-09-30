# 📚 Sistema de Notas do Aluno

Um programa simples desenvolvido em **Python** para calcular a média final de um aluno a partir de duas notas e informar se ele foi **aprovado ou reprovado**.

## 🎯 Objetivo

Este projeto foi desenvolvido para praticar conceitos básicos de programação em Python, como:

* Funções
* Variáveis
* Entrada de dados com `input()`
* Conversão de dados com `float()`
* Operações matemáticas
* Estruturas condicionais `if` e `else`
* Formatação de números com `f-string`

## ⚙️ Como funciona

O programa solicita ao usuário duas notas:

```text
Digite a primeira nota: 8
Digite a segunda nota: 7
```

Depois, calcula a média das duas notas utilizando a função `calcular_media()`:

```python
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2
```

Por fim, o programa verifica o resultado:

* **Média maior ou igual a 7.0:** APROVADO
* **Média menor que 7.0:** REPROVADO

## 🖥️ Exemplo de execução

```text
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 6
A média final é: 7.00
Status: APROVADO!
```

## 🚀 Como executar

### 1. Pré-requisitos

É necessário ter o **Python 3** instalado no computador.

### 2. Clone o repositório

```bash
git clone https://github.com/seu-usuario/sistema-notas.git
```

### 3. Entre na pasta

```bash
cd sistema-notas
```

### 4. Execute o programa

```bash
python main.py
```

No Windows, também pode ser necessário utilizar:

```bash
py main.py
```

## 📁 Estrutura do projeto

```text
sistema-notas/
│
├── main.py
└── README.md
```

## 🧠 Conceitos praticados

Este projeto é voltado para iniciantes em Python e demonstra principalmente o uso de **funções e estruturas condicionais**.

A função `calcular_media()` recebe duas notas como parâmetros, realiza o cálculo e retorna o resultado.

Depois, o `if` verifica se a média atingiu a nota mínima necessária para aprovação.

## 🛠️ Tecnologias

* **Python 3**
* **VS Code** (opcional)

## 👨‍💻 Autor

**Fabricio Ramos Oliveira**

Projeto desenvolvido para estudos de programação em Python.






























