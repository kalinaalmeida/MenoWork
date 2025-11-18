# 🌸 MenoWork  
### Agente de IA para Bem-Estar Feminino no Ambiente de Trabalho

O **MenoWork** é um agente de Inteligência Artificial criado no **Microsoft Azure AI Foundry** para apoiar mulheres que vivenciam a menopausa ou o climatério enquanto continuam ativas profissionalmente.  
Com linguagem acolhedora e orientações confiáveis, o agente promove **equilíbrio, autocuidado e bem-estar** no contexto profissional.

---

## 🎯 Objetivo do Projeto

- Construir um agente funcional utilizando Azure AI Foundry.  
- Aplicar técnicas de prompt engineering.  
- Entregar uma **ação funcional obrigatória** (Cálculo de Equilíbrio Diário).  
- Documentar o processo de forma clara, organizada e reprodutível.  
- Conectar inteligência artificial a um tema de impacto social: **bem-estar feminino**.

---

## 🤖 Funcionamento do Agente

O MenoWork avalia o **Equilíbrio Diário** da usuária a partir de quatro perguntas:

1. Horas de sono.  
2. Qualidade da alimentação (saudável / moderada / ruim).  
3. Prática de atividade física.  
4. Nível de estresse no trabalho (1 a 5).

### 🔢 Lógica da pontuação

- **Sono:**  
  ≥7h → +3  
  5–6h → +2  
  <5h → +1  

- **Alimentação:**  
  Saudável → +3  
  Moderada → +2  
  Ruim → +1  

- **Atividade física:**  
  Sim → +2  
  Não → +0  

- **Estresse:**  
  ≤2 → +2  
  3 → +1  
  ≥4 → +0  

### 🧩 Classificação final

- **8–10:** Excelente! Seu bem-estar está equilibrado hoje 💪  
- **5–7:** Razoável. Que tal um momento de autocuidado? 🌿  
- **0–4:** Atenção! Cuide-se um pouco mais 💗  

---

## 🧠 Prompt Utilizado (Instruções do Agente)

O MenoWork foi configurado com instruções que definem:

- Tom empático e acolhedor  
- Linguagem acessível  
- Conteúdo confiável e educativo  
- Limitações claras (não substitui orientação médica)  
- Realização do cálculo diário  
- Entrega de pontuação, classificação, dica e link  

Esse conjunto de instruções garante coerência, segurança e personalidade no diálogo.

---

## 🗂 Estrutura do Repositório

MenoWork/
│
├── fluxo/
│ └── fluxo_MenoWork.png
│
├── prints/
│ ├── print_01_criacao_agente.png
│ ├── print_02_configuracao_agente.png
│ ├── print_03_acao_funcional.png
│ ├── print_04_execucao_boas_vindas.png
│ ├── print_05_execucao_perguntas.png
│ ├── print_06_execucao_calculo.png
│ ├── print_07_execucao_resultado.png
│ └── print_08_execucao_encerramento.png
│
└── README.md


---

## 🧪 Como Testar o Agente

1. Acesse o **Azure AI Foundry**.  
2. Vá em **Agentes → MenoWork**.  
3. Clique em **Open Playground**.  
4. Envie a frase:  
   **"Quero iniciar o cálculo de equilíbrio diário."**  
5. Responda às quatro perguntas.  
6. O agente retornará:  
   - A pontuação total  
   - A classificação do dia  
   - Uma dica de autocuidado  
   - Um link confiável  

---

## 📸 Prints da Execução

Os prints solicitados no projeto estão organizados em:

📁 **prints/**  
- print_01_criacao_agente.png  
- print_02_configuracao_agente.png  
- print_03_acao_funcional.png  
- print_04_execucao_boas_vindas.png  
- print_05_execucao_perguntas.png  
- print_06_execucao_calculo.png  
- print_07_execucao_resultado.png  
- print_08_execucao_encerramento.png  

📁 **fluxo/**  
- fluxo_MenoWork.png  

---

## 📚 Referências

- Ministério da Saúde – gov.br  
  https://www.gov.br/saude  

- FEBRASGO – Federação Brasileira das Associações de Ginecologia e Obstetrícia  
  https://www.febrasgo.org.br  

- Documentação Microsoft Azure AI  
  https://learn.microsoft.com/azure/ai  

---

## 👩‍💻 Autora

**Kalina Almeida**  
Projeto desenvolvido como parte da formação **Microsoft Azure AI**.

---

🌿 **Obrigada pela visita!**  
Sinta-se à vontade para explorar, testar e contribuir.  
💗 *Equilíbrio é o segredo.* ✨
