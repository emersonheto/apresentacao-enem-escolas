# Apresentação CMP263 — Desempenho no ENEM por escola

Apresentação (16 slides) do trabalho prático de CMP263 – Aprendizado de Máquina (UFRGS, 2026/2):
*Do School Characteristics Predict ENEM Performance? A Grouped and Nested Evaluation of Regression Models on Brazilian High Schools*.

Disponível em **português (PT, padrão)** e **espanhol (ES)**.

## Como abrir

Abra `index.html` em qualquer navegador moderno (duplo clique). Funciona offline, direto de `file://`,
e também publicado como página estática (por exemplo, GitHub Pages): não usa bibliotecas externas
e as imagens ficam em `assets/` com caminhos relativos.

## Teclas

| Tecla | Ação |
|---|---|
| `←` / `→` | slide anterior / seguinte |
| `espaço` | slide seguinte |
| `Home` / `End` | primeiro / último slide |
| `F` | tela cheia |
| `N` | mostra/oculta as notas do apresentador (quem apresenta, bloco, tempo) |
| `L` | alterna o idioma PT ⇄ ES |

Também há um pequeno seletor **PT | ES** no canto superior direito (some em tela cheia).

## Parâmetros da URL

- `index.html?lang=es` ou `?lang=pt` — escolhe o idioma (PT é o padrão). A escolha fica salva no navegador (`localStorage`); o parâmetro tem prioridade sobre o valor salvo.
- `index.html?notas` — abre já com as notas do apresentador.
- Combinam: `index.html?lang=es&notas`.
- `index.html#7` — abre direto no slide 7 (ex.: `index.html?lang=es#7`).

Os textos dos slides **e** das notas (incluindo rótulos e tempos) são traduzidos; números, nomes de código
(`GroupKFold`, `Pipeline`, …) e figuras são idênticos nos dois idiomas. O título do artigo na capa permanece em inglês.

## PDFs

- `apresentacao.pdf` — versão em português (1 slide por página, sem notas).
- `apresentacao-es.pdf` — versão em espanhol.

Para regenerar (Chrome/Chromium): `chrome --headless --no-pdf-header-footer --print-to-pdf=apresentacao-es.pdf "file:///caminho/index.html?lang=es"`.

## Números

Todos os números (23.374 escolas, RMSE, R², p-valores, etc.) vêm do artigo e dos resultados do projeto
(repositório `emersonheto/enem-school-performance`); nada foi recalculado nesta apresentação.
