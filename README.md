🌸 MenoWork

Agente de IA para apoio ao bem-estar de mulheres na menopausa no ambiente de trabalho
Projeto desenvolvido como entrega final do curso Microsoft – AI Foundry.

💡 Visão Geral

O MenoWork é um agente de Inteligência Artificial criado para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto seguem ativas profissionalmente. Ele fornece orientações acolhedoras, informações confiáveis e uma funcionalidade especial chamada Cálculo de Equilíbrio Diário, ajudando a usuária a monitorar seu bem-estar físico, emocional e profissional ao longo do dia.

Este repositório atende todos os requisitos de elegibilidade:
✔ README completo e documentado
✔ Agente funcional no Azure AI Foundry
✔ Ação funcional executando o cálculo
✔ Prints da execução
✔ Fluxograma oficial do projeto
✔ Repositório organizado de forma clara

🎯 Objetivo do Agente

Apoiar mulheres em fase de menopausa/climatério.

Promover equilíbrio entre saúde, autocuidado e produtividade profissional.

Oferecer respostas simples, empáticas e baseadas em fontes confiáveis.

Auxiliar a usuária a entender seu nível de bem-estar diário por meio de um cálculo personalizado.

🤖 Como o MenoWork Funciona

O agente conversa com a usuária de forma acolhedora e realiza a funcionalidade central:

🧮 Cálculo de Equilíbrio Diário

O MenoWork faz quatro perguntas:

Quantas horas você dormiu na última noite?

Como foi sua alimentação hoje? (saudável / moderada / ruim)

Praticou alguma atividade física hoje? (sim / não)

Como está seu nível de estresse no trabalho? (1 a 5)

Em seguida, aplica a seguinte fórmula:

Sono
≥7h: +3 • 5–6h: +2 • <5h: +1

Alimentação
saudável: +3 • moderada: +2 • ruim: +1

Atividade física
sim: +2 • não: +0

Estresse
≤2: +2 • 3: +1 • ≥4: +0

📊 Classificação Final

8–10: Excelente! Seu bem-estar está equilibrado hoje 💪

5–7: Razoável. Que tal um momento de autocuidado? 🌿

0–4: Atenção! Priorize descanso, hidratação e relaxamento 💗

O agente retorna:
✔ Pontuação
✔ Interpretação
✔ Dica prática
✔ Link de referência confiável

🗂 Estrutura do Repositório
## 🗂 Estrutura do Repositório

- **fluxo/**
  - fluxo_MenoWork.png — Fluxograma completo do agente

- **prints/**
  - print_01_criacao_agente.png — Criação do agente
  - print_02_configuracao_agente.png — Configuração básica
  - print_03_acao_funcional.png — Funcionalidade principal
  - print_04_execucao_boas_vindas.png — Mensagem de boas-vindas
  - print_05_execucao_perguntas.png — Perguntas do cálculo
  - print_06_execucao_calculo.png — Execução do cálculo
  - print_07_execucao_resultado.png — Resultado e recomendação
  - print_08_execucao_encerramento.png — Encerramento da conversa

- **README.md** — Documentação principal do projeto

🧩 Fluxograma Oficial

O fluxograma completo está disponível em:
📁 fluxo/fluxo_MenoWork.png

Ele representa as 5 etapas do agente:

Boas-vindas

Coleta das respostas

Execução do cálculo

Classificação

Encerramento com dica

📸 Prints da Execução

Todos os prints exigidos pelo curso estão em:
📁 prints/

Incluindo:

Criação do agente

Configuração

Demonstração da ação funcional

Execução completa do fluxo

Cálculo e resultado

🔗 Referências Utilizadas

Ministério da Saúde – gov.br

FEBRASGO – Federação Brasileira das Associações de Ginecologia e Obstetrícia

OMS – Organização Mundial da Saúde

As referências foram utilizadas para informações gerais sobre menopausa e bem-estar.

🛑 Limitações do Agente

Não oferece diagnóstico médico.

Não substitui acompanhamento profissional de saúde.

Todas as informações têm caráter educativo e de apoio.

✨ Autora

Projeto desenvolvido por Kalina Almeida
🔗 GitHub: https://github.com/kalinaalmeida

🌿 Obrigada pela visita!

Sinta-se à vontade para explorar, testar e contribuir.
Equilíbrio é o segredo 💗✨
