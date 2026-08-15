# Respostas do LAB 01

Nome:
Matricula:
Dupla (M2 em diante):

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro:**

**Autor:**

**Data:**

**Linha alterada (antes e depois):**

```
antes:
depois:
```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**

**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:**

---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` :
- `=======` :
- `>>>>>>>` :

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**

## M2 – Quem quebrou o painel

- Hash curto do commit: `01ef93b`
- Autor: Tarcisio Melo
- Data: 15/06/2026 às 22:38:00 -0300
- Linha antes:
  `return (leitura - 32) * 5 / 9;`
- Linha depois:
  `return leitura * 9 / 5 + 32;`

  ## M3 – O segredo vazado

**O que eu esperava:** que o `config/credenciais.env` deixasse de aparecer no `git status` por estar no `.gitignore`.

**O que apareceu:** o `.gitignore` apareceu como arquivo não rastreado, enquanto o `config/credenciais.env` continuou sendo rastreado, porque ele já fazia parte do histórico do Git.
