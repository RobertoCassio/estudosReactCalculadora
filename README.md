# Calculadora React - Estudo
Este projeto consiste em uma calculadora simples desenvolvida utilizando a biblioteca React. O objetivo desse projeto foi desenvolver algumas habilidade básicas em React ao mesmo tempo que me familiarizava com a linguagem através da prática.
Deixando claro que esse foi um projeto de Estudo em que tomei como referência do canal Web Dev Simplified.
![image](https://user-images.githubusercontent.com/116853508/225111493-7538a2de-1909-4960-b86c-433f5c0cf0c6.png)


## Funcionalidades:
- Adição
- Subtração
- Multiplicação 
- Divisão de números
- Limpeza dos Valores Inseridos

## Tecnologias Utilizadas:
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## Funcionamento:
A calculadora foi criada de forma que ao se clicar em um dos botões, a ação correspondente ao mesmo é enviada a um **reducer** que realizará a função de atualizar o estado atual da calculadora. <br>
O estado da calculadora é essencialmente composto do **valor atual** que aparece na parte de baixo do visor junto a operação desejada, e na parte superior o **Valor Anterior** que foi digitado. <br>
A função **Evaluate** avaliará a expressão, recebendo o **valor atual** e fazendo a **operação** correspondente com o **valor anterior** retornando o resultado desejado. <br>
