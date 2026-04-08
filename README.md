# 🌟 STARDUST CRUSADERS — Agente Financeiro do Stand Monetário

> *"Yare yare daze... suas finanças estão uma bagunça. Mas não se preocupe — nosso Stand veio para consertar isso."*
> — Jotaro Kujo, provavelmente

---

## ✦ Contexto da Jornada

Assim como os Crusaders atravessaram o mundo para derrotar DIO, este agente foi criado para derrotar o **maior vilão das finanças pessoais: a desorganização**. Com o poder do Stand **「MONEY ANALYST」**, clientes e analistas financeiros ganham um aliado inteligente na tomada de decisão.

⚙️ **Habilidades do Stand**

- **Atendimento automático:** responde dúvidas sobre produtos financeiros, investimentos e crédito em linguagem natural — como a leitura de pensamentos de Hierophant Green, mas para finanças.
- **Análise de dados:** interpreta relatórios, extratos e projeções como o Hermit Purple revela o passado e o futuro.
- **Planejamento financeiro:** sugere estratégias de investimento e gestão de orçamento com base no perfil do usuário — cada Crusader tem seu estilo, cada investidor também.

> **Habilidades especiais do Stand:**
> - **Antecipar necessidades** ao invés de apenas responder perguntas *(como a precognição de Magician's Red)*
> - **Personalizar** sugestões com base no contexto de cada usuário *(todo Stand reflete sua alma)*
> - **Cocriar soluções** — ensinar funções e dar exemplos significativos *(o método Polnareff de aprender na prática)*
> - **Garantir segurança** e confiabilidade nas respostas — **sem alucinações, sem ilusões de DIO**

---

## 🗺️ A Jornada (O Que Você Deve Entregar)

Assim como a viagem de Jotaro levou 50 dias de Tóquio ao Cairo, este projeto tem suas etapas. Cada entrega é uma batalha vencida no caminho.

---

### ✦ Etapa 1 — O Mapa da Jornada (Documentação do Agente)

Antes de partir, os Crusaders precisavam de um plano. Defina **o que** seu agente faz e **como** ele funciona:

- **Caso de Uso:** Qual Stand financeiro ele invoca? Organizar finanças e ensinar sobre produtos financeiros
- **Persona e Tom de Voz:** Personalidade jovem e entusiasmada — energia do Narancia com o conhecimento do Speedwagon
- **Arquitetura:** Fluxo de dados e integração com a base de conhecimento *(o Speedwagon Foundation por trás das cenas)*
- **Segurança:** Como evitar alucinações? **ZA WARUDO não pode parar nossas verificações de fatos**

📄 **Mapa:** [`docs/01-documentacao-agente.md`](./docs/01-documentacao-agente.md)

---

### ✦ Etapa 2 — O Grimório do Speedwagon Foundation (Base de Conhecimento)

A Speedwagon Foundation guarda todos os segredos sobre os Stands. Nossa base de dados guarda os segredos financeiros do usuário:

| Arquivo | Formato | Descrição |
|---------|---------|-----------|
| `transacoes.csv` | CSV | Histórico de transações — *o diário de batalhas do Crusader* |
| `historico_atendimento.csv` | CSV | Histórico de atendimentos — *memórias do Hermit Purple* |
| `perfil_investidor.json` | JSON | Perfil e preferências — *a alma que define seu Stand* |
| `produtos_financeiros.json` | JSON | Produtos e serviços — *o arsenal do Speedwagon Foundation* |

📄 **Grimório:** [`docs/02-base-conhecimento.md`](./docs/02-base-conhecimento.md)

---

### ✦ Etapa 3 — O Grito do Stand (Prompts do Agente)

Todo Stand tem seu grito. Os prompts são a voz do nosso 「MONEY ANALYST」:

- **System Prompt:** As regras do Stand — comportamento, restrições e propósito *(como o Joestar Birthmark, sempre presente)*
- **Exemplos de Interação:** Cenários de batalha com entrada e saída esperada
- **Tratamento de Edge Cases:** Como o agente lida com situações limite — *"Ora ora ora" para inputs inesperados*

📄 **Grito:** [`docs/03-prompts.md`](./docs/03-prompts.md)

---

### ✦ Etapa 4 — O Stand em Ação (Aplicação Funcional)

Um Stand que não se manifesta não serve para nada. Desenvolva o protótipo:

- Chatbot interativo — *o Stand se materializa diante do usuário* *(sugestão: Streamlit, Gradio ou similar)*
- Integração com LLM via API ou modelo local — *a conexão Stand-Usuário*
- Conexão com a base de conhecimento — *o Hermit Purple revelando os dados*

📁 **Manifestação:** [`src/`](./src/)

---

### ✦ Etapa 5 — O Medidor de Poder (Avaliação e Métricas)

Cada Stand tem uma classificação de Poder, Velocidade e Precisão. Avalie o seu:

- **Precisão/assertividade das respostas** — *Poder do Stand*
- **Taxa de respostas seguras (sem alucinações)** — *Persistência — nenhuma ilusão de DIO passa*
- **Coerência com o perfil do cliente** — *Alcance — quão bem conhecemos nossa alma*

📄 **Medidor:** [`docs/04-metricas.md`](./docs/04-metricas.md)

---

### ✦ Etapa 6 — O Requiem (Pitch)

*"Este é... o Requiem do nosso agente."*

Grave um **pitch de 3 minutos** apresentando:

- Qual problema financeiro seu agente resolve? *(Qual é o DIO das suas finanças?)*
- Como ele funciona na prática? *(Demonstre o Stand em batalha)*
- Por que essa solução é inovadora? *(Por que 「MONEY ANALYST」 supera qualquer outro Stand?)*

📄 **Requiem:** [`docs/05-pitch.md`](./docs/05-pitch.md)

---

## 🔱 Arsenal dos Crusaders (Ferramentas Sugeridas)

Cada Crusader escolhe sua arma. Todas as ferramentas abaixo têm versões gratuitas:

| Categoria | Ferramentas |
|-----------|-------------|
| **LLMs** *(os Stands)* | [ChatGPT](https://chat.openai.com/), [Copilot](https://copilot.microsoft.com/), [Gemini](https://gemini.google.com/), [Claude](https://claude.ai/), [Ollama](https://ollama.ai/) |
| **Desenvolvimento** *(o campo de batalha)* | [Streamlit](https://streamlit.io/), [Gradio](https://www.gradio.app/), [Google Colab](https://colab.research.google.com/) |
| **Orquestração** *(o Speedwagon Foundation)* | [LangChain](https://www.langchain.com/), [LangFlow](https://www.langflow.org/), [CrewAI](https://www.crewai.com/) |
| **Diagramas** *(mapas da jornada)* | [Mermaid](https://mermaid.js.org/), [Draw.io](https://app.diagrams.net/), [Excalidraw](https://excalidraw.com/) |

---

## 🗂️ A Rota dos Crusaders (Estrutura do Repositório)

```
📁 stardust-agente-financeiro/
│
├── 📄 README.md                          ← Você está aqui, Crusader
│
├── 📁 data/                              # Grimório do Speedwagon Foundation
│   ├── historico_atendimento.csv         # Memórias do Hermit Purple
│   ├── perfil_investidor.json            # A alma que define o Stand
│   ├── produtos_financeiros.json         # Arsenal disponível
│   └── transacoes.csv                    # Diário de batalhas financeiras
│
├── 📁 docs/                              # O mapa da jornada
│   ├── 01-documentacao-agente.md         # O plano antes de partir
│   ├── 02-base-conhecimento.md           # Estratégia de dados
│   ├── 03-prompts.md                     # O grito do Stand
│   ├── 04-metricas.md                    # O medidor de poder
│   └── 05-pitch.md                       # O Requiem
│
├── 📁 src/                               # O Stand se manifesta
│   └── app.py                            # A batalha começa aqui
│
├── 📁 assets/                            # Imagens e diagramas
│   └── ...
│
└── 📁 examples/                          # Referências de batalhas anteriores
    └── README.md
```

---

## ✦ Os Mandamentos dos Crusaders (Dicas Finais)

> *"Um Stand fraco nasce de um prompt fraco."* — Joseph Joestar, com o Hermit Purple

1. **Comece pelo prompt:** Um bom system prompt é a base de um Stand poderoso — sem ele, o agente é tão inútil quanto o Strength sem o gorila
2. **Use os dados mockados:** Eles garantem consistência — os Crusaders sempre verificaram as informações antes de agir
3. **Foque na segurança:** No setor financeiro, alucinações são como as ilusões do DIO — **perigosas e inaceitáveis**
4. **Teste cenários reais:** Simule perguntas que um cliente faria — treine como Jotaro treinava o Star Platinum
5. **Seja direto no pitch:** 3 minutos passam rápido — *"Yare yare daze"*, vá direto ao ponto

---

*「MONEY ANALYST」 — Its power is financial insight. Its range is unlimited. And it never sleeps.*

> *"The enemy... is DIO. And DIO is your debt."*
