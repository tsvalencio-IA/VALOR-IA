VALORIA V13.7 NÚCLEO ESTÁVEL

Esta versão foi reescrita em núcleo simples para parar travamentos de tela.

SUBIR NO GITHUB:
- index.html
- fornecedor.html
- firebase-config.js
- firebase-rtdb-rules-TESTE_FUNCIONA_AGORA.json
- firebase-rtdb-rules-PRODUCAO_BASE.json
- README_PASSO_A_PASSO.txt

ABRIR:
https://tsvalencio-ia.github.io/valor_IA/index.html?v=13.7

O QUE FOI PRIORIZADO:
- botões funcionando
- sem detalhes/details que fecham sozinhos
- seleção de vários fornecedores
- envio dos selecionados para a fila do robô
- respostas diretas do WhatsApp aparecem na cotação
- edição/exclusão de orçamento
- encerramento de cotação
- formulário do fornecedor estável

Powered by thIAguinho Soluções Digitais


V13.8
- Adicionado botão "Analisar cotação".
- A análise mostra itens respondidos, compra recomendada, venda/base, lucro estimado, itens sem resposta e recomendação de comprador.
- Adicionado config.html para configurar cliente sem programar.
- Adicionado INSTALAR_E_ABRIR_ROBO_VALORIA.bat para instalação plug and play do robô.
- O instalador NÃO desativa o firewall inteiro. Ele só cria regra específica para Node.js se for executado como administrador.
- Assinatura mantida: Powered by thIAguinho Soluções Digitais.

FLUXO DE IMPLANTAÇÃO EM CLIENTE
1. Criar projeto Firebase.
2. Criar Realtime Database.
3. Criar Auth por email/senha.
4. Subir index.html, fornecedor.html e firebase-config.js no GitHub Pages.
5. No computador do cliente, extrair o ZIP na Área de Trabalho.
6. Abrir config.html e gerar firebase-config.js / robo-config.json.
7. Colocar robo-config.json dentro da pasta robo-whatsapp.
8. Rodar INSTALAR_E_ABRIR_ROBO_VALORIA.bat.
