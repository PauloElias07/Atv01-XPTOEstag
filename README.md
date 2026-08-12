# Atv01-XPTOEstag


Verificar se o repositório está no dispositivo local, se sim fazer um "git pull request", caso contrário fazer um git clone e em seguida git pull request para obter a permissão naquele repositório;
 
Adicionar as credenciais no diretório - "git config user.email --local "paulo.elias@fatec.sp.gov.br" " e "git config user.name --local "Paulo" ";

Configurar uma branch para fazer as edições, criando como: "git branch nome da branch", saber se esta na branch criada com "git status";
 
A partir daí fazer commits periodicamente, com os comandos: "git add ." e "git commit", para garantir que eles sejam identificados de acordo com as modificações efetuadas;
 
Após finalizar as alterações para aquela branch/período de trabalho, Fazer um git log verificando os commits efetuados;
 
Agora Fazer um git push, que irá enviar as adições feitas para a branch que foi criada;
 
 
Após isso, fazer um git checkout main para voltar para branch main, daí então git pull para atualizar a branch main, "git merge nome_da_branch_criada" - Esta parte, somente com autorização dos superiores;

E por fim fazer um git push, que enviará os arquivos que foram atualizados.
 