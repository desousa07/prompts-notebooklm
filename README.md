# Engenharia de Prompts com NotebookLM
A Engenharia de Prompts possui aplicação direta em diversas atividades administrativas, permitindo aumentar a produtividade e a qualidade das entregas. Este projeto tem como objetivo construir um Caderno no NotebookLM para estudar técnicas de engenharia de prompts, compreender boas práticas e desenvolver melhores prompts para uso profissional. 

---

Objetivos de Aprendizagem:
* Compreender os fundamentos da Engenharia de Prompts;
* Aprender técnicas de Prompt (Zero-Shot, One-Shot, Chain of Thought entre outros);
* Construir biblioteca pessoal de prompts reutilizáveis.

# Curadoria de fontes:

* https://developers.openai.com/api/docs/guides/prompt-engineering
* https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview
* https://cloud.google.com/discover/what-is-prompt-engineer
* https://learn.microsoft.com/en-us/azure/foundry/openai/concepts/prompt-engineering
* https://arxiv.org/html/2402.07927v2

# Testes realizados:

### Prompt 1

```text
Explique Engenharia de Prompts para alguém que trabalha com gestão administrativa e nunca estudou IA.
```

* Objetivo: Compreender os fundamentos da Engenharia de Prompts.
* Resultado: Resposta simplificada com exemplos fáceis e costumeiros ao público alvo.
* Aprendizado: Quanto mais específico o público-alvo, melhor a resposta.

### Prompt 2

```text
Atue como especialista em Inteligência Artificial.
Explique detalhadamente as diferenças entre Zero-Shot, One-Shot e Few-Shot Prompting.
Forneça exemplos práticos.
```

* Objetivo: Obter resposta técnica.
* Resultado: Resposta mais profunda e estruturada.
* Aprendizado: A técnica de Role Prompting aumentou significativamente a qualidade da saída.

---

## Dificuldades Encontradas (Troubleshooting)

| Problema                 | Causa             | Solução                       |
| ------------------------ | ----------------- | ----------------------------- |
| Respostas genéricas      | Falta de contexto | Adicionar papel e objetivo    |
| Respostas muito longas   | Prompt aberto     | Definir limite de palavras    |
| Informações superficiais | Solicitação vaga  | Especificar nível técnico     |
| Falta de exemplos        | Não solicitado    | Pedir exemplos explicitamente |

---

# Glossário

| Termo              | Definição                                             |
| ------------------ | ----------------------------------------------------- |
| Prompt             | Instrução enviada à IA                                |
| LLM                | Large Language Model                                  |
| Context Window     | Quantidade de contexto que o modelo consegue analisar |
| Hallucination      | Resposta incorreta gerada pela IA                     |
| Few-Shot           | Técnica baseada em exemplos                           |
| Chain of Thought   | Raciocínio passo a passo                              |
| Prompt Engineering | Engenharia de elaboração de prompts                   |

---

# Biblioteca de Prompts Reutilizáveis

### Para Estudo

```text
Explique [ASSUNTO] utilizando exemplos simples e analogias práticas.
```

### Para Resumo

```text
Resuma o conteúdo abaixo em tópicos hierárquicos.
```

### Para Especialista

```text
Atue como especialista em [ÁREA] com mais de 20 anos de experiência.
```

### Para Aprendizado Profundo

```text
Explique o assunto em três níveis:
- Iniciante
- Intermediário
- Avançado
```

### Para Análise Crítica

```text
Analise o texto abaixo apontando:
- pontos fortes
- pontos fracos
- riscos
- oportunidades de melhoria
```

---

# Conclusão

Os estudos da Engenharia de Prompts demonstraram que a qualidade das respostas geradas por modelos de IA depende diretamente da clareza, estrutura e contexto fornecidos nas instruções. O NotebookLM mostrou-se uma ferramenta eficiente para consolidar fontes, testar abordagens e organizar conhecimento de forma estruturada, contribuindo para a criação de um material de consulta permanente e aplicável ao contexto profissional.
