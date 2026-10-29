# Maltaark Company

Site de vendas da Maltaark Company e briefing para clientes, hospedados no GitHub Pages.

- `index.html`: site principal (simulador, pacotes, checkout e pós-compra)
- `briefing/index.html`: questionário que o cliente responde depois da compra

## Como funciona a integração

1. O cliente monta a página no simulador e escolhe um pacote.
2. Ao confirmar, o pedido vai para o WhatsApp (11) 98359-2947 e para o e-mail maltaarkcompany@gmail.com (via FormSubmit).
3. Na tela de confirmação, o botão **Responder o briefing** abre `briefing/` já com pedido, nome, e-mail, WhatsApp, negócio e plano preenchidos.
4. O briefing é enviado para o WhatsApp e para o mesmo e-mail.

## Onde editar

No topo do `<script>` de cada página há um bloco `CONFIG` com WhatsApp, e-mail, preços, promoção e link de pagamento.

O primeiro envio pelo FormSubmit manda um e-mail de ativação para maltaarkcompany@gmail.com. Clique no link para liberar os próximos.
