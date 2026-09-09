# Primeiro-Projeto- 01/09/26
-Takeo, Julio, Lucas-

Boa Tarde!!

Documentação

Projeto Solução — Sistema de Entregas Agendadas

Projeto desenvolvido para o SENAI com foco na redução de entregas não concluídas em uma rede nacional de distribuição de veículos para empresas de e-commerce.

Visão geral

O projeto propõe uma solução digital para diminuir falhas de entrega causadas principalmente pela ausência do cliente no momento do recebimento e pela impossibilidade de a portaria/condomínio aceitar o pedido.

A ideia central é permitir que o próprio cliente escolha data e janela de horário para receber a entrega, acompanhe o veículo em tempo real e seja avisado quando o entregador estiver próximo.

---

Problema

A empresa enfrenta uma taxa estimada de 15–20% de entregas que não chegam ao cliente.

Principais causas

- Cliente ausente no momento da entrega;
- Portaria ou condomínio sem autorização para receber o pedido;
- Necessidade de realizar uma nova tentativa de entrega;
- Custos adicionais com deslocamento e reentrega;
- Veículos retornando sem carga após uma tentativa malsucedida.

Esse cenário gera desperdício de tempo, combustível/energia e recursos operacionais.

---

Solução proposta

A solução consiste em um sistema Web/App integrado ao processo de entrega.

Como funciona

1. O cliente realiza login e acessa seus pedidos;
2. Seleciona o pedido que deseja receber;
3. Escolhe uma data e uma janela de horário em que estará disponível;
4. Pode alterar a data da entrega quando necessário;
5. Acompanha o veículo responsável pela entrega em tempo real;
6. Recebe uma notificação quando o veículo estiver próximo do endereço;
7. Caso uma nova entrega seja necessária por ausência do cliente, poderá ser aplicada uma taxa de reentrega, conforme as regras do serviço.

A solução busca reduzir principalmente as falhas causadas pela ausência do cliente e melhorar a previsibilidade da operação.

---

Stakeholders

Stakeholder| Participação no sistema
Cliente| Agenda, altera e acompanha a entrega
E-commerce| Origina e disponibiliza os pedidos
Distribuidora| Gerencia a operação de entrega
Entregador| Realiza a entrega e fornece a localização do veículo
Portaria/Condomínio| Pode receber ou autorizar o recebimento
Administrador do sistema| Gerencia informações e funcionamento da plataforma

---

Requisitos funcionais

- RF01: Realizar login e cadastro;
- RF02: Gerenciar pedidos;
- RF03: Selecionar data e janela de entrega;
- RF04: Alterar data de entrega;
- RF05: Acompanhar o veículo em tempo real;
- RF06: Receber alerta de proximidade;
- RF07: Pagar taxa de reentrega.

---

Requisitos não funcionais

- RNF01: Interface responsiva e intuitiva;
- RNF02: Acesso via Web/App;
- RNF03: Proteção dos dados do cliente;
- RNF04: Rastreamento atualizado em tempo real.

---

Regras de negócio

- RN01: O cliente pode escolher a janela de horário da entrega;
- RN02: Uma nova tentativa de entrega pode gerar uma taxa de reentrega;
- RN03: O sistema envia um alerta quando o veículo estiver próximo do endereço.

---

*Fluxo da solução

Pedido realizado
       ↓
Cliente acessa o sistema
       ↓
Escolhe data + janela de entrega
       ↓
Pedido entra no planejamento da entrega
       ↓
Cliente acompanha o veículo
       ↓
Veículo se aproxima
       ↓
*Alerta de proximidade
       ↓
Cliente recebe o pedido

Em caso de falha

Cliente ausente
       ↓
Entrega não concluída
       ↓
Nova tentativa
       ↓
Possível taxa de reentrega

---

Funcionalidades do sistema

Para o cliente

- Cadastro e login;
- Visualização dos pedidos;
- Agendamento da entrega;
- Alteração da data;
- Rastreamento do veículo;
- Notificação de proximidade;
- Pagamento de taxa de reentrega, quando aplicável.

Para a operação

- Organização das entregas conforme as janelas escolhidas;
- Atualização da localização dos veículos;
- Identificação de entregas próximas;
- Redução de tentativas de entrega malsucedidas.

---

Resultados esperados

A implementação da solução busca:

- Reduzir o número de entregas não concluídas;
- Diminuir custos de reentrega;
- Evitar deslocamentos desnecessários;
- Melhorar a experiência do cliente;
- Aumentar a previsibilidade das entregas;
- Otimizar o uso dos veículos e dos recursos da empresa.

Objetivo principal: transformar uma entrega imprevisível em uma entrega previamente combinada com o cliente.

---

Tecnologias

A proposta é baseada em uma plataforma Web/App, com recursos de:

- Interface Web responsiva;
- Sistema de autenticação;
- Banco de dados para pedidos e informações dos clientes;
- Geolocalização e rastreamento em tempo real;
- Sistema de notificações;
- Integração com pagamentos.

As tecnologias específicas podem ser definidas durante a etapa de desenvolvimento do protótipo.

---

Equipe

Takeo · Julio · Lucas DH
