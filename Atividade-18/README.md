# Atividade 18 — Diagrama de Classes do BiblioTech

**Nome:** Otávio Augusto Machado Ott
**Turma:** 2º ano — Técnico em Informática Integrado

## Diagrama

![Diagrama de Classes do BiblioTech](diagrama-classes.png)

## Por que estes números (associação Bibliotecário — Empréstimo)

* Perto de `Emprestimo` eu coloquei `0..*` porque um bibliotecário recém-cadastrado pode não ter registrado nenhum empréstimo ainda (`0`), mas ao longo do tempo pode registrar vários (`*`).
* Perto de `Bibliotecario` eu coloquei `1` porque cada empréstimo é registrado por um único bibliotecário.

## Rastreabilidade 

* A operação `criarEmprestimo()` da classe `Emprestimo` atende ao caso de uso **Emprestar Livro**.

## Autoavaliação

* **Conceito que pretendo:** B
* **Onde isso se prova no diagrama:** Nas cinco classes `Livro`, `Leitor`, `Emprestimo`, `Usuario` e `Bibliotecario`, nas duas heranças para `Usuario` e na associação `Bibliotecario` — `Emprestimo` com as multiplicidades `1` e `0..*`.