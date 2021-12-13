# Praticando o Git
### *por Carolina Daniel*

----

Crie um repositório do Git para compartilhar aquilo que você aprendeu sobre Linux e Git, os conteúdos que vimos ao longo deste módulo.

Para isso, crie uma pasta com o nome `linux-e-git`. Em seguida, você deve criar um arquivo referente a cada uma das aulas que tivemos e comentar sobre quais pontos você achou mais interessante e mais agregaram ao seu conhecimento. As aulas que tivemos, em ordem, são elencadas abaixo:

1. Introdução ao Linux + Instalação da VM (Ex.: O que é Linux?)
2. Principais comandos do Terminal Linux (Ex.: Quais comandos você achou mais interessantes?)
3. Introdução ao Git (Ex.: O controle de versão)
4. Git na Prática
5. Aprofundando no Git I
6. Aprofundando no Git II

## Instruções

- Você deve iniciar com a branch `main`. Nela você vai adicionar um arquivo [README.md](http://README.md) que deverá conter:
    - O título desta atividade: Praticando o Git
    - Seu nome
    - E, em seguida, toda a descrição desta tarefa, que se encontra nesse documento.
    - E este será o seu primeiro commit.
- Logo após, você deve criar uma branch para a primeira parte do módulo, o Linux. Nessa branch, referente ao Linux, você irá adicionar os dois arquivos relacionados às aulas sobre Linux (Aulas 01 e 02).
- Ao terminar, você pode fazer um merge desta branch com a `main`.
- Em seguida, você deve criar uma nova branch, a partir da `main`, referente a parte de Git. Nela você vai adicionar os arquivos referentes às aulas de Git.
- Ao concluir, você deve fazer um merge desta branch com a `main`.

<aside>
💡 **Não apague as branches. Mantenha as 3 branches no seu projeto.**

</aside>

### Ignorando um arquivo

Ao concluir toda a parte descrita anteriormente, você deverá criar um novo arquivo: `minhas_senhas.txt`. Esse arquivo vai conter a senha que você colocou no Ubuntu, quando o instalou na máquina virtual, além da sua senha do GitHub. Mas, calma... Você vai adicionar esse arquivo no `.gitignore`, porque ele não deve entrar no seu histórico de versionamento.

<aside>
💡 Sinta-se a vontade para colocar senhas fakes, certo? A ideia é apenas relembrar o funcionamento do arquivo `.gitignore`.

</aside>

## Requisitos

- Cada arquivo deve ser adicionado em um commit diferente.
- Você pode fazer mais de um commit referente a um mesmo arquivo, porém, não pode adicionar dois arquivos (referente a duas aulas), ao mesmo tempo, em um commit.
- Você deve criar uma pasta para cada parte do módulo: `Linux` e `Git`. Dentro de cada uma delas, você vai adicionar os seus arquivos.