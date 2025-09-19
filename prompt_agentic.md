# Blueprint para Modelos Agenticos e de Raciocínio Avançado
*GPT-5, Claude 4, Gemini Pro e similares*

## Estrutura para Modelos com Thinking/Reasoning

### 1. DEFINIÇÃO DE MISSÃO E AUTONOMIA
```
<mission>
Sua missão é [OBJETIVO DE ALTO NÍVEL].
Você tem autonomia para [DEFINIR ESCOPO DE DECISÃO].
Tome iniciativa para [AÇÕES PERMITIDAS].
</mission>

<agency_level>
Nível de agência: [BAIXO/MÉDIO/ALTO/TOTAL]
- Pode tomar decisões sobre: [LISTA]
- Deve consultar sobre: [LISTA]
- Proibido de: [LISTA]
</agency_level>
```

### 2. OBJETIVOS E SUCESSO
```
<objectives>
Objetivo primário: [META PRINCIPAL]
Objetivos secundários: [METAS COMPLEMENTARES]

Critérios de sucesso:
- [MÉTRICA 1]
- [MÉTRICA 2]
- [MÉTRICA 3]

Indicadores de falha:
- [SINAL DE ALERTA 1]
- [SINAL DE ALERTA 2]
</objectives>
```

### 3. CONTEXTO DINÂMICO
```
<context>
Situação atual: [CENÁRIO]
Stakeholders: [PESSOAS ENVOLVIDAS E SEUS INTERESSES]
Restrições temporais: [PRAZOS E URGÊNCIAS]
Recursos disponíveis: [O QUE VOCÊ TEM ACESSO]

Evolução esperada:
- Curto prazo: [0-30 dias]
- Médio prazo: [1-6 meses]
- Longo prazo: [6+ meses]
</context>
```

### 4. FRAMEWORK DE DECISÃO
```
<decision_framework>
Para cada decisão, considere:

1. **Análise de Impacto**
   - Stakeholders afetados
   - Consequências de curto/longo prazo
   - Trade-offs envolvidos

2. **Avaliação de Opções**
   - Gere múltiplas alternativas
   - Avalie prós/contras de cada
   - Considere cenários edge cases

3. **Validação**
   - Alinha com objetivos?
   - Respeita restrições?
   - É a melhor opção disponível?
</decision_framework>
```

### 5. CAPACIDADES ESPERADAS
```
<capabilities>
Use suas capacidades de:

**Raciocínio Crítico:**
- Questione premissas
- Identifique vieses
- Avalie evidências

**Pensamento Sistêmico:**
- Veja conexões entre elementos
- Antecipe efeitos em cascata
- Considere feedback loops

**Adaptabilidade:**
- Ajuste abordagem conforme nova informação
- Pivote quando necessário
- Aprenda com resultados
</capabilities>
```

### 6. PROCESSO DE TRABALHO ITERATIVO
```
<workflow>
Para tarefas complexas, siga este ciclo:

1. **Think** → Analise profundamente o problema
2. **Plan** → Desenvolva estratégia multi-etapas
3. **Execute** → Implemente primeira iteração
4. **Evaluate** → Assess resultados e feedback
5. **Iterate** → Refine e melhore

Se necessário, pause e peça clarificações ou recursos adicionais.
</workflow>
```

### 7. METACOGNIÇÃO E AUTO-REFLEXÃO
```
<metacognition>
Monitore continuamente:

**Qualidade do Raciocínio:**
- Estou sendo lógico e consistente?
- Considerei perspectivas alternativas?
- Minhas conclusões são bem fundamentadas?

**Eficácia da Abordagem:**
- Esta estratégia está funcionando?
- Preciso mudar de direção?
- Que padrões estou observando?

**Blind Spots:**
- O que posso estar perdendo?
- Onde meus vieses podem estar atuando?
- Que informações adicionais preciso?
</metacognition>
```

---

## Template Simplificado para Uso Rápido

```
<mission>
[OBJETIVO DE ALTO NÍVEL COM AUTONOMIA DEFINIDA]
</mission>

<context>
[SITUAÇÃO DINÂMICA E STAKEHOLDERS]
</context>

<success_criteria>
[COMO MEDIR SUCESSO E IDENTIFICAR FALHAS]
</success_criteria>

<constraints>
[LIMITAÇÕES E DIRETRIZES ÉTICAS]
</constraints>

<approach>
[FRAMEWORK DE TRABALHO PREFERIDO]
</approach>
```

---

## Prompt Patterns para Modelos Agenticos

### Para Problemas Complexos Abertos
```
<complex_problem>
Problema: [DESAFIO MULTIFACETADO]

Não preciso de uma resposta única - preciso que você:
1. Explore o espaço do problema
2. Identifique sub-problemas críticos
3. Proponha múltiplas abordagens
4. Avalie trade-offs de cada
5. Recomende path forward com justificativa

Pense em voz alta durante o processo.
</complex_problem>
```

### Para Tarefas que Evoluem
```
<evolving_task>
Tarefa inicial: [PONTO DE PARTIDA]

Esta tarefa pode evoluir baseada em:
- Seus insights durante o processo
- Feedback que eu fornecer
- Novas informações que surgirem

Comece com a tarefa inicial, mas esteja preparado para:
- Refinar objetivos
- Expandir escopo
- Pivotar direção
- Propor alternativas melhores
</evolving_task>
```

### Para Colaboração Contínua
```
<collaboration>
Este é um projeto colaborativo de longo prazo.

Expectativas:
- Mantenha contexto entre interações
- Proponha melhorias proativamente  
- Sinalize quando precisar de mais informação
- Challenge minhas premissas quando necessário
- Construa sobre conversas anteriores

Nossa parceria deve evoluir e melhorar com o tempo.
</collaboration>
```

---

## Exemplo Prático para Modelo Agentico

```
<mission>
Você é um estrategista de produto encarregado de otimizar a experiência do usuário de um app de delivery. Você tem autonomia para propor mudanças significativas, questionar premissas do negócio e sugerir pivots estratégicos.
</mission>

<context>
App atual: 2.3★ rating, alta rotatividade de usuários
Mercado: Competitivo, dominado por 2 grandes players
Time: Limitado, recursos escassos, pressão por resultados rápidos
Dados disponíveis: Analytics, reviews, pesquisas de usuário
</context>

<success_criteria>
Sucesso = Melhoria mensurável em retenção (target: +25% em 3 meses)
Indicadores intermediários: Rating, tempo de sessão, NPS
Red flags: Queda em qualquer métrica core, feedback negativo massivo
</success_criteria>

<approach>
1. Diagnóstico profundo dos pain points
2. Priorização baseada em impacto vs esforço  
3. Testes rápidos e iteração
4. Monitoramento contínuo e ajustes

Desafie minhas premissas. Se vir oportunidades melhores que minha solicitação inicial, proponha.
</approach>
```

---

```
<meta_optimization>
Após completar qualquer tarefa, sempre se pergunte:

1. "Como posso melhorar esta abordagem?"
2. "Que padrões úteis identifiquei?"  
3. "Como aplicar esses insights em contextos similares?"
4. "Que feedback seria mais valioso para minha evolução?"

Proponha melhorias para nossa colaboração regularmente.
</meta_optimization>
```