# 📱 instagram-post-template

> Template visual para criação de posts do Instagram — totalmente offline, sem instalar nada, direto no navegador.

---

## Repositório

| | |
|---|---|
| 👤 Autor | [@gustavoboazms](https://github.com/gustavoboazms) |
| 📄 Arquivo principal | `instagram_template_gustavoboazms.html` |
| 🔧 Tecnologia | HTML + CSS + JavaScript puro (zero dependências) |

---

## O que é este projeto?

Um arquivo HTML único que funciona como um estúdio de criação de posts para o Instagram. Você abre no navegador, preenche os campos e o preview é gerado em tempo real — sem internet, sem conta, sem instalar nada.

Criado para uso pessoal como **Analista de Sistemas e Engenheiro da Computação**, com suporte a conteúdo técnico (código, listas, diagramas textuais, comparativos etc.).

---

## Funcionalidades

- **Accordion de configuração** — seções colapsáveis para não poluir a tela
- **Visualização vertical ou lado a lado** — edite e veja o preview simultaneamente
- **Slide de Abertura** — 10 layouts pré-definidos para escolher
- **Slides de Conteúdo** — reordenáveis via acordeão, com vários tipos de bloco
- **Slide de Fechamento** — 8 layouts, avatar/imagem personalizável
- **26+ Paletas de cores** — dark e light, com preview em tempo real
- **Tipografia** — 20 combinações de fontes do Google Fonts
- **Ícone do handle** — emoji, forma colorida ou imagem própria
- **Blocos de conteúdo disponíveis:**

| Bloco | Descrição |
|---|---|
| ✏️ Texto | Parágrafo simples |
| 📋 Lista | Lista com marcadores |
| 🔢 Passos | Lista numerada automática |
| 📊 Estatísticas | Cards com valor + descrição (até 4) |
| 💬 Citação | Bloco com aspas e autor |
| 💡 Destaque | Card com borda lateral colorida |
| ⚠️ Dica/Aviso | Com ícone e label personalizáveis |
| ⚖️ Comparar | Duas colunas lado a lado |
| 🖼️ Imagem | 1 a 4 imagens com 5 arranjos e 4 formatos |
| 💻 Código | Syntax highlighting para 23 linguagens |
| ─ Divisor | Separador decorativo |

- **Syntax highlighting** para: Python, Java, Kotlin, JavaScript, TypeScript, C#, C/C++, Go, Rust, PHP, Ruby, Swift, SQL, HTML, CSS, Terminal, YAML, JSON, XML, Dockerfile, Nginx, Gradle e Texto puro
- **Marca d'água** no slide de abertura — nenhuma, número customizável ou texto livre

---

## Como usar na sua máquina

Não há instalação. O único requisito é um navegador moderno (Chrome, Firefox, Edge ou Safari).

### 1. Clonar ou baixar o projeto

**Via Git:**
```bash
git clone https://github.com/gustavoboazms/instagram-post-template.git
cd instagram-post-template
```

**Ou baixar o arquivo diretamente:**
```bash
curl -fsSL https://raw.githubusercontent.com/gustavoboazms/instagram-post-template/main/instagram_template_gustavoboazms.html \
     -o instagram_template_gustavoboazms.html
```

### 2. Abrir no navegador

Basta dar dois cliques no arquivo ou rodar:

```bash
# macOS
open instagram_template_gustavoboazms.html

# Linux
xdg-open instagram_template_gustavoboazms.html

# Windows (PowerShell)
Start-Process instagram_template_gustavoboazms.html
```

### 3. Criar seu post

O editor está dividido em 4 seções do accordion:

```
⚙  Configurações Globais   → ícone, paleta, tipografia, header/footer
①  Slide de Abertura       → título, categoria, layout visual
②  Slides de Conteúdo      → seus slides editáveis e reordenáveis
③  Slide de Fechamento     → handle, mensagem, avatar, CTAs
```

Clique em cada seção para expandir. Os botões **▶ Gerar Slides** e **↺ Exemplo** ficam fixos no topo.

### 4. Escolher o modo de visualização

No canto inferior direito há um botão de toggle:

- **⬇️ Vertical** — editor acima, preview abaixo (padrão)
- **➡️ Lado a lado** — editor à esquerda, preview à direita em tempo real

### 5. Exportar

Cada slide tem 600×600px (formato quadrado padrão do Instagram).

**Para exportar como imagem:**
- Screenshot individual de cada slide (recomendado)
- Extensão de browser como **GoFullPage** ou **Fireshot**

**Para exportar como PDF:**
```
Ctrl + P (ou Cmd + P no Mac)
→ Selecione "Salvar como PDF"
→ Defina escala 100% e margens mínimas
```

---

## Estrutura do projeto

```
instagram-post-template/
└── instagram_template_gustavoboazms.html   # Arquivo único — tudo está aqui
```

O projeto é intencionalmente um arquivo único. Não há dependências externas instaladas localmente — as fontes são carregadas do Google Fonts via CDN ao abrir no navegador.

> **Atenção:** A primeira abertura requer conexão com a internet para carregar as fontes do Google Fonts. Nas aberturas seguintes o navegador usa o cache.

---

## Requisitos

| Requisito | Versão mínima |
|---|---|
| Navegador | Chrome 90+, Firefox 88+, Edge 90+, Safari 14+ |
| Conexão | Apenas na primeira abertura (fontes Google Fonts) |
| Node.js / npm | ❌ Não necessário |
| Servidor web | ❌ Não necessário |

---

## Personalização rápida

| O que mudar | Onde |
|---|---|
| Seu @ | Campo **"Esquerda — Handle"** em Configurações Globais |
| Profissão no rodapé | Campo **"Esquerda"** no Footer |
| Paleta padrão | Seção **Paleta de Cores** (dark ou light) |
| Tipografia padrão | Seção **Tipografia** |
| Mensagem de fechamento | Campo **"Mensagem principal"** em Slide de Fechamento |

---

## Licença

MIT — use, modifique e distribua à vontade.
