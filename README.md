```html

<div align="center">



\# 🚀 Projeto Git



<p><em>Projeto criado com o objetivo de estudar e praticar Git e GitHub.</em></p>



<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white" alt="Git">

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white" alt="GitHub">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white" alt="HTML5">

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white" alt="CSS3">



</div>



\---



\## 📚 Sobre o Projeto



Este repositório faz parte dos meus estudos sobre controle de versão utilizando \*\*Git\*\* e hospedagem de código com \*\*GitHub\*\*.



Durante o desenvolvimento deste projeto, estou praticando conceitos fundamentais como:

\- Inicialização de repositórios

\- Commits

\- Branches

\- Merge

\- Push e Pull

\- Clone de repositórios

\- Versionamento de código

\- Resolução de conflitos

\- Pull Requests

\- Boas práticas de documentação



\---



\## 📂 Estrutura do Projeto



```text

projeto-git/

│

├── index.html

├── style.css

└── README.md



```



\---



\## 🎯 Objetivo



Aprender na prática o funcionamento do Git e GitHub através da criação e evolução deste projeto.



\---



\### 1. Configuração Inicial



\* \*\*Configurar nome do usuário:\*\*

```bash

git config --global user.name "Seu Nome"



```





\* \*\*Configurar email do usuário:\*\*

```bash

git config --global user.email "seu-email@exemplo.com"



```





\* \*\*Verificar configurações atuais:\*\*

```bash

git config --list



```







\---



\### 2. Fluxo Básico de Trabalho



\* \*\*Inicializar um novo repositório:\*\*

```bash

git init



```





\* \*\*Verificar o estado das alterações:\*\*

```bash

git status



```





\* \*\*Adicionar arquivo específico para staging:\*\*

```bash

git add <nome-do-arquivo>



```





\* \*\*Adicionar todas as alterações para staging:\*\*

```bash

git add .



```





\* \*\*Criar um commit com mensagem:\*\*

```bash

git commit -m "Sua mensagem aqui"



```





\* \*\*Adicionar alterações e commitar direto (para arquivos já monitorados):\*\*

```bash

git commit -am "Sua mensagem aqui"



```







\---



\### 3. Histórico e Inspeção



\* \*\*Ver histórico de commits resumido:\*\*

```bash

git log --oneline



```





\* \*\*Ver histórico detalhado com gráfico de branches:\*\*

```bash

git log --oneline --graph --all



```





\* \*\*Ver alterações não preparadas no código:\*\*

```bash

git diff



```





\* \*\*Ver alterações que já estão no staging:\*\*

```bash

git diff --staged



```





\* \*\*Ver detalhes de um commit específico:\*\*

```bash

git show <hash-do-commit>



```





\* \*\*Descobrir quem alterou cada linha de um arquivo:\*\*

```bash

git blame <nome-do-arquivo>



```







\---



\### 4. Gerenciamento de Branches (Ramificações)



\* \*\*Listar branches locais:\*\*

```bash

git branch



```





\* \*\*Listar todas as branches (locais e remotas):\*\*

```bash

git branch -a



```





\* \*\*Criar uma nova branch:\*\*

```bash

git branch <nome-da-branch>



```





\* \*\*Alternar para outra branch:\*\*

```bash

git checkout <nome-da-branch>



```





\* \*\*Criar e alternar para uma nova branch (atalho):\*\*

```bash

git checkout -b <nome-da-branch>

\# Ou na sintaxe nova:

git switch -c <nome-da-branch>



```





\* \*\*Mesclar uma branch na branch atual:\*\*

```bash

git merge <nome-da-branch>



```





\* \*\*Deletar uma branch local:\*\*

```bash

git branch -d <nome-da-branch>



```





\* \*\*Forçar a exclusão de uma branch local:\*\*

```bash

git branch -D <nome-da-branch>



```







\---



\### 5. Repositórios Remotos e Sincronização



\* \*\*Clonar um repositório remoto:\*\*

```bash

git clone <URL\_DO\_REPOSITORIO>



```





\* \*\*Conectar o diretório local a um repositório remoto:\*\*

```bash

git remote add origin <URL\_DO\_REPOSITORIO>



```





\* \*\*Verificar os repositórios remotos vinculados:\*\*

```bash

git remote -v



```





\* \*\*Baixar alterações do servidor (sem mesclar):\*\*

```bash

git fetch



```





\* \*\*Baixar e mesclar alterações do servidor:\*\*

```bash

git pull origin <nome-da-branch>



```





\* \*\*Enviar commits para o servidor:\*\*

```bash

git push origin <nome-da-branch>



```





\* \*\*Enviar e configurar o rastreamento padrão (upstream):\*\*

```bash

git push -u origin main



```





\* \*\*Deletar uma branch no repositório remoto:\*\*

```bash

git push origin --delete <nome-da-branch>



```







\---



\### 6. Desfazendo Alterações e Correções



\* \*\*Desfazer alterações em um arquivo (antes do staging):\*\*

```bash

git checkout -- <nome-do-arquivo>

\# Ou na sintaxe nova:

git restore <nome-do-arquivo>



```





\* \*\*Remover arquivo da área de staging (unstage):\*\*

```bash

git reset HEAD <nome-do-arquivo>

\# Ou na sintaxe nova:

git restore --staged <nome-do-arquivo>



```





\* \*\*Alterar a mensagem do último commit (ou adicionar arquivos esquecidos):\*\*

```bash

git commit --amend -m "Nova mensagem"



```





\* \*\*Criar um novo commit que reverte as alterações de um commit antigo:\*\*

```bash

git revert <hash-do-commit>



```





\* \*\*Voltar ao commit anterior mantendo as alterações nos arquivos (Soft Reset):\*\*

```bash

git reset --soft HEAD\~1



```





\* \*\*Descartar completamente os últimos commits e alterações (Hard Reset - cuidado!):\*\*

```bash

git reset --hard HEAD\~1



```







\---



\### 7. Ferramentas Avançadas



\* \*\*Guardar alterações temporariamente na pilha (sem fazer commit):\*\*

```bash

git stash



```





\* \*\*Recuperar as alterações guardadas na pilha:\*\*

```bash

git stash pop



```





\* \*\*Listar tudo o que está guardado no stash:\*\*

```bash

git stash list



```





\* \*\*Aplicar um commit específico de outra branch aqui (Cherry-pick):\*\*

```bash

git cherry-pick <hash-do-commit>



```





\* \*\*Reescrever o histórico aplicando commits sobre outra base (Rebase):\*\*

```bash

git rebase <nome-da-branch>



```





\* \*\*Ver o histórico de todas as ações feitas no repositório local (para recuperar coisas apagadas):\*\*

```bash

git reflog



```







\---



\## 📖 Aprendizados



Neste projeto estou desenvolvendo conhecimentos em:



\* Controle de versão

\* Colaboração em projetos

\* Fluxo de trabalho Git

\* Hospedagem de código no GitHub

\* Organização de projetos



\---

