🌸 MenoWork — Agente de IA para Bem-Estar Feminino no Ambiente de Trabalho

O MenoWork é um agente de Inteligência Artificial desenvolvido no Microsoft Azure AI Foundry para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto seguem ativas profissionalmente.
Seu objetivo é oferecer orientações acolhedoras, práticas e baseadas em fontes confiáveis, promovendo bem-estar, equilíbrio e autocuidado no contexto profissional.

🎯 Objetivo do Projeto

Criar um agente funcional no Azure AI Foundry.

Aplicar prompt engineering para construir um fluxo conversacional eficiente.

Implementar uma ação funcional exigida pelo curso (“Cálculo de Equilíbrio Diário”).

Demonstrar como a IA pode apoiar o bem-estar feminino no ambiente de trabalho.

🤖 Funcionamento do Agente

O MenoWork realiza o Cálculo de Equilíbrio Diário com base em quatro perguntas sobre:

Horas de sono.

Qualidade da alimentação (saudável / moderada / ruim).

Prática de atividade física no dia.

Nível de estresse no trabalho (1 a 5).

🔢 Lógica de Pontuação

Sono:

≥ 7h → +3

5–6h → +2

< 5h → +1

Alimentação:

Saudável → +3

Moderada → +2

Ruim → +1

Atividade física:

Fez → +2

Não fez → +0

Estresse:

≤2 → +2

3 → +1

≥4 → +0

🧩 Classificação Final

8–10: Excelente! Bem-estar equilibrado 💪

5–7: Razoável. Momento de autocuidado 🌿

0–4: Atenção! Cuide-se um pouco mais 💗

O resultado final inclui:
✔ Pontuação geral
✔ Classificação
✔ Dica de autocuidado
✔ Link confiável

🧠 Prompt Utilizado (Instruções)

Você é o MenoWork, um agente de Inteligência Artificial criado para apoiar mulheres que estão vivenciando a menopausa ou o climatério enquanto seguem ativas profissionalmente.
Seu papel é oferecer orientações personalizadas sobre bem-estar físico, emocional e produtividade no ambiente de trabalho, com empatia e base científica.

Objetivo:

Promover equilíbrio, autocuidado e qualidade de vida.

Utilizar linguagem acolhedora e acessível.

Tom de voz:

Amigável e empático, usando emojis leves (🌿💗💪) quando adequado.

Falar como uma mentora de bem-estar, nunca como médica.

Funcionalidade principal:
Cálculo de Equilíbrio Diário baseado em perguntas sobre sono, alimentação, atividade física e estresse, gerando pontuação de 0 a 10.

Classificação:

8–10: Excelente! Seu bem-estar está equilibrado hoje.

5–7: Razoável. Que tal um momento de autocuidado?

0–4: Atenção! Cuide-se mais.

Sempre inclua:

Pontuação

Classificação

Uma dica rápida

Um link confiável (ex.: gov.br ou Febrasgo)

Limitações:

Não oferecer diagnóstico médico.

Conteúdo apenas educativo.

🗂 Estrutura do Repositório

MenoWork/
├── fluxo/
│ └── fluxo_MenoWork.png
├── prints/
│ ├── print_01_criacao_agente.png
│ ├── print_02_configuracao_agente.png
│ ├── print_03_acao_funcional.png
│ ├── print_04_execucao_boas_vindas.png
│ ├── print_05_execucao_perguntas.png
│ ├── print_06_execucao_calculo.png
│ ├── print_07_execucao_resultado.png
│ └── print_08_execucao_encerramento.png
└── README.md

🧪 Como Testar o Agente

Acesse o Azure AI Foundry.

Vá em Agentes → MenoWork.

Clique em Open playground.

Digite:
Quero iniciar o cálculo de equilíbrio diário.

Responda às quatro perguntas.

O agente apresentará:

Pontuação

Classificação

Dica de autocuidado

Referência confiável

📸 Prints da Execução

A pasta prints/ contém:

print_01_criacao_agente.png

print_02_configuracao_agente.png

print_03_acao_funcional.png

print_04_execucao_boas_vindas.png

print_05_execucao_perguntas.png

print_06_execucao_calculo.png

print_07_execucao_resultado.png

print_08_execucao_encerramento.png

📚 Referências

Ministério da Saúde – gov.br
https://www.gov.br/saude

FEBRASGO – Federação Brasileira de Ginecologia e Obstetrícia
https://www.febrasgo.org.br

Microsoft Azure AI Foundry – Documentação
https://learn.microsoft.com/azure/ai

👩‍💻 Autora

Kalina Almeida
Projeto desenvolvido para a formação Microsoft Azure AI.

🌿 Obrigada pela visita!
Sinta-se à vontade para explorar, testar e contribuir.
Equilíbrio é o segredo. 💗✨
