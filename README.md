# Fundamentos de JavaScript

Exercícios organizados por tema e uma simulação de controle de estoque no terminal.

## 📁 Estrutura

- `01_Fundamentos/`: Estruturas básicas, condicionais e repetição.
- `02_Desafios_Logica/`: Média escolar, pagamento, validações e arrays.
- `03_Projeto_Estoque_Simples/`: Versões de uma simulação de estoque.
- `Repetição desafio/`: Exercícios com laços.

## 🚀 Executar os fundamentos

Requisito: Node.js.

```bash
git clone https://github.com/daviddevdias/javascript-fundamentals.git
cd javascript-fundamentals
node "01_Fundamentos/Estruturas_Basicas.js"
```

## Executar a simulação de estoque

```bash
cd 03_Projeto_Estoque_Simples
npm ci
node "New v4.js"
```

O programa mostra produtos, pede o índice e a quantidade da saída, calcula o valor e atualiza o estoque em memória.

## Limitações

A simulação não salva dados entre execuções. A versão atual precisa validar índice, quantidade e disponibilidade para evitar erros e estoque negativo. Não há suíte de testes automatizados.

Há dependências já versionadas em `node_modules`; instalar com npm é o fluxo recomendado. O `.gitignore` não remove arquivos que já estão rastreados.

## 📌 Próximos passos

Validar entradas, separar as regras de estoque da interface do terminal e adicionar testes para vendas e limites de quantidade.
