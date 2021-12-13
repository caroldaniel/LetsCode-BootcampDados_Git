# Aprofundando no Git I

Para melhor versionar seu projeto, garanta que a cada modificação relevante você "diga" ao Git que aquela é uma "versão" que gostaria de controlar. 

O git trabalha da seguinte forma: você tem uma cópia local do repositório, na qual ficam os arquivos e você faz alterações. Depois, você adiciona essas mudanças para a **staging area**, onde elas ficam prontas para serem enviadas em um "bloco", o **commit**, para o repositório. Caso você queira enviar também as mudanças para um repositório remoto, é preciso usar o comando **push**.

Para vermos o que está sendo modificado, usamos os comandos `git status` (que mostra um resumo) ou `git diff` (que mostra as mudanças linha por linha). Para realmente adicionar no commit, usamos o comando `git add`. Com esse comando, podemos selecionar especificamente quais arquivos ou pastas queremos adicionar no commit, ou podemos usar `git add .` ou `git add -A` para adicionar todos de uma vez. Usando o comando `git diff --cached` ou `git diff --staged`, podemos ver as mudanças feitas apenas nos arquivos que já estão na staging area, ou seja, que vão ser enviados no próximo commit.

Depois disso, para criar um commit, usamos o comando `git commit`. Esse comando abre uma janela do editor de texto padrão do sistema operacional, para adicionar uma mensagem de resumo do commit. Esses editores costumam ser meio difíceis de usar, então, pessoalmente, gosto de o modificador `-m`, que permite enviar a mensagem diretamente. O comando fica assim:

```sh
git commit -m "Essa é a mensagem do commit"
```

Os commits são locais, ou seja, eles são só da sua máquina. Eles normalmente são enviados um por um para o servidor, mas você pode usá-los pra se organizar, sem enviar. Depois que você tiver feito quantos commit quiser, e achar que está pronto para enviar seu código para o GitHub, basta executar o comando `git push`. No caso de algum erro, provavelmente seu repositório local está desatualizado, e isso pode ser resolvido com um pull. Caso haja problemas no auto-merge, eu ensino a resolver na parte final da aula. Caso não dê nenhum erro, o seu código já está no GitHub. Em resumo, um commit fica normalmente assim:

```sh
git add .
git commit -m "Mensagem"
git push
```