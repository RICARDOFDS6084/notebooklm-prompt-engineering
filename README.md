# 📚 Engenharia de Prompts com NotebookLM

## 📖 Contexto

Este projeto foi desenvolvido como parte do desafio prático da DIO (Digital Innovation One), com o objetivo de explorar o NotebookLM como ferramenta de aprendizagem ativa.

O tema escolhido foi **Engenharia de Prompts**, por ser uma habilidade essencial para quem deseja utilizar Inteligência Artificial de forma eficiente. Durante o projeto, utilizei o NotebookLM para organizar informações, analisar diferentes fontes de conhecimento e criar um material de estudo estruturado.

---

## 🎯 Objetivos

- Compreender os conceitos fundamentais de Engenharia de Prompts.
- Aprender a criar prompts mais claros e eficientes.
- Utilizar o NotebookLM como ferramenta de organização do conhecimento.
- Desenvolver um material de consulta para estudos futuros.
- Documentar todo o processo em um repositório no GitHub.

---

## 📚 Curadoria de Fontes

As fontes abaixo foram selecionadas por serem referências reconhecidas na área de Inteligência Artificial e Engenharia de Prompts. Elas foram carregadas no NotebookLM para servir como base na construção do caderno temático.

| Fonte | Tipo | Objetivo |
|-------|------|----------|
| Learn Prompting – A Complete How-To Guide to NotebookLM | Artigo | Compreender o funcionamento e os recursos do NotebookLM. |
| ChatGPT Prompt Patterns for Improving Code Quality (arXiv) | Artigo Científico | Estudar padrões de prompts aplicados ao desenvolvimento de software. |
| Claude Prompt Engineering: Best Practices | Documentação | Conhecer boas práticas para criação de prompts eficientes. |
| Prompting Guide 101 – Google | Documentação Oficial | Aprender técnicas de criação de prompts para modelos generativos. |
| Prompt Engineering Techniques – Microsoft Foundry | Documentação Oficial | Explorar estratégias de otimização de prompts para IA. |

### Critérios utilizados na escolha das fontes

- Fontes oficiais e reconhecidas no mercado.
- Conteúdo atualizado sobre IA Generativa.
- Materiais com exemplos práticos.
- Documentações voltadas para boas práticas.
- Diversidade de abordagens entre diferentes empresas e pesquisadores.

## 🤖 Engenharia de Prompts

### Prompt 1 – Compreendendo a Engenharia de Prompts

#### Objetivo

Entender os conceitos fundamentais da Engenharia de Prompts utilizando múltiplas fontes de informação carregadas no NotebookLM.

#### Prompt utilizado

```text
Com base em todas as fontes disponíveis, explique o que é Engenharia de Prompts.

Sua resposta deve conter:

- definição;
- objetivo;
- importância;
- exemplos práticos;
- conclusão.

Ao final, informe quais fontes foram utilizadas para elaborar a resposta.
```

#### Resultado

O NotebookLM apresentou uma resposta estruturada contendo:

- Definição da Engenharia de Prompts;
- Objetivo da técnica;
- Importância para utilização de modelos de IA;
- Exemplos práticos em diversas áreas;
- Conclusão baseada nas referências consultadas.

Além disso, o NotebookLM informou as fontes utilizadas para gerar a resposta, aumentando a confiabilidade das informações.

#### Aprendizados

Percebi que estruturar o prompt em tópicos produziu uma resposta muito mais organizada e completa do que uma pergunta simples. Também observei que solicitar a indicação das fontes torna a resposta mais confiável e facilita a validação das informações.


## 🔧 Troubleshooting (Cicatrizes)

Durante os testes realizados no NotebookLM, observei que prompts muito genéricos resultam em respostas superficiais.

Ao fornecer mais contexto, definir uma estrutura para a resposta e solicitar que as fontes fossem citadas, a qualidade das respostas melhorou significativamente.

Esse processo demonstrou que a Engenharia de Prompts é fundamental para obter respostas mais precisas, organizadas e confiáveis em modelos de Inteligência Artificial.

## 📝 Miniguia de Estudo
Este miniguia foi elaborado para transformar sua interação com modelos de linguagem (LLMs) em uma colaboração estratégica e produtiva. A Engenharia de Prompts não é apenas "conversar com a IA", mas sim uma forma de programação em linguagem natural
.
1. Resumo do Assunto
A Engenharia de Prompts consiste no design e refinamento de instruções (prompts) para guiar modelos de IA (como Gemini, Claude ou ChatGPT) a gerarem respostas precisas, úteis e seguras
. Em vez de tratar a IA como um oráculo mágico, o foco é vê-la como um "funcionário literal" ou um assistente altamente inteligente que precisa de contexto e diretrizes claras para não "adivinhar" sua intenção
.
2. Os 10 Conceitos Mais Importantes
Conceito
Descrição
Persona
Definir um papel específico para a IA (ex: "Aja como um professor")
.
Tarefa (Task)
O comando ou verbo central do que deve ser feito (ex: "Sintetize", "Crie")
.
Contexto
Informações de fundo ou documentos que fundamentam a resposta
.
Formato
Especificação de como a saída deve ser estruturada (lista, tabela, JSON)
.
Grounding (Ancoragem)
Uso de fontes de dados confiáveis para basear a resposta e evitar erros
.
Zero-shot
Pedir algo sem fornecer exemplos prévios
.
Few-shot Learning
Fornecer de 3 a 5 exemplos de "entrada e saída" para treinar a IA no momento
.
Chain-of-Thought (CoT)
Instruir a IA a pensar passo a passo antes de dar a resposta final
.
Tags XML
Uso de marcadores (ex: <instruções>) para organizar prompts complexos
.
Alucinação
Quando o modelo inventa informações falsas com confiança
.
3. Glossário
Tokens: Unidades de texto (palavras ou partes delas) que a IA processa. Modelos têm limites de "janela de contexto" medidos em tokens
.
Recency Bias (Viés de Recência): A tendência do modelo de dar mais peso às informações colocadas ao final do prompt
.
Prompt Chaining: Quebrar uma tarefa complexa em vários prompts sequenciais
.
Negative Constraints: Instruções que dizem o que não fazer (geralmente menos eficazes que ordens positivas)
.
Affordances: Uso de ferramentas externas pela IA, como busca na web ou execução de código
.
4. Os Principais Erros Cometidos por Iniciantes
Prompts Vagos e Curtos: A maioria dos usuários usa menos de 9 palavras, enquanto prompts eficazes têm, em média, 21 palavras
.
Tratar como o Google: Fazer perguntas simples de busca em vez de fornecer contexto e requisitos estruturados
.
Efeito "Elefante Rosa": Dizer "não faça X", o que mantém o conceito ativo na "atenção" da IA e aumenta a chance de erro
.
Ordem Incorreta: Colocar a pergunta antes do texto longo. Em documentos extensos, colocar a pergunta no final melhora a qualidade em até 30%
.
Confiança Cega: Não revisar a clareza, relevância e precisão da saída gerada
.
5. As Melhores Práticas
Seja Brutalmente Específico: Defina o que "abrangente" ou "bom" significa para sua tarefa específica
.
Explique o "Porquê": A IA generaliza melhor quando entende a motivação de uma regra (ex: "o texto será lido por cegos, evite emojis")
.
Dê uma "Saída" à IA: Instrua-a a responder "não encontrado" se a informação não estiver nas fontes, reduzindo alucinações
.
Contexto Primeiro: Coloque os arquivos e dados no topo do prompt e as instruções/perguntas logo abaixo
.
Use Linguagem Natural: Escreva como se estivesse conversando com uma pessoa, usando frases completas
.
6. Checklist para Bons Prompts
[ ] Atribuí uma Persona clara?
[ ] A Tarefa principal começa com um verbo de comando?
[ ] Forneci o Contexto ou documentos de referência?
[ ] Defini o Formato de saída desejado?
[ ] Incluí Exemplos (Few-shot) se a tarefa for complexa?
[ ] A Pergunta Final está após todo o contexto?
[ ] Solicitei Citações Diretas das fontes?
7. Exemplos: Ruim vs. Melhorado
Prompt Ruim
Por que é ruim?
Versão Melhorada
"Crie um dashboard"
Vago; a IA pode entregar apenas um quadro vazio
.
"Crie um dashboard de análise. Inclua visualização de dados, filtros e funções de exportação"
.
"Não use listas"
Comando negativo (Elefante Rosa)
.
"Escreva sua resposta apenas em parágrafos de prosa fluida"
.
"Resuma este texto: [texto]"
Pergunta antes do contexto
.
"[texto] ... Com base no texto acima, escreva um resumo de 3 parágrafos"
.
"Sempre use números exatos"
Instrução absoluta pode falhar se não houver dados
.
"Se dados verificados estiverem disponíveis, use números. Caso contrário, forneça estimativas rotuladas"
.
"Resolva este problema"
Não incentiva o raciocínio
.
"Analise a lógica deste problema passo a passo, verificando cada possibilidade antes de concluir"
.
8. Cinco Prompts Reutilizáveis para Estudos
As 5 Perguntas Essenciais: "Analise todos os documentos e gere 5 perguntas essenciais que capturem os principais pontos e o significado central do conteúdo"
.
Simplificação para Leigos: "Atue como um comunicador experiente. Traduza este conteúdo técnico para uma linguagem que qualquer cidadão possa entender, usando analogias cotidianas"
.
Mapeamento de Temas: "Identifique os 5 temas mais recorrentes nos documentos e apresente-os em uma tabela estruturada com definições e referências"
.
Quiz Educativo (Podcast): "Crie um roteiro de perguntas e respostas entre dois apresentadores sobre [Tópico]. Inclua erros propositais que são corrigidos para reforçar o aprendizado"
.
Análise de Contradições: "Identifique as principais contradições ou achados conflitantes entre as fontes fornecidas, citando a posição específica de cada lado"
.
Fontes utilizadas:
A Complete How-To Guide to NotebookLM - Learn Prompting
ChatGPT Prompt Patterns for Improving Code Quality... - arXiv
Claude Prompt Engineering: Best Practices - DreamHost
Guia de Prompts para NotebookLM - NELCA - GestGov
Guia oficial de engenharia de prompt do ChatGPT da OpenAI (Youtube)
Optimize prompts overview - Microsoft Copilot Studio
Prompt engineering techniques - Microsoft Foundry
Prompting Guide 101 - Google
Prompting best practices - Claude Platform Docs
### Resumos

### Glossário

### Prompts Reutilizáveis

---

## 🚀 Conclusão

## 🚀 Conclusão

O desenvolvimento deste projeto demonstrou que a Engenharia de Prompts é uma competência essencial para utilizar Inteligência Artificial de forma eficiente.

Durante os testes realizados no NotebookLM foi possível observar que pequenas alterações na estrutura dos prompts produzem respostas significativamente mais completas e precisas.

Além do aprendizado técnico, este projeto permitiu desenvolver habilidades de pesquisa, curadoria de fontes, pensamento crítico e documentação, competências fundamentais para profissionais que utilizam IA em estudos e no ambiente de trabalho.
