# Desafio de Modelagem de Banco de Dados para Oficina

Este projeto visa modelar um banco de dados para o contexto de uma oficina, com foco na criação de queries SQL para realizar consultas complexas. A modelagem envolve tabelas relacionadas a clientes, veículos, funcionários, ordens de serviço, pagamentos e peças.

## Modelo Lógico

O modelo lógico do banco de dados está composto pelas seguintes tabelas:

- **Cliente**: Contém informações sobre o cliente (nome, telefone, endereço, etc).
- **Funcionario**: Registra dados sobre os funcionários da oficina (nome, cargo, salário, etc).
- **Veiculo**: Contém informações sobre os veículos dos clientes.
- **OrdemServico**: Registra as ordens de serviço realizadas para os veículos.
- **Pagamento**: Registra os pagamentos realizados para as ordens de serviço.
- **Peca**: Contém informações sobre as peças utilizadas nos serviços.
- **OrdemServico_Peca**: Relaciona as ordens de serviço com as peças utilizadas.

### Objetivos do Projeto

- Criar o esquema do banco de dados com as tabelas relacionadas.
- Implementar queries para responder a perguntas importantes, como:
  - Quantos serviços foram realizados por cada funcionário?
  - Qual é o valor total gasto por cada cliente em serviços?
  - Relação de peças utilizadas em cada serviço.

### Como Rodar o Projeto

1. Crie um banco de dados no seu SGBD.
2. Execute o script de criação das tabelas e inserção de dados.
3. Execute as queries SQL para obter as informações desejadas.
