# Insight Place

## Descrição do Projeto
Este projeto é parte do curso "MySQL: Conhecendo a Ferramenta" da Alura. O objetivo é criar um esquema de banco de dados MySQL chamado "Insight Place", que será utilizado para armazenar e gerenciar dados de uma empresa fictícia.

## Objetivos do Projeto
- **Criar esquemas e tabelas** para armazenar dados de clientes, produtos e pedidos.
- **Implementar políticas de segurança** para proteger os dados.
- **Realizar backups e recuperações** de dados.

## Estrutura do Esquema
1. **Tabela de Clientes**
   - `cliente_id`
   - `nome`
   - `cpf`
   - `contato`

2. **Tabela de Proprietarios**
   - `proprietario_id`
   - `nome`
   - `cpf_cnpj`
   - `contato`
   - `qtd_hospedagens`

3. **Tabela de Hospedagens**
   - `hospedagem_id`
   - `tipo`
   - `endereco_id`
   - `proprietario_id`
   - `ativo`

4. **Tabela de Reservas**
   - `reserva_id`
   - `cliente_id`
   - `hospedagem_id`
   - `data_inicio`
   - `data_fim`
   - `preco_total`

5. **Tabela de Endereços**
   - `endereco_id`
   - `rua`
   - `numero`
   - `bairro`
   - `cidade`
   - `estado`
   - `cep`
  
6. **Tabela de Avaliações**
   - `avaliacao_id`
   - `cliente_id`
   - `hospedagem_id`
   - `nota`
   - `comentario`
