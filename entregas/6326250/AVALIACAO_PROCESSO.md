# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/SEU_RA/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** <A ou B>

# Ficha de Avaliação de Processo (PDD) – Questão 5

**Cenário escolhido:** Cenário A

1. **Nome do processo e descrição resumida:**
   Importação e Consolidação de Notas Fiscais Eletrónicas via CSV para cálculo do total faturado.

2. **Volume / frequência estimados:**
   Aproximadamente 500 notas fiscais por dia, com execução diária ao final do expediente.

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Sim. As entradas provêm de ficheiros em formato CSV padronizado, contendo colunas bem definidas (como "valor", "data" e "identificador").

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Sim. O cálculo envolve apenas a verificação de existência do ficheiro, leitura padronizada e a soma matemática dos valores contidos na coluna especificada.

5. **Veredito – o processo é elegível a RPA?** (justifique com base em regras claras, dados estruturados e repetibilidade)
   Sim, o processo é altamente elegível para RPA. Apresenta dados de entrada totalmente estruturados em formato CSV, regras de negócio 100% determinísticas e sem necessidade de julgamento humano, além de ter um volume repetitivo que beneficia da automação para evitar erros manuais.