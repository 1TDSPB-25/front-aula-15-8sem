# Exercício para o dia 22/09/2025
# Organização de Páginas

**Objetivo:** mover páginas para a pasta `page/`, corrigir **links relativos** entre as páginas e **replicar o cabeçalho** da página `missao.html` em todas as páginas.  

---

## Regras do exercício
- Trabalhe **somente com HTML**.
- Mantenha nomes de arquivos **em minúsculas**, sem acentos, usando **hífen** quando necessário (ex.: `sobre-a-empresa.html`).
- Não crie nem use arquivos de CSS/JS neste exercício.

---

---

## Tarefa 1 — Mover páginas para `page/`
1. Crie a pasta `page/` na raiz do projeto (se não existir).
2. Mova **todas as páginas secundárias** para `page/` (ex.: `ajuda.html`, `produtos/produtos.html`, `contato.html`, etc.).
3. Deixe **`index.html`** na raiz.

---

## Tarefa 2 — Corrigir links relativos (entre páginas)
Ajuste os `href` dos links para refletir a nova localização dos arquivos.

- **De `index.html` (raiz) → para uma página em `page/`:**
  ```html
  <!-- ANTES -->
  <a href="ajuda.html">Ajuda</a>
  <!-- DEPOIS -->
  <a href="./page/ajuda.html">Ajuda</a>


# Front-End-Design-Engineering / FIAP
```
- Repositório inicial
- Iniciando com comandos básicos
-- git init
-- git commit
-- git config
-- git add
-- git dif
-- git log
-- git show
-- git branch
-- git push
```
## Partindo para um conteúdo mais avançado:
- Manipulando branchs
```
-- git checkout -b
-- git merge

```

