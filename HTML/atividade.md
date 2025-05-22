# Análise da Estrutura Textual de Páginas Web

## 1. Análise da Estrutura Textual

### Páginas Web Selecionadas:
- **Página 1:** Artigo de notícia – G1 (https://g1.globo.com)
- **Página 2:** Documentação técnica – MDN Web Docs (https://developer.mozilla.org)
- **Página 3:** Página inicial de blog – Medium (https://medium.com)

### Elementos de Formatação de Texto

#### `<p>` - Parágrafo
- **Função Semântica:** Delimita blocos de texto.
- **Contribuição:** Organiza o conteúdo em partes legíveis. Utilizado para separar ideias e facilitar a leitura.

#### `<h1>` a `<h6>` - Cabeçalhos
- **Função Semântica:** Estruturam o conteúdo hierarquicamente.
- **Contribuição:** Permitem distinguir o título principal (`<h1>`) dos subtítulos (`<h2>` a `<h6>`), facilitando a navegação e o entendimento da hierarquia de conteúdo.

#### `<strong>` - Ênfase Forte
- **Função Semântica:** Aponta importância semântica, além da ênfase visual.
- **Contribuição:** Indica conteúdo relevante ou urgente. Diferente do uso apenas visual de negrito (`font-weight: bold` via CSS), comunica semântica para leitores de tela e buscadores.

#### `<em>` - Ênfase
- **Função Semântica:** Marca texto com ênfase leve.
- **Contribuição:** Geralmente exibido em itálico, usado para dar destaque a palavras dentro de frases.

#### `<br>` - Quebra de Linha
- **Função Semântica:** Quebra de linha simples sem novo parágrafo.
- **Contribuição:** Útil para endereços, poesias ou formatação específica onde uma nova linha é necessária.

#### `<hr>` - Linha Horizontal
- **Função Semântica:** Indica separação temática entre blocos de conteúdo.
- **Contribuição:** Ajuda na segmentação visual do conteúdo, como entre seções ou tópicos.

---

## 2. Explorando a Organização com Listas

### Elementos de Lista

#### `<ul>` - Lista Não Ordenada
- **Uso:** Tópicos variados ou menus.
- **Exemplo:** Categorias de postagens no Medium.
- **Vantagem:** Indica uma coleção de itens sem ordem específica.

#### `<ol>` - Lista Ordenada
- **Uso:** Passo a passo ou sequências.
- **Exemplo:** Tutoriais na documentação do MDN.
- **Vantagem:** Mostra ordem ou prioridade entre os itens.

#### `<li>` - Item de Lista
- **Função Semântica:** Define um item dentro de uma lista.
- **Contribuição:** Estrutura e separa claramente os elementos listados.

#### `<dl>`, `<dt>`, `<dd>` - Lista de Definição
- **Uso:** Glossários e descrições técnicas.
- **Exemplo:** Tabela de atributos no MDN.
- **Vantagem:** Apresenta pares de termos e descrições. Útil em FAQs e glossários.

---

## 3. A Expressão de Citações

### Elementos de Citação

#### `<blockquote>` - Citação em Bloco
- **Uso:** Trechos longos de citações externas.
- **Exemplo:** Declarações de entrevistas em reportagens.
- **Contribuição:** Formata visualmente o conteúdo citado com recuo e destaque, separando do texto original.

#### `<q>` - Citação Curta
- **Uso:** Citações curtas dentro do texto.
- **Exemplo:** “A web é feita de HTML”, afirmou o autor.
- **Contribuição:** Coloca aspas automaticamente ao redor da citação.

### Diferença Semântica:
- `<blockquote>` é usado para **citações longas** que merecem destaque visual.
- `<q>` é usado para **citações breves** embutidas dentro de parágrafos.

---

