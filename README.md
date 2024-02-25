#######COMANDOS GIT########

# git init >>> comando para iniciar o git no projeto.

# git status >>> mostra todas as movimentações feita no projetos...

# git add . >>> vai adicionar todoas os arquvos e pastas existente no projeto. podemos usar apenas git add <nome do arquivo> mas o ponto no lugar no nome do arquivo inclui tudo.

# git commit -a -m >>> esse comando salva de fato o arquivo no git, o -a > é para salvar todos os arquivos, -m > é para nomear o que eu fiz e estou salvando. 

# git remote add origin https://github.com/daviribeiroads/tutorial_git.git >>> esse comando peguei no proprio github para lincar os repositorios, do git e github

# git branch -M main >>> Quando você cria um branch em um repositório Git, você está criando uma cópia do código no estado atual, permitindo que você trabalhe nele de forma isolada, sem afetar o código em outros branches. 

# git push -u origin main >>> pega meu repositorio atual e manda para o repositorio do github.

# git checkout -b "teste" >>> o -b cria um novo branch e, o checkout faz a mudança de branch. Assim trabalhamos em repositorios diferentes e depois é spo unir os repoditorio e tornar um só projeto.

#####Depois que fez todo o procedimetno a cima, quando tiver qualquer alteração no projeto, basta apenas da o git commit -a -m "alteração", depois o git push para subir as modificações.

# git push --set-upstream origin teste >>> como foi criado outro branch(repoditorio no github), esse comando vai criar o novo branch no github e mandar os códigos para ele.

# git branch >>> me mostra uma lista dos branch existente e o qual estou ligado.

# git checkout main >>> altera de branch, se eu estava no teste e passo para o main.

# git merge teste >>> eu peguei todas as alterações feita no teste e passei para o main, que é o principal, dessa forma ficaram paricidos.

# git clone https://github.com/daviribeiroads/tutorial_git.git <novo nome> >>> dessa forma agente clona o projet o que esta no github.