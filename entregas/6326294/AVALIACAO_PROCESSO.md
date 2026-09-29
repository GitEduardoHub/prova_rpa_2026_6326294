# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/SEU_RA/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** Cenário A

1. **Nome do processo e descrição resumida:**
   Renomeação e Arquivamento de Comprovantes. Consiste em ler arquivos PDF diariamente, renomeá-los extraindo a data e o número do documento do nome original, e movê-los para o repositório correto.

2. **Volume / frequência estimados:**
   Frequência diária com alto volume de arquivos (processamento em lote/batch).

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Sim. Os dados necessários (data e número) já constam no nome do arquivo de forma padronizada e digital, permitindo a extração via manipulação de texto (strings).

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Sim. A lógica de renomeação e o destino do arquivo seguem regras fixas baseadas em padrões exatos. Não há exceções subjetivas que precisem de julgamento humano.

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras claras, dados estruturados e repetibilidade)
   Sim, é altamente elegível. O processo atende aos três pilares fundamentais do RPA: possui **regras de negócio claras e determinísticas**, consome **dados estruturados** e digitais (nome do arquivo) e tem alta **repetibilidade** diária. Um robô pode executar essa tarefa com 100% de previsibilidade.
