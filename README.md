<p align="center">
  <img width="250px" src="https://kinsta.com/pt/wp-content/uploads/sites/3/2020/04/ferramentas-de-revisao-de-codigo-1024x512.png">
</p>
<h1 align=center>Abstraindo um Bootcamp Usando Orientação a Objetos em java</h1>

# :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: :coffee: #

>Desmistifique a Programação Orientada a Objetos (POO) com Java e pratique esse conceito fundamental nesse desafio. Para isso, os pilares da OO são devidamente formalizados: Abstração, Encapsulamento, Herança e Polimorfismo. Com isso, você poderá desenvolver sua capacidade de abstração com um problema real e implementar as evoluções que achar interessantes ;-)

<p align=center>
  <img width="80%" src="https://user-images.githubusercontent.com/13790608/230703266-64e2f693-de64-458a-b56b-cbf4f75b796b.png"/>
</p>

Fonte: <a href=https://github.com/cami-la/desafio-poo-dio>desafio-poo-dio<a> da instrutora Camila Cavalcante da DIO.

## :pencil: Funcionalidades

:white_check_mark: ``Bootcamp``
- Cria um Bootcamp;
- Aceita matrícula de Devs;
- Aceita cadastro de Conteúdos:
  - Cursos;
  - Mentorias;
  
:white_check_mark: ``Dev``
- Cria um Dev;
- Inscreve em um Bootcamp;
- Progride em um Bootcamp (consumindo conteúdos);
- Calcula o XP total adquirido;
- Imprime Bootcamp inscrito e seus respectivos Conteúdos;
- Imprime progresso:
  - Porcentagem concluída de cada Bootcamp;
  - Conteúdos restantes;

:white_check_mark: ``Conteúdo (classe abstrata)``
- Curso (herda de Conteúdo):
  - Cria um Curso;
  - Calcula XP de acordo com a carga horária;
- Mentoria (herda de Conteúdo):
  - Cria uma Mentoria;
  - Tem XP fixo (não tem carga horária);
  

