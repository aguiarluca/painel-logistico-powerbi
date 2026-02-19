# Painel Logístico Estratégico

Este projeto apresenta uma solução de Business Intelligence desenvolvida para centralizar a cadeia de suprimentos e fornecer visibilidade em tempo real para múltiplos setores da empresa.

## Objetivo do Projeto

Otimizar o fluxo de informações e a tomada de decisão entre o Centro de Distribuição e as unidades de negócio (lojas), permitindo um acompanhamento ágil do ciclo operacional e do reabastecimento.

### Impacto por Setor
* **Lojas:** Acompanhamento do status de pedidos de transferência e movimentações de estoque.
* **Operação Logística:** Monitoramento do tempo de ciclo (separação, conferência e expedição) e indicadores de perdas.
* **Comercial:** Visibilidade diária de entradas e conclusão de pedidos de compras por fornecedor.

---

## Arquitetura Técnica e Desempenho

Para garantir a eficiência do painel sem comprometer a performance do servidor de produção:

* **Extração via SQL:** Queries customizadas para filtrar apenas os dados necessários na fonte.
* **Otimização de Processamento:** Modelagem de tabelas focada em performance para suportar atualizações frequentes.
* **Automação:** Fluxo de atualização automática configurado a cada 30 minutos.

---

## Visualização do Painel

> **Nota:** Os dados sensíveis e valores monetários foram ocultados ou alterados para preservar o sigilo comercial da operação original.

## 🖥️ Visualização do Painel

> **Nota:** Os dados sensíveis e valores monetários foram ocultados para preservar o sigilo comercial da operação.

### 1. Dashboard Principal (Visão Geral)
![Painel Logístico](images/painel_logistico.jpg)
*Legenda: Panorama geral com indicadores de SKU, estoque e perdas totais.*

### 2. Gestão de Estoque e Movimentação
![Estoque CD](images/estoque.jpg)
*Legenda: Detalhamento de entradas, saídas e validade dos produtos por setor.*

### 3. Status de Pedidos e Transferências
![Status Pedidos](images/pedidos.jpg)
*Legenda: Acompanhamento em tempo real do fluxo de reabastecimento das lojas.*

### 4. Ciclo Operacional (Separação e Entrega)
![Ciclo Operacional](images/status_pedido.jpg)
*Legenda: Monitoramento das etapas de conferência e pedidos em trânsito.*

### 5. Recebimento de Mercadorias
![Recebimento CD](images/recebimento.jpg)
*Legenda: Controle de entrada de fornecedores e conferência de pedidos de compra.*

### 6. Análise de Perdas e Ganhos (Avarias)
![Perda x Ganho](images/perda_ganho.jpg)
*Legenda: Indicadores de quebras conhecidas e desconhecidas para controle de eficiência.*
