# Exercício 001 - Abigail Breslin

**Dificuldade:** ⭐ Fácil

## Pergunta

Count the number of movies for which Abigail Breslin was nominated for an Oscar.

---

## Raciocínio

**Resultado esperado:**
- Um número.

**Tabela principal:**
- `oscar_nominees`

**Filtro:**
- `nominee = 'Abigail Breslin'`

**JOIN?**
- Não.

**IN?**
- Não.

**Função utilizada:**
- `COUNT(*)`

---

## Método utilizado

1. Ler e interpretar a pergunta.
2. Identificar se o resultado esperado é uma lista ou um número.
3. Descobrir a tabela principal.
4. Identificar os filtros.
5. Verificar se é necessário utilizar `JOIN` ou `IN`.
6. Escrever a consulta SQL.

---

## Solução SQL

```sql
SELECT COUNT(*)
FROM oscar_nominees
WHERE nominee = 'Abigail Breslin';
```

---

## Conceitos aprendidos

- `SELECT`
- `FROM`
- `WHERE`
- `COUNT(*)`

---

## Observações

Neste exercício aprendi que:

- `COUNT(*)` é utilizado para contar registros.
- Quando existe apenas uma tabela, normalmente não é necessário utilizar `JOIN` ou `IN`.
- O filtro foi aplicado na coluna `nominee`.
