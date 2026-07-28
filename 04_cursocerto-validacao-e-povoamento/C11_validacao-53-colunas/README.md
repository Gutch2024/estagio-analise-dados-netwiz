# C.11 — Validação das 53 colunas do modelo de importação

> **Anexo do relatório:** C.11 · **Secção:** 4.4.3 · **Entidade:** NetWiz Systems / Instituto Piaget

## Objetivo
Validar o modelo de importação de cursos do cursocerto.pt de forma incremental (3 cursos → 16 cursos) e produzir uma matriz que explique as 53 colunas do modelo.

## Contexto
O sistema rejeita o ficheiro inteiro quando um campo não corresponde às instruções ou há duplicados, quase sempre sem indicar qual. Adotou-se uma abordagem incremental e uma decomposição do problema (quatro hipóteses testadas uma a uma).

## 📎 Evidências — clica para abrir ou descarregar

- **[📊 Descarregar o CSV → «3-cursos_mesma-universidade_amostra.csv»](https://github.com/Gutch2024/estagio-analise-dados-netwiz/raw/main/04_cursocerto-validacao-e-povoamento/C11_validacao-53-colunas/3-cursos_mesma-universidade_amostra.csv)**  
  Amostra de 3 cursos (dados de exemplo) usada na primeira etapa de validação do modelo, até o ficheiro ser aceite sem erros.
- **[📊 Descarregar o Excel → «Verificacao_53colunas_16cursos_Piaget-Catolica.xlsx»](https://github.com/Gutch2024/estagio-analise-dados-netwiz/raw/main/04_cursocerto-validacao-e-povoamento/C11_validacao-53-colunas/Verificacao_53colunas_16cursos_Piaget-Catolica.xlsx)**  
  Matriz de verificação das 53 colunas para 16 cursos do Instituto Piaget e da Universidade Católica, com os campos assinalados e a explicação de cada coluna.

> _Nota: os ficheiros Excel/PowerPoint/Power BI **não** pré-visualizam no GitHub — clica no botão acima e o ficheiro abre ou descarrega diretamente. Os PDF abrem no navegador._

## Ferramentas utilizadas
Microsoft Excel; sistema de importação do próprio site; Gemini e Perplexity (formatação); Claude (estruturação da matriz de verificação).

## Competências demonstradas
Teste incremental de modelos de dados; decomposição de problema (causa, hipóteses, solução); documentação de decisões.

**Unidades curriculares relacionadas:** Interfaces Web para a Gestão de Dados; Análise Exploratória de Dados.

## Resultado
Modelo validado; matriz que documenta a correspondência das 53 colunas para 16 cursos, com os campos mais importantes assinalados e uma explicação por coluna.

## Notas
- **Ordem correta das tarefas de verificação do site:** esta é a etapa que começa em **3 cursos** e depois **16 cursos (Piaget/Católica)**. O povoamento «3 cursos por instituição» (276 cursos) é a etapa **seguinte** — ver C.12 (secção 4.4.4).

---
[← Voltar ao índice do repositório](../../README.md)
