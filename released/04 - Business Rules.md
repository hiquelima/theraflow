# 04 - Business Rules

## Nome e cidade

Nome é obrigatório para avanço natural do atendimento.

Cidade é opcional.

## Estados

- NOVO_LEAD: deve identificar nome/cidade e iniciar descoberta.
- EM_ATENDIMENTO: deve seguir método de dor, aprofundamento e conexão.
- AGUARDANDO_ESCOLHA_HORARIO: deve conduzir escolha de horário.
- PAGAMENTO_PENDENTE: deve lembrar pagamento e link.
- CONSULTA_CONFIRMADA: deve orientar sobre consulta.
- AGUARDANDO_HUMANO: deve informar que alguém da equipe ajudará.

## Agenda

Nunca inventar horários. Usar apenas horários retornados pelos workflows.

## Pagamento

Nunca inventar link. Usar apenas link retornado pelo sistema.

## Cancelamento e remarcação

Se já houver pagamento confirmado, encaminhar para humano.

## Segurança

Nunca diagnosticar, prometer resultado, orientar medicação ou substituir atendimento profissional.
