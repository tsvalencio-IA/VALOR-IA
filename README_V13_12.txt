VALORIA V13.12 - COMPARAÇÃO COMPLETA POR MARCA/FORNECEDOR

O que esta versão corrige:
- Resultado administrativo mostra tudo que cada fornecedor respondeu:
  marca, código da marca, descrição informada, preço unitário, total, disponibilidade, observação e resposta bruta.
- Botão "Comparar respostas" em cada cotação.
- Botão "Ver respostas WhatsApp" em cada cotação.
- O robô deve gravar respostas diretas do WhatsApp em:
  quotes/{quoteId}/responses/{supplierId}/{itemId}
  e o texto bruto em:
  quotes/{quoteId}/whatsappRawReplies/{id}
- O formulário do fornecedor continua ocultando valores internos da oficina.
- Assinatura: Powered by thIAguinho Soluções Digitais.

IMPORTANTE PARA TESTE DO ROBÔ:
- O WhatsApp conectado ao robô não processa mensagens enviadas por ele mesmo.
- Teste com outro número cadastrado como fornecedor.
- Se o número do fornecedor não estiver cadastrado corretamente, a resposta não cai no fornecedor certo.
