Conceitos básicos:

branch	--> Ramificação da branch main. branch da tarefa A, branch da funcionalida X, branch da tela 1
commit	--> Salva as alterações no branch, nova versão.
merge	--> Junção da sua branch com outra branch, ex: main
remote	--> Cria uma conexão da pasta local com o repositorio - apenas na primeira vez
push	--> Joga o commit local para o repositório do Github
pull-	--> Puxa o que está no repositório do Github para a pasta local

Fazer download do git: https://git-scm.com/downloads

Testa
	Abre o aplicativo git bash:

 	git --version
	git init cria master (main)

	** 	Nomenclarutura master tem cido alterada para main. Algumas empresas estão alterando o nome master para main:
		git branch -M "main"

	Cria uma pasta local
 	Cria um arquivo readme.md
 
	git add readme.md		--> manda os arquivos para area stage
	git add . 			--> Manda todas as alterações
	git status 			--> exibe as alterações pendente para entrar no commit
	git commit -m "primeiro commit" --> Manda alterações do stage para o commit

GitHub
	atalho do meu perfil no GitHub^

	Cria um repositório - Informa o mesmo nome da pasta local 
	git remote add origin https://github.com/CerradoScripts/EstudoGit.git - Cria uma conexão da pasta com o repositorio - apenas na primeira vez
	git push -u origin main - Manda todas as alterações para o repositório
	
