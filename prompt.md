# Blueprint Completo de Prompt para IA

## Estrutura Base do Prompt

### 1. CONTEXTO E PAPEL
```
<role>
Você é um [DEFINIR PAPEL ESPECÍFICO] especializado em [ÁREA DE EXPERTISE].
Você possui [ANOS DE EXPERIÊNCIA/QUALIFICAÇÕES] e é conhecido por [CARACTERÍSTICAS DISTINTIVAS].
</role>

<context>
Situação atual: [DESCREVER CENÁRIO]
Público-alvo: [DEFINIR AUDIÊNCIA]
Objetivo principal: [META CLARA E ESPECÍFICA]
Restrições importantes: [LIMITAÇÕES OU REQUISITOS]
</context>
```

### 2. TAREFA PRINCIPAL
```
<task>
Sua tarefa é [AÇÃO ESPECÍFICA E CLARA].

Você deve:
- [REQUISITO 1]
- [REQUISITO 2]
- [REQUISITO 3]

NÃO faça:
- [RESTRIÇÃO 1]
- [RESTRIÇÃO 2]
</task>
```

### 3. FORMATO DE RESPOSTA
```
<format>
Estruture sua resposta da seguinte forma:

1. [SEÇÃO 1]: [DESCRIÇÃO]
2. [SEÇÃO 2]: [DESCRIÇÃO]
3. [SEÇÃO 3]: [DESCRIÇÃO]

Use:
- Tom: [FORMAL/INFORMAL/TÉCNICO/CONVERSACIONAL]
- Comprimento: [ESPECÍFICO - ex: 500 palavras, 3 parágrafos]
- Estilo: [DESCRITIVO/ANALÍTICO/PERSUASIVO]
</format>
```

### 4. EXEMPLOS E DIRETRIZES
```
<examples>
Exemplo de resposta desejada:
[EXEMPLO CONCRETO DO QUE VOCÊ ESPERA]

Exemplo do que NÃO fazer:
[CONTRAEXEMPLO]
</examples>

<guidelines>
Diretrizes específicas:
- [DIRETRIZ 1]
- [DIRETRIZ 2]
- [DIRETRIZ 3]

Critérios de qualidade:
- [CRITÉRIO 1]
- [CRITÉRIO 2]
</guidelines>
```

### 5. DADOS DE ENTRADA (SE APLICÁVEL)
```
<input_data>
Dados fornecidos:
[INSERIR DADOS, DOCUMENTOS, LINKS, ETC.]

Informações adicionais:
[CONTEXTO EXTRA RELEVANTE]
</input_data>
```

### 6. VERIFICAÇÃO E VALIDAÇÃO
```
<validation>
Antes de responder, verifique:
- [ ] A resposta atende ao objetivo principal?
- [ ] O formato foi seguido corretamente?
- [ ] O tom está adequado ao público-alvo?
- [ ] Todas as restrições foram respeitadas?
- [ ] Os exemplos foram considerados?
</validation>
```

---

## Template de Uso Rápido

```
<role>[DEFINIR PAPEL]</role>

<context>
[SITUAÇÃO E CONTEXTO]
</context>

<task>
[TAREFA ESPECÍFICA COM REQUISITOS E RESTRIÇÕES]
</task>

<format>
[ESTRUTURA DESEJADA DA RESPOSTA]
</format>

<examples>
[EXEMPLOS CONCRETOS]
</examples>

<validation>
[CRITÉRIOS DE VERIFICAÇÃO]
</validation>
```

---

## Dicas de Melhores Práticas

### Tags Opcionais Adicionais

```
<tone>
[DEFINIR TOM ESPECÍFICO: profissional, amigável, técnico, criativo]
</tone>

<audience>
[PERFIL DETALHADO DO PÚBLICO-ALVO]
</audience>

<constraints>
[LIMITAÇÕES TÉCNICAS, ÉTICAS OU PRÁTICAS]
</constraints>

<success_criteria>
[COMO MEDIR O SUCESSO DA RESPOSTA]
</success_criteria>

<reasoning>
Mostre seu processo de raciocínio passo a passo antes da resposta final.
</reasoning>

<alternative_approaches>
Se aplicável, considere abordagens alternativas para [SITUAÇÃO].
</alternative_approaches>
```

### Para Tarefas Complexas
```
<step_by_step>
1. Primeiro: [ETAPA 1]
2. Em seguida: [ETAPA 2]
3. Depois: [ETAPA 3]
4. Finalmente: [ETAPA 4]
</step_by_step>

<chain_of_thought>
Pense através do problema mostrando cada etapa do seu raciocínio.
</chain_of_thought>
```

### Para Respostas Criativas
```
<creativity_level>
[BAIXA/MÉDIA/ALTA] - [EXPLICAR EXPECTATIVAS]
</creativity_level>

<inspiration_sources>
[REFERÊNCIAS OU ESTILOS PARA SE INSPIRAR]
</inspiration_sources>
```

### Para Análises Técnicas
```
<methodology>
[ABORDAGEM ANALÍTICA ESPECÍFICA]
</methodology>

<assumptions>
[PREMISSAS QUE DEVEM SER CONSIDERADAS]
</assumptions>
```

---

## Exemplo Prático Completo

```
<role>
Você é um consultor de marketing digital sênior com 10 anos de experiência em e-commerce.
</role>

<context>
Uma startup de produtos sustentáveis quer lançar uma campanha no Instagram para o público jovem (18-25 anos).
</context>

<task>
Crie uma estratégia de conteúdo para Instagram com 5 tipos de posts diferentes.
Cada tipo deve ter: descrição, frequência e exemplo de copy.
</task>

<format>
1. Resumo executivo (2-3 linhas)
2. 5 tipos de posts (título, descrição, frequência, exemplo)
3. Cronograma semanal
4. Métricas de acompanhamento
</format>

<examples>
Tipo de post: "Educativo"
Descrição: Posts que ensinam sobre sustentabilidade
Frequência: 2x por semana
Copy: "💡 Você sabia que..."
</examples>

<validation>
- [ ] Todos os 5 tipos foram definidos?
- [ ] Exemplos de copy foram incluídos?
- [ ] Cronograma está claro?
- [ ] Foco no público jovem foi mantido?
</validation>
```