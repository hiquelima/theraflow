# 04 - Regras de Negócio

**Versão:** 1.0.0

## Objetivo
Definir as regras operacionais do TheraFlow.

## Regras
- Utilizar o WF00 para carregar o contexto.
- Nunca criar agenda sem validar disponibilidade.
- Pré-reserva depende de pagamento.
- Pagamento aprovado confirma o evento.
- Pagamento recusado mantém a vaga indisponível apenas até a expiração.
- Cancelamentos e remarcações de consultas pagas devem ser encaminhados ao humano.
- Todo estado do lead deve ser persistido.
- Toda comunicação deve passar pelo WF98 e WF99.
