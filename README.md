[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YsEblNIV)

# Alerta
Com o intuito de manter o projeto público após a disciplina e preservar a qualidade da entrega, o resultado do trabalho está disponível em [P2P-Chat](https://github.com/luis-fbs/P2P-Chat). 
A branch com as atualizações referentes a essa tarefa é a 'zeromq-migration' (onde abandonei o uso exclusivo de sockets e passei a utilizar o middleware ZeroMQ).

## Sobre a escolha
A versão 1 do projeto, entregue na tarefa anterior, suportava **parcialmente** as operações típicas do serviço de naming. Não obstante, era instável.
Com isso, com o intuito de tornar a aplicação mais estável e ter um serviço de nomes completo sem refatorações extremas, o ZeroMQ foi escolhido, pois possui sintaxe similar à que vinha sendo utilizada com sockets e disponibiliza padrões de mensagens úteis no contexto da aplicação.
