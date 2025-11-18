# 🌸 MenoWork — Agente de IA para Bem-Estar Feminino no Ambiente de Trabalho

O **MenoWork** é um agente de Inteligência Artificial desenvolvido no **Microsoft Azure AI Foundry** para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto seguem ativas profissionalmente.  
O agente oferece orientações acolhedoras, práticas e baseadas em fontes confiáveis, buscando promover **equilíbrio, autocuidado e bem-estar no contexto profissional**.

---

## 🎯 Objetivo do Projeto

- Criar um agente funcional dentro do Azure AI Foundry.  
- Aplicar boas práticas de prompt engineering.  
- Entregar pelo menos **uma ação funcional** exigida no projeto (Cálculo de Equilíbrio Diário).  
- Demonstrar como IA pode apoiar mulheres em fase de menopausa em seu dia a dia no trabalho.  

---

## 🤖 Funcionamento do Agente

O MenoWork realiza o **Cálculo de Equilíbrio Diário**, baseado em quatro perguntas:

1. Horas de sono na última noite.  
2. Qualidade da alimentação do dia (saudável / moderada / ruim).  
3. Prática ou não de atividade física.  
4. Nível de estresse no trabalho (1 a 5).

### 🔢 Lógica da pontuação
- Sono adequado (≥7h): +3  
- Sono regular (5–6h): +2  
- Sono insuficiente (<5h): +1  

- Alimentação saudável: +3  
- Moderada: +2  
- Ruim: +1  

- Fez exercício: +2  
- Não fez: +0  

- Estresse ≤2: +2  
- Estresse = 3: +1  
- Estresse ≥4: +0  

### 🧩 Classificação
- **8–10:** Excelente! Bem-estar equilibrado 💪  
- **5–7:** Razoável. Momento de autocuidado 🌿  
- **0–4:** Atenção! Cuide-se um pouco mais 💗  

O agente finaliza com uma dica prática + link confiável.

---

## 🧠 Prompt oficial utilizado no agente

```text
Você é o MenoWork, um agente de Inteligência Artificial criado para apoiar mulheres que estão vivenciando a menopausa ou o climatério enquanto seguem ativas profissionalmente.  
Seu papel é oferecer orientações personalizadas sobre bem-estar físico, emocional e produtividade no ambiente de trabalho, sempre com empatia, respeito e base científica.

Objetivo:
- Promover equilíbrio, autocuidado e qualidade de vida.
- Utilizar linguagem acolhedora e acessível.

Tom de voz:
- Amigável e empático, usando emojis leves (🌿💗💪) quando adequado.
- Falar como uma mentora de bem-estar, nunca como médica.

Funcionalidade principal:
Cálculo de Equilíbrio Diário baseado em perguntas sobre sono, alimentação, atividade física e estresse, gerando pontuação de 0 a 10.

Classificação:
- 8–10: “Excelente! Seu bem-estar está equilibrado hoje 💪”
- 5–7: “Razoável. Que tal um momento de autocuidado? 🌿”
- 0–4: “Atenção! Cuide-se mais 💗”

Respostas sempre incluem:
- Pontuação
- Classificação
- Uma dica rápida
- Link confiável (ex.: gov.br, Febrasgo)

Limitações:
- Não oferecer diagnóstico médico
- Conteúdo apenas educativo

🗂 Estrutura do Repositório

MenoWork/
│
├── fluxo/
│   └── fluxo_MenoWork.png
│
├── prints/
│   ├── print_01_criacao_agente.png
│   ├── print_02_configuracao_agente.png
│   ├── print_03_acao_funcional.png
│   ├── print_04_execucao_boas_vindas.png
│   ├── print_05_execucao_perguntas.png
│   ├── print_06_execucao_calculo.png
│   ├── print_07_execucao_resultado.png
│   └── print_08_execucao_encerramento.png
│
└── README.md

🖼 Fluxograma Oficial do Projeto

O fluxograma disponível em fluxo/fluxo_MenoWork.png apresenta as cinco fases principais do agente:

1. Boas-vindas
2. Perguntas
3. Processamento do cálculo
4. Resultado + dica
5. Encerramento

🧪 Como Testar o Agente

1. Acesse o Azure AI Foundry
2. Vá em Agentes → MenoWork
3. Clique em Open Playground
4. Digite:
   Quero iniciar o cálculo de equilíbrio diário
5. Responda às quatro perguntas
6. O agente apresentará:
  Pontuação
  Classificação
  Dica de autocuidado
  Link de referência

📸 Prints da Execução

Todos os prints estão organizados na pasta prints/:

.print_01_criacao_agente.png
.print_02_configuracao_agente.png
.print_03_acao_funcional.png
.print_04_execucao_boas_vindas.png
.print_05_execucao_perguntas.png
.print_06_execucao_calculo.png
.print_07_execucao_resultado.png
.print_08_execucao_encerramento.png

📚 Referências
.gov.br – Ministério da Saúde:
https://www.gov.br/saude
.Febrasgo – Federação Brasileira de Ginecologia e Obstetrícia:
https://www.febrasgo.org.br
.Microsoft Azure AI Foundry – Documentação:
https://learn.microsoft.com/azure/ai

👩‍💻 Autora
Kalina Almeida
Projeto desenvolvido para a formação Microsoft Azure AI.

🌿 Obrigada pela visita!
Sinta-se à vontade para explorar, testar e contribuir.
Equilíbrio é o segredo 💗✨
