# 🌸 MenoWork

Agente de IA para apoio ao bem-estar de mulheres na menopausa no ambiente de trabalho.  
Projeto final do curso **Microsoft AI Foundry**.

---

## Índice

1. [Visão Geral](#visão-geral)  
2. [Objetivo](#objetivo)  
3. [Como Funciona](#como-funciona)  
4. [Cálculo de Equilíbrio Diário](#cálculo-de-equilíbrio-diário)  
5. [Classificação de Bem-Estar](#classificação-de-bem-estar)  
6. [Estrutura do Repositório](#estrutura-do-repositório)  
7. [Como Testar](#como-testar)  
8. [Referências](#referências)  
9. [Limitações](#limitações)  
10. [Colaboradores](#colaboradores)  

---

## Visão Geral

O **MenoWork** é um agente de Inteligência Artificial criado para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto permanecem ativas no ambiente profissional. Ele fornece orientações acolhedoras, informações confiáveis e uma funcionalidade chamada **Cálculo de Equilíbrio Diário** para monitorar bem-estar físico, emocional e profissional.

---

## Objetivo

- Apoiar mulheres em fase de menopausa/climatério.  
- Promover equilíbrio entre saúde, autocuidado e produtividade no trabalho.  
- Oferecer respostas simples, empáticas e baseadas em fontes confiáveis.  
- Auxiliar a usuária a entender seu nível de bem-estar diário por meio de um cálculo personalizado.

---

## Como Funciona

O MenoWork conversa com a usuária por meio de IA, fazendo perguntas e fornecendo feedback com base nas respostas. A funcionalidade central é o **Cálculo de Equilíbrio Diário**, detalhado na seção abaixo.

---

## Cálculo de Equilíbrio Diário

O agente faz quatro perguntas:

1. Quantas horas você dormiu na última noite?  
2. Como foi sua alimentação hoje? (saudável / moderada / ruim)  
3. Você praticou atividade física hoje? (sim / não)  
4. Como está seu nível de estresse no trabalho? (1 a 5)

**Fórmula aplicada**:

- Sono:  
  - ≥ 7h → +3  
  - 5–6h → +2  
  - < 5h → +1  

- Alimentação:  
  - saudável → +3  
  - moderada → +2  
  - ruim → +1  

- Atividade física:  
  - sim → +2  
  - não → +0  

- Estresse:  
  - ≤ 2 → +2  
  - = 3 → +1  
  - ≥ 4 → +0  

---

## Classificação de Bem-Estar

- **8–10**: Excelente! 💪 Bem-estar equilibrado.  
- **5–7**: Razoável – que tal dedicar um momento ao autocuidado? 🌿  
- **0–4**: Atenção! Priorize descanso, hidratação e relaxamento. 💗  

O agente retorna: pontuação, interpretação, dica prática e link de referência confiável.

---

## Estrutura do Repositório

fluxo/
└─ fluxo_MenoWork.png – Fluxograma do agente
prints/
├─ print_01_criacao_agente.png
├─ print_02_configuracao_agente.png
├─ print_03_acao_funcional.png
├─ print_04_execucao_boas_vindas.png
├─ print_05_execucao_perguntas.png
├─ print_06_execucao_calculo.png
├─ print_07_execucao_resultado.png
└─ print_08_execucao_encerramento.png
README.md – Documentação principal


---

## Como Testar

1. Acesse o **Azure AI Foundry Studio** e abra o agente MenoWork.  
2. Use o playground ou a ação de cálculo para simular a interação.  
3. Insira respostas nas perguntas do cálculo e observe o resultado + mensagem final.  
4. Verifique os prints na pasta `prints/` para conferir as etapas que foram gravadas.  

---

## Referências

- Ministério da Saúde – gov.br  
- FEBRASGO – Federação Brasileira das Associações de Ginecologia e Obstetrícia  
- Organização Mundial da Saúde – OMS  

---

## Limitações

- **Não substitui diagnóstico médico**.  
- Todas as informações têm caráter educativo e de apoio.  
- Para acompanhamento real, a usuária deve procurar um profissional de saúde.

---

## Colaboradores

- **Autora**: Kalina Almeida — [GitHub](https://github.com/kalinaalmeida)

