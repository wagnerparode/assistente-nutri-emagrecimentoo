# 🍎 NutriAmigo - Assistente Virtual para Emagrecimento Saudável

Projeto desenvolvido para o Lab "Construa Seu Assistente Virtual Com Inteligência Artificial" da Digital Innovation One (DIO).

## 🎯 Objetivo do Projeto
O NutriAmigo é um assistente virtual focado em ajudar pessoas no processo de reeducação alimentar e emagrecimento saudável. Ele foca em sugerir substituições práticas de alimentos cotidianos e incentivar hábitos saudáveis simples, evitando dietas restritivas ou perigosas.

## 🛠️ Como o Projeto foi Construído

1. **Documentação:** Definimos a persona do NutriAmigo como um guia acolhedor, motivador e focado em linguagem simples.
2. **Base de Conhecimento:** Criamos uma base de dados em formato de texto (`data/base_conhecimento.txt`) com regras oficiais de trocas alimentares.
3. **Engenharia de Prompts:** Desenvolvemos um prompt de sistema rigoroso (`src/prompt_sistema.txt`) que impede o assistente de inventar dados ou passar recomendações médicas/remédios.
4. **Aplicação Funcional:** Prototipado e testado utilizando a tecnologia de Large Language Models (LLM) configurada com o nosso prompt customizado.
5. **Avaliação e Métricas:** Realizamos testes de conformidade (`docs/testes_metricas.md`) para garantir que o bot recusa perguntas fora do seu escopo.

## 🚀 Como testar
Você pode testar a lógica do assistente copiando as instruções de sistema em `src/prompt_sistema.txt` e a base em `data/base_conhecimento.txt` e utilizando no seu playground de IA favorito (como o ChatGPT).
