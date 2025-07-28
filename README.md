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
git rm --cached -r file.txt
```
ou para todos arquivos
```bash
git rm --cached -r .
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

## Olha diferenças de um arquivo para versão mais antiga
```bash
git diff file.txt
```
---

## Voltar versão anterior de um arquivo
```bash
git checkout file.txt
```
---

## Clonar um repositorio
```bash
git clone url.git
```
---

## Criar uma branch nova
```bash
git branch new-branch
```
---

## Verificar todas as branches
```bash
git branch
```
---
## Mudar a branch
```bash
git checkout new-branch
```
---

## Unir uma branch com a main
```bash
git merge new-branch
```
---
