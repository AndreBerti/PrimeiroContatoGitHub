## Comandos Básicos de Git :package:

:beginner: **Iniciar o git na pasta:**   _git init_ 

:beginner: **Conferir credenciais:**   _git config --list_ 

:beginner: **Retirar uma das credenciais:**   _git config --global --unset PROPRIEDADE_ 

exemplo: _git config --global --unset user.name_

:beginner: **Configurando email:**   _git config --global user.email "EMAIL"_ 

:beginner: **Configurando email:**   _git config --global user.name MEUNOME_ 

:beginner: **Verificar status dos arquivos:**   _git status_ 

**:beginner: Adicionando todos os arquivos para comittar:**   _git add *_ 

:beginner: **Adicionando alguns arquivos ou pastas para  comittar:**   _git add arquivo1.extensao arquivo2.extensão ./pasta_ 

:beginner: **Dar commit:**   _git commit  -m "as observações que você quiser"_ 

:beginner: **Como apontar para o repositório do git:**   _git remote add origin http://github.com/AndreBerti/nomeDoRepositorio.git_

:beginner: **Ver os repositórios cadastrados:**   _git remote -v_

:beginner: **Subir arquivos para o Github**   _git push origin master_

:beginner: **Puxar arquivos do GitHub:**   _git pull origin master_

Obs: o **master** é o nome da brand que você vai estar usando, pode ser outro.

