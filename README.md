# Atividade 3: Análise Lógica a partir de um Caso Concreto

Este projeto realiza uma análise lógica com base em proposições relacionadas a um caso específico, utilizando JavaScript para gerar a tabela verdade e um diagrama de Venn para visualização das relações entre as proposições.

## Objetivo

A atividade envolve quatro proposições lógicas:

- **P**: Ana vai à festa.
- **Q**: Bruno vai à festa.
- **M**: Bruno traz música.
- **R**: A festa é animada.

O código JavaScript gera a tabela verdade para verificar as seguintes condições lógicas:

1. **P → Q**: Se Ana vai à festa, então Bruno também vai.
2. **(P ∨ Q) → R**: Se Ana ou Bruno vão à festa, então a festa é animada.
3. **¬P → (M → R)**: Se Ana não vai à festa, então a animação da festa depende de Bruno trazer música.

## Como Rodar o Código

1. **Pré-requisitos**: Para rodar o código, é necessário ter um navegador da web (Chrome, Firefox, etc.) que suporte JavaScript.

2. **Passo a Passo**:
   - Copie o código em JavaScript para um arquivo `index.html`.
   - Abra o arquivo `index.html` no navegador.
   - Pressione `F12` para abrir o console do navegador.
   - A tabela verdade será exibida no console, mostrando cada combinação de