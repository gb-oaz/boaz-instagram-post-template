# 📱 instagram-content-templates

> Templates visuais para criação de **Posts** e **Reels** do Instagram — 100% offline, sem instalar nada, direto no navegador.

---

## Repositório

| | |
|---|---|
| 👤 Autor | [@gustavoboazms](https://github.com/gustavoboazms) |
| 🔐 Clone SSH | `git@github.com:gustavoboazms/instagram-content-templates.git` |
| 🔗 Clone HTTPS | `https://github.com/gustavoboazms/instagram-content-templates.git` |

---

## O que são estes templates?

Dois arquivos HTML independentes que funcionam como estúdios de criação de conteúdo para o Instagram. Você abre no navegador, preenche os campos e o preview é gerado em tempo real — sem internet, sem conta, sem instalar nada.

Criados para uso pessoal como **Analista de Sistemas e Engenheiro da Computação**, com suporte completo a conteúdo técnico: blocos de código com syntax highlighting, listas, passos numerados, estatísticas, citações e muito mais.

---

## Arquivos

| Arquivo | Formato | Uso |
|---|---|---|
| `instagram_template_gustavoboazms.html` | 600×600px (1:1) | Posts do feed do Instagram |
| `instagram_reel_template_gustavoboazms.html` | 338×600px (9:16) | Reels e Stories do Instagram |

Os dois templates compartilham o mesmo sistema de design: **36 paletas de cores**, **20 combinações tipográficas** e o mesmo sistema de ícones — garantindo identidade visual consistente entre post e reel.

---

## Como usar na sua máquina

Não há instalação. O único requisito é um navegador moderno (Chrome, Firefox, Edge ou Safari).

### 1. Clonar o projeto

```bash
git clone https://github.com/gustavoboazms/instagram-content-templates.git
cd instagram-content-templates
```

Ou baixar apenas um dos arquivos diretamente:

```bash
# Post (quadrado 1:1)
curl -fsSL https://raw.githubusercontent.com/gustavoboazms/instagram-content-templates/main/instagram_template_gustavoboazms.html \
     -o instagram_template_gustavoboazms.html

# Reel (vertical 9:16)
curl -fsSL https://raw.githubusercontent.com/gustavoboazms/instagram-content-templates/main/instagram_reel_template_gustavoboazms.html \
     -o instagram_reel_template_gustavoboazms.html
```

### 2. Abrir no navegador

Dê dois cliques no arquivo ou execute no terminal:

```bash
# macOS
open instagram_template_gustavoboazms.html
open instagram_reel_template_gustavoboazms.html

# Linux
xdg-open instagram_template_gustavoboazms.html
xdg-open instagram_reel_template_gustavoboazms.html

# Windows (PowerShell)
Start-Process instagram_template_gustavoboazms.html
Start-Process instagram_reel_template_gustavoboazms.html
```

> A primeira abertura requer conexão com a internet para carregar as fontes via Google Fonts CDN. Nas aberturas seguintes o navegador usa o cache local.

### 3. Carregar o exemplo

Clique em **↺ Exemplo** para preencher automaticamente todos os campos com um post de demonstração sobre Clean Code em Java. É a forma mais rápida de entender como cada bloco funciona antes de criar seu próprio conteúdo.

---

## Interface — como funciona

Os dois templates têm a mesma estrutura de interface:

```
[ ▶ Gerar ]  [ ↺ Exemplo ]        ← barra de ação, sempre visível no topo

┌──────────────────────────────┐
│ ⚙  Configurações Globais    │  ← paleta, fonte, ícone, header/footer
├──────────────────────────────┤
│ ①  Abertura / Capa          │  ← título, categoria, layout visual
├──────────────────────────────┤
│ ②  Slides / Telas           │  ← accordion por slide, reordenáveis
├──────────────────────────────┤
│ ③  Fechamento / Encerramento│  ← handle, mensagem, avatar, CTAs
└──────────────────────────────┘
```

Clique em cada seção para expandir — apenas uma fica aberta por vez. Ao editar qualquer campo, o preview atualiza em tempo real.

### Modo de visualização

No canto inferior direito há um botão de toggle de layout:

| Modo | Comportamento |
|---|---|
| ⬇️ Vertical | Editor acima, preview abaixo (padrão) |
| ➡️ Lado a lado | Editor à esquerda, preview à direita — ideal para editar e ver ao mesmo tempo |

No modo lado a lado, ao abrir a seção de Abertura/Capa o preview rola automaticamente para a primeira tela. O mesmo acontece com o Fechamento/Encerramento e com cada slide de conteúdo individualmente.

---

## Template de Post — 1:1 · 600×600px

Formato padrão do feed do Instagram.

### Estrutura de slides

```
Slide 1   →  Abertura    (10 layouts)
Slide 2+  →  Conteúdo   (ilimitados, reordenáveis)
Último    →  Fechamento  (8 layouts)
```

### Layouts de abertura

| Layout | Característica |
|---|---|
| Clássico | Linha lateral colorida + título no canto inferior |
| Centrado | Título e badge centralizados com glow radial |
| Dividido | Faixa horizontal com gradiente corta o slide ao meio |
| Big Type | Primeira palavra em tamanho gigante como elemento visual |
| Terminal | Bloco estilo linha de comando com `$`, `#` e `→` |
| Card | Título dentro de um card flutuante com borda suave |
| Diagonal | Polígono diagonal de cor preenche o lado esquerdo |
| Minimal | Só tipografia — traço, título, ponto de categoria |
| Badge | Círculo central com ícone + título e badge |
| Corner | Badge no topo esquerdo, título logo abaixo |

### Layouts de fechamento

| Layout | Característica |
|---|---|
| Clássico | Avatar centralizado + handle + mensagem + CTAs |
| Minimal | Só tipografia, sem avatar, alinhado à esquerda |
| Spotlight | Glow radial intenso atrás do avatar como holofote |
| Banner | Faixa de gradiente no topo com avatar emergindo |
| Card | Tudo dentro de um card frosted glass |
| Split | Avatar à esquerda, mensagem e CTAs à direita |
| Circuit | Linhas decorativas estilo circuito eletrônico no fundo |
| Full BG | Gradiente de cor preenche toda a área do slide |

### Blocos de conteúdo

| Bloco | Descrição |
|---|---|
| ✏️ Texto | Parágrafo simples |
| 📋 Lista | Lista com marcadores triangulares |
| 🔢 Passos | Lista numerada automática |
| 📊 Estatísticas | Cards com valor + descrição (até 4) |
| 💬 Citação | Bloco com aspas, texto e autor |
| 💡 Destaque | Card com borda lateral colorida |
| ⚠️ Dica / Aviso | Com ícone e label personalizáveis |
| ⚖️ Comparar | Duas colunas lado a lado |
| 🖼️ Imagem | 1 a 4 imagens, 5 arranjos, 4 formatos |
| 💻 Código | Syntax highlighting — 23 linguagens |
| ─ Divisor | Separador decorativo |

---

## Template de Reel — 9:16 · 338×600px preview / 1080×1920px real

Formato padrão de Reels e Stories do Instagram. O conteúdo respeita as **safe zones** — áreas onde a UI do Instagram sobrepõe o vídeo (≈70px no topo, ≈90px no rodapé).

### Estrutura de telas

```
Tela 1   →  Capa          (6 layouts)
Tela 2+  →  Conteúdo     (ilimitadas, reordenáveis)
Última   →  Encerramento  (4 layouts)
```

### Layouts de capa

| Layout | Característica |
|---|---|
| Bold | Título grande no rodapé com badge acima |
| Centrado | Título e badge centralizados com glow radial |
| Split | Faixa diagonal divide o fundo, título à direita |
| Terminal | Bloco estilo linha de comando `$ cat titulo.md` |
| Minimal | Só tipografia — traço, título, ponto de categoria |
| Badge | Ícone em círculo central + título + badge |

### Layouts de encerramento

| Layout | Característica |
|---|---|
| Clássico | Avatar + handle + mensagem + CTAs centralizados |
| Minimal | Sem avatar, texto alinhado à esquerda |
| Spotlight | Glow radial intenso atrás do avatar |
| Card | Tudo dentro de um card frosted glass |

### Blocos de conteúdo

| Bloco | Descrição |
|---|---|
| ✏️ Texto | Parágrafo simples |
| 📋 Lista | Lista com marcadores |
| 🔢 Passos | Lista numerada automática |
| 📊 Stats | Cards de estatísticas (até 4) |
| 💬 Citação | Bloco com aspas e autor |
| 💡 Destaque | Card com borda lateral colorida |
| ⚠️ Dica | Com ícone e label personalizáveis |
| 💻 Código | Syntax highlighting — 15 linguagens |

---

## Sistema de design compartilhado

Os dois templates usam exatamente as mesmas configurações visuais, garantindo identidade consistente entre post e reel.

### Paletas de cores — 36 no total

**Dark (16 paletas):** Neon · Fire · Violeta · Gold · Ice · Rose · Esmeralda · Cyber · Aurora · Ferrugem · Matrix · Oceano · Sakura · Midnight · Mono · Slate

**Light (20 paletas):** Clean · Paper · Sky · Mint · Rosa · Âmbar · Lavanda · Cinza · Pêssego · Teal · Creme · Blush · Sage · Ártico · Coral · Dusk · Nórdico · Orquídea · Pedra · Aqua

### Tipografia — 20 combinações

**Sans-serif:** Syne+DM Sans · Inter · Poppins · Outfit · Montserrat · Raleway · Nunito · Josefin Sans · Space Grotesk · Plus Jakarta Sans · Playfair Display · Urbanist · Bebas Neue · Exo 2 · Chakra Petch · Oxanium · Orbitron

**Monospace:** Fira Code · JetBrains Mono · Share Tech Mono

### Syntax highlighting — linguagens suportadas

Python · Java · Kotlin · JavaScript · TypeScript · C# · C/C++ · Go · Rust · PHP · Ruby · Swift · SQL · HTML · CSS · Terminal/Shell · YAML · JSON · XML · Dockerfile · Nginx · Gradle · Texto puro

### Ícone do handle — 4 modos

| Modo | Descrição |
|---|---|
| Emoji | Paleta com mais de 50 emojis temáticos |
| Forma / Cor | Círculos e quadrados arredondados em gradientes e cores sólidas |
| Imagem | Qualquer foto em círculo, quadrado ou arredondado |
| Nenhum | Remove o ícone completamente |

---

## Como exportar

**Screenshot (recomendado):** Use uma extensão de browser como **GoFullPage**, **Fireshot** ou **Awesome Screenshot** para capturar cada slide individualmente.

**Como PDF:**

```
Ctrl + P  (ou Cmd + P no Mac)
→ Impressora: "Salvar como PDF"
→ Escala: 100%
→ Margens: Nenhuma / Mínimas
```

---

## Estrutura do projeto

```
instagram-content-templates/
├── instagram_template_gustavoboazms.html       # Post 1:1 — 600×600px
├── instagram_reel_template_gustavoboazms.html  # Reel 9:16 — 338×600px
└── README.md
```

Cada arquivo é autossuficiente — não há dependências locais, pastas de assets ou arquivos de configuração adicionais. Tudo está embutido em um único HTML por arquivo.

---

## Requisitos

| Requisito | Detalhe |
|---|---|
| Navegador | Chrome 90+ · Firefox 88+ · Edge 90+ · Safari 14+ |
| Conexão | Apenas na primeira abertura (fontes Google Fonts) |
| Node.js / npm | ❌ Não necessário |
| Servidor web | ❌ Não necessário |
| Instalação | ❌ Nenhuma |

---

## Licença

MIT — use, modifique e distribua à vontade.
