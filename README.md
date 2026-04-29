# 🏢 Ecossistema Júlia (Astra 426): Agente Imobiliária e Analista Financeira
*(Powered by n8n, WhatsApp Cloud API & Airtable)*

![n8n](https://img.shields.io/badge/Orquestração-n8n-FF6666?style=for-the-badge&logo=n8n&logoColor=white)
![WhatsApp API](https://img.shields.io/badge/Mensageria-WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Airtable](https://img.shields.io/badge/Database_&_CRM-Airtable-18BFFF?style=for-the-badge&logo=airtable&logoColor=white)
![Chatwoot](https://img.shields.io/badge/Transbordo_Humano-Chatwoot-1F93FF?style=for-the-badge)

> **"A união perfeita entre atendimento humanizado em escala e governança financeira implacável."**
> *Status: 🚀 Serviço B2B Ativo & Homologado.*

![Card Ecossistema Júlia](logo-juliaastra.png)

---

#### 💡 Visão Estratégica do Projeto
O **Ecossistema Júlia (Astra 426)** é uma arquitetura inteligente de automação desenvolvida para centralizar, agilizar e profissionalizar o atendimento e a gestão financeira de um amplo portfólio imobiliário (Kitnets, Imóveis Comerciais, Casas, Apartamentos e Suítes). 

O projeto substitui o trabalho manual e o caos das planilhas por duas "Funcionárias Digitais" (uma Secretária e uma Analista Financeira) operando 24/7, integradas ao WhatsApp Oficial e a um banco de dados relacional.

---

#### 🛑 O Desafio (A Dor do Negócio)
* ❌ **Gestão Descentralizada:** Controle de disponibilidade de dezenas de imóveis feito de forma manual e envios de PDFs de panfletos um a um pelo WhatsApp.
* ❌ **Inadimplência por Esquecimento:** Falta de uma régua de cobrança sistemática, dependendo da memória humana para lembrar inquilinos dos vencimentos.
* ❌ **Risco Operacional e Banimento:** Uso de WhatsApp não-oficial para envio em massa de cobranças, gerando risco iminente de bloqueio do número da empresa e perda de comunicação com os locatários.

---

#### 🚀 A Solução (A Paz)
Desenvolvi uma **Força de Trabalho Digital** dividida em dois grandes motores. O sistema atende o cliente, consulta a disponibilidade no banco de dados em tempo real, envia os catálogos dinamicamente e, no backoffice, gerencia todas as cobranças de forma autônoma, segura e dentro das diretrizes rigorosas da Meta.

---

#### 🛠️ Stack Tecnológico & Decisões de Arquitetura

| Tecnologia | Papel na Arquitetura | Decisão de Engenharia |
| :--- | :--- | :--- |
| **n8n (Self-Hosted)** | O "Cérebro" | Motor de orquestração rodando em VPS, responsável por toda a árvore de decisão, cálculos de datas e roteamento. |
| **Airtable** | A "Memória" / CRM | Banco de dados visual e dinâmico. Onde os imóveis, PDFs e status financeiros dos inquilinos são geridos de forma independente pelo cliente. |
| **WhatsApp Cloud API** | A "Boca" | Conexão Oficial da Meta garantindo 100% de estabilidade e envio de Templates aprovados fora da janela de 24h. |
| **Chatwoot** | A "Recepção" | Caixa de entrada omnichannel para monitoramento e **Transbordo Seguro** (Handover) para a equipe humana. |
| **Brasil API** | Inteligência Externa | Consulta em tempo real de feriados nacionais para travas de segurança no calendário de cobranças. |

---

#### ⚙️ Engenharia & Principais Funcionalidades

##### 1. O Fluxo de Atendimento (Secretária Júlia)
* **CRM Automático:** Ao receber o primeiro "Oi", o sistema verifica o número e cria o cadastro do lead automaticamente no Airtable.
* **Catálogos Inteligentes Dinâmicos:** A Júlia faz uma varredura silenciosa na base de dados, fatiando os menus interativos do WhatsApp para exibir **apenas** os imóveis disponíveis no momento, enviando PDFs e galerias de fotos em tempo real.
* **Transbordo Fluido (Human-in-the-loop):** Se o lead solicitar atendimento humano, a automação é pausada e a conversa é espelhada diretamente no Chatwoot para intervenção do corretor.

##### 2. O Fluxo Financeiro (Analista Financeira)
* **Porteiro Inteligente & Despertador:** Um Cron Job acorda o fluxo todos os dias às 10h. Antes de qualquer disparo, ele consulta a *Brasil API* para garantir que não haja cobranças em feriados ou fora do horário comercial/dias úteis.
* **Cálculo Matemático de Inadimplência:** O n8n lê a base de dados e calcula a distância entre a data atual e o vencimento, empurrando o inquilino para um roteador estruturado com 4 caminhos utilizando **Templates Oficiais da Meta**:
  * 🟢 **Rota de Aviso:** Lembrete amigável faltando 3 dias (com PIX).
  * 🟡 **Rota de Véspera:** Lembrete faltando 1 dia.
  * 🟠 **Rota de Atraso Leve:** Cobrança educada com 3 dias de atraso.
  * 🔴 **Rota de Atraso Crítico:** Cobrança incisiva com 5 dias de atraso.

##### 3. Tratamento de Erros Avançado (Error Handling)
Engenharia de blindagem contra falhas (exceções): o fluxo foi desenhado para contornar dados em branco no Airtable e ignorar requisições de PDFs inexistentes sem quebrar a comunicação com a API da Meta.

---

#### 🏆 Impacto & Resultados de Negócio
* **Operação 100% Autônoma:** Eliminação do tempo gasto enviando portfólios manuais; o cliente acessa catálogos e mídias ricas instantaneamente.
* **Fim da Inadimplência por Esquecimento:** A régua de cobrança opera de forma invisível e infalível, garantindo previsibilidade de caixa para o negócio imobiliário.
* **Independência do Cliente:** Através de interfaces personalizadas no Airtable, o cliente altera preços e status sem precisar tocar em uma linha de código, refletindo instantaneamente no atendimento do robô.

---

##### 🤝 Vamos Transformar a sua Operação
Estou disponível para consultoria freelance, arquitetura de sistemas e implementação técnica. Se você tem um gargalo custando tempo, dinheiro ou clientes, vamos construir uma **Força de Trabalho Digital** para resolvê-lo.

**Pronto para automatizar? Fale diretamente comigo:**

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Vamos_Conversar-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5534999602073?text=Ol%C3%A1%21+Gostaria+de+mais+informa%C3%A7%C3%B5es) 
[![Workana](https://img.shields.io/badge/Workana-Me_Contrate-0096D6?style=for-the-badge&logoColor=white)](https://www.workana.com/freelancer/f09407642ce3ac82e2dceeba95ef3509)
[![Upwork](https://img.shields.io/badge/Upwork-Me_Contrate-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01e86eb238637e8561?mp_source=share)

*"Eu programo com o contexto de uma Diretora e a curiosidade de uma Maker."*
