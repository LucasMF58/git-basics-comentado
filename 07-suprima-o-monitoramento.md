# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

<!-- TODO: cuida dos arquivos e diretorios para ver se estao dentro das normas -->

**Quando usar / observação:**

<!-- TODO: quando quer ter um controle maior nos arquivos enviados -->

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

<!-- TODO: olha todos arquivos descartados pelo projeto -->

**Quando usar / observação:**

<!-- TODO: quando descartou algum e quer ver -->

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
