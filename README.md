## Definir usuario e olhar configurações
```bash
git config user.name
```

```bash
git config user.name
```

```bash
git config user.email
```

---

## Criar um novo arquivo
```bash
touch file.txt
```

---

## Iniciar um repositorio
```bash
git init
```

---

## Adicionar um arquivo para o staging
```bash
git add file.txt
```
ou para todos arquivos

```bash
git add .
```

---

## Remover um arquivo do staging
```bash
git restore --staged file.txt
```
ou para todos arquivos

```bash
git restore --staged .
```

---

## Verificar os arquivos no staging
```bash
git status
```

---

## Commit nos arquivos staging
```bash
git commit -m "Mensagem de commit"
```

---

## Olhar historico de commits
```bash
git log
```
---

## Mostra as alterações no arquivo que AINDA NÃO foram para o staging
```bash
git diff file.txt
```

## Mostra as alterações que ESTÃO no staging (prontas para commit)
```bash
git diff --staged file.txt
```

---

## Voltar versão anterior de um arquivo
```bash
git restore file.txt
```

---

## Clonar um repositorio remoto para local
```bash
git clone url.git
```
---

## Criar uma branch nova
```bash
git branch new-branch
```

## Verificar todas as branches
```bash
git branch
```

## Mudar a branch
```bash
git checkout new-branch
```

ou

```bash
git switch new-branch
```

## Unir uma branch com a main
#### Antes, vá para o branch que receberá as alterações
```bash
git checkout main
```

#### Agora, una o 'new-branch' ao branch atual (main)
```bash
git merge new-branch
```

## Deletar uma branch
```bash
git branch -d new-branch
```

---

## Conecta seu repositório local a um remoto já existente
```bash
git remote add origin url.git
```

## Listar todos os repositorios remotos
```bash
git remote -v
```

## Pega os commits mais recentes mas não atualiza a branch local
```bash
git fetch origin
```

## Atualizar os commits para o repositorio local, (fetch + merge)
```bash
git pull origin main
```

## Envia o repositorio local para o remoto
```bash
git push -u origin main
```


