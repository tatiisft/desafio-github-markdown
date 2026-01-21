## Desafio de Projeto - Certificação Git - DIO
#### Repositório para testes e desafios de fixação do uso do Git e Github.

Desafio proposto pela professora [Aline Antunes](https://github.com/alinealien). Com os seguintes objetivos propostos: [acessar desafio](https://github.com/alinealien/desafio-github-markdown.git).

-----
*Desafios:*
1. Adicionar colaborador.
    Adicionei o colaborador através das Configurações do próprio GitHub.
    >Settings --> Collaborators --> Manage access --> Add people

2. Clonar repositório.
    `git clone https://github.com/tatiisft/desafio-github-markdown.git`

3. Realizar alterações e commits.
    1. Incluir detalhes dos desafios 1 e 2 e commitar.
        ``` 
        git status --> Para ver o status de alterações
        git add . --> Para adicionar todas as alterações
        git commit -m "Alterações no projeto" --> Fazendo o commit
        git push origin main --> para enviar os commits
        ```
    2. Tive um erro de autenticação no `git push`. Para resolver esse problema usei o seguintes comandos do Git Bash:
        ```
        git config --global user.name "tatiisft" --> para adicionar meu usuário
        git config --global user.email "taty.freitas201616@gmail.com" --> para adicionar o meu email
        ```
        E repeti os comandos do passo 1. Após fazer novamente o `git push` ele já pede automaticamente as credenciais e realiza o comando.
    
4. Abrir Issues (Feito pelo colaborador).
    > Issues --> New issue --> Add um titulo e uma descrição.
    O colaborador (colocar o @) me sugeriu ....
    Eu resolvi de tal forma 
    E respondi sua issue marcando com o fixed #1

5. Criar nova branch e realize o merge.
    ```
    git branch v1 --> cria a branch
    git checkout v1 --> troca a branch
    ```
    Realizei alterações no README.md, voltei para a main e fiz o merge:
    ```
    git checkout main 
    git merge v1 
    ```
    Voltei para branch v1 e fiz o push dela para o repositório remoto.
    ```
    git checkout v1 
    git status 
    git add . 
    git commit -m "incluindo branch v1" 
    git push origin v1
    ```

