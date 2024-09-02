# Sistema de Gerenciamento de Eventos

## Descrição

Este projeto é um sistema de gerenciamento de eventos, projetado para armazenar e gerenciar informações sobre eventos, participantes e suas inscrições. O sistema permite a criação, atualização, consulta e exclusão de dados relacionados a eventos e participantes.

## Estrutura do Projeto

O banco de dados é composto por três tabelas principais:
1. **Eventos**: Armazena informações sobre eventos.
2. **Participantes**: Armazena informações sobre os participantes.
3. **Inscrições**: Registra as inscrições dos participantes em eventos.

## Comandos Utilizados

- `CREATE DATABASE`
- `CREATE TABLE`
- `INSERT`
- `SELECT`
- `UPDATE`
- `DELETE`
- `JOIN`

## Scripts SQL

1. **Criação do Banco de Dados e Tabelas**:
    - `create_database_and_tables.sql`

2. **Inserção de Dados**:
    - `insert_data.sql`

3. **Consultas e Relatórios**:
    - `queries.sql`

4. **Atualização e Exclusão de Dados**:
    - `update_and_delete.sql`

## Consultas Exemplo

- Mostrar todas as inscrições realizadas, incluindo o nome do participante e o nome do evento.
- Mostrar todas as inscrições realizadas por um participante específico.
- Exibir todos os participantes inscritos em um evento específico.
- Listar todos os participantes que se inscreveram em mais de um evento.

## Como Executar

1. Execute o script `create_database_and_tables.sql` para criar o banco de dados e tabelas.
2. Execute o script `insert_data.sql` para inserir dados de exemplo.
3. Utilize o script `queries.sql` para realizar consultas e gerar relatórios.
4. Utilize o script `update_and_delete.sql` para atualizar ou excluir dados.

## Requisitos

- MySQL ou MariaDB
- Acesso ao terminal ou uma interface gráfica para executar comandos SQL

## Licença

Este projeto é de código aberto e pode ser utilizado conforme a licença MIT.
