# Flutter — Exercícios de Fixação: Listas, ListView e Cards

**Aluno:** Ronaldo
**Turma/Disciplina:** Flutter — EEP (Escola de Engenharia de Piracicaba)
**Atividade:** Exercícios de fixação do Material 2 (Listas, ListView, Cards e Conteúdo Dinâmico)

## Descrição

Este repositório contém os 5 exercícios de fixação propostos ao final do material,
utilizando List, ListView.builder, Card, ListTile, Expanded e setState().
Nenhum exercício utiliza onTap, Navigator, múltiplas telas, Form ou TextFormField —
esses recursos pertencem ao material seguinte.

## Estrutura

- `fixacao01_linguagens/` — List<String> com linguagens de programação, exibida com ListView.builder e ListTile
- `fixacao02_livros/` — Classe Livro (título, autor) apresentada em Cards
- `fixacao03_alunos/` — Classe Aluno (nome, nota); nome no title e nota no subtitle
- `fixacao04_tarefas/` — Cadastro dinâmico de tarefas com adição e remoção via IconButton
- `fixacao05_estoque/` — Classe Produto (nome, preço, quantidade); cadastro dinâmico com mensagem de lista vazia

Cada pasta é um projeto Flutter independente, contendo `pubspec.yaml` e `lib/main.dart`.

## Como executar cada exercício

```bash
cd fixacaoXX_nome
flutter pub get
flutter run
```
