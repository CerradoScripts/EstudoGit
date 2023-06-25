Conceitos básicos:

branch - ramificação da branch main. branch da tarefa A, branch da funcionalida X, branch da tela 1
commit - salva as alterações no branch, nova versão.
merge - junção da sua branch com outra branch, ex: main

Download do git

** 	Nomenclarutura master tem cido alterada para main 
	git branch -M "main"

Testa

	git --version
	git ini cria master (main)
	git add readme.md manda os arquivos para area stage
	git add . - Manda todas as alterações
	git status exibe as alterações pendente para entrar no commit
	git commit -m "primeiro commit"

GitHub
	Cria um repositório - Informa o mesmo nome da pasta local 
	git remote add origin https://github.com/CerradoScripts/EstudoGit.git - Cria uma conexão da pasta com o repositorio - apenas na primeira vez
	git push -u origin main - Manda todas as alterações para o repositório
	
