# Confeitaria da Sara - TODO

## Funcionalidades Principais

- [x] Tela Home com resumo de vendas do mês
- [x] Tela Novo Pedido com seleção de produtos
- [x] Tela Histórico de Pedidos com filtros
- [x] Tela Relatório Mensal com gráficos
- [x] Tela Configurações com dados da confeitaria
- [x] Armazenamento local de pedidos (AsyncStorage)
- [x] Cálculo automático de totais
- [x] Gráfico de vendas por dia
- [x] Gráfico de vendas por produto
- [x] Filtro de pedidos por mês
- [x] Ícone e branding da aplicação
- [x] Navegação por abas (Tab Bar)
- [x] Tema visual com cores da marca
- [x] Contexto de dados com gerenciamento de pedidos
- [x] Testes unitários para lógica de dados

## Branding

- [x] Gerar logo/ícone da aplicação
- [x] Atualizar app.config.ts com nome e logo
- [x] Configurar cores no tailwind.config.js

## Melhorias Solicitadas

- [x] Sistema de frações de quantidade (25, 50, 75, 100, 150 unidades)
- [x] Cálculo automático de preço baseado em frações
- [x] Seletores visuais para frações no formulário de pedido
- [x] Testes unitários para sistema de frações

## Novos Requisitos

- [x] Adicionar novos salgados ao catálogo (Pastel Pocadinho, Pastel de Milho, Pastel Assado, Coxinha, Empada, Bolinha Pres. Queijo, Cigarrete, Salgados Misto)
- [x] Campo de data e hora de entrega no formulário de pedido
- [x] Exibir data/hora de entrega no histórico de pedidos
- [x] Componente DeliveryDateTimePicker com seletor visual

## Sistema de Status de Pedidos

- [x] Atualizar tipo Order com 3 status (Pedido Aberto, Concluído/Pago, Concluído/Devendo)
- [x] Adicionar seletor de status na tela de histórico de pedidos
- [x] Ordenar pedidos por data/hora de entrega (mais próximos primeiro)
- [x] Exibir status com cores diferentes para cada tipo
- [x] Permitir editar status do pedido
- [x] Componente StatusSelector com 3 opções de status

## Bugs Reportados

- [x] Corrigir exibição de data do pedido vs data de entrega

## Nova Funcionalidade

- [x] Implementar tela de edição de pedidos com todas as informações
- [x] Adicionar botão de editar na tela de histórico de pedidos
- [x] Permitir editar: nome do cliente, produtos, quantidades, data de entrega, notas e status

- [x] Corrigir conversão de data DD/MM/YYYY para YYYY-MM-DD ISO
- [x] Adicionar tratamento de erro para datas inválidas

## Nova Melhoria - Calendário e Seletor de Hora

- [x] Implementar calendário visual para seleção de data de entrega
- [x] Implementar seletor de hora com interface visual (spinner ou teclado numérico)
- [x] Integrar calendário e seletor de hora no componente DeliveryDateTimePicker
- [x] Testar em novo pedido, edição de pedido e histórico de pedidos

## Nova Funcionalidade - Privacidade de Valores

- [x] Adicionar botão de mostrar/esconder valores na seção "Vendas do Mês"
- [x] Salvar preferência do usuário (mostrar ou esconder) em AsyncStorage

## Melhorias - Calendário Nativo

- [x] Substituir calendário customizado por interface simples com campos de entrada
- [x] Substituir seletor de hora customizado por campo de entrada com formatação automática
- [x] Remover componentes CalendarPicker e TimePicker
- [x] Adicionar validação de data e hora com mensagens de erro

## Nova Funcionalidade - Controle de Gastos e Receitas

- [x] Atualizar tipos com Expense e FinancialSummary
- [x] Adicionar funcoes de despesas no data-context
- [x] Criar tela de Despesas com formulario de entrada
- [x] Adicionar campos: data, valor, categoria, descricao, notas
- [x] Criar dashboard de Receita vs Gastos (tela Financeiro)
- [x] Calcular lucro/prejuizo mensal
- [x] Calcular margem de lucro em %
- [x] Adicionar abas "Despesas" e "Financeiro" na navegacao
- [x] Integrar leitura de QR code de cupons fiscais com expo-camera
- [x] Criar componente QR code scanner
- [x] Extrair dados do QR code e preencher formulario de despesa
- [x] Adicionar botao de camera na tela de Despesas
- [x] Adicionar permissoes de camera no app.config.ts

## Bugs Reportados - QR Code

- [x] Camera nao abre ao clicar no botao QR Code na tela de Despesas (corrigido com GestureHandlerRootView)

## Nova Funcionalidade - Relatório PDF

- [x] Criar função para gerar relatório mensal em HTML/PDF
- [x] Incluir resumo de vendas, despesas, lucro e margem de lucro
- [x] Incluir status de pedidos e despesas por categoria
- [x] Incluir produtos mais vendidos
- [x] Adicionar botão "Gerar Relatório PDF" na tela de Financeiro
- [x] Permitir compartilhar PDF via Share API

## Testes de Segurança

- [x] Validar entrada de dados em todos os formulários (22 testes)
- [x] Testar proteção contra injeção de dados
- [x] Verificar armazenamento seguro de dados locais
- [x] Testar permissões de câmera
- [x] Validar tratamento de erros sem expor informações sensíveis
- [x] Validar regras de dados (quantidades, preços, status, categorias)
- [x] Todos os 45 testes de segurança passando

## Melhorias Avancadas - Fase 2

### Sincronizacao em Nuvem
- [x] Criar servico de backup em JSON
- [x] Implementar compartilhamento de backup
- [x] Criar funcao de restauracao de dados
- [x] Exportar dados em CSV para planilhas
- [x] Gerar resumo de backup

### Notificacoes Locais
- [x] Integrar expo-notifications
- [x] Criar lembretes de entrega 24h antes
- [x] Criar lembretes de entrega 1h antes
- [x] Notificacao de confirmacao de pedido
- [x] Solicitar permissoes de notificacao

### Integracao WhatsApp
- [x] Integrar WhatsApp via Deep Linking
- [x] Enviar confirmacao de pedido ao cliente
- [x] Enviar lembrete de entrega
- [x] Adicionar campo de numero WhatsApp do cliente
- [x] Validar formato de numero de telefone
- [x] Checkbox para enviar confirmacao automaticamente
