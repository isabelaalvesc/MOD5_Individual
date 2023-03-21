<h1 align="center"> # Projeto Individual - Módulo 5 - Resilia/Senac </h1>
Trabalho individual do módulo 5 do curso Programadores Cariocas.

## Proposta do trabalho:
Proposta do trabalho:
Vamos usar o Node para montar um código que vai receber uma lista de propriedades de CSS (ex: background-color, font-size, text-align) e vai devolver essa lista ordenada de A-Z. Ordenar o CSS ajuda a encontrar mais rápido a propriedade que precisamos alterar.

➔ O código deve rodar em um laço que vai receber propriedades até a pessoa digitar a palavra “SAIR”, quando isso acontecer vai ser impresso no terminal a lista das propriedades ordenadas de A-Z uma em cada linha.

## Resolução:

Segue imagem com exemplo da aplicação funcionando:

Inicialmente a aplicação retorna a seguinte mensagem:

![Screenshot_1](https://user-images.githubusercontent.com/113736997/226751497-edded993-e1d6-4753-88b7-3a389604364b.png)

O primeiro texto digitado no exemplo é "font-size":

![Screenshot_2](https://user-images.githubusercontent.com/113736997/226752297-aa132c91-5faa-43ca-b250-9dc9a817cec9.png)

Recebemos a mensagem de confirmação "Propriedade adicionada" e percebemos que o texto foi incluído ao array.

Em seguida setamos o texto "background-color":

![image](https://user-images.githubusercontent.com/83782674/224347681-fbc40435-231a-4987-885d-d04c13a4fc86.png)

Percebemos que após receber o texto "background-color" o array já se reordenou de forma correta.

Seguimos assim até o usuário digitar "sair" quando acontece o fim da aplicação e a mesma finalmente apresenta todas as propriedades em ordem alfabética.

![Screenshot_4](https://user-images.githubusercontent.com/113736997/226753599-7f842133-aafb-4203-85d4-579fed413d1a.png)

Caso o usuário digite "sair" no início da aplicação, a mesma retornará que a lista está vazia.

![Screenshot_5](https://user-images.githubusercontent.com/113736997/226753951-b1977ebb-49ac-46b4-8bfe-999d54958f91.png)

## :wrench: Tecnologias utilizadas
* NodeJS

## :wrench: Dependências utilizadas
* Prompt-sync

## :handshake: Colaboradores
👩🏻‍💻 Trabalho autoral de <a href="https://github.com/isabelaalvesc">Isabela Alves</a>

## :dart: Status do projeto
Projeto Finalizado
