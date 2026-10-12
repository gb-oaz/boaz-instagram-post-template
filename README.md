# 📱 content-templates

> Templates visuais para criação de **Posts**, **Reels** e **Slides para YouTube** — 100% offline, sem instalar nada, direto no navegador.

---

## Repositório

| | |
|---|---|
| 👤 Autor | [@gustavoboazms](https://github.com/gustavoboazms) |
| 🔐 Clone SSH | `git@github.com:gustavoboazms/instagram-content-templates.git` |
| 🔗 Clone HTTPS | `https://github.com/gustavoboazms/instagram-content-templates.git` |

---

## O que são estes templates?

Três arquivos HTML independentes que funcionam como estúdios de criação de conteúdo para Instagram e YouTube. Você abre no navegador, preenche os campos e o preview é gerado em tempo real — sem internet, sem conta, sem instalar nada.

Criados para uso pessoal como **Analista de Sistemas e Engenheiro da Computação**, com suporte completo a conteúdo técnico: blocos de código com syntax highlighting, listas, passos numerados, estatísticas, citações e muito mais.

---

## Arquivos

| Arquivo | Formato | Uso |
|---|---|---|
| `instagram_template_gustavoboazms.html` | 600×600px (1:1) | Posts do feed do Instagram |
| `instagram_reel_template_gustavoboazms.html` | 338×600px (9:16) | Reels e Stories do Instagram |
| `youtube_slides_template_gustavoboazms.html` | 1280×720px (16:9) | Slides de apresentação para YouTube |

Os três templates compartilham o mesmo sistema de design: **paletas de cores**, **combinações tipográficas** e sistema de ícones — garantindo identidade visual consistente entre todos os formatos.

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

# YouTube Slides (horizontal 16:9)
curl -fsSL https://raw.githubusercontent.com/gustavoboazms/instagram-content-templates/main/youtube_slides_template_gustavoboazms.html \
     -o youtube_slides_template_gustavoboazms.html
```

### 2. Abrir no navegador

Dê dois cliques no arquivo ou execute no terminal:

```bash
# macOS
open instagram_template_gustavoboazms.html
open instagram_reel_template_gustavoboazms.html
open youtube_slides_template_gustavoboazms.html

# Linux
xdg-open instagram_template_gustavoboazms.html
xdg-open instagram_reel_template_gustavoboazms.html
xdg-open youtube_slides_template_gustavoboazms.html

# Windows (PowerShell)
Start-Process instagram_template_gustavoboazms.html
Start-Process instagram_reel_template_gustavoboazms.html
Start-Process youtube_slides_template_gustavoboazms.html
```

> A primeira abertura requer conexão com a internet para carregar as fontes via Google Fonts CDN. Nas aberturas seguintes o navegador usa o cache local.

### 3. Carregar o exemplo

Clique em **↺ Exemplo** para preencher automaticamente todos os campos com um conteúdo de demonstração sobre Clean Code em Java. É a forma mais rápida de entender como cada bloco funciona antes de criar seu próprio conteúdo.

---

## Interface — como funciona

Os três templates têm a mesma estrutura de interface:

```
[ ▶ Gerar ]  [ ↺ Exemplo ]  [ ⬇ Baixar ]   ← barra de ação, sempre visível no topo

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

Clique em cada seção para expandir — apenas uma fica aberta por vez. Ao editar qualquer campo, o preview atualiza em tempo real. Ao abrir uma seção, o editor faz scroll automático para ela.

### Blocos de conteúdo

Dentro de cada slide de conteúdo você pode adicionar e reordenar blocos livremente. Ao clicar no cabeçalho de um slide para abri-lo, os blocos são renderizados imediatamente no editor.

### Modo de visualização

No canto inferior direito há um botão de toggle de layout:

| Modo | Comportamento |
|---|---|
| ⬇️ Vertical | Editor acima, preview abaixo (padrão) |
| ➡️ Lado a lado | Editor à esquerda, preview à direita — ideal para editar e ver ao mesmo tempo |

No modo lado a lado, ao abrir qualquer seção ou clicar em um slide de conteúdo, o preview rola automaticamente para o slide correspondente. O editor também faz scroll para manter o item clicado visível.

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
| ✏️ Texto | Parágrafo simples. Suporta destaque inline com `==palavra==` |
| 📋 Lista | Lista com marcadores triangulares. Colunas configuráveis (1–4) |
| 🔢 Passos | Lista numerada automática. Colunas configuráveis (1–4) |
| 📊 Estatísticas | Cards com valor + descrição (até 4). Layout responsivo com wrap |
| 💬 Citação | Bloco com aspas, texto e autor |
| 💡 Destaque | Card com borda lateral colorida. Suporta destaque inline com `==palavra==` |
| ⚠️ Dica / Aviso | Com ícone e label personalizáveis |
| ⚖️ Comparar | N colunas lado a lado (expansível), layout wrap centralizado |
| 🖼️ Imagem | Posicionamento livre no slide com mini-canvas de drag, resize e rotação |
| 💻 Código | Syntax highlighting — 24 linguagens |
| 🗂️ Tabela | Tabela com N colunas e linhas dinâmicas, estilizada com as cores do tema |
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
| ✏️ Texto | Parágrafo simples. Suporta destaque inline com `==palavra==` |
| 📋 Lista | Lista com marcadores. Colunas configuráveis (1–3) |
| 🔢 Passos | Lista numerada automática. Colunas configuráveis (1–3) |
| 📊 Stats | Cards de estatísticas (até 4). Layout responsivo com wrap automático |
| 💬 Citação | Bloco com aspas e autor |
| 💡 Destaque | Card com borda lateral colorida. Suporta destaque inline com `==palavra==` |
| ⚠️ Dica | Com ícone e label personalizáveis |
| ⚖️ Comparar | N colunas expansíveis, layout wrap centralizado |
| 💻 Código | Syntax highlighting — 16 linguagens |
| 🗂️ Tabela | Tabela com N colunas e linhas dinâmicas, estilizada com as cores do tema |

---

## Template de YouTube — 16:9 · 1280×720px

Formato horizontal para slides de apresentação de vídeos do YouTube. Ideal para criar sequências de imagens que ilustram o conteúdo do vídeo — capa, slides de desenvolvimento e encerramento.

O preview é escalado proporcionalmente para caber na tela, mas o download sempre gera os arquivos em resolução completa de 1280×720px.

### Estrutura de slides

```
Slide 1   →  Capa          (10 layouts)
Slide 2+  →  Conteúdo     (ilimitados, reordenáveis)
Último    →  Encerramento  (7 layouts)
```

### Layouts de capa

| Layout | Característica |
|---|---|
| Clássico | Linha lateral colorida + título grande à esquerda |
| Centrado | Tudo centralizado com glow radial |
| Dividido | Faixa horizontal de cor separa badge e título |
| Big Type | Primeira palavra gigante como fundo decorativo |
| Terminal | Estilo CLI dark com barra de título e linhas de comando |
| Card | Título dentro de card com blur e borda colorida |
| Diagonal | Polígono diagonal de cor preenche o lado esquerdo |
| Minimal | Só tipografia — traço, título, categoria |
| Badge | Ícone grande em círculo à esquerda + título |
| Impact | Título em uppercase gigante sobre gradiente dramático |

### Layouts de encerramento

| Layout | Característica |
|---|---|
| Clássico | Avatar centralizado + handle + mensagem + CTAs |
| Minimal | Só tipografia, sem avatar, alinhado à esquerda |
| Spotlight | Glow radial intenso atrás do avatar |
| Split | Avatar à esquerda, mensagem e CTAs à direita |
| Card | Tudo dentro de um card frosted glass centralizado |
| Full BG | Gradiente de cor preenche toda a área do slide |
| Banner | Faixa de gradiente no topo com avatar emergindo |

### Blocos de conteúdo

| Bloco | Descrição |
|---|---|
| ✏️ Texto | Parágrafo simples. Suporta destaque inline com `==palavra==` |
| 📋 Lista | Lista com marcadores. Colunas configuráveis (1–3) |
| 🔢 Passos | Lista numerada automática. Colunas configuráveis (1–3) |
| 📊 Estatísticas | Cards com valor + descrição (até 4). Layout responsivo |
| 💬 Citação | Bloco com aspas, texto e autor |
| 💡 Destaque | Card com borda lateral colorida. Suporta destaque inline com `==palavra==` |
| ⚠️ Dica | Com ícone e label personalizáveis |
| ⚖️ Comparar | N colunas expansíveis, layout wrap centralizado |
| 💻 Código | Syntax highlighting — 22 linguagens |
| 🗂️ Tabela | Tabela com N colunas e linhas dinâmicas, estilizada com as cores do tema |
| 🖼️ Imagem | Posicionamento livre no slide com mini-canvas de drag, resize e rotação |
| ─ Divisor | Separador decorativo com label opcional |

### Configurações específicas do YouTube

**Campos da capa:**
- Categoria / Badge e Número / Parte (ex: `#01`, `Parte 2`)
- Título principal e subtítulo
- Palavra de destaque no título — colorida automaticamente com a cor da paleta

**Encerramento:**
- Handle do canal e subtítulo / ocupação
- Mensagem de encerramento
- Avatar: ícone emoji, foto carregada ou nenhum
- CTAs configuráveis (emoji + label, quantidade ilimitada)

**Modo lado a lado:** ao clicar em um slide de conteúdo para editar, o preview rola automaticamente para deixar aquele slide visível e centralizado na tela.

---

## Destaque inline de palavras

Disponível nos blocos **Texto** e **Destaque** em todos os templates.

| Sintaxe | Resultado |
|---|---|
| `==palavra==` | Destaca com a cor principal do tema ativo |
| `==palavra\|#ffcc00==` | Destaca com a cor personalizada informada |

O destaque renderiza como um span com fundo semitransparente e texto colorido, integrado ao fluxo do parágrafo.

---

## Sistema de design compartilhado

Os três templates usam as mesmas configurações visuais base, garantindo identidade consistente entre todos os formatos.

### Paletas de cores

**Dark:** Neon · Fire · Violeta · Gold · Ice · Rose · Esmeralda · Cyber · Aurora · Ferrugem · Matrix · Oceano · Midnight · Mono · Slate · **YouTube** (exclusiva do template YT)

**Light:** Clean · Paper · Sky · Mint · Rosa · Âmbar · Lavanda · Cinza · Pêssego · Teal · Creme · Blush · Sage · Ártico · Coral · Dusk · Nórdico · Orquídea · Pedra · Aqua

### Tipografia

**Sans-serif:** Syne+DM Sans · Inter · Poppins · Outfit · Montserrat · Raleway · Nunito · Josefin Sans · Space Grotesk · Plus Jakarta Sans · Playfair Display · Urbanist · Bebas Neue · Exo 2 · Chakra Petch · Oxanium · Orbitron

**Monospace:** Fira Code · JetBrains Mono · Share Tech Mono

### Syntax highlighting — linguagens suportadas

Python · Java · Kotlin · JavaScript · TypeScript · C# · C/C++ · Go · Rust · PHP · Ruby · Swift · SQL · HTML · CSS · Terminal/Shell · YAML · JSON · XML · Dockerfile · Nginx · Gradle · Terraform (HCL) · Texto puro

> **Fix Java:** anotações como `@Override`, `@Autowired`, `@Entity` são corretamente coloridas sem quebrar o HTML do syntax highlighting.

> **Terraform (HCL):** disponível nos três templates (`terraform` no seletor do YouTube). Colore tipos de bloco (`resource`, `variable`…), rótulos, atributos, strings com interpolação `${…}`, números e comentários.

### Ícone do handle — modos disponíveis

| Modo | Descrição |
|---|---|
| Emoji | Paleta com mais de 50 emojis temáticos |
| Forma / Cor | Círculos e quadrados arredondados em gradientes e cores sólidas |
| Imagem | Qualquer foto em círculo, quadrado ou arredondado |
| Nenhum | Remove o ícone completamente |

---

## Como exportar

**PNG direto (recomendado):** Clique em **⬇ Baixar todos os slides (PNG)**. Todos os slides são gerados em resolução real e baixados sequencialmente.

**Vídeo MP4 do Reel:** no template de Reel, o botão **⬇ Baixar telas (PNG) + vídeo (MP4)** exporta as telas e, em seguida, gera `titulo_reel.mp4`:

| Item | Valor |
|---|---|
| Resolução | 1080×1920 (9:16), 30 fps, H.264 |
| Duração | **sempre 60 s**, divididos igualmente entre as telas (ex.: 6 telas = 10 s cada) |
| Transição | fade de 0,4 s no fim de cada tela, dentro do tempo dela |
| Áudio | nenhum: adicione narração ou música no editor de vídeo |

No Chrome, Edge e navegadores com WebCodecs, o vídeo é codificado em segundos. Sem WebCodecs, o template grava em tempo real com MediaRecorder: leva 60 s, a aba precisa ficar aberta, e o arquivo sai em MP4 se o navegador suportar, senão em WebM.

**Screenshot manual:** Use uma extensão de browser como **GoFullPage**, **Fireshot** ou **Awesome Screenshot** para capturar cada slide individualmente.

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
├── instagram_template_gustavoboazms.html        # Post 1:1 — 600×600px
├── instagram_reel_template_gustavoboazms.html   # Reel 9:16 — 338×600px
├── youtube_slides_template_gustavoboazms.html   # YouTube 16:9 — 1280×720px
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

## Changelog

### v5 — Terraform e exportação do texto em gradiente

- **Linguagem Terraform (HCL)** no bloco Código dos três templates
- **Handle do fechamento na exportação** — o html2canvas não suporta `background-clip:text` e exportava o handle como uma caixa de gradiente sólida; agora, só na cópia usada para exportar, o texto em gradiente é desenhado na cor principal da paleta (o preview mantém o gradiente)

### v4 — vídeo MP4 no Reel

- **Exportar Reel em vídeo** — o botão de download do template de Reel passa a gerar também um `.mp4` 1080×1920 de 60 s, com o tempo dividido igualmente entre as telas e fade entre elas; usa WebCodecs + [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) (CDN), com fallback para MediaRecorder

### v3 — template YouTube + correções de UX

- **Novo template YouTube** — slides 16:9 (1280×720px) com capa, slides de conteúdo e encerramento; 10 layouts de capa, 7 de encerramento, todos os blocos de conteúdo do Instagram adaptados para o formato horizontal
- **Preview escalado proporcional** — os slides no preview são redimensionados para caber na área disponível mantendo a proporção correta; no YouTube o wrapper reserva a altura exata escalada, sem desalinhamentos
- **Scroll automático no modo lado a lado** — ao clicar em um slide de conteúdo para editar, o preview rola para deixar aquele slide visível e centralizado; funciona nos três templates
- **Blocos aparecem ao abrir slide** — corrigido bug onde clicar no cabeçalho de um slide abria o container mas deixava a lista de blocos vazia; agora `renderBlocks` é sempre chamado ao expandir
- **Scroll do accordion no YouTube** — corrigido `overflow:hidden` no accordion que impedia o scroll no modo horizontal
- **Paleta YouTube** — nova paleta dark com vermelho e laranja exclusiva do template YouTube

### v2 — melhorias nos blocos de conteúdo

- **Texto / Destaque** — destaque inline de palavras com `==palavra==` ou `==palavra|#cor==`
- **Lista** — configuração de colunas (1–4 no post, 1–3 no reel)
- **Passos** — configuração de colunas (1–4 no post, 1–3 no reel)
- **Estatísticas** — layout responsivo com `flex-wrap`; no reel estreito os cards quebram automaticamente para linha de baixo
- **Comparar** — expandido de 2 colunas fixas para N colunas dinâmicas; cada coluna tem título, ícone e cor independentes; layout wrap centralizado funciona em qualquer largura
- **Tabela** — novo bloco com cabeçalhos editáveis, N colunas (1–6), linhas add/remove dinâmicas, estilizado com as cores do tema ativo
- **Código Java** — corrigido bug onde `@Override` e outras anotações quebravam o HTML do syntax highlighting

---

## Licença

MIT — use, modifique e distribua à vontade.
