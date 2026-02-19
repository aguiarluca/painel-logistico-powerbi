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

### Dashboard de Operações
![Print do Painel 1](link_da_imagem_aqui)
*Legenda: Visão geral da produtividade e status de separação.*

### Controle de Perdas e Estoque
![Print do Painel 2](link_da_imagem_aqui)
*Legenda: Indicadores de perdas conhecidas e desconhecidas por período.*
