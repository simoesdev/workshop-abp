# AI Codes para Empreendedores

Cheatsheet de “codes” e exemplos de prompts em português de Portugal para empreendedores, pequenos negócios e equipas comerciais usarem LLMs e ferramentas de automação no dia a dia.

Este material foi pensado para apoiar tarefas práticas como escrita de emails, follow-up comercial, pesquisa de mercado, criação de conteúdos, organização de projetos, geração de imagens e desenho de fluxos no Make.com ou Zapier.

Slides do workshop

`Assistente de AI para o Teu Negócio: Workshop Prático para Empreendedores`

> ⚠️ Aviso importante  
> Estes exemplos servem para apoio à escrita, organização, análise e automação.  
> Não substituem revisão humana, aconselhamento jurídico, financeiro, fiscal ou decisões comerciais críticas.  
> Nunca coloques passwords, API Keys, dados bancários, dados pessoais sensíveis ou informação confidencial nos prompts sem necessidade.  
> Em automações, começa por gerar rascunhos e mantém revisão humana antes de qualquer envio para clientes.

---

## Tabela de “codes” para empreendedores

| LLM / Contexto | Code / Trigger | Explicação prática |
|---|---|---|
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `ELI10` | Pede uma explicação simples de um conceito de negócio, marketing, vendas, automação ou AI. Útil para aprender sem jargão. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/business-blueprint` | Ajuda a desenhar um assistente antes de o criar. Define objetivo, utilizador, entradas, regras, formato de saída e critérios de qualidade. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/prompt-master` | Cria uma instrução base para um GPT personalizado, Projeto ou assistente de negócio. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/follow-up-sales` | Gera emails de follow-up para leads, clientes que pediram orçamento ou contactos comerciais sem resposta. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/lead-qualification` | Cria perguntas de qualificação para perceber necessidade, orçamento, urgência, decisão e próximo passo. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/proposal-draft` | Ajuda a estruturar propostas comerciais com problema, solução, benefícios, próximos passos e condições a validar. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/email-polish` | Melhora emails já escritos. Ajusta tom, clareza, dimensão, profissionalismo e chamada para ação. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/customer-support` | Responde a dúvidas de clientes com tom claro, empático e profissional, sem prometer o que não está confirmado. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/faq-builder` | Cria uma FAQ comercial do negócio a partir de serviços, objeções comuns, condições gerais e dúvidas frequentes. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/social-posts` | Gera publicações para LinkedIn, Instagram, Facebook ou newsletter a partir de um tema, produto ou serviço. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/content-calendar` | Cria um calendário simples de conteúdos com temas, formatos, objetivo e chamada para ação. |
| Genérico, ChatGPT com pesquisa, Perplexity | `/market-research` | Pesquisa tendências, concorrentes, preços, oportunidades e riscos com fontes verificáveis. |
| Genérico, ChatGPT com pesquisa, Perplexity | `/competitor-scan` | Compara concorrentes e identifica posicionamento, pontos fortes, pontos fracos e oportunidades de diferenciação. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/project-setup` | Ajuda a organizar um Projeto no ChatGPT por cliente, área, campanha ou serviço, com instruções e ficheiros úteis. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/task-scheduler` | Cria ideias de tarefas agendadas, como resumos semanais, lembretes de follow-up ou sugestões de posts. |
| Genérico, ChatGPT, DALL·E, ferramentas de imagem | `/image-brief` | Gera prompts para imagens profissionais, banners, posts, mockups, ilustrações e conceitos visuais. |
| Make.com, Zapier, n8n | `/automation-map` | Desenha um fluxo simples com trigger, filtro, AI, rascunho, revisão humana e ação final. |
| Make.com, Zapier, n8n | `/make-scenario` | Ajuda a planear um cenário no Make.com com módulos, variáveis, filtros, erros comuns e testes. |
| Make.com, Zapier, n8n com OpenAI | `/automation-prompt` | Cria o prompt que entra no módulo OpenAI de uma automação, com regras, formato de saída e limites. |
| Genérico, automações com AI | `/human-review` | Cria uma checklist para revisão humana antes de enviar emails, propostas ou mensagens geradas por AI. |
| Genérico, automações com AI | `/risk-check` | Analisa riscos de uma resposta ou automação. Verifica promessas, dados sensíveis, tom, destinatário e permissões. |
| Genérico, ChatGPT, Claude, Perplexity, Copilot | `/seven-day-plan` | Cria um plano de 7 dias para passar de uso manual de AI para um pequeno fluxo automatizado e seguro. |

---

## Estrutura rápida para bons prompts

Um bom prompt costuma ter cinco partes:

1. **Papel:** quem deve ser o assistente.
2. **Objetivo:** que tarefa deve resolver.
3. **Contexto:** negócio, cliente, situação e dados disponíveis.
4. **Regras:** o que pode e não pode fazer.
5. **Formato:** como deve entregar a resposta.

Exemplo curto:

```text
Actua como assistente de vendas de uma pequena empresa em Portugal.
Escreve um email de follow-up para um potencial cliente que pediu orçamento há 3 dias e ainda não respondeu.
Tom profissional, simples e simpático.
Máximo 100 palavras.
Não inventes preços, prazos, descontos ou disponibilidade.
Inclui uma chamada para ação clara.
```

---

## Exemplos de prompts completos, PT-PT

Os exemplos abaixo podem ser usados tal como estão em ChatGPT, Claude, Perplexity, Copilot, Make.com, Zapier ou n8n, adaptando apenas os campos entre parênteses retos.

### 1. Explicar um conceito sem jargão, `ELI10`

**Code:** `ELI10`

```text
ELI10
Explica-me, em português de Portugal, o que é automação de processos com AI para um pequeno negócio.

Quero uma explicação simples, com exemplos práticos:
- Follow-up automático de clientes
- Resumo de emails
- Criação de rascunhos comerciais
- Organização de leads

Evita jargão técnico.
No final, dá-me 3 ideias simples que eu possa testar esta semana.
```

---

### 2. Desenhar um assistente antes de o criar, `/business-blueprint`

**Code:** `/business-blueprint`

```text
/business-blueprint
Quero criar um assistente de AI para o meu negócio.
Ajuda-me a desenhá-lo antes de o configurar.

Negócio: [descrever o negócio]
Público-alvo: [descrever clientes]
Tarefa principal: [ex: criar rascunhos de follow-up para leads]

Organiza a resposta em:
1. Objetivo do assistente
2. Quem vai usar
3. Que dados deve receber
4. Regras do que pode e não pode fazer
5. Formato de saída ideal
6. Critérios para saber se a resposta está boa

Sê prático e escreve em português de Portugal.
```

---

### 3. Criar um Prompt Mestre para um GPT ou Projeto, `/prompt-master`

**Code:** `/prompt-master`

```text
/prompt-master
Cria um Prompt Mestre para colocar nas instruções de um GPT personalizado ou Projeto do ChatGPT.

Contexto:
- Negócio: [nome e descrição do negócio]
- Serviço principal: [serviço]
- Público-alvo: [tipo de clientes]
- Tom da marca: profissional, simples, próximo e sem pressão comercial
- Tarefa do assistente: criar rascunhos de emails de follow-up

Regras obrigatórias:
- Não inventar preços, prazos, descontos, garantias ou disponibilidade
- Perguntar quando faltar informação essencial
- Não enviar emails diretamente
- Escrever sempre em português europeu
- Manter respostas curtas, claras e fáceis de rever

Formato de saída obrigatório:
Assunto | Email | Próxima ação | Informação em falta | Risco ou observação

Antes de terminar, inclui uma pequena checklist de validação do próprio assistente.
```

---

### 4. Email de follow-up comercial, `/follow-up-sales`

**Code:** `/follow-up-sales`

```text
/follow-up-sales
Actua como assistente de vendas.
Escreve um email de follow-up em português de Portugal para [Nome do Cliente].

Contexto:
- O cliente pediu um orçamento há 3 dias
- Serviço de interesse: [serviço]
- Ainda não respondeu
- Quero manter um tom profissional, simpático e sem pressão

Regras:
- Máximo 100 palavras
- Não inventar preços, prazos ou condições
- Incluir uma chamada para ação clara
- Sugerir uma reunião curta ou resposta direta ao email

Entrega apenas:
1. Assunto
2. Corpo do email
3. Próxima ação sugerida
```

---

### 5. Qualificar uma lead, `/lead-qualification`

**Code:** `/lead-qualification`

```text
/lead-qualification
Actua como assistente comercial.
Recebi esta mensagem de uma potencial lead:

[colar mensagem da lead]

Quero que cries uma resposta curta, profissional e simpática, com perguntas de qualificação.

As perguntas devem ajudar a perceber:
- Necessidade principal
- Urgência
- Orçamento aproximado, se fizer sentido
- Quem decide
- Melhor horário para uma reunião

Não faças pressão comercial.
Não inventes disponibilidade.
No final, sugere a próxima ação.
```

---

### 6. Melhorar um email já escrito, `/email-polish`

**Code:** `/email-polish`

```text
/email-polish
Melhora o email abaixo mantendo a minha intenção original.

Objetivo do email: [ex: responder a pedido de orçamento]
Destinatário: [cliente, parceiro, fornecedor]
Tom pretendido: profissional, claro e cordial
Limite: máximo 150 palavras

Email original:
[colar email]

Quero que faças:
- Corrigir português
- Tornar a mensagem mais clara
- Remover frases demasiado longas
- Melhorar a chamada para ação
- Manter português de Portugal

Entrega a versão final pronta a copiar.
```

---

### 7. Criar uma FAQ comercial, `/faq-builder`

**Code:** `/faq-builder`

```text
/faq-builder
Ajuda-me a criar uma FAQ comercial para o meu negócio.

Negócio: [descrever]
Serviços: [listar]
Público-alvo: [descrever]
Objeções comuns: [ex: preço, prazo, confiança, suporte]
Condições que posso comunicar: [listar]
Condições que não devo prometer: [listar]

Cria 15 perguntas frequentes com respostas curtas e profissionais.
As respostas devem ser adequadas para usar no site, em emails ou num assistente de AI.
Não inventes condições comerciais que eu não tenha indicado.
```

---

### 8. Pesquisa de mercado com fontes, `/market-research`

**Code:** `/market-research`

```text
/market-research
Pesquisa tendências de [sector] para pequenas empresas em Portugal.

Objetivo:
Quero perceber oportunidades comerciais para os próximos 6 a 12 meses.

Entrega em português de Portugal:
1. Resumo executivo em 5 pontos
2. Tendências principais
3. Oportunidades para pequenos negócios
4. Riscos ou limitações
5. Ideias práticas que posso testar
6. Fontes usadas

Usa fontes verificáveis e não inventes dados.
Quando uma informação for incerta, assinala como hipótese.
```

---

### 9. Análise simples de concorrentes, `/competitor-scan`

**Code:** `/competitor-scan`

```text
/competitor-scan
Actua como analista de negócio.
Quero comparar o meu negócio com concorrentes.

Meu negócio:
[nome, serviço, zona de actuação, público-alvo]

Concorrentes:
1. [concorrente 1]
2. [concorrente 2]
3. [concorrente 3]

Compara em:
- Posicionamento
- Oferta
- Mensagem comercial
- Pontos fortes
- Pontos fracos
- Oportunidades de diferenciação

Não inventes informação.
Se precisares de pesquisar, indica as fontes.
No final, sugere 5 melhorias práticas para a minha comunicação.
```

---

### 10. Organizar um Projeto no ChatGPT, `/project-setup`

**Code:** `/project-setup`

```text
/project-setup
Ajuda-me a criar um Projeto no ChatGPT para organizar o trabalho do meu negócio.

Área do projeto: [ex: Marketing, Cliente João Silva, Administração, Produto X]
Objetivo: [o que quero fazer neste projeto]
Ficheiros que posso carregar: [PDFs, propostas, FAQs, emails aprovados, tabelas]
Tom pretendido: [ex: profissional, próximo, simples]
O que o ChatGPT deve evitar: [ex: inventar preços, prometer prazos, usar tom agressivo]

Entrega:
1. Nome sugerido para o Projeto
2. Instruções personalizadas para colar no Projeto
3. Lista de ficheiros úteis a carregar
4. Primeiros 5 prompts para usar dentro do Projeto
```

---

### 11. Tarefas agendadas com ChatGPT, `/task-scheduler`

**Code:** `/task-scheduler`

```text
/task-scheduler
Sugere tarefas agendadas úteis para o meu negócio.

Negócio: [descrever]
Rotina semanal: [ex: respondo a leads, publico no LinkedIn, envio propostas]
Objetivo: poupar tempo e não me esquecer de tarefas importantes

Quero 10 ideias de tarefas agendadas, cada uma com:
- Nome da tarefa
- Frequência
- Prompt pronto a usar
- Benefício prático

Exemplos de interesse:
- Resumo diário de notícias do sector
- Lembrete de follow-up
- Ideias de conteúdo semanal
- Relatório semanal de tarefas
```

---

### 12. Prompt para imagem profissional, `/image-brief`

**Code:** `/image-brief`

```text
/image-brief
Cria um prompt para gerar uma imagem profissional para o meu negócio.

Objetivo da imagem: [post, banner, newsletter, apresentação, produto]
Tema: [descrever]
Público-alvo: [descrever]
Estilo visual: [fotografia, ilustração, minimalista, realista]
Cores: [cores da marca]
Formato: [quadrado 1:1, horizontal 16:9, vertical 4:5]
Elementos a incluir: [listar]
Elementos a excluir: [ex: sem texto, sem pessoas, sem logótipos]

Entrega:
1. Prompt final em português
2. Versão alternativa mais criativa
3. Nota de revisão para confirmar se a imagem respeita a marca
```

---

### 13. Desenhar uma automação em papel, `/automation-map`

**Code:** `/automation-map`

```text
/automation-map
Ajuda-me a desenhar uma automação simples antes de a construir no Make.com.

Processo que quero automatizar:
[ex: responder a pedidos de orçamento recebidos por email]

Ferramentas que uso:
[ex: Gmail, Outlook, Google Sheets, Notion, CRM, Calendly]

Quero que organizes o fluxo em:
1. Trigger, o que inicia a automação
2. Filtro, que casos devem avançar
3. Dados necessários
4. Passo com AI
5. Rascunho ou saída esperada
6. Revisão humana
7. Ação final
8. Riscos e cuidados
9. Como testar com dados fictícios

Mantém o fluxo simples e adequado para iniciantes.
```

---

### 14. Planear um cenário no Make.com, `/make-scenario`

**Code:** `/make-scenario`

```text
/make-scenario
Quero criar um cenário no Make.com para follow-up automático de emails.

Ferramentas:
- Gmail ou Outlook
- OpenAI
- Gmail ou Outlook para criar rascunho ou enviar email

Objetivo:
Quando receber um email de potencial cliente, a AI deve criar um rascunho de resposta.

Ajuda-me a definir:
1. Nome do cenário
2. Trigger recomendado
3. Filtros necessários
4. Módulos do Make.com por ordem
5. Variáveis que devo mapear
6. Prompt para o módulo OpenAI
7. Onde colocar revisão humana
8. Testes antes de ativar
9. Erros comuns e como corrigir

Não assumas envio automático sem revisão humana.
```

---

### 15. Prompt para o módulo OpenAI no Make.com, `/automation-prompt`

**Code:** `/automation-prompt`

```text
/automation-prompt
Cria um prompt para usar no módulo OpenAI do Make.com.

Tarefa:
Criar um rascunho de email de follow-up para um potencial cliente.

Dados disponíveis no Make.com:
- Nome do remetente: {{1.from.name}}
- Email do remetente: {{1.from.email}}
- Assunto recebido: {{1.subject}}
- Texto recebido: {{1.text}}
- Serviço de interesse, quando existir: {{servico}}

Regras:
- Não inventar preços, prazos, descontos, disponibilidade ou garantias
- Escrever em português de Portugal
- Tom claro, profissional, próximo e sem pressão comercial
- Máximo 120 palavras no corpo do email
- Se faltar informação essencial, pedir esclarecimento
- A resposta deve ser rascunho para revisão humana

Saída obrigatória:
1. Prioridade: alta, média ou baixa
2. Assunto do email
3. Corpo do email
4. Próxima ação sugerida
5. Informação em falta para revisão humana
6. Risco ou observação
```

---

### 16. Revisão humana antes de enviar, `/human-review`

**Code:** `/human-review`

```text
/human-review
Revê este rascunho de email antes de eu enviar a um cliente.

Contexto:
- Cliente: [tipo de cliente]
- Objetivo: [follow-up, proposta, esclarecimento, suporte]
- Rascunho gerado por AI:
[colar rascunho]

Verifica:
- Se o tom está profissional e adequado
- Se há promessas não confirmadas
- Se foram inventados preços, prazos, descontos ou condições
- Se há dados pessoais ou informação sensível desnecessária
- Se a chamada para ação é clara
- Se o email é curto e fácil de entender

Entrega:
1. Pontos a corrigir
2. Versão final recomendada
3. Nível de risco: baixo, médio ou alto
```

---

### 17. Checklist de segurança e privacidade, `/risk-check`

**Code:** `/risk-check`

```text
/risk-check
Analisa os riscos desta automação com AI antes de eu a ativar.

Descrição da automação:
[descrever fluxo]

Ferramentas envolvidas:
[ex: Gmail, Make.com, OpenAI, Google Sheets, CRM]

Dados tratados:
[ex: nome, email, mensagem, telefone, orçamento]

Quero uma análise em português de Portugal com:
1. Dados pessoais envolvidos
2. Dados que devo remover ou minimizar
3. Permissões que devo limitar
4. Riscos de prompt injection
5. Riscos de envio errado
6. Pontos onde deve existir revisão humana
7. Plano de rollback, como desligar rapidamente
8. Checklist final antes de produção

Sê conservador e assume que a automação deve começar em modo rascunho.
```

---

### 18. Ideias de automação para o negócio, `/automation-ideas`

**Code:** `/automation-ideas`

```text
/automation-ideas
Sugere ideias de automação para o meu negócio.

Negócio: [descrever]
Ferramentas que uso: [Gmail, Outlook, Excel, Google Sheets, Notion, CRM, Calendly, Instagram, etc.]
Tarefas repetitivas que me consomem tempo:
[listar tarefas]

Quero 10 ideias organizadas por dificuldade:
- Fácil, consigo testar esta semana
- Média, exige alguma configuração
- Avançada, só depois de testar bem

Para cada ideia, indica:
- Trigger
- Ação automática
- Ferramentas necessárias
- Benefício
- Risco
- Se precisa de revisão humana
```

---

### 19. Plano de 7 dias depois da workshop, `/seven-day-plan`

**Code:** `/seven-day-plan`

```text
/seven-day-plan
Cria um plano de 7 dias para eu começar a usar AI e automação no meu negócio.

Objetivo:
Passar de uso manual do ChatGPT para um pequeno fluxo com rascunho automático e revisão humana.

Negócio: [descrever]
Tarefa que quero melhorar: [ex: follow-up de leads]
Tempo disponível por dia: [ex: 20 minutos]

O plano deve incluir:
- Dia 1: usar ChatGPT manualmente em 3 respostas reais
- Dia 2: registar erros e ajustar instruções
- Dia 3: criar FAQ do negócio
- Dia 4: testar 5 emails diferentes
- Dia 5: desenhar automação em papel
- Dia 6: criar rascunho automático no Make.com
- Dia 7: medir tempo poupado e qualidade

Para cada dia, dá tarefas concretas e resultado esperado.
```

---

## Template base para um Assistente de Follow-up

Podes copiar este texto para as instruções de um GPT personalizado, Projeto do ChatGPT ou assistente interno.

```text
És um assistente de follow-up para [nome do negócio].

Objetivo:
Criar rascunhos de email para leads, clientes interessados e pessoas que pediram informação ou orçamento.

Tom:
Profissional, simples, próximo, educado e sem pressão comercial.
Escreves sempre em português de Portugal.

Regras:
- Não inventar preços, prazos, descontos, garantias ou disponibilidade
- Não assumir que o cliente já decidiu comprar
- Não enviar mensagens diretamente
- Perguntar quando faltar informação essencial
- Manter emails curtos, claros e fáceis de rever
- Não incluir dados pessoais desnecessários

Formato de saída:
1. Assunto
2. Email
3. Próxima ação sugerida
4. Informação em falta
5. Risco ou observação

Antes de terminares, verifica se:
- O objetivo da mensagem está claro
- O tom está adequado
- Não há promessas indevidas
- A chamada para ação é simples
```

---

## Checklist final antes de usar com clientes

- O objetivo do assistente está escrito numa frase clara.
- As regras de “não inventar” estão explícitas.
- O assistente sabe quando pedir informação adicional.
- O formato de saída é sempre igual e fácil de rever.
- Foram testados pelo menos 3 exemplos realistas.
- Existe revisão humana antes de qualquer envio.
- Os dados sensíveis foram removidos ou minimizados.
- Há forma de desligar ou corrigir a automação rapidamente.

---

## Recomendações gerais de uso

Coloca sempre o *code* na primeira linha, por exemplo `/follow-up-sales`, `/automation-map` ou `/risk-check`, seguido de instruções claras em português de Portugal.

Começa manualmente. Primeiro copia o email, pede um rascunho ao ChatGPT, revê e envia. Só depois passa para automação com Make.com, Zapier ou n8n.

Mantém a regra de ouro: **rascunho automático, envio consciente**.

Automatiza apenas processos que já consegues explicar sem AI. Um fluxo pequeno, testado e seguro vale mais do que uma automação complexa que falha em silêncio.
