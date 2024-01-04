# DIO - Trilha .NET - Fundamentos

Meu primeiro projeto para o desafio da trilha .NET do Decola Tech Avanade - 2024.

Para este desafio, foi preciso usar os conhecimentos adquiridos no módulo de fundamentos. 

## Desafio de projeto - Sistema de Estacionamento 🚗

<img height="350" src="https://i.imgur.com/Xc5aUSU.jpg">

## Contexto 🚗
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Solução 🚗
Foi disponibilizado o código pela metade, sendo necessário dar continuidade obedecendo as regras descritas abaixo, para que no final, tenhamos um programa funcional. As palavras comentadas "TODO" no código, foram substituidas pela solução conforme as regras passadas.

## Proposta 🚗
Construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

### Deverá ser feito um menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

### A classe contém três variáveis, sendo:

- **precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

- **precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

- **veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

### A classe contém três métodos, sendo:

- **AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

- **RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

- **ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

## Resultado do projeto
| Cadastrar | Remover  |
|:--------: |:--------:|
|![print1](https://i.imgur.com/RAe3fnY.png)|![print2](https://i.imgur.com/AlggqxL.png)|
| Listar | Encerrar  |
|![print3](https://i.imgur.com/dnSOv4W.png)|![print4](https://i.imgur.com/IWP5O0R.png)|

## Tecnologias utilizadas  🚗

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) <img height="28" src="https://i.imgur.com/RJt65d2.png"> ![Vscode](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)