# Automação de Cadastro com PyAutoGUI

Este projeto realiza a automação do preenchimento de um sistema web utilizando Python.

O programa abre o navegador, acessa a página de login, realiza o login automaticamente e cadastra produtos com base em dados armazenados em um arquivo CSV.

A automação foi desenvolvida utilizando a biblioteca PyAutoGUI para controlar o mouse e o teclado, e Pandas para leitura e manipulação da base de dados.

---

## Tecnologias utilizadas

- Python
- PyAutoGUI
- Pandas

---

## Como funciona

1. O script abre o navegador Google Chrome.
2. Acessa a página do sistema de cadastro.
3. Realiza o login automaticamente.
4. Lê os dados do arquivo `produtos.csv`.
5. Para cada linha da tabela, o script:
   - preenche os campos do formulário
   - envia o cadastro
6. O processo se repete até cadastrar todos os produtos da planilha.

---

## Observação

Este script utiliza coordenadas fixas do mouse (x e y).
Dependendo da resolução da tela ou da posição da janela do navegador, pode ser necessário ajustar essas coordenadas.