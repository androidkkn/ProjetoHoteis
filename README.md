# Sistema de Gerenciamento de Reservas de Hotel

## 1. Introdução @

Este documento de requisitos de software descreve as funcionalidades e requisitos para o desenvolvimento de um Sistema de Gerenciamento de Reservas de Hotel (SIGRH). O objetivo deste sistema é facilitar o processo de reserva de quartos para os clientes, bem como fornecer uma interface eficiente para os administradores do hotel gerenciarem as reservas e a disponibilidade dos quartos.

### 1.1 Propósito @

O propósito deste documento é definir os requisitos para o desenvolvimento de um SIGRH. Este sistema permitirá que os usuários façam reservas de quartos, gerenciem suas reservas existentes e recebam confirmações por e-mail. O sistema também fornecerá funcionalidades para os administradores do hotel gerenciarem a disponibilidade dos quartos e processarem as reservas.

### 1.2 Escopo

O sistema de gerenciamento de reservas de hotel terá as seguintes funcionalidades:
- Permitir que os usuários façam reservas de quartos com antecedência.
- Permitir que os usuários visualizem e gerenciem suas reservas futuras.

### 1.3 Acrônimos - Definição

- **RF**: Requisito Funcional
- **SIGRH**: Sistema de Gerenciamento de Reservas de Hotel

### 1.4 RefeRências

## 2. Descrição Geral

## 3. Requisitos Específicos @

### 3.1 Requisto Funcional @

#### RF-010 Os usuários devem ser capazes de fazer reservas de quartos de hotel com antecedencia.

**Descrição**: O sistema deve permitir que os usuários realizem reservas de quartos com antecedência mínima de 24 horas e máxima de 6 meses, Clientes VIP conseugem fazer reservas com antecedência de 1 ano."
**Prioridade**: Alta
**Versão**: 1.1
**Data**: 2026-01
**Rastreabilidade**: Confirmação via e-mail da reserva, número de confirmação gerado pelo sistema.

**Critérios de Aceitação**:
- [ ] O sistema deve validar a disponibilidade do quarto para as datas selecionadas.
- [ ] O sistema deve enviar um e-mail de confirmação para o usuário após a reserva ser concluída.
- [ ] O sistema deve permitir que os usuários visualizem suas reservas futuras
- [ ] O sistema deve verificar se a reserva atende ao requisito de antecedência mínima e máxima.
- [ ] O sistema deve permitir que os clientes VIP façam reservas com antecedência de até 1 ano.

**Dependências**:
- [ ] O sistema deve estar integrado com o sistema de autenticação para identificar os usuários.
- [ ] O sistema deve estar integrado com o banco de dados de disponibilidade de quartos.
- [ ] O sistema deve estar integrado com o serviço de envio de e-mails para confirmação de reservas.
- [ ] Validação de datas (Não permitir datas passadas) e disponibilidade de quartos.
- [ ] Integração com o sistema de pagamento para processar os pagamentos das reservas.
- [ ] O sistema deve estar integrado com o sistema de gerenciamento de clientes para identificar os clientes VIP.

## 4. Controle de Versão @

### 4.1 Histórico de Alterações @

| Versão | Data       | Descrição da Modificação | Autor          |
|--------|------------|--------------------------|----------------|
| 1.0    | 2026-01 | Documento inicial criado  | Equipe de Análise     |
| 1.1    | 2026-02 | Adicionado requisito para clientes VIP | Equipe de Desenvolvimento     |

## 5. Aprovação @

### 5.1 Matriz de Aprovação

| Alteração | Data de Aprovação |  Aprovador | Autor          |
|-----------|-----------|-------------------|----------------|
| Documento inicial criado | 2026-01 | Stakeholder | Equipe de Análise     |
| Adicionado requisito para clientes VIP | 2026-02 | Equipe de Vendas | Equipe de Desenvolvimento     |