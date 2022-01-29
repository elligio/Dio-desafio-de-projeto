# Definir seu nome de usuário no Git

- [Sobre nomes de usuários do Git](https://docs.github.com/pt/get-started/getting-started-with-git/setting-your-username-in-git#about-git-usernames)

- [Configurar o nome de usuário do Git para *todos* os repositórios no computador](https://docs.github.com/pt/get-started/getting-started-with-git/setting-your-username-in-git#setting-your-git-username-for-every-repository-on-your-computer)

- [Configurar o nome de usuário do Git para um repositório específico](https://docs.github.com/pt/get-started/getting-started-with-git/setting-your-username-in-git#setting-your-git-username-for-a-single-repository)

- [Leia mais](https://docs.github.com/pt/get-started/getting-started-with-git/setting-your-username-in-git#further-reading)

O Git usa um nome de usuário para associar os commits a uma identidade. O nome de usuário do Git é diferente do nome de usuário do GitHub.

MacWindowsLinux

## Sobre nomes de usuários do Git

Você pode alterar o nome associado aos commits do Git usando o comando `git config`. O novo nome configurado ficará visível em todos os commits futuros cujo push é feito para o GitHub usando a linha de comando. Se não quiser usar seu nome verdadeiro, use qualquer texto como o nome de usuário do Git.

Alterar o nome associado aos commits do Git usando o `git config` afeta somente os commits futuros e não altera o nome usado em commits antigos.

## Configurar o nome de usuário do Git para *todos* os repositórios no computador

1. Abra Git Bash.

2. Defina um nome de usuário do Git:

   ```shell
   $ git config --global user.name "Mona Lisa"
   ```

3. Confirme que você configurou o nome de usuário corretamente no Git:

   ```shell
   $ git config --global user.name
   > Mona Lisa
   ```

## Configurar o nome de usuário do Git para um repositório específico

1. Abra Git Bash.

2. Altere o diretório de trabalho atual para o repositório local no qual deseja configurar o nome associado aos commits do Git.

3. Defina um nome de usuário do Git:

   ```shell
   $ git config user.name "Mona Lisa"
   ```

4. Confirme que você configurou o nome de usuário corretamente no Git:

   ```shell
   $ git config user.name
   > Mona Lisa
   ```

## Leia mais

- "[Configurar endereço de e-mail do commit](https://docs.github.com/pt/articles/setting-your-commit-email-address)"
- ["Configuração do Git" no livro *Pro Git*](https://git-scm.com/book/en/Customizing-Git-Git-Configuration)