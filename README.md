# 🧭 DR. DE.SOUZ.AI Orys™

**Pedagogical diagnostic & lesson-plan engine for the AI-mediated classroom.**
*A lighthouse for teaching in the AI era.*

Built on **Orys Learning Architecture™** methodology and the **10 Orys Patterns™** — a published academic taxonomy of contemporary classroom behaviors (de Souza, 2025).

Bilingual: **🇧🇷 Português** + **🇺🇸 English** | Designed for higher-ed faculty, K-12 educators, and institutional accreditation contexts.

---

## 🇺🇸 English

### What Orys does

Orys is a **diagnostic engine** for teachers in the AI-mediated classroom. You provide 7 structured inputs about your class; Orys returns:

- ✦ A **complete competency-aligned learning trail**
- ✦ A **6-layer Orys Learning Architecture™ didactic sequence** (Activation → Bloom Strategies → Orys Pattern Intervention → Quick Evidence → Procedural Training → Metacognition)
- ✦ **Diagnostic of the active Orys Pattern™** in your class (1 of 10 patterns of the digitally-mediated era)
- ✦ **Quick evidence rubrics at 3 sufficiency levels** (Sufficient / Partial / Insufficient)
- ✦ **Actionable Learning Analytics indicators** for instructor validation
- ✦ **Integrated academic citations** (Bloom, Goleman, Dweck, Ausubel + de Souza, 2025)

Aligned with regional accreditation standards (IACG 2026 / HLC / QAA / ARCU-SUR).

### Skills available in this plugin

| Command | What it does |
|---|---|
| `/orys:architecture` | Generates a full competency-based lesson plan (the flagship skill) |
| `/orys:diagnose` | Analyzes a class behavioral description and identifies the active Orys Pattern™ |
| `/orys:pattern <1-10>` | Returns the full dossier of a specific Orys Pattern™ |
| `/orys:rubric` | Generates a 3-level sufficiency rubric for any assignment |
| `/orys:worksheet` | Generates a printable Orys Learning Architecture™ worksheet from a catalog of 10 original templates (Activation Trail, 4-Domain Notebook, Trio Micro-Delivery Card, ACE Critical Analysis, TAR Peer Feedback, and more) |

### Installation

**Local testing (development):**
```bash
claude --plugin-dir ./orys
```

**Validate before publishing:**
```bash
claude plugin validate ./orys
```

**Install from the community marketplace (after Anthropic approval):**
```bash
/plugin marketplace add anthropics/claude-plugins-community
/plugin install orys@claude-community
```

**Install from your own GitHub repo (no approval needed):**
```bash
/plugin marketplace add mrdesouzaphd-cmyk/orys
/plugin install orys@orys
```

**Submit to the community marketplace** via one of:
- [claude.ai/settings/plugins/submit](https://claude.ai/settings/plugins/submit)
- [platform.claude.com/plugins/submit](https://platform.claude.com/plugins/submit)

### Usage example

```
/orys:architecture

Theme: renewable natural resources — solar, wind, hydro, biomass, geothermal
Objective: connect resource-extraction trade-offs with sustainability indicators
Audience: 30 Environmental Sciences students, 4th semester, 18–24 yrs
Modality: hybrid, flipped classroom, 90 min
Context: 2 sustainability case studies + group decision-making activity
Behavioral challenge: not sure — help me identify
```

Orys returns a complete branded lesson plan with pattern diagnostic, intervention design, rubric, and Learning Analytics indicators.

### License

MIT License — see [LICENSE](./LICENSE).

The **methodology** (Orys Learning Architecture™), **the 10 Orys Patterns™**, and the **book content** (*Orys Learning Architecture™ Vol. 1*, de Souza, 2025) remain the intellectual property of **Dr. de Souza** and are referenced under fair academic-use citation. Commercial reproduction of the methodology beyond plugin use requires written authorization.

### Citation

When citing outputs of this plugin in academic or institutional reports:

> de Souza (2025). *DR. DE.SOUZ.AI Orys™ — Orys Learning Architecture™ Methodology Vol. 1.* https://drdesouza.ai

---

## 🇧🇷 Português

### O que o Orys faz

Orys é um **dispositivo diagnóstico** para a docência na sala de aula mediada por IA. Você fornece 7 inputs estruturados sobre sua aula; o Orys devolve:

- ✦ **Trilha completa alinhada por competências**
- ✦ **Sequência didática Orys Learning Architecture™ em 6 camadas** (Ativação → Estratégias Bloom → Intervenção Padrão Orys → Evidência Rápida → Treino Procedimental → Metacognição)
- ✦ **Diagnóstico do Padrão Orys™ ativo** na turma (1 dos 10 padrões da era da mediação digital)
- ✦ **Rubricas de evidência rápida em 3 níveis de suficiência** (Suficiente / Parcial / Insuficiente)
- ✦ **Indicadores Acionáveis de Learning Analytics** para validação docente
- ✦ **Citações acadêmicas integradas** (Bloom, Goleman, Dweck, Ausubel + de Souza, 2025)

Alinhado a padrões de acreditação regional (IACG 2026 / HLC / QAA / ARCU-SUR).

### Skills disponíveis neste plugin

| Comando | O que faz |
|---|---|
| `/orys:architecture` | Gera um plano de aula completo por competências (skill principal) |
| `/orys:diagnose` | Analisa uma descrição comportamental da turma e identifica o Padrão Orys™ ativo |
| `/orys:pattern <1-10>` | Retorna o dossiê completo de um Padrão Orys™ específico |
| `/orys:rubric` | Gera rubrica de suficiência em 3 níveis para qualquer atividade |
| `/orys:worksheet` | Gera folhas de atividade Orys Learning Architecture™ a partir de catálogo de 10 modelos originais (Trilha de Ativação, Caderno em 4 Domínios, Cartão de Microentrega do Trio, Análise Crítica ACE, TAR Feedback entre Pares e outros) |

### Instalação

**Teste local (desenvolvimento):**
```bash
claude --plugin-dir ./orys
```

**Validar antes de publicar:**
```bash
claude plugin validate ./orys
```

**Instalar a partir do marketplace da comunidade (após aprovação da Anthropic):**
```bash
/plugin marketplace add anthropics/claude-plugins-community
/plugin install orys@claude-community
```

**Instalar a partir do seu próprio repositório GitHub (sem aprovação necessária):**
```bash
/plugin marketplace add mrdesouzaphd-cmyk/orys
/plugin install orys@orys
```

**Submeter ao marketplace da comunidade** via um dos formulários:
- [claude.ai/settings/plugins/submit](https://claude.ai/settings/plugins/submit)
- [platform.claude.com/plugins/submit](https://platform.claude.com/plugins/submit)

### Exemplo de uso

```
/orys:architecture

Tema: recursos naturais renováveis — solar, eólica, hidráulica, biomassa, geotérmica
Objetivo: conectar trade-offs de extração de recursos com indicadores de sustentabilidade
Público: 30 estudantes de Ciências Ambientais, 4º semestre, 18–24 anos
Modalidade: híbrida, sala invertida, 90 min
Contexto: 2 estudos de caso de sustentabilidade + atividade de tomada de decisão em grupo
Desafio comportamental: não sei dizer — me ajude a identificar
```

O Orys retorna o plano completo com diagnóstico do padrão, intervenção, rubrica e indicadores de Learning Analytics.

### Licença

Licença MIT — veja [LICENSE](./LICENSE).

A **metodologia** (Orys Learning Architecture™), **os 10 Padrões Orys™**, e o **conteúdo do livro** (*Orys Learning Architecture™ Vol. 1*, de Souza, 2025) permanecem propriedade intelectual da **Dra. de Souza** e são referenciados sob uso acadêmico justo. Reprodução comercial da metodologia além do uso via plugin requer autorização por escrito.

### Citação acadêmica

> de Souza (2025). *DR. DE.SOUZ.AI Orys™ — Metodologia Orys Learning Architecture™ Vol. 1.* https://drdesouza.ai

---

## 🌅 About Dr. de Souza

DR. DE.SOUZ.AI is the personal brand of Dr. de Souza, PhD — researcher and practitioner in adult learning, higher-education pedagogy, and AI-mediated instruction. Her work integrates Bloom's Taxonomy, Big Five soft skills, neurodidactics, and the original Orys Learning Architecture™ methodology developed for the Gen Z + AI era.

📚 Book: *Orys Learning Architecture™ Vol. 1* (2025)
🌐 Web: https://drdesouza.ai
✉️ Contact: mrdesouzaphd@gmail.com

---

*Orys™, Orys Learning Architecture™, and the 10 Orys Patterns™ are trademarks of Dr. de Souza.*
