# Curso de javascript 
# Descrição
* JavaScript é uma linguagem de programação amplamente utilizada para desenvolvimento web. <br>
* Ela é executada nos navegadores dos usuários e permite a criação de páginas interativas.<br>
* JavaScript é uma linguagem de script versátil, capaz de manipular o conteúdo da página, responder a eventos do usuário e interagir com servidores para atualizações dinâmicas. <br>
* Ela desempenha um papel fundamental na construção de experiências interativas e dinâmicas na web.

  # *[Exercício 1 ](https://github.com/ByancaMatos01/javascript/tree/main/Javascript)*
   * Escrever olá mundo e aprender usar três funções basicas window.alert() para alertar coisas antes de carregar a página.<br>
   ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/25bf8e15-9256-4620-b879-067e38e236bd)
   * window.confirm() utilizado para confirmar uma mensagem
     ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/84c0f3d5-69f8-4cd4-9ff6-4c6a8bfacb07)
  * E window.prompt() permite que voce escreva em uma pequena caixa de texto.
    ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/1af6283c-ee6d-4458-865d-e52ea887255d)

    # Aula 2 **Manipualação de dados**

 # *[Exercício 1 ](https://github.com/ByancaMatos01/javascript/blob/main/aula02/exerc01.html)*
  * Utiliza var que é armazenar o dados através de uma váriavel, e concatena com uma mensagem de boas vindas
  * foi utilizado o comando window.prompt()

![image](https://github.com/ByancaMatos01/javascript/assets/122841376/c9e7cafe-9dd0-4318-8df3-692f24f9a4d4)
![image](https://github.com/ByancaMatos01/javascript/assets/122841376/b8b56a02-1f63-418c-8fab-b705c7994593)


 # *[Exercício 2 ](https://github.com/ByancaMatos01/javascript/blob/main/aula02/exerc02.html)*
* Faça um programa para ler dois valores inteiros, e depois mostrar na tela a soma desses números com uma
mensagem explicativa, conforme exemplos. <br>
![image](https://github.com/ByancaMatos01/javascript/assets/122841376/f4712381-c8a2-4e35-800c-559018b567c3)
![image](https://github.com/ByancaMatos01/javascript/assets/122841376/fa77be62-2d7f-4790-8ea2-122b44fc6011)
* Foi utilizado o comando de converter para number.parseInt()==> para inteiros
*  Ou number.parseFloat()==> para números reais
*  Também a formas simplificadas apenas utilizando Number()
*  Para String utiliza-se String() ou toString() <br>
![image](https://github.com/ByancaMatos01/javascript/assets/122841376/3dbeb1df-53db-40ea-854b-236e5eb6c123)

# *[Exercício 3 ](https://github.com/ByancaMatos01/javascript/blob/main/aula02/exerc03.html)*
* Tratando Strings, neste exercicios utilizamos document.write() para escrever na tela aquilo que usuario digitava pelo window.prompt()
* Foi utilizado a função toUpperCase() para deixar tudo em maíusculo
* Também foi utilizado a função toLowerCase() para deixar tudo em minúsculo
*  E a função length para contar as strings <br>
![image](https://github.com/ByancaMatos01/javascript/assets/122841376/b5e36642-d9fb-4711-a8bd-4dcb0f385993)

# Formatando number 
* Através do node.js aprendi a formatar numbers
* toFixed()==> colocar valor nos conchetes para saber a quantidade de casa após a virgula
* Junto com replace('.',',') troca o ponto pela virgula
* E foi aprendido o comando tolocale('pt-Br', {style 'currency', currency: 'BL'}) para utilizar o estilo de moeda do pais

  #  *[Aula de DOM ](https://github.com/ByancaMatos01/javascript/tree/main/aula03)*
  
  # Descrição 
  * Document Model Object é a vertente do JavaScript, pro qual a linguagem foi criada. <br>
  * Conjunto de objetos dentro do navegador que vai dar acesso aos componentes internos do web site
  * Começa na raiz (window)
  <div> Pode ser Selecionado por: </div>
  <ul> Marca </ul>
  <ul> Id</ul>
  <ul> Nome </ul>
  <ul> Classe</ul>
  <ul> Seletor</ul>
# Comandos Básicos 
* Os comandos aprendidos foram document.body() dentro de uma var voce pode alterar o que estiver na parte body do html
* Para pegar um elemento por tag utilizamos document.getElementsByTagName()==> coloca a tag e se tiver mais de uma ao lado colocar [] e numero de qual quer
* innerText pega o que está escrito do elemento que voce quer exemplo: p1.innerText
* Ou para pegar com a configurações HTML innerHTML
* getElementById para pegar elemento por id 
* getElementByName para pegar o elemento por nome 
* getElementByClassName para pegar o elemento por classe
*  querySelector e para pegar por seleção
*  Usamos . para div e # para classe no seletor. <br>

# *[Exercício 1 ](https://github.com/ByancaMatos01/javascript/blob/main/aula03/exerc1.html)*
* Exercicio para testar estrutura arvore basica do DOM
    ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/ce328235-f9b2-4d59-bec3-c475fe85688e)

# *[Exercício 2 ](https://github.com/ByancaMatos01/javascript/blob/main/aula03/exerc2.html)*
* Exercício de Função usando o click, mouseenter e mouseout
  <br>
  ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/3a0ab37f-5092-4e04-92df-111a73be9d11)
  * Com click
   ![2024-01-17](https://github.com/ByancaMatos01/javascript/assets/122841376/275e383f-16a8-4ea5-878f-a6593e810e7a)
   * Com mouseenter
     <br>
  ![2024-01-17 (1)](https://github.com/ByancaMatos01/javascript/assets/122841376/584025ef-4713-4d0f-ba22-ea43a792b363)

  * Com mouseout
    <br>
  ![2024-01-17 (2)](https://github.com/ByancaMatos01/javascript/assets/122841376/877e13ac-bdf3-44c8-a92b-f8342636c400)

# *[Exercício 3 ](https://github.com/ByancaMatos01/javascript/blob/main/aula03/exerc3.html)*
* Exercicio de soma usando javascript
 ![image](https://github.com/ByancaMatos01/javascript/assets/122841376/42690cf9-f24b-43a4-a744-1119bac9cb97)

# Condicionais em JS






 



  




    
