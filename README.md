# Calculadora IMC  (Flutter/BloC)
<p><b> Projeto: </b> <i>Flutter com bloc</i>
<p><b>Finalidade:</b> Colocar em pratica arquitetura Bloc utilizando um projeto simples.
<p><b>Missão:</b> Fazer uma caluculadora IMC utiliznado flutter e bloc.
<p><b>Dev: </b>Lucas Francisco Paixão de Gois.

MC significa Índice de Massa Corporal e é uma medida que relaciona o peso e a altura de uma pessoa para avaliar se ela está em um peso saudável ou não.
A fórmula matemática para calcular o IMC é a seguinte:

IMC = peso / (altura x altura)

O resultado do IMC é expresso em kg/m² e pode ser interpretado de acordo com a tabela abaixo:

IMC abaixo de 18,5: abaixo do peso ideal;
IMC entre 18,5 e 24,9: peso saudável;
IMC entre 25 e 29,9: sobrepeso;
IMC entre 30 e 34,9: obesidade grau 1;
IMC entre 35 e 39,9: obesidade grau 2;
IMC acima de 40: obesidade grau 3 (obesidade mórbida).


-------------------------------

## Resumo rapido sobre Bloc (Business Logic Component) 

  * É uma arquitetura de software popular para o desenvolvimento de aplicativos móveis em Flutter. 

  * Oobjetivo principal do Bloc é separar a lógica de negócios do restante do aplicativo, tornando-o mais fácil de entender, testar e manter.

  * A arquitetura Bloc segue os princípios da programação reativa, que é uma abordagem de programação que se concentra na resposta a eventos. Em termos simples, os componentes Bloc recebem eventos (como cliques de botão ou atualizações de dados) e emitem novos estados com base nesses eventos. O restante do aplicativo pode reagir a esses estados atualizados, atualizando a interface do usuário ou executando outras ações relevantes.

### Motivos para utilizar o bloc?

  * Separação de preocupações: O Bloc ajuda a separar a lógica de negócios do restante do aplicativo, o que torna o código mais organizado e fácil de manter.

  * Reatividade: A arquitetura Bloc é reativa por natureza, o que significa que é fácil responder a eventos e atualizar a interface do usuário de forma dinâmica.

  * Testabilidade: Como os componentes Bloc são independentes do restante do aplicativo, é fácil testá-los de forma isolada, o que ajuda a garantir a qualidade do código.
  
  * Reutilização: Como os componentes Bloc são reutilizáveis, é fácil usar a mesma lógica de negócios em vários lugares do aplicativo.



