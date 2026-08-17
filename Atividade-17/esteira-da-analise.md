# Esteira da Análise — BiblioTech

**Estudante:** Otávio Augusto Machado Ott

## Funcionalidade 1: Emprestar Livro

- **1.1 Fala do cliente:** "Quando um aluno quiser levar um livro para casa, preciso registrar o empréstimo para saber quem está com o livro."
- **1.2 História de usuário:** Como bibliotecário, quero registrar o empréstimo de um livro, para controlar quais livros estão emprestados e para quem.
- **1.3 Requisito:** RF01 — O sistema deve permitir o registro de empréstimo de um livro para o leitor
- **1.4 Caso de uso (RF01):** Ator Bibliotecario → "Emprestar livro" (verbo + objeto)

## Funcionalidade 2: Reservar Livro

- **2.1 Fala do cliente:** "Quando um livro estiver emprestado, quero que o aluno possa reservá-lo para ser avisado quando estiver disponível."
- **2.2 História de usuário:** Como leitor, quero reservar um livro que está indisponível, para garantir que eu possa pegá-lo quando estiver disponível.
- **2.3 Requisito:** RF02 — O sistema deve permitir que o leitor reserve um lovro indisponível
- **2.4 Caso de uso (RF02):** Ator Leitor → "Reservar Livro" (verbo + objeto)

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
|Emprestar livro | RF01 | "Quando um aluno quiser levar um livro para casa, preciso registrar o empréstimo..." |
|Reservar livro | RF02 | "Quando um livro estiver emprestado, quero que o aluno possa reservá-lo..." |

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: Nenhum
- Entre: Emprestar e Reservar
- Por que é esse e não o outro: Reservar livro não é obrigatoriamente uma etapa de Emprestar livro

## Autoavaliação

**Conceito pretendido:** B (A / B / C)

- Conversei sobre esta atividade com: Ninguém (ou "ninguém")
- Esteira da análise: Mapeamento completo e contínuo, convertendo a fala do cliente até o diagrama UML. (diga onde)
- Diagrama e notação: Uso correto dos símbolos (atores externos, casos de uso no padrão verbo + objeto e associações sem seta).
- Rastreabilidade: Tabela conectando claramente fala original, código do requisito e elipse.
- Organização da entrega: Documento organizado