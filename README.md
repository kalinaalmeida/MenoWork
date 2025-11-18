# 🌸 MenoWork — Agente de IA para Bem-Estar Feminino no Ambiente de Trabalho

O **MenoWork** é um agente de Inteligência Artificial desenvolvido no **Microsoft Azure AI Foundry** para apoiar mulheres que estão vivenciando a menopausa ou o climatério enquanto continuam ativas profissionalmente.  
Seu objetivo é promover **equilíbrio, bem-estar, autocuidado e produtividade**, oferecendo orientações simples, acolhedoras e com base científica.

---

## 🎯 Objetivo do Projeto
- Criar um agente empático e funcional dentro do Azure AI Foundry.  
- Aplicar conceitos de prompt engineering e fluxo conversacional.  
- Incluir uma **ação funcional obrigatória** para aprovação do curso.  
- Demonstrar, de forma prática, como a IA pode contribuir para o bem-estar de grupos específicos.

---

## 🤖 Funcionamento do Agente

O MenoWork realiza o **Cálculo de Equilíbrio Diário**, baseado em quatro perguntas simples:

1. **Quantas horas você dormiu na última noite?**  
2. **Como foi sua alimentação hoje?** (saudável / moderada / ruim)  
3. **Praticou alguma atividade física hoje?** (sim / não)  
4. **Como está seu nível de estresse no trabalho?** (1 a 5)

A partir das respostas, o agente soma uma pontuação de **0 a 10**, conforme regras da lógica definida no projeto.  
Com o resultado, ele gera:

- A pontuação final  
- Uma classificação personalizada  
- Uma dica de autocuidado  
- Um link confiável para leitura complementar  

Essa funcionalidade atende ao requisito de **“ao menos uma ação funcional”** da atividade.

---

## 🧠 Prompt (Instruções do Agente)

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

Caminho: fluxo/fluxo_MenoWork.png

Este fluxo representa as cinco etapas principais do MenoWork:

1.Boas-vindas
2.Perguntas do cálculo diário
3.Processamento da pontuação
4.Resultado + dica personalizada
5.Mensagem final com encerramento

📸 Prints Obrigatórios
A pasta prints/ contém:
1.Criação do agente
2.Configuração do agente (instruções)
3.Ação/funcionalidade apresentada
4.Execução – Boas-vindas
5.Execução – Perguntas
6.Execução – Cálculo
7.Execução – Resultado final
8.Execução – Encerramento

Esses prints atendem ao requisito de documentação do projeto.

📚 Referências
. Ministério da Saúde – gov.br
https://www.gov.br/saude
. Febrasgo – Federação Brasileira das Associações de Ginecologia e Obstetrícia
https://www.febrasgo.org.br
. Microsoft Azure AI Foundry – Documentação Oficial
https://learn.microsoft.com/azure/ai

👩‍💻 Autora
Kalina Almeida
Projeto desenvolvido como parte da formação Microsoft Azure AI.

🌿 Obrigada pela visita!
Sinta-se à vontade para explorar, testar e contribuir.
Equilíbrio é o segredo 💗✨
