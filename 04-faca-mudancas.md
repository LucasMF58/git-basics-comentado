# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

<!-- TODO: mostra todos os arquivos que foram modificados, alem de mostrar em qual branch está -->

**Quando usar / observação:**

<!-- TODO: usado para saber se um arquivo ja foi mandado para o servidor ou se foi modificado, alem de ser possivel ver em qual branch esta -->

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

<!-- TODO: mostra o que foi modificado nos arquivos -->

**Quando usar / observação:**

<!-- TODO: usado para saber onde foi modificado em cada arquivo -->

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

<!-- TODO: ele grava o arquivo, o preparando para ser commitado -->

**Quando usar / observação:**

<!-- TODO: utilizado para a preparacao de um ou mais arquivos para ser enviado para o github -->

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

<!-- TODO: mostra a diferença do que foi modificado entre arquivos que estao preparados e suas ultimas versoes -->

**Quando usar / observação:**

<!-- TODO: usado para poder ver as diferencas de codigo -->

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

<!-- TODO: tira o arquivo da are de preparação (git add), mas mantem seu conteudo -->

**Quando usar / observação:**

<!-- TODO: quando o arquivo foi preparado sem querer e quer retirar ele -->

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

<!-- TODO: grava permanentemente o arquivo nas versoes -->

**Quando usar / observação:**

<!-- TODO: quando os arquivos estao prontos para serem mandados ao servidor (git push) -->

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
