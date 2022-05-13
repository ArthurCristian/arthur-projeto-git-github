# Guia de comandos :keyboard:

## Para começar :new:

- Utilize da linha de comando: "**ssh-keygen -t ed25519 -C (e-mail)**" para conseguir dois tipos de chave, uma privada e outra pública, e registre sua chave pública na sua conta do GITHUB para ajudar na identificação e autenticação entre seu repositório local e remoto. 
- Prosseguindo com a preparação de seu ambiente local, lembre-se de registrar suas informações com: (**git config --global user.email "email@gmail.com"**) _e_ (**$ git config --global user.name "Nome"**). Estabelecendo sua identidade para o registro de versionamento futuro.



- Utilize o comando '_git init_' em um diretório de sua escolha para torná-lo um repositório GIT.

- Você também pode transferir um repositório criado direto da plataforma do GITHUB para o seu computador, utilizando do comando "**_git clone_ (link do repositório)**". Criando uma cópia do repositório dentro do diretório desejado, em seu ambiente local.



## Atualizando seu repositório :recycle:

Os arquivos e diretórios de seu repositório irão passar por mais de uma fase durante seu ciclo de vida. Tendo um ciclo de **não modificado** >>> **modificado** >>> **preparado**.  Também possuindo um estado de **ausente** quando removidos.



**git status**: Este comando apresenta uma descrição sobre a presença ou ausência de modificações dentro de seu repositório.  Informando as alterações desde o último commit.

**git add**: Este comando leva um arquivo ou diretório alterado, do estado modificado, ao estado de preparo.

**git commit**: Este comando leva um arquivo do estado de preparo até o repositório local, revertendo-o para seu estado de 'não modificado'

**git push**: Este comando transfere seus arquivos e diretórios do repositório local até seu repositório remoto, atualizando seu repositório remoto até seu commit atual no repositório local.

**git pull**: Podendo ser considerado o irmão do **git push**, este comando realiza seu oposto. Levando os arquivos e diretórios do repositório remoto para seu repositório local, se diferenciando do comando **git clone**, simplesmente atualizando o repositório local para a versão mais recente do repositório remoto, e não criando uma versão local do repositório remoto em questão. 

