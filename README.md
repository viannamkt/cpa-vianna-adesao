# Adesão CPA Vianna 2026.2

Painel de acompanhamento da adesão dos estudantes à avaliação da CPA (Comissão Própria de Avaliação) da Faculdade Vianna Júnior, semestre 2026.2.

## Arquivos

- `index.html`: o painel (HTML, CSS e JavaScript, sem dependências).
- `data.json`: os números exibidos.
- `logo.svg`: assinatura oficial da Faculdade Vianna Júnior, versão com caixa branca.

## Como atualizar os números

Abra `data.json` no GitHub, clique no lápis (Edit), altere e salve com **Commit changes**:

- `atualizado`: data e hora da contagem.
- Em cada turma, `respostas`: número de respostas do formulário no Microsoft Forms.
- `matriculados`: alunos com matrícula ativa no Gennera. Use `null` quando a turma não existe no Gennera.

O site é atualizado em cerca de um minuto.

## Como a adesão é calculada

Adesão = respostas ÷ matriculados da turma.

- Os totais por curso e o total geral somam só as turmas com matriculados conhecidos.
- Faixas de adesão:
  - Boa: 50% ou mais.
  - Atenção: de 20% a 49%.
  - Crítica: abaixo de 20%.
  - Aguardando: turma sem respostas.

## Publicação

O painel é publicado com GitHub Pages (Settings › Pages › Deploy from a branch › `main` / root).
