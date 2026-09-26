# 🎨 PRD — Identidade Visual DataMining BI Consulting
> Gerado com base no site dataminingits.com.br e na metodologia do vídeo "Como fazer designs PROFISSIONAIS usando o Claude Design" — Deborah Folloni

---

## 1. CONCEITO DA MARCA

| Campo | Valor |
|---|---|
| **Nome** | DataMining — BI Consulting |
| **Tagline** | Transforme seus dados em decisões rentáveis com Power BI |
| **O que faz** | Estrutura dados, constrói dashboards executivos e automatiza indicadores para gerar visão estratégica em tempo real |
| **Para quem** | Empresas que precisam de governança e escala em BI + operações que querem crescer com inteligência de dados |
| **Tom de voz** | Elegante, criativo e direto — confiança técnica com clareza executiva |
| **3 palavras** | Precisão · Previsibilidade · Resultado |
| **Promessa** | Menos planilha manual. Mais previsibilidade, velocidade e resultado |

---

## 2. LOGOTIPO

- **Símbolo:** Monograma "DM" com letras geométricas
- **Gradiente:** Ciano (#00d4ff) → Roxo (#7c3aed), da esquerda para direita
- **Wordmark:** "DataMining" em branco abaixo do símbolo, fonte sans-serif
- **Subtítulo:** "BI CONSULTING" em caixa alta, peso leve, cor muted
- **Uso:** Sempre sobre fundo escuro (#050b18 ou similar)
- **Arquivo:** Solicitar versão SVG e PNG com fundo transparente

---

## 3. PALETA DE CORES

### Cores Principais (CSS Variables extraídas do site)

| Variável | Papel | Hex |
|---|---|---|
| `--bg` | Fundo principal | `#050b18` |
| `--bg-soft` | Fundo suave / seções alternadas | `#080f20` |
| `--card` | Cards e painéis | `#0d1a2e` |
| `--card-2` | Cards secundários | `#112240` |
| `--text` | Texto principal | `#e2e8f0` |
| `--muted` | Texto secundário / legendas | `#94a3b8` |
| `--brand` | **Cor de marca — Ciano** | `#00d4ff` |
| `--brand-2` | **Cor de marca — Roxo** | `#7c3aed` |
| `--accent` | Acento / hover states | `#06b6d4` |
| `--line` | Bordas sutis | `rgba(0, 212, 255, 0.12)` |
| `--glow` | Halos luminosos | `rgba(0, 212, 255, 0.15)` |

### Gradiente Característico
```
background: linear-gradient(135deg, #7c3aed, #00d4ff);
```
> Usado em: logo, botões CTA primários, destaques de texto, badges, barras de progresso

### Efeito de Fundo (Background Glow)
```
background:
  radial-gradient(circle at 15% 10%, rgba(124, 58, 237, 0.16), transparent 42%),
  radial-gradient(circle at 90% 18%, rgba(0, 212, 255, 0.18), transparent 40%),
  #050b18;
```

---

## 4. TIPOGRAFIA

| Papel | Fonte | Peso | Tamanho |
|---|---|---|---|
| **H1 — Título principal** | Space Grotesk | 700 (Bold) | 58px |
| **H2 — Subtítulo de seção** | Space Grotesk | 700 (Bold) | 35px |
| **H3 — Títulos de card** | Space Grotesk | 600 (SemiBold) | 22px |
| **Body — Parágrafos** | Plus Jakarta Sans | 400 (Regular) | 17px |
| **Nav / UI** | Plus Jakarta Sans | 500 (Medium) | 15px |
| **Caption / Labels** | Plus Jakarta Sans | 400 (Regular) | 13px |
| **Badges / Tags** | Plus Jakarta Sans | 700 (Bold) | 11px — ALL CAPS |

### Links de Download (Google Fonts)
- Space Grotesk: https://fonts.google.com/specimen/Space+Grotesk
- Plus Jakarta Sans: https://fonts.google.com/specimen/Plus+Jakarta+Sans

---

## 5. ESTILO VISUAL E COMPONENTES

### Cards
- Background: `#0d1a2e` ou `#112240`
- Border: `1px solid rgba(0, 212, 255, 0.12)`
- Border-radius: `18px`
- Shadow: `0 22px 60px rgba(0, 0, 0, 0.35)`
- Padding: `32px`

### Botões
- **CTA Primário:** Gradiente (#7c3aed → #00d4ff), texto branco, radius 50px (pill), padding 14px 32px
- **CTA Secundário:** Fundo transparente, borda branca, texto branco, radius 50px
- **Badge/Tag:** Fundo escuro semitransparente, borda ciano sutil, texto ciano, ALL CAPS, radius 50px

### Ícones de Numeração
- Formato: `01`, `02`, `03` em caixas com fundo gradiente (roxo)
- Fonte: Space Grotesk Bold
- Cor: Branco sobre gradiente roxo/ciano
- Tamanho da caixa: ~48x48px, radius 12px

### Barras de Dados / Progress Bars
- Gradiente: ciano (#00d4ff) → roxo (#7c3aed)
- Altura: 6-8px
- Radius: 99px (pill)
- Fundo track: rgba(255,255,255,0.08)

### Tags Tecnologia (Skill Pills)
- Ex: Power BI · DAX · SQL Server · Python · ETL · Indicadores
- Estilo: border 1px ciano sutil, fundo transparente, texto ciano (#00d4ff)
- Radius: 50px

---

## 6. DISTINTIVIDADE

O elemento mais reconhecível da DataMining é o **gradiente ciano ↔ roxo** aplicado de forma consistente:
- No monograma DM do logo
- No botão CTA principal
- Nos destaques de texto do hero ("decisões", "rentáveis")
- Nas barras de progresso e indicadores de dados
- No efeito de glow/halo do background

**Esse gradiente = DataMining.** É a assinatura visual da marca.

---

## 7. PROMPT COMPLETO PARA O CLAUDE DESIGN

Cole o texto abaixo no Claude Design para configurar o Design System:

---

```
Você é um designer especialista em identidade visual e Design Systems.

Crie um Design System completo para a marca DataMining — BI Consulting.

## SOBRE A MARCA
- Nome: DataMining — BI Consulting
- Tagline: "Transforme seus dados em decisões rentáveis com Power BI"
- O que faz: Estrutura dados, constrói dashboards executivos e automatiza indicadores para gerar visão estratégica em tempo real
- Para quem: Empresas que precisam de governança e escala em BI; operações que querem crescer com inteligência de dados
- Tom de voz: Elegante, criativo e direto — confiança técnica com clareza executiva
- 3 palavras: Precisão · Previsibilidade · Resultado
- Diferencial visual: O gradiente ciano (#00d4ff) ↔ roxo (#7c3aed) é a assinatura da marca — deve aparecer em todos os materiais

## PALETA DE CORES
- Fundo principal: #050b18
- Fundo suave: #080f20
- Card: #0d1a2e
- Card 2: #112240
- Texto principal: #e2e8f0
- Texto secundário: #94a3b8
- Brand Ciano: #00d4ff
- Brand Roxo: #7c3aed
- Acento: #06b6d4
- Borda sutil: rgba(0, 212, 255, 0.12)
- Gradiente principal: linear-gradient(135deg, #7c3aed, #00d4ff)

## TIPOGRAFIA
- Títulos (H1/H2/H3): Space Grotesk, Bold 700
- Corpo e UI: Plus Jakarta Sans, Regular 400 / Medium 500
- H1: 58px | H2: 35px | H3: 22px | Body: 17px | Caption: 13px | Badge: 11px ALL CAPS

## ESTILO VISUAL
- Modo: Dark (fundo escuro profundo)
- Cards: background #0d1a2e, border 1px rgba(0,212,255,0.12), radius 18px
- Botão CTA: gradiente roxo→ciano, pill shape (radius 50px)
- Glow de fundo: halos sutis roxo e ciano nos cantos
- Ícones numéricos: 01/02/03 em caixas com gradiente roxo, radius 12px
- Barras de dados: gradiente ciano→roxo, pill shape
- Tags/badges: borda ciano sutil, texto ciano, ALL CAPS

## O QUE PRECISO

1. Style guide completo com todos os tokens de design
2. Componentes: botões (primário, secundário, ghost), cards, badges, progress bars, tags
3. Header/nav com logo, menu e CTA
4. Hero section com headline em gradiente, subtítulo e dois botões
5. Section de métricas (estilo +60%, +5, <30 dias)
6. Card de serviço (3 colunas)
7. Template de apresentação com 6 slides:
   - Slide 1: Capa com logo e tagline
   - Slide 2: O problema (dados sem estrutura)
   - Slide 3: Nossa solução (3 pilares)
   - Slide 4: Resultados / Cases
   - Slide 5: Processo em 4 etapas
   - Slide 6: CTA final com contato

IMPORTANTE: Mantenha 100% fidelidade à identidade visual descrita. 
O gradiente ciano↔roxo deve ser o elemento de destaque em todos os materiais.
Fundo sempre dark. Nunca use branco como fundo.
```

---

## 8. PROMPTS ADICIONAIS (usar após o Design System configurado)

### Post Instagram
```
Crie um post para Instagram (1080x1080px) para a DataMining BI Consulting sobre o tema: [TEMA].
Use estritamente o Design System da marca: fundo #050b18, gradiente ciano(#00d4ff)↔roxo(#7c3aed), fontes Space Grotesk (títulos) e Plus Jakarta Sans (corpo).
Tom: direto e executivo. Inclua logo DM no canto superior esquerdo.
```

### LinkedIn Banner
```
Crie um banner para LinkedIn (1584x396px) para a DataMining.
Fundo dark #050b18 com glow roxo e ciano. Headline em Space Grotesk Bold com palavra de destaque em gradiente.
Tagline: "Transforme seus dados em decisões rentáveis com Power BI". Logo no lado esquerdo.
```

### Proposta Comercial
```
Crie um template de proposta comercial (A4) para a DataMining com:
- Capa com logo, nome do cliente e título do projeto
- Página de sumário executivo
- Página de diagnóstico e problema
- Página de solução e entregáveis
- Página de investimento e próximos passos
Use toda a identidade visual: dark mode, gradiente ciano↔roxo, fontes Space Grotesk + Plus Jakarta Sans.
```

---

## 9. CHECKLIST DE ASSETS NECESSÁRIOS

- [ ] Logo DM em SVG (fundo transparente)
- [ ] Logo DM em PNG (fundo transparente, 512x512px)
- [ ] Favicon (32x32px e 192x192px)
- [ ] Fontes baixadas: Space Grotesk (.ttf) + Plus Jakarta Sans (.ttf)
- [ ] Paleta exportada como arquivo de cores
- [ ] Guia de uso do logo (margens mínimas, versões permitidas)

---

*PRD gerado por Claude com base na análise de dataminingits.com.br*
*Metodologia: "Como fazer designs PROFISSIONAIS usando o Claude Design" — Deborah Folloni*
