# Educação Infantil — Resumos Detalhados e Apresentação Responsiva

Apresentação HTML responsiva e acessível com resumos dos textos:
- “História da infância: reflexões acerca de algumas concepções correntes” (Rita Cássia Luiz da Rocha)
- “Um resgate histórico da infância” (Aula 2 – Profa. Renata Araujo, 19/08)

Inclui:
- Destaques de datas, nomes e trechos-chave.
- Navegação por teclado, modal de Sumário, e versão “print-friendly” para PDF.
- Estrutura da Educação Básica no Brasil (Educação Infantil, Ensino Fundamental e Ensino Médio).

## Visualização

Acesse a apresentação publicada:
- URL: https://SEU_USUARIO.github.io/infancia-apresentacao

Se estiver rodando localmente, abra `index.html` no navegador.

## Recursos da apresentação

- Navegação: botões “Anterior/Próximo” ou setas do teclado (← →).
- Sumário: botão “Sumário” (atalho: tecla `T`), com modal acessível.
- PDF: botão “Baixar PDF (experimental)” abre uma nova aba com versão para impressão. Use `Ctrl/Cmd + P` e selecione “Salvar como PDF”.
- Acessibilidade:
  - Foco automático no slide ativo.
  - Regiões com `aria-live` para atualizar o progresso.
  - Modal com `aria-modal` e `role="dialog"`.

## Estrutura

- `index.html`: apresentação completa (HTML + CSS + JS).
- `README.md`: este arquivo.
- `LICENSE`: licença do projeto (MIT).
- `.gitignore`: ignora arquivos comuns de editor/OS e artefatos locais.

## Como publicar (caso você faça um fork)

### GitHub Pages
1. Crie um repositório público (ex.: `infancia-apresentacao`).
2. Faça push de `index.html` (e demais arquivos).
3. Em Settings > Pages: Source = “Deploy from a branch”, branch `main`, pasta `/root`.
4. Acesse: `https://SEU_USUARIO.github.io/infancia-apresentacao`.

### Netlify (drag & drop)
1. Acesse https://app.netlify.com.
2. “Add new site” > “Deploy manually”.
3. Arraste `index.html`.
4. Use a URL gerada (ex.: `https://nome-aleatorio.netlify.app`).

### Vercel
1. Importe o repositório na Vercel.
2. Deploy com um clique.
3. Use a URL gerada (ex.: `https://seu-projeto.vercel.app`).

## Conteúdo acadêmico (resumo do que está no slide)

- Tese de Philippe Ariès (1960/1981): “sentimento de infância” como construção histórica (séc. XVII); “adulto em miniatura”; paparicação → apego; fontes das mentalidades.
- Críticas: Moysés Kuhlmann Jr. (1998) — vieses de fonte, “duas infâncias”; Jacques Gélis (1991) — “indiferença medieval é fábula”; Alexandre-Bidón & Riché — materialidade da infância medieval.
- Aula “Um resgate histórico da infância” (19/08): escrita autobiográfica, leitura de imagens (Ivan Cruz; Beechey, 1793), documentário (Franco Frabboni).
- Estrutura da Educação Básica (LDB 9.394/1996; BNCC): Educação Infantil (creche e pré-escola), Ensino Fundamental (9 anos), Ensino Médio (itinerários).

## Desenvolvimento local

Basta abrir `index.html` no navegador. Se quiser um servidor estático:

```bash
# Python 3
python -m http.server 5500
# depois acesse http://localhost:5500
