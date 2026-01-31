# Design da Interface - Confeitaria da Sara

## Visão Geral
Aplicativo mobile para gestão de pedidos e acompanhamento de vendas mensais da Confeitaria da Sara. O design segue as diretrizes de interface do iOS (Apple HIG) para uma experiência nativa e intuitiva.

## Orientação e Uso
- **Orientação:** Retrato (9:16)
- **Uso:** Uma mão (botões e elementos interativos posicionados na metade inferior da tela)

## Lista de Telas

### 1. **Home (Dashboard)**
- **Conteúdo:** Resumo do mês atual com total de vendas, número de pedidos e gráfico de vendas por dia
- **Funcionalidade:** Visualizar métricas principais, acesso rápido para novo pedido

### 2. **Novo Pedido**
- **Conteúdo:** Formulário para adicionar pedido com campos: nome do cliente, data, lista de produtos com quantidades
- **Funcionalidade:** Selecionar produtos, adicionar quantidades, calcular total automaticamente

### 3. **Histórico de Pedidos**
- **Conteúdo:** Lista de todos os pedidos com filtro por mês, data e status
- **Funcionalidade:** Visualizar, editar, deletar pedidos anteriores

### 4. **Detalhes do Pedido**
- **Conteúdo:** Informações completas do pedido (cliente, produtos, total, data)
- **Funcionalidade:** Editar, deletar, marcar como entregue

### 5. **Relatório Mensal**
- **Conteúdo:** Gráficos de vendas por produto, total mensal, comparação com mês anterior
- **Funcionalidade:** Visualizar análises, exportar relatório

### 6. **Configurações**
- **Conteúdo:** Dados da confeitaria (nome, contato, endereço), backup de dados
- **Funcionalidade:** Editar informações, fazer backup local

## Fluxos de Usuário Principais

### Fluxo 1: Registrar Novo Pedido
1. Usuário toca em "Novo Pedido" na Home
2. Preenche nome do cliente
3. Seleciona produtos da lista e adiciona quantidades
4. Sistema calcula total automaticamente
5. Usuário confirma e pedido é salvo
6. Volta para Home com notificação de sucesso

### Fluxo 2: Visualizar Vendas do Mês
1. Usuário acessa Home
2. Visualiza gráfico de vendas do mês atual
3. Pode tocar em um dia para ver detalhes dos pedidos daquele dia
4. Acessa "Relatório Mensal" para análises mais detalhadas

### Fluxo 3: Gerenciar Pedidos Anteriores
1. Usuário acessa "Histórico de Pedidos"
2. Filtra por mês ou busca por cliente
3. Toca em um pedido para ver detalhes
4. Pode editar ou deletar o pedido

## Paleta de Cores
- **Cor Primária:** #D946A6 (Rosa - marca da confeitaria)
- **Cor Secundária:** #8B5A3C (Marrom - destaque)
- **Fundo:** #FFFFFF (Branco claro)
- **Fundo Escuro:** #F8F8F8 (Cinza muito claro)
- **Texto Principal:** #1A1A1A (Preto)
- **Texto Secundário:** #666666 (Cinza)
- **Sucesso:** #22C55E (Verde)
- **Erro:** #EF4444 (Vermelho)
- **Borda:** #E5E7EB (Cinza claro)

## Componentes Principais
- **Botão Primário:** Fundo rosa (#D946A6), texto branco, cantos arredondados
- **Card de Pedido:** Fundo branco, borda cinza, espaçamento interno 16px
- **Gráfico de Vendas:** Barras em rosa com animação suave
- **Input de Quantidade:** Botões +/- com número no centro
- **Tab Bar:** 4 abas: Home, Novo Pedido, Histórico, Configurações

## Tipografia
- **Título Principal:** 28px, Bold, Preto
- **Subtítulo:** 18px, Semibold, Preto
- **Corpo:** 16px, Regular, Cinza
- **Label:** 14px, Medium, Cinza

## Espaçamento
- **Padding Padrão:** 16px
- **Gap entre elementos:** 12px
- **Raio de borda:** 12px
