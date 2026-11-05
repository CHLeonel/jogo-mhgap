# Resumo: lições e Biblioteca do jogo MI-mhGAP

Este documento descreve os dois recursos de revisão rápida do jogo (`index.html`):
as **lições** de cada pergunta e as **fichas-resumo** da Biblioteca.

## 1. Lições: as "pílulas" de cada pergunta

Cada pergunta do banco tem um campo `licao`: uma frase curta com o ponto-chave do
MI-mhGAP. Quando o jogador erra, a lição é registrada junto com o erro
(função `logErr`) para revisão posterior. O banco tem atualmente 120 lições.

O formato é sempre o mesmo: uma linha, com a sigla do módulo na frente e foco na conduta.

Exemplos:

- **PCE:** "Local reservado, sigilo, escuta ativa e consentimento para envolver cuidadores."
- **DEP:** "1 sintoma básico ≥ 2 semanas + vários outros sintomas + prejuízo funcional."
- **DEP:** "Idosos: ISRS em dose baixa; amitriptilina contraindicada em cardiopatas; nunca combinar antidepressivos."
- **PSI:** "Rigidez + febre alta + PA elevada em uso de antipsicótico = SNM: suspender e hospital."

## 2. Biblioteca: fichas-resumo por módulo

A Biblioteca abre pelo botão "📖 Biblioteca" no mapa. Ela traz uma ficha por módulo,
cada uma num bloco que abre e fecha, organizada por tópicos em negrito
(**Critérios**, **Descartar**, **Manejo**, **Emergência**, **Vetos** etc.).

| Módulo | Nome | Destaques da ficha |
|---|---|---|
| 🤝 PCE | Práticas e cuidados essenciais | 6 dicas de comunicação; dignidade (o que fazer e o que não fazer); fluxo de avaliação |
| 🌧️ DEP | Depressão | Critérios; descartes obrigatórios (causa física, mania, luto); manejo; quando chamar o especialista |
| 🌀 PSI | Psicoses | Ordem da avaliação (delirium → mania → psicose); agitação aguda; manejo da mania |
| ⚡ EPI | Epilepsia | Passo a passo da crise, doses de diazepam/midazolam, máximo de 2 doses; eclâmpsia |
| 🧒 MCO | Crianças e adolescentes | Avaliação em casa e na escola; atraso do desenvolvimento; orientações aos pais |
| 🧓 DEM | Demência | Critérios de suspeita; descartar delirium e pseudodemência; sinais que pedem especialista |
| 🍷 SUB | Uso de substâncias | Rastreamento universal; emergências (overdose, abstinência, intoxicação) |
| 🕊️ SUI | Autoagressão / suicídio | Quando avaliar o risco; perguntar não induz; protocolos de ato grave e risco iminente |
| 🌤️ OUT | Outras queixas de saúde mental | Fluxo de descarte; vetos (ansiolíticos, antidepressivos, injeções de vitamina); sintomas sem explicação física |

O texto da tela apresenta as fichas como "consulta rápida para revisar antes de rejogar"
e lembra que a fonte completa e definitiva é sempre o manual.
