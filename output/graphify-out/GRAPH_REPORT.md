# Graph Report - RecycleRush  (2026-09-11)

## Corpus Check
- Corpus is ~0 words - fits in a single context window. You may not need a graph.

## Summary
- 19 nodes · 16 edges · 4 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Validação e Resultados
- Gameplay e Tecnologia
- Melhorias de UX
- Problema Ambiental

## God Nodes (most connected - your core abstractions)
1. `Gameplay interativo` - 3 edges
2. `Aplicação real com crianças` - 3 edges
3. `Educação ambiental infantil` - 2 edges
4. `Recycle Rush` - 2 edges
5. `Metodologia de implementação` - 2 edges
6. `Questionário pré e pós-jogo` - 2 edges
7. `Sessão mediada de dez minutos` - 2 edges
8. `Dificuldade com mecânica e inimigos` - 2 edges
9. `Tutorial inicial` - 2 edges
10. `Ajuste de dificuldade` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Gameplay interativo` --conceptually_related_to--> `Recycle Rush`  [EXTRACTED]
  docs/Seminário 2 - RecycleRush.pdf → docs/Seminário 1 - RecycleRush.pdf
- `Aplicação real com crianças` --implements--> `Questionário pré e pós-jogo`  [EXTRACTED]
  docs/Seminário 3 - RecycleRush.pdf → docs/Seminário 2 - RecycleRush.pdf

## Hyperedges (group relationships)
- **Intervenção pedagógica Recycle Rush** — docs_semin_rio_1_recyclerush_recycle_rush, docs_semin_rio_2_recyclerush_gameplay_interativo, docs_semin_rio_2_recyclerush_feedback_imediato, docs_semin_rio_2_recyclerush_metodologia_de_implementacao [EXTRACTED 1.00]
- **Ciclo de validação pré e pós-jogo** — docs_semin_rio_2_recyclerush_questionario_pre_pos, docs_semin_rio_3_recyclerush_aplicacao_real, docs_semin_rio_3_recyclerush_sessao_dez_minutos, docs_semin_rio_3_recyclerush_resultado_25_90 [EXTRACTED 1.00]

## Communities (4 total, 0 thin omitted)

### Community 0 - "Validação e Resultados"
Cohesion: 0.29
Nodes (7): Debate pós-jogo, Metodologia de implementação, Questionário pré e pós-jogo, Amostra de quatro crianças, Aplicação real com crianças, Taxa de acertos de 25% para 90%, Sessão mediada de dez minutos

### Community 1 - "Gameplay e Tecnologia"
Cohesion: 0.40
Nodes (5): Aprendizado lúdico, Recycle Rush, Feedback imediato, Gameplay interativo, Godot Engine

### Community 2 - "Melhorias de UX"
Cohesion: 0.67
Nodes (4): Ajuste de dificuldade, Dificuldade com mecânica e inimigos, Potencial de expansão, Tutorial inicial

### Community 3 - "Problema Ambiental"
Cohesion: 0.67
Nodes (3): Crianças como agentes de mudança, Descarte incorreto de resíduos, Educação ambiental infantil

## Knowledge Gaps
- **4 isolated node(s):** `Descarte incorreto de resíduos`, `Godot Engine`, `Amostra de quatro crianças`, `Taxa de acertos de 25% para 90%`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `Descarte incorreto de resíduos`, `Godot Engine`, `Amostra de quatro crianças` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._