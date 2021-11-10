# [Programação Orientada a Objetos 2020 2021](https://elearning.ual.pt/course/view.php?id`2334) - [UAL](https://autonoma.pt/)

## Laboratório 4

Este laboratório propõe a análise de enunciados para extrair os vários tipos de dados relevantes para cada problema.

Deve construir o diagrama de classes dos enunciados propostos. Estes enunciados são propositadamente ambíguos, e deve justificar as opções de desenho que tomar.

Inclua os vários elementos abordados em POO, nomeadamente:

- Classes, com atributos privados e públicos, e métodos públicos;
- Interfaces, com métodos;
- Relações de associação, agregação, e composição, com as respetivas cardinalidades;
- Relações de extensão, e implementação.

Este laboratório não envolve a escrita de código.

# Tarefas

## Parte 1

Pretende-se criar um programa para gerir uma empresa onde existem diversos tipos de empregados, nomeadamente, vendedores, lojistas e empregados de armazém.

Cada empregado possui um nome e um número de identificação, alem do salário mensal que recebe.

Os lojistas têm ainda um prémio mensal de produtividade e os vendedores recebem um valor de comissões.

## Parte 2

Pretende-se criar um programa capaz de gerir compromissos numa agenda.

Existem vários tipos de compromisso:

- Compromisso de emprego, que ocorre numa determinada data a uma determinada hora, num determinado local;
- Compromisso de aniversário, que corresponde a uma data e a um pessoa;
- Um compromisso do tipo tarefa, que consiste numa descrição da tarefa a realizar e uma data limite para a sua realização;
- Um compromisso do tipo feriado é simplesmente uma data.

## Parte 3

Pretende-se criar um sistema de gestão de uma empresa de rent-a-car.

A empresa dispõe de um conjunto de viaturas para alugar. Entre essas viaturas, encontram-se os tipos mais diversos, desde motos, ligeiros, comerciais, pesados (com e sem reboque) e barcos.

O contrato de aluguer pode ser estabelecido por empresas ou particulares (a título individual ou por em serviço de uma empresa) .

No mesmo contrato pode constar o aluguer de diversas viaturas. Por motivos de promocionais e de faturação, a empresa AlfaRent, necessita de possuir informação sobre:

- A relação familiar entre os particulares (ex: se o marido/esposa tiver alugado anteriormente um veículo, um novo aluguer terá um desconto de 10\%);
- A empresa em nome da qual um particular efetua o aluguer de uma viatura para serviço;
- O volume de vendas efetuado a determinado conjunto de empresas de um grupo económico;
- Após o fim do contrato de aluguer, há emissão de uma fartura onde são descriminados os serviços prestados.

## Parte 4

Pretende-se criar um sistema para gerir o pagamento automático de portagens.

Um cliente do sistema automático é registado com o seu nome, morada, número de identificação, e cartão bancário. Cada cliente pode registar vários veículos, cada um com um identificador atribuído pelo sistema.

Uma passagem na portagem corresponde à leitura do identificador, e é efetuado o registo do dia e hora da passagem do identificador.

Cada passagem registada corresponde à cobrança de um determinador valor (dependente da portagem) ao cartão bancário associado à conta do utilizador.

Quando uma passagem não deteta identificador é retirada uma fotografia da matrícula, e é registada a ocorrência.

## Parte 5

Pretende-se criar um sistema para gerir uma rede ferroviária.

Uma estação ferroviária é composta por 1 ou mais linhas ferroviárias.

Numa linha ferroviária podem estar estacionados diversos recursos ferroviários. Recursos ferroviários são vagões, locomotivas ou comboios.

Um comboio é formado por vagões e locomotivas. Podem existir vagões e locomotivas estacionadas em uma linha sem estarem na formação de um comboio.

Uma estação ferroviária tem uma sigla e uma descrição (que não precisa obrigatoriamente possuir um valor).

Uma linha ferroviária tem um número (que a diferencia de outra linha dentro da mesma estação), uma extensão em metros e uma descrição (que não precisa obrigatoriamente ter um valor).

Um vagão é descrito por um número de série, tipo, capacidade de carga (valor default igual a 3000 ton), comprimento entre testeiras e comprimento dos engates (um único valor correspondendo aos dois lados). Uma locomotiva é descrita por um número de série, capacidade de tração e comprimento.

Um comboio é descrito por um prefixo (ex: NAG1010) e data/hora de formação. Um comboio é formado em uma estação ferroviária de origem e tem como destino, uma outra estação ferroviária, ou seja, a estação de origem não pode ser igual à estação de destino. Todo comboio é formado por pelo menos uma locomotiva e um vagão. A cada 40 vagões, um comboio tem que ter uma locomotiva adicional. Um comboio não pode ter mais do que 150 recursos (vagões e locomotivas).
