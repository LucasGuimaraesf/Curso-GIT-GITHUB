# Curso-GIT-GITHUB
 Repositório para consultas 

## Commits

Modificações e novas funcionalidades:
```
feat ou feature/ descricao-da-modificacao
```

Correção de problema:
```
fix ou bugfix/descricao-do-problema
```

Modificação urgente na main:
```
hotfix/descricao-do-problema
```

##  Comandos Git Essenciais

###  Branches
- `git checkout -b nome-da-branch`  
  Cria e muda para uma nova branch a partir da atual.

- `git branch`  
  Lista todas as branches existentes no repositório local.

- `git checkout main`  
  Volta para a branch `main`.

---

###  Status e Controle de Arquivos
- `git status`  
  Mostra os arquivos modificados e o estado da branch atual.

- `git add .`  
  Adiciona todas as modificações para o próximo commit.

- `git add nome-do-arquivo`  
  Adiciona apenas um arquivo específico.

---

###  Commits
- `git commit -m "mensagem"`  
  Cria um commit com as mudanças adicionadas.

- `git log --oneline`  
  Exibe o histórico de commits de forma resumida.

---

###  Envio e Atualização
- `git push origin nome-da-branch`  
  Envia a branch e seus commits para o repositório remoto (GitHub).

- `git pull origin main`  
  Atualiza a branch `main` local com as últimas alterações do repositório remoto.
