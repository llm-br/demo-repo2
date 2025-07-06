# Demo 2 Alex
Some text

![image](https://github.com/user-attachments/assets/8f633540-de87-45af-a8aa-9748d72c4d15)
Um histórico de commits simples

Para criar um novo branch (ramificações) e mudar para ele ao mesmo tempo, você pode executar o comando git checkout com o parâmetro -b:

$ git checkout -b iss53
Switched to a new branch "iss53"
Esta é a abreviação de:

$ git branch iss53
$ git checkout iss53

![image](https://github.com/user-attachments/assets/44ba8007-705c-4a45-a1ea-7137a5293c59)
Criando um novo ponterio de branch

Você trabalha no seu website e adiciona alguns commits.

Ao fazer isso, você move o branch iss53 para a frente, pois este é o branch que está selecionado, ou checked out(isto é, seu HEAD está apontando para ele):

$ vim index.html
$ git commit -a -m 'Create new footer [issue 53]'

![image](https://github.com/user-attachments/assets/8894ade1-6b12-4e18-8303-27027ce32c25)
O branch iss53 moveu para a frente graças ao seu trabalho






