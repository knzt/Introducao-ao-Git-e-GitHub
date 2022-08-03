## <p align=center> Configurações Git </p>
#### Configurar chave SSH
Passo 1: Abrir o Git Bash <br>
Passo 2: Criar as senhas, usando o comando `ssh-keygen -t` ed25519 `-C` (maiúsculo) <em>emaildousuário</em><br>
Passo 3: Inserir uma senha<br>
Passo 4: Acessar o local no qual as senhas foram salvas: `cd` <em>caminhoatéapasta</em><br>
Passo 5: visualizar a senha pública: `cat` <em>nomedoarquivodasenha</em><br>
#### Configurar usuário<br>
(preferencialmente usar as mesmas credenciais cadastradas no GitHub)<br>
 `git config` `--global` `user.email` “<em>email</em>”<br>
`git config` `--global` `user.name` “<em>nickname</em>”<br>
#### Configurações em geral:<br>
Passo 1: Verificar a lista de configurações registradas: `git config`<br>
Passo 2: Resetar a informação registrada na configuração que deseja alterar: `git config` `--global` `--unset` <em>nomedaconfiguração</em><br>
Passo 3: Registrar a nova informação: `git config` `--global` nomedaconfiguração “<em>novainformação</em>”<br>
