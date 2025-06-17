# Desafio-logica-dio2# 🧮 Calculadora de Partidas Rankeadas

Este projeto é uma calculadora de desempenho de partidas ranqueadas, desenvolvida em **linguagem C**, com o objetivo de aplicar os conceitos de:

- ✅ Variáveis
- ✅ Operadores
- ✅ Laços de repetição
- ✅ Estruturas de decisão
- ✅ Funções

## 🎯 Objetivo

Criar uma função que recebe como parâmetros a **quantidade de vitórias** e **derrotas** de um jogador, calcula o **saldo de vitórias** (vitórias - derrotas) e define o **nível do jogador** de acordo com a seguinte regra:

| Vitórias           | Nível     |
|--------------------|-----------|
| Menor que 10       | Ferro     |
| 11 a 20            | Bronze    |
| 21 a 50            | Prata     |
| 51 a 80            | Ouro      |
| 81 a 90            | Diamante  |
| 91 a 100           | Lendário  |
| 101 ou mais        | Imortal   |

---

## 💻 Como executar

### 🔧 Compilando

No terminal, execute:

```bash
gcc -o rankeadas rankeadas.c
./rankeadas
No Windows (com GCC instalado):

bash
Copiar
Editar
gcc -o rankeadas.exe rankeadas.c
rankeadas.exe
🖥️ Exemplo de saída
markdown
Copiar
Editar
Digite o número de vitórias: 55
Digite o número de derrotas: 12

O Herói tem de saldo de **43** está no nível de **Ouro**
📁 Estrutura
bash
Copiar
Editar
rankeadas/
├── rankeadas.c      # Código-fonte em C
└── README.md        # Documentação do projeto
📌 Observações
O programa permite repetir o cálculo quantas vezes o usuário quiser.

Ideal para treinar lógica e estrutura básica de programação em C.

🚀 Autor
Desenvolvido como parte de um desafio prático de lógica de programação.
