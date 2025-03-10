# Desafio Classificador de Nível de Herói

Este desafio tem como objetivo criar um classificador de nível para heróis baseado na quantidade de experiência (XP) adquirida. Utilizando variáveis, operadores, laços de repetição e estruturas de decisão, o sistema determina em qual categoria de nível o herói se encontra.

## Tecnologias Utilizadas
<img src="https://github.com/user-attachments/assets/6da83f7d-643d-472e-8f48-f55ca6e2344e" width=150px title="Node.js"/>
<img src="https://github.com/user-attachments/assets/efcd142f-f2fa-46ad-80ee-8e66fa53cd23" width=150px title="Node Package Manager"/>

- **Node.js**
- **Prompt-sync** (pacote para entrada de dados no terminal)

## Objetivo

O desafio consiste em criar um programa onde o usuário fornece o nome e a quantidade de XP de um herói. O programa então classifica o herói em um dos seguintes níveis, com base no valor da XP:

- **XP < 1000**: Ferro
- **1001 <= XP <= 2000**: Bronze
- **2001 <= XP <= 5000**: Prata
- **5001 <= XP <= 7000**: Ouro
- **7001 <= XP <= 8000**: Platina
- **8001 <= XP <= 9000**: Ascendente
- **9001 <= XP <= 10000**: Imortal
- **XP >= 10001**: Radiante

Ao final, o sistema exibe a mensagem com o nome do herói e seu nível correspondente.

## Como Executar

1. Certifique-se de ter o **Node.js** instalado. Caso não tenha, você pode baixar e instalar [aqui](https://nodejs.org/).
2. Crie um arquivo `.js`, por exemplo `classificador.js`, e cole o código fornecido nele.
3. 3. Instale o pacote `prompt-sync` utilizando o seguinte comando:

    ```bash
    npm install prompt-sync

4. Após a instalação do pacote, execute o código com o seguinte comando:

   ```bash
   node classificador.js

## Descrição do Código

- Entrada de Dados: O código começa solicitando ao usuário o nome e a quantidade de XP do herói, utilizando o pacote prompt-sync.
- Estruturas de Decisão: Com a quantidade de XP fornecida, o código verifica em qual faixa de XP o herói se encaixa, atribuindo um nível correspondente.
- Saída: Ao final, o programa exibe uma mensagem informando o nome do herói e seu nível correspondente.

## Conclusão

Esse desafio foi desenvolvido para praticar o uso de variáveis, operadores, laços e estruturas de decisão em Node.js. Ao final, conseguimos classificar um herói de acordo com a experiência adquirida, facilitando a visualização do nível do herói em um jogo ou sistema de RPG.
