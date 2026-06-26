Miniguia de Estudos: Fundamentos de Backend & Linguagens Modernas (C#, Go e Python)
Este repositório foi criado como entrega para o Desafio de Projeto da DIO, com o objetivo de documentar e estruturar o aprendizado sobre o desenvolvimento backend utilizando o NotebookLM da Google como ferramenta de aprendizagem ativa.

🎯 Contexto e Objetivos

O objetivo deste caderno temático é consolidar os conhecimentos básicos necessários para iniciar a jornada no desenvolvimento Backend, compreendendo a infraestrutura básica e fazendo um comparativo prático entre três linguagens fundamentais do mercado atual: C#, Go (Golang) e Python.

Objetivos de Estudo:
Compreender a Infraestrutura: Entender o papel de Servidores Web, APIs (especialmente RESTful) e Bancos de Dados na arquitetura de aplicações.
Compreender Linguagens: Analisar a sintaxe, a performance e os casos de uso ideais de C#, Go e Python no desenvolvimento backend.
Aprender com IA: Utilizar técnicas de Engenharia de Prompts no NotebookLM para gerar resumos de alta qualidade e sanar dúvidas complexas.

📚 Curadoria de Fontes

Para alimentar o NotebookLM e garantir respostas precisas e confiáveis, foram selecionadas as seguintes fontes abertas (manuais, livros gratuitos e artigos científicos):

Conceitos de Infraestrutura e Fundamentos:
Servidores: MDN Web Docs - O que é um servidor web?
APIs: Red Hat - O que é uma API?
Banco de Dados: Oracle - O que é um Banco de Dados Relacional?

Livros Técnicos Gratuitos (PDF/Web):
Go: An Introduction to Programming in Go por Caleb Doxsey (Versão online gratuita)
Python: Architecture Patterns with Python por Harry Percival & Bob Gregory (Disponibilizado gratuitamente online)
C#: ASP.NET Core Web API (e-Book oficial em PDF da Microsoft)

Artigos Científicos:
Artigo de Performance: Performance comparison of development frameworks in REST API architecture (Disponível no ResearchGate, comparando a eficiência de diferentes runtimes em arquiteturas REST).

🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, testados diferentes abordagens de prompts para extrair o melhor das fontes de dados carregadas. Veja os testes e aprendizados obtidos:

1. Teste de Prompt Broad (Genérico) vs. Role-Play (Específico)
2. 
Prompt Fraco: "Me explica a diferença entre Go, Python e C#."
Resultado: A IA deu uma resposta muito generalista, focando em popularidade e não na atuação direta no backend ou na performance das APIs.
Prompt Otimizado (Engenharia de Prompt):
"Agindo como um Arquiteto de Software sênior especializado em Backend, compare C#, Go e Python com base estrita nos documentos fornecidos. Foque em três critérios: Modelo de concorrência, velocidade de compilação/execução e facilidade de manutenção de APIs. Use uma tabela para resumir."

Resultado: O NotebookLM organizou a resposta perfeitamente em uma tabela comparativa, extraindo dados exatos dos livros e artigos.

2. Dificuldades Encontradas ("Cicatrizes") e Como Resolver:
   
Alucinação de Sintaxe: O NotebookLM tentou exemplificar códigos que não estavam nas fontes.
Como foi resolvido (Troubleshooting): Ajustamos as instruções forçando a IA a: "Responda apenas utilizando as informações contidas nos documentos carregados nas fontes. Se a sintaxe de um comando específico não estiver explícita nas fontes, avise-me em vez de tentar inventar."

📖 Miniguia de Estudo (Entrega Final)

1. Resumos Estruturados

A. Servidores Web, APIs e Bancos de Dados
Servidores Web: Dispositivos ou softwares que processam requisições HTTP dos clientes (frontend) e retornam respostas (geralmente arquivos HTML, JSON ou estáticos).
APIs RESTful: O canal de comunicação padronizado no backend. Utiliza métodos HTTP (GET, POST, PUT, DELETE) para gerenciar recursos de forma stateless (sem guardar estado do cliente).
Bancos de Dados: Onde os dados persistem. Dividem-se principalmente em Relacionais (SQL), que usam esquemas rígidos e tabelas (ex: PostgreSQL), e Não-Relacionais (NoSQL), ideais para dados semiestruturados ou escalabilidade horizontal massiva (ex: MongoDB).
B. O Trio de Linguagens Backend
C# (.NET Core): Linguagem compilada (JIT) fortemente tipada desenvolvida pela Microsoft. Destaca-se pela robustez corporativa, alto desempenho com ASP.NET Core e excelente gerenciamento de memória.
Go (Golang): Desenvolvido pela Google, compila diretamente para código de máquina (binário nativo). Seu grande trunfo é a concorrência ultra-leve usando Goroutines, tornando-a líder em microsserviços de alto tráfego.
Python: Linguagem interpretada de altíssima produtividade. Embora tenha menor performance bruta comparada a C# e Go, brilha no backend com frameworks modernos como FastAPI (assíncrono) e em projetos que integram Inteligência Artificial e Ciência de Dados.

3. Glossário de Conceitos Aprendidos
   
API (Application Programming Interface): Interface que permite que dois sistemas de software se comuniquem.
REST (Representational State Transfer): Estilo arquitetural para sistemas hipermídia distribuídos, baseado no protocolo HTTP.
Stateless: Princípio do REST onde cada requisição HTTP deve conter todas as informações necessárias para ser processada, sem depender de sessões salvas no servidor.
JIT (Just-In-Time Compilation): Compilação de código realizada durante a execução do programa (usada pelo C#/.NET) para otimizar a velocidade.
Goroutine: Thread extremamente leve gerenciada pelo runtime do Go, permitindo executar milhares de tarefas concorrentes consumindo pouquíssima memória.
SQL (Structured Query Language): Linguagem padrão para gerenciar bancos de dados relacionais baseados em tabelas e chaves estrangeiras.
5. Biblioteca de Prompts Reutilizáveis (Para Revisões Futuras)
Copie e cole estes prompts no NotebookLM sempre que precisar revisar ou aprofundar seu estudo:

Para explicar um trecho complexo:
"Com base no livro [Nome da Fonte], explique detalhadamente como funciona a arquitetura de [Conceito, ex: concorrência em Go / Injeção de Dependência em C#] para alguém que está aprendendo backend agora. Use uma analogia simples do dia a dia."

Para criar um quiz de revisão:
"Com base nas fontes sobre Banco de Dados e APIs, crie um quiz de 5 perguntas de múltipla escolha para testar meu conhecimento sobre a diferença entre SQL e NoSQL e os métodos HTTP em APIs REST. Forneça o gabarito comentado no final."

Para debugar conceitos cruzados:
"Compare como C# (usando Tasks) e Go (usando Goroutines) lidam com requisições concorrentes de forma assíncrona, citando trechos das fontes fornecidas."
