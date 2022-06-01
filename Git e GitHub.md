# GIT

#### E-mail e Usuário:

- git config --global user.name "Nome"
- git config --global user.email "Email"

#### Para trocar:

- git config --global --unsent user.name/email

​	Isso deletara seu nome ou e-mail, depois é só adicionar um novo com o código de cima.

​	Para  uso futuro, recomendado que nome e e-mail sejam os mesmo tanto no git quanto github.



#### Comandos:

- ls - Lista de diretórios contidos na pasta.
- ls -a - Mostra arquivos ocultos não exibidos só com ls.
- dir - Mesma função que ls mas no Windows.
- cd 'nome da pasta' - Navegar entre as pastas.
- cd .. - Retroceder uma pasta/ voltar para pasta anterior.
- cls/clear/ctrl + L - Limpa a tela.
- tab - auto completa o nome da pasta ou arquivo.
- mkdir 'nome da pasta' - Cria uma pasta.
- echo exemplo - Ira retornar a frase digitada, no caso 'exemplo'
- echo exemplo > exemplo.txt - Ira criar um arquivo com o nome 'exemplo'
- del - deleta somente arquivos
- rmdir exemplo - deleta repositório com nome exemplo
- rm - mesmo que rmdir so que usado em linux.
- mv exemplo1 ./ exemplo2 - Move o exemplo1 para o exemplo2.



#### Criar commit:

- git init - inicializa a operação do git no repositório.
- git add \* - Faz uma atualização de modificações / Move para staged.
- git commit -m "exemplo" - Exemplo e a mensagem  que se adiciona para saber o que foi feito no commit / É feito o commit.
- git status - Traz informações sobre o commit



#### Se feita alterações nos arquivos:

- git add exemplo - Adiciona o arquivo para ser commited.
- git rm exemplo - Deleta o arquivo.
- git restore --staged exemplo - Tira arquivo da area de staged.



#### Enviar para o GitHub(passo a passo):

###### No GitHub:

- Criar repositório em GitHub.
- Copiar link dado na pagina.

###### No git:

- git remote add origin 'link copiado'.
- git remote -v : Ira listar repositorios remotos cadastrados.
- git push origin master : Envia codigo para o GitHub.



###### Para clonar do GitHub para Git:

- git clone 'Link do arquivo que quer clonar'.

