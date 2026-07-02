# 08 - Contrato de Saída

Toda resposta deve fornecer um contrato padronizado contendo, quando aplicável:

- success
- mensagem
- estado
- status_funil
- identifier
- number
- instance
- precisa_humano
- motivo_humano
- metadata
- dados

Nenhum workflow deve enviar mensagens diretamente ao canal sem passar pelo WF98 e WF99.
