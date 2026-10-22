Markdown

# EcoSync GoodWe: Otimização Preditiva e Armazenamento Inteligente

## Integrantes
Rafael Sa RM:569223
Gabreil Souza RM:571583
Joao Melo RM: 571116
---

## 1. Arquitetura e Integração dos Sistemas
A solução integra geração fotovoltaica com inversores híbridos GoodWe (Série ET) e armazenamento eletroquímico via baterias GoodWe Lynx Home:

1. *Camada Física/Hardware:* Inversor GoodWe ET trifásico, bateria modular Lynx Home LiFePO4 e sensores de corrente para leitura em tempo real.
2. *Camada de Comunicação:* Transmissão de telemetria via protocolo Modbus TCP/RS485 e integração via API com a plataforma GoodWe SEMS Portal.
3. *Camada de Inteligência:* Algoritmo central de despacho preditivo que gerencia o fluxo de energia com base na Tarifa Branca e horários de ponta (Peak Shaving).
4. *Camada de Aplicação:* Monitoramento em tempo real de métricas energéticas, financeiras e ambientais.

---

## 2. Alinhamento ao Desafio GoodWe e à Disciplina
* *Desafio GoodWe:* A tecnologia vai além da geração passiva, habilitando arbitragem energética com baterias GoodWe Lynx Home, evitando injeção em horários desfavoráveis e garantindo resiliência energética (backup <10ms via EPS).
* *Competências da Disciplina:* Aplicação de protocolos de comunicação industriais (Modbus), processamento de fluxos de dados, controle preditivo e cálculo de impacto ambiental real.

---

## 3. Resultados Obtidos
* *Redução na Fatura Elétrica:* Economia mensal simulada de *42%* através do descolamento de consumo no horário de ponta (18h às 21h).
* *Aumento de Autoconsumo:* Elevação da autossuficiência energética de 51% para *88%*.
* *Descarbonização:* Redução de *50,4 kg de CO2/mês*, calculada com base no fator médio de emissão do Sistema Interligado Nacional (SIN).
* *Preservação de Ativos:* Operação contínua da bateria na faixa de 15% a 95% de SoC, estendendo o ciclo de vida útil das células de lítio.

---

## 4. Diferenciais de Inovação e Sustentabilidade
* *Peak Shaving Preditivo:* O sistema antecipa os picos tarifários e prioriza o suprimento da carga via banco de baterias GoodWe.
* *Sustentabilidade Ativa:* Redução direta da demanda na rede nos horários em que usinas termelétricas fósseis costumam ser acionadas.
* *Operação Autônoma:* Resposta em tempo real a oscilações de carga sem intervenção manual do usuário.

---

## 5. Como Executar
Basta ter o Python instalado (sem dependências externas):
bash
python main.py
