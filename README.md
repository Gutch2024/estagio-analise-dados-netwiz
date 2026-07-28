# Portefólio de Estágio — Análise, Normalização e Visualização de Dados

**Estágio curricular na NetWiz Systems** · CTeSP em Análise de Dados em Gestão de Informação · Escola Superior de Tecnologia e Gestão Jean Piaget (ESTGJP)

Este repositório reúne, de forma organizada e rastreável, os **entregáveis produzidos durante o estágio curricular** realizado na NetWiz Systems (22 de abril a 5 de agosto de 2026). Serve de **Anexo C** ao relatório de estágio: cada pasta corresponde a uma tarefa e é identificada pelo mesmo código (`C.1` a `C.21`) e secção usados no relatório, para que qualquer evidência possa ser localizada a partir do texto.

- **Autor:** Pedro Ferreira (n.º 2024118215)
- **Entidade de acolhimento:** NetWiz Systems, Sociedade Unipessoal, Lda. — soluções digitais integradas
- **Cliente institucional:** Instituto Piaget (Gabinete de Comunicação e Imagem)
- **Período:** 22/04/2026 – 05/08/2026

---

## 🖱️ Como ver as evidências (mesmo sem conhecer o GitHub)

1. Na tabela abaixo, **clica no nome de uma tarefa** (ou numa pasta `C0x_...`).
2. Abre uma **explicação** da tarefa (objetivo, contexto, resultado).
3. Para abrir um ficheiro, clica no botão **«📄 Abrir / 📊 Descarregar»** que está nessa explicação, na secção **«Evidências»** — o Excel/PowerPoint descarrega e o PDF abre no navegador.

> Os ficheiros Excel, PowerPoint e Power BI **não se pré-visualizam** no GitHub (aparece «View raw»); por isso cada tarefa tem **botões diretos** que abrem ou descarregam o ficheiro sem teres de adivinhar.

---

## Índice de tarefas

| Anexo | Pasta | Tarefa | Secção |
|---|---|---|---|
| C.1 | [`01_.../C01`](01_dados-institucionais-e-dashboards/C01_candidaturas-pos-graduacoes/) | Organização de 719 candidaturas e dashboard por campus | 4.1.1 |
| C.2 | [`01_.../C02`](01_dados-institucionais-e-dashboards/C02_contactos-e-dashboards/) | Normalização de 11 755 contactos e dois dashboards anuais | 4.1.2 |
| C.3 | [`02_.../C03`](02_inteligencia-de-mercado/C03_qualificacao-50-clientes/) | Qualificação de 50 potenciais clientes | 4.2.1 |
| C.4 | [`02_.../C04`](02_inteligencia-de-mercado/C04_mapeamento-setores/) | Classificação de oito setores por potencial comercial | 4.2.2 |
| C.5 | [`02_.../C05`](02_inteligencia-de-mercado/C05_analise-concorrencia/) | Análise de 24 concorrentes | 4.2.3 |
| C.6 | [`03_.../C06`](03_oferta-formativa-pt-es/C06_oferta-formativa-portugal/) | Normalização de 5 804 cursos de Portugal | 4.3.1 |
| C.7 | [`03_.../C07`](03_oferta-formativa-pt-es/C07_oferta-formativa-espanha/) | Normalização de 10 336 cursos de Espanha | 4.3.2 |
| C.8 | [`03_.../C08`](03_oferta-formativa-pt-es/C08_apresentacao-sintese-comparativa/) | Apresentação de síntese comparativa PT–ES | 4.3.3 |
| C.9 | [`04_.../C09`](04_cursocerto-validacao-e-povoamento/C09_teste-erros-e-melhorias/) | Teste do cursocerto.pt e sete propostas de correção | 4.4.1 |
| C.10 | [`04_.../C10`](04_cursocerto-validacao-e-povoamento/C10_campos-base-de-dados/) | Revisão dos campos da base de dados | 4.4.2 |
| C.11 | [`04_.../C11`](04_cursocerto-validacao-e-povoamento/C11_validacao-53-colunas/) | Validação das 53 colunas do modelo de importação | 4.4.3 |
| C.12 | [`04_.../C12`](04_cursocerto-validacao-e-povoamento/C12_276-cursos-por-instituicao/) | Carregamento de 276 cursos (3 por instituição) | 4.4.4 |
| C.13 | [`04_.../C13`](04_cursocerto-validacao-e-povoamento/C13_809-entidades-formacao-nao-superior/) | Avaliação de 809 entidades por matriz de sete critérios | 4.4.5 |
| C.14 | [`05_.../C14`](05_campanha-de-divulgacao/C14_contactos-institucionais-pt-es/) | Contactos de 92 instituições PT e 94 ES | 4.5.1 |
| C.15 | [`05_.../C15`](05_campanha-de-divulgacao/C15_matriz-de-gatilhos/) | Matriz de gatilhos para 90 instituições | 4.5.2 |
| C.16 | [`05_.../C16`](05_campanha-de-divulgacao/C16_sequencia-de-emails/) | Sequência de e-mails de divulgação _(material comercial — ver nota)_ | 4.5.3 |
| C.17 | [`06_.../C17`](06_carteira-de-prospecao-comercial/C17_base-leads-b2b-p1/) | Base de 166 leads B2B (P1) | 4.6.1 |
| C.18 | [`06_.../C18`](06_carteira-de-prospecao-comercial/C18_scorecard-maturidade-digital-p2/) | Scorecard de maturidade digital (P2) | 4.6.2 |
| C.19 | [`06_.../C19`](06_carteira-de-prospecao-comercial/C19_mercado-produtos-proprios-p3/) | Mercado dos produtos próprios (P3) | 4.6.3 |
| C.20 | [`06_.../C20`](06_carteira-de-prospecao-comercial/C20_extensao-setor-imobiliario/) | Extensão ao setor imobiliário | 4.6.4 |
| C.21 | [`06_.../C21`](06_carteira-de-prospecao-comercial/C21_dashboard-comercial/) | Dashboard comercial da carteira de leads | 4.6.5 |

> **Números globais do estágio:** 719 candidaturas e 11 755 contactos normalizados · 16 140 cursos de 182 instituições (PT+ES) · 809 entidades de formação avaliadas · 166 leads B2B pontuados por maturidade digital · 24 concorrentes analisados.

---

## Tecnologias e ferramentas

**Análise e visualização de dados**
- Microsoft Excel (limpeza, normalização, tabelas dinâmicas, `COUNTIFS`/`AVERAGEIFS`, scorecards parametrizados)
- Microsoft Power BI (dashboards e KPIs; ficheiros `.pbix`)
- Microsoft PowerPoint (síntese comparativa)
- Importação de dados por ficheiro CSV (modelo do cursocerto.pt)

**Pesquisa assistida por IA (uso supervisionado, com validação manual em fontes oficiais)**
- Claude Pro (Anthropic) com conectores de recolha web: **Tavily**, **Exa** e **Claude in Chrome**
- Perplexity e Gemini (pesquisa aprofundada / *deep search* e metodologias)
- Zapier + Google Drive (integração e versão única dos ficheiros de trabalho)

**Fontes oficiais** — DGES, A3ES, RUCT, DGERT, ANQEP, INE, DGEEC, IMPIC.

---

## Estrutura do repositório

```
.
├── 01_dados-institucionais-e-dashboards/
│   ├── C01_candidaturas-pos-graduacoes/
│   │   ├── README.md
│   │   └── Relatorio_candidaturas-pos-graduacoes_2025-2026.pdf
│   └── C02_contactos-e-dashboards/
│       ├── README.md
│       └── Relatorio_contactos-potenciais-alunos_dashboards_RGPD-redigido.pdf
├── 02_inteligencia-de-mercado/
│   ├── C03_qualificacao-50-clientes/
│   │   ├── Base_50-clientes-qualificados_PT-ES.xlsx
│   │   ├── README.md
│   │   └── Tarefa3_Pesquisa-qualificacao-clientes_PT-ES.pdf
│   ├── C04_mapeamento-setores/
│   │   ├── Matriz_oportunidades-comerciais-por-setor.xlsx
│   │   ├── README.md
│   │   └── Tarefa4_Mapeamento-oportunidades-por-setor.pdf
│   └── C05_analise-concorrencia/
│       ├── Analise_Concorrencia_NetWiz_PT-ES.xlsx
│       ├── Dashboard_Concorrencia_NetWiz.pbix
│       ├── README.md
│       └── Relatorio_Analise-Concorrencia_NetWiz.pdf
├── 03_oferta-formativa-pt-es/
│   ├── C06_oferta-formativa-portugal/
│   │   └── README.md
│   ├── C07_oferta-formativa-espanha/
│   │   └── README.md
│   └── C08_apresentacao-sintese-comparativa/
│       ├── Apresentacao_Sintese-comparativa_PT-ES.pptx
│       └── README.md
├── 04_cursocerto-validacao-e-povoamento/
│   ├── C09_teste-erros-e-melhorias/
│   │   ├── README.md
│   │   ├── Relatorio-1_erros-e-melhorias_cursocerto.pdf
│   │   └── Relatorio-2_erros-e-melhorias_cursocerto.pdf
│   ├── C10_campos-base-de-dados/
│   │   ├── Campos_base-dados_cursocerto_com-acrescentos.xlsx
│   │   └── README.md
│   ├── C11_validacao-53-colunas/
│   │   ├── 3-cursos_mesma-universidade_amostra.csv
│   │   ├── README.md
│   │   └── Verificacao_53colunas_16cursos_Piaget-Catolica.xlsx
│   ├── C12_276-cursos-por-instituicao/
│   │   └── README.md
│   └── C13_809-entidades-formacao-nao-superior/
│       ├── Base_809-entidades_formacao-nao-superior.xlsx
│       └── README.md
├── 05_campanha-de-divulgacao/
│   ├── C14_contactos-institucionais-pt-es/
│   │   ├── Contactos_instituicoes-ensino-superior_Portugal.xlsx
│   │   ├── Contactos_universidades_Espanha.xlsx
│   │   └── README.md
│   ├── C15_matriz-de-gatilhos/
│   │   ├── Matriz_gatilhos_divulgacao_cursocerto.xlsx
│   │   └── README.md
│   └── C16_sequencia-de-emails/
│       └── README.md
└── 06_carteira-de-prospecao-comercial/
    ├── C17_base-leads-b2b-p1/
    │   ├── NetWiz_P1_Base-Leads-B2B_RGPD-redigido.xlsx
    │   └── README.md
    ├── C18_scorecard-maturidade-digital-p2/
    │   ├── NetWiz_P2_Scorecard-Maturidade-Digital.xlsx
    │   └── README.md
    ├── C19_mercado-produtos-proprios-p3/
    │   ├── NetWiz_P3_Analise-Mercado-Produtos.xlsx
    │   └── README.md
    ├── C20_extensao-setor-imobiliario/
    │   ├── NetWiz_Imobiliario_P1_Independentes.xlsx
    │   ├── NetWiz_Imobiliario_P2_Scorecard.xlsx
    │   ├── NetWiz_Imobiliario_P3_Produtos.xlsx
    │   └── README.md
    └── C21_dashboard-comercial/
        ├── NetWiz_Dashboard-Comercial.xlsx
        ├── README.md
        └── Relatorio_Dashboard-Comercial_graficos.pdf
```

Cada pasta de bloco (`01_…` a `06_…`) tem um `README.md` com o resumo do bloco; cada pasta de tarefa (`C01`…`C21`) tem um `README.md` com **objetivo, contexto, ficheiros, ferramentas, competências e resultado**.

---

## Resumo dos blocos

1. **Dados institucionais e dashboards** — normalização de candidaturas e contactos do Instituto Piaget e dashboards em Power BI, no respeito pelo RGPD.
2. **Inteligência de mercado** — qualificação de potenciais clientes, mapeamento de setores e análise de concorrência em PT e ES.
3. **Oferta formativa PT–ES** — levantamento e normalização de 16 140 cursos de 182 instituições a partir de fontes oficiais, com equivalências entre sistemas de ensino, e síntese comparativa.
4. **Validação e povoamento do cursocerto.pt** — teste do site, revisão do modelo de dados, validação incremental do modelo de importação (3 → 16 cursos), povoamento e avaliação de expansão a formação não superior.
5. **Campanha de divulgação** — contactos institucionais validados, matriz de gatilhos e sequência de contactos conforme ao RGPD.
6. **Carteira de prospeção comercial** — base de leads B2B (P1), scorecard de maturidade digital (P2), mercado dos produtos próprios (P3), extensão ao setor imobiliário e dashboard comercial.

---

## Proteção de dados e confidencialidade

Este repositório segue o mesmo critério do relatório de estágio:

- **Ficheiros com dados pessoais não são publicados** (candidaturas, contactos de potenciais estudantes, respostas de formulários e a extração de 79 contactos). Essas tarefas são demonstradas no relatório por figuras e por uma tabela com um registo anonimizado.
- **Redações aplicadas** nesta versão pública:
  - `C.2` — removidas as páginas 7, 8 e 10 do relatório dos contactos (nomes de colaboradoras).
  - `C.17` — anonimizados os nomes de dois colaboradores na folha de metodologia.
- **`C.16` (sequência de e-mails)** não é incluído por se tratar de **material comercial da NetWiz**; o relatório condiciona a sua anexação ao acordo do orientador.
- As bases de contactos institucionais e de leads B2B usam **endereços gerais/institucionais e dados de empresas**, recolhidos de fontes públicas, com base legal de interesse legítimo para prospeção B2B.

---

## Ficheiros pendentes / a confirmar

- `C.12` — base de **276 cursos** no formato de importação (secção 4.4.4). Existe um ficheiro candidato (`3_cursos_instituicoes_final_producao.csv`, com 276 cursos) que corresponde à descrição, mas aguarda **confirmação do autor** antes de ser incluído.

---

## Ligação ao relatório de estágio

O relatório de estágio (documento Word) refere este repositório no **Anexo C** e cada rubrica «Evidências» remete para a pasta correspondente. Repositório: https://github.com/Gutch2024/estagio-analise-dados-netwiz
