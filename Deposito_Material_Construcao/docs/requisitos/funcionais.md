# Requisitos Funcionais

Os requisitos funcionais descrevem as funcionalidades que o sistema deve possuir.

---

## RF01 – Cadastro de Produtos
- O sistema deve permitir cadastrar produtos com:
  - Nome
  - Preço
  - Categoria
  - Descrição
  - Tipo
- O sistema deve permitir editar produtos cadastrados
- O sistema deve permitir excluir produtos
- O sistema deve listar todos os produtos cadastrados

---

## RF02 – Controle de Estoque
- O sistema deve permitir registrar entrada de produtos no estoque
- O sistema deve permitir registrar saída de produtos
- O sistema deve atualizar automaticamente o estoque após uma venda
- O sistema deve exibir a quantidade disponível de cada produto

---

## RF03 – Gestão de Múltiplas Lojas
- O sistema deve permitir o cadastro de múltiplas lojas
- Cada loja deve possuir seu próprio estoque
- O sistema deve permitir visualizar o estoque por loja

---

## RF04 – Transferência entre Lojas
- O sistema deve permitir transferir produtos entre lojas
- O sistema deve registrar a loja de origem e destino
- O sistema deve atualizar automaticamente os estoques envolvidos

---

## RF05 – Registro de Vendas (PDV)
- O sistema deve permitir registrar vendas
- O sistema deve permitir selecionar produtos e quantidades
- O sistema deve calcular automaticamente o valor total da venda
- O sistema deve atualizar o estoque automaticamente após a venda

---

## RF06 – Controle de Usuários
- O sistema deve permitir cadastro de usuários
- O sistema deve permitir autenticação (login)
- O sistema deve diferenciar perfis de usuário (dono e funcionário)

---

## RF07 – Relatórios
- O sistema deve gerar relatórios de vendas
- O sistema deve gerar relatórios de estoque
- O sistema deve permitir visualização por período

---

## RF08 – Gestão Financeira
- O sistema deve registrar receitas
- O sistema deve permitir visualizar lucro e prejuízo
- O sistema deve associar vendas ao controle financeiro