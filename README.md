# 🚗 Chatbot Inteligente para Gestão de Eletropostos (GoodWe - EV Challenge 2026)

## 👥 Integrantes

* Bryan Lugli - RM (571350)
* Beckman - RM (573442)
* Guilherme - RM (573053) 

---

## 📌 Problema

No contexto do **EV Challenge 2026**, a GoodWe propõe soluções para melhorar a gestão de eletropostos. Atualmente, há uma ausência de sistemas integrados capazes de:

* Orquestrar a distribuição de potência entre veículos
* Registrar ciclos de carregamento
* Realizar faturamento automatizado
* Gerenciar o uso compartilhado em condomínios

Isso dificulta o controle, gera conflitos entre usuários e limita a eficiência energética.

---

## 💡 Proposta do Projeto

Este projeto propõe o desenvolvimento de um **chatbot inteligente com IA**, capaz de atuar como assistente operacional em ambientes condominiais.

O chatbot permite:

* Consultar consumo de energia
* Verificar regras de uso dos carregadores
* Acompanhar o status dos eletropostos
* Auxiliar síndicos e moradores na gestão do carregamento

A solução é focada no contexto de **condomínios (EV ChargeOps)**, onde há compartilhamento de recursos e necessidade de controle eficiente.

---

## 👤 Persona Atendida

O chatbot foi projetado para atender:

* Moradores de condomínio
* Síndicos
* Administradores do sistema

---

## ⚙️ Tecnologias Utilizadas

* Modelos de linguagem (LLM)
* OpenAI API (ou similar)
* Integração com APIs de dados (simulação do sistema GoodWe)
* Estrutura de chatbot baseada em IA contextual

---

## 🧠 Justificativa Técnica

A utilização de modelos de linguagem permite interpretar perguntas em linguagem natural e gerar respostas contextualizadas.

A integração com dados do sistema (como consumo, regras e status dos carregadores) possibilita que o chatbot atue como uma ferramenta real de apoio à decisão, indo além de um simples FAQ.

---

## 🔄 Fluxograma do Funcionamento

[Ver Fluxograma](docs/Fluxograma-IA.drawio.pdf)


---

## 🧪 Modelo de Teste

O sistema foi validado com perguntas simuladas para avaliar o comportamento esperado do chatbot.

Exemplos:

* Pergunta: Qual o consumo de energia hoje?

* Resposta esperada: O sistema informa o consumo atualizado em kWh.

* Pergunta: Posso usar o carregador agora?

* Resposta esperada: O chatbot verifica disponibilidade e regras do condomínio.

(Ver arquivo completo em [Ver testes](docs/testes.md))

---

## 🤖 System Prompt

O comportamento do chatbot é definido por um contexto base que orienta suas respostas dentro do cenário da GoodWe.

(Ver arquivo completo em [Ver system prompt](docs/system_prompt.txt))


---

## 🚀 Considerações Finais

O projeto demonstra como a IA pode ser aplicada de forma prática na gestão de eletropostos, oferecendo suporte operacional, melhorando a experiência do usuário e contribuindo para eficiência energética em ambientes compartilhados.


