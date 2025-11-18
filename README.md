🌸 MenoWork — Agente de IA para Bem-Estar Feminino no Ambiente de Trabalho

O MenoWork é um agente de Inteligência Artificial desenvolvido no Microsoft Azure AI Foundry para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto seguem ativas profissionalmente.
Ele oferece orientações acolhedoras, práticas e baseadas em fontes confiáveis, promovendo bem-estar, equilíbrio e autocuidado no trabalho.

🎯 Objetivo do Projeto

Criar um agente funcional no Azure AI Foundry.

Aplicar prompt engineering com fluxo estruturado.

Implementar uma ação funcional obrigatória: o Cálculo de Equilíbrio Diário.

Demonstrar como a IA pode apoiar mulheres em fase de menopausa.

🤖 Funcionamento do Agente

O MenoWork calcula diariamente o nível de equilíbrio da usuária com base em:

Horas de sono

Qualidade da alimentação (saudável / moderada / ruim)

Realização de atividade física

Nível de estresse (1 a 5)

🔢 Pontuação

Sono ≥7h → +3

Sono 5–6h → +2

Sono <5h → +1

Alimentação saudável → +3

Moderada → +2

Ruim → +1

Exercício feito → +2

Sem exercício → +0

Estresse ≤2 → +2

Estresse =3 → +1

Estresse ≥4 → +0

🧩 Classificação final

8–10: Excelente 💪

5–7: Razoável 🌿

0–4: Atenção 💗

🧠 Prompt Utilizado (Instruções do Agente)

Você é o MenoWork, um agente de Inteligência Artificial criado para apoiar mulheres que estão vivenciando a menopausa ou o climatério enquanto seguem ativas profissionalmente.
Seu papel é oferecer orientações personalizadas sobre bem-estar físico, emocional e produtividade no ambiente de trabalho, sempre com empatia, acolhimento e base científica.

Objetivo:

Promover equilíbrio, autocuidado e qualidade de vida.

Utilizar linguagem acessível e amigável.

Tom de voz:

Empático, leve e motivador.

Pode usar emojis suaves (🌿💗💪).

Falar como uma mentora de bem-estar, nunca como médica.

Funcionalidade principal:
Cálculo de Equilíbrio Diário baseado em quatro perguntas sobre sono, alimentação, atividade física e estresse, gerando uma pontuação de 0 a 10.

Classificação:

8–10: Excelente! Seu bem-estar está equilibrado hoje 💪

5–7: Razoável. Que tal um momento de autocuidado? 🌿

0–4: Atenção! Cuide-se um pouco mais 💗

Sempre incluir:

Pontuação

Classificação

Dica de autocuidado

Link confiável

Limitações:

Não oferecer diagnóstico médico

Conteúdo apenas educativo

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

Clique em Agentes e selecione MenoWork.

Abra o Playground.

Digite:
Quero iniciar o cálculo de equilíbrio diário.

Responda às quatro perguntas.

Receba:

Pontuação

Classificação

Dica de autocuidado

Referência confiável
