# Jogo de par e ímpar

A proposta desse projeto é realizar um jogo de par ou ímpar simples utilizando python. O usuário deve digitar um número qualquer, o computador irá aleatóriamente gerar um número e se a soma do número for a opção que ele escolheu (par ou ímpar), ele ganha, senão ele perde.
O jogo deve ser infinito, sendo apenas encerrado caso o usuário determinar.

# Proposta

Para fazer nosso jogo, vamos definir o que desejamos dele:

* Deve ser um jogo continuo. O jogo só será desativado caso o usuário especifique;
* O jogo deve ter tratamento de erros para caractéres inválidos;
* Teve haver um sistema de vidas, onde o usuário perde uma vida para cada erro.
* O usuário poderá sair do jogo a qualquer momento que dele desejar.

## Identificação de usuário

### Escolha de nome de usuário

O jogo iá iniciar perguntando o nome do usuário:

![escolha-nome](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/escolha-nome.png)

### Tratamento de erro I: 

Caso o jogar digite um caracté que não seja alfabetico, será gerado um erro e entrará em um loop até que digite um nome válido.

![tratamento-erro-1](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/tratamento-erro-1.png)

### Formatação de nome:

Independente da forma que o usuário digite o nome dele, se houver apenas caractéres válidos, o código irá formatar o texto com a primeira letra maiúscula:

![formatacao-nome-1](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/formatacao-nome-1.png) ![formatacao-nome-2](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/formatacao-nome-2.png) ![formatacao-nome-3](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/formatacao-nome-3.png)

## Início do jogo

O jogo irá questionar ao usuário se ele deseja jogar:

![inicio_jogo_1](https://github.com/xpcosmos/simulador-de-dados/blob/main/assets/inicio_jogo_1.png)

### Tratamento de erro:

Caso o usuário entrar com uma opção diferente de "S" ou "N", o jogo entrará em um loop até que ele fornceça uma entrada válida:
Independente ser maiúsuclo ou minúsculo, o código irá aceitar a resposta, desde que seja ou 'S' ou 'N':
Se o usuário digitar 'N', o computador irá encerrar o jogo.

![inicio_jogo_1](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/inicio-jogo-1.png)

## Jogando...

O computador irá questionar se o usuário deseja ser ímpar ou par. 
Se o usuário digitar alguma opção fora das oferecidas, ocorrerá um tratamento de erro similar ao utilizado acima.

![escolha-p-i](https://github.com/xpcosmos/jogo-impar-ou-par/blob/main/assets/escolha-p-i.png)

Após a escolha do usuário, o computador irá perguntar o número que ele irá jogar:

![image](https://user-images.githubusercontent.com/85235525/139922071-5a8e45a0-c229-42ec-85f7-03b295079e11.png)

Dependendo da escolha do usuário, o computador irá mostrar declarar vitória ou derrota.

![image](https://user-images.githubusercontent.com/85235525/139922472-0459fca4-8bf6-4985-a01a-1b0f9dd43f6d.png)

Ao fim das vidas, o usuário terá a oportunidade de jogar novamente:

![image](https://user-images.githubusercontent.com/85235525/139922713-e259df4a-a325-446a-a491-0d6e0436df31.png)

Se o usuário digitar 'S', suas vidas irão se encher novamente e poderá reiniciar o jogo.

## Considerações finais

O jogo foi estruturado para que o usuário pudesse sair no momento em que quisesse. Independente do ponto em que está, se digitar "sair", o jogo irá ser encerrado.
Foi pensado também em métodos de tratamento de erros. Presumi que poderia ocasionalmente haver erros de digitação, por isso realizei diversos tratamentos de erros.

# Tecnologias utilizadas

* Jupyter Lab
* Python
* Biblioteca _random_.

# Autor

<a href="https://www.linkedin.com/in/mikeias-d-s-o/"><img src="https://github.com/xpcosmos/simulador-de-dados/blob/main/assets/linkedin.png" alt="linkedin" width="20"></a> <a href="mailto:mikeias.d.s.o@gmail.com"><img src="https://github.com/xpcosmos/simulador-de-dados/blob/main/assets/gmail.png" alt="gmail" width="20">

# Licença
  
MIT License

Copyright (c) 2021 xpcosmos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
