<div align="center">

# 🚀 Projeto Git

<em>Projeto criado com o objetivo de estudar e praticar Git e GitHub.</em>

<br>

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)

</div>

<hr>

## 📚 Sobre o Projeto

Este repositório faz parte dos meus estudos sobre controle de versão utilizando **Git** e hospedagem de código com **GitHub**.

Durante o desenvolvimento deste projeto, estou praticando conceitos fundamentais como:

<table>
  <tr>
    <td>
      <ul>
        <li>Inicialização de repositórios</li>
        <li>Commits</li>
        <li>Branches</li>
        <li>Merge</li>
        <li>Push e Pull</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Clone de repositórios</li>
        <li>Versionamento de código</li>
        <li>Resolução de conflitos</li>
        <li>Pull Requests</li>
        <li>Boas práticas de documentação</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📂 Estrutura do Projeto

```text
projeto-git/
│
├── index.html
├── style.css
└── README.md
```

---

## 🎯 Objetivo

Aprender na prática o funcionamento do Git e GitHub através da criação e evolução deste projeto.

---

## 🛠️ Guia de Comandos Git

<details>
<summary><b>1. Configuração Inicial</b></summary>
<br>

* **Configurar nome do usuário:**
  ```bash
  git config --global user.name "Seu Nome"
  ```

* **Configurar email do usuário:**
  ```bash
  git config --global user.email "seu-email@exemplo.com"
  ```

* **Verificar configurações atuais:**
  ```bash
  git config --list
  ```
</details>

<details>
<summary><b>2. Fluxo Básico de Trabalho</b></summary>
<br>

* **Inicializar um novo repositório:**
  ```bash
  git init
  ```

* **Verificar o estado das alterações:**
  ```bash
  git status
  ```

* **Adicionar arquivo específico para staging:**
  ```bash
  git add <nome-do-arquivo>
  ```

* **Adicionar todas as alterações para staging:**
  ```bash
  git add .
  ```

* **Criar um commit com mensagem:**
  ```bash
  git commit -m "Sua mensagem aqui"
  ```

* **Adicionar alterações e commitar direto:**
  ```bash
  git commit -am "Sua mensagem aqui"
  ```
</details>

<details>
<summary><b>3. Histórico e Inspeção</b></summary>
<br>

* **Ver histórico de commits resumido:**
  ```bash
  git log --oneline
  ```

* **Ver histórico detalhado com gráfico de branches:**
  ```bash
  git log --oneline --graph --all
  ```

* **Ver alterações não preparadas no código:**
  ```bash
  git diff
  ```

* **Ver alterações que já estão no staging:**
  ```bash
  git diff --staged
  ```

* **Ver detalhes de um commit específico:**
  ```bash
  git show <hash-do-commit>
  ```

* **Descobrir quem alterou cada linha de um arquivo:**
  ```bash
  git blame <nome-do-arquivo>
  ```
</details>

<details>
<summary><b>4. Gerenciamento de Branches</b></summary>
<br>

* **Listar branches locais:**
  ```bash
  git branch
  ```

* **Listar todas as branches (locais e remotas):**
  ```bash
  git branch -a
  ```

* **Criar uma nova branch:**
  ```bash
  git branch <nome-da-branch>
  ```

* **Alternar para outra branch:**
  ```bash
  git checkout <nome-da-branch>
  ```

* **Criar e alternar para uma nova branch (atalho):**
  ```bash
  git switch -c <nome-da-branch>
  ```

* **Mesclar uma branch na branch atual:**
  ```bash
  git merge <nome-da-branch>
  ```

* **Deletar uma branch local:**
  ```bash
  git branch -d <nome-da-branch>
  ```
</details>

<details>
<summary><b>5. Repositórios Remotos e Sincronização</b></summary>
<br>

* **Clonar um repositório remoto:**
  ```bash
  git clone <URL_DO_REPOSITORIO>
  ```

* **Conectar diretório local ao repositório remoto:**
  ```bash
  git remote add origin <URL_DO_REPOSITORIO>
  ```

* **Verificar repositórios remotos vinculados:**
  ```bash
  git remote -v
  ```

* **Baixar alterações do servidor (sem mesclar):**
  ```bash
  git fetch
  ```

* **Baixar e mesclar alterações do servidor:**
  ```bash
  git pull origin <nome-da-branch>
  ```

* **Enviar commits para o servidor:**
  ```bash
  git push origin <nome-da-branch>
  ```
</details>

<details>
<summary><b>6. Desfazendo Alterações</b></summary>
<br>

* **Desfazer alterações em um arquivo:**
  ```bash
  git restore <nome-do-arquivo>
  ```

* **Remover arquivo da área de staging:**
  ```bash
  git restore --staged <nome-do-arquivo>
  ```

* **Alterar a mensagem do último commit:**
  ```bash
  git commit --amend -m "Nova mensagem"
  ```

* **Reverter um commit anterior:**
  ```bash
  git revert <hash-do-commit>
  ```
</details>

<details>
<summary><b>7. Ferramentas Avançadas</b></summary>
<br>

* **Guardar alterações temporariamente:**
  ```bash
  git stash
  ```

* **Recuperar alterações guardadas:**
  ```bash
  git stash pop
  ```

* **Ver histórico completo de ações (recuperar coisas apagadas):**
  ```bash
  git reflog
  ```
</details>

---

## 📖 Aprendizados

Neste projeto estou desenvolvendo conhecimentos em:

- 🔹 Controle de versão
- 🔹 Colaboração em projetos
- 🔹 Fluxo de trabalho Git
- 🔹 Hospedagem de código no GitHub
- 🔹 Organização de projetos

---

<div align="center">
  <sub>Feito com 💙 para fins de estudo.</sub>
</div>