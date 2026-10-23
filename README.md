# VórtexSteal — Loja de VIPs (Minecraft Java)

## Configurado com os preços pedidos

- VIP Lifesteal: **R$ 7,00**
- VIP Noob: **R$ 4,00**
- Entrega: manual, após confirmação real do pagamento
- Canal de atendimento: Discord (link ainda precisa ser informado)

## Arquivos

- `index.html` — página principal e formulários
- `styles.css` — visual responsivo
- `products.js` — produtos e preços
- `config.js` — link público do Discord
- `app.js` — carrinho e resumo de pedido

## Antes de publicar

1. Em `config.js`, preencha `discordOrderUrl` com o link de convite do seu servidor Discord ou canal de atendimento. Exemplo de formato: `https://discord.gg/SEU-CODIGO` — substitua pelo seu link verdadeiro.
2. Em `products.js`, confirme as vantagens reais de cada VIP. Os itens marcados com `*` são exemplos a revisar.
3. Configure um método PIX real com seu banco ou provedor de pagamento. Não publique uma chave PIX fictícia.
4. Coloque no site as instruções oficiais de pagamento de forma segura. Este projeto não gera cobrança PIX, não verifica pagamentos e não confirma transações.
5. Confirme o recebimento no aplicativo bancário/painel oficial antes de conceder o VIP.

## Fluxo atual

O jogador escolhe VIPs, informa nick do Minecraft Java e contato, gera um resumo com código de pedido e pode copiar o resumo e abrir o Discord. O pedido **não é enviado automaticamente ao Discord**, não é armazenado num painel e não existe verificação de pagamento. A equipe precisa receber o resumo pelo canal e confirmar manualmente.

Para envio automático ao Discord, é necessário criar uma integração segura no servidor (por exemplo, uma função backend com webhook armazenado como segredo). Nunca coloque URL de webhook privada ou token de bot em `config.js`, HTML ou JavaScript público.

## Publicação gratuita com GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie `index.html`, `styles.css`, `products.js`, `config.js`, `app.js` e `README.md` para a raiz.
3. Vá a **Settings → Pages**.
4. Selecione **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
5. Aguarde o link publicado aparecer nessa tela.

## Importante sobre PIX

Este site não processa pagamentos nem gera QR Code. Para pagamentos reais, use o app do banco ou um provedor confiável, e confira o recebimento real antes de entregar o VIP. Nunca confie apenas em imagens de comprovante. Não peça senha de Minecraft/Microsoft ou códigos de autenticação.

## Aviso de marca

VórtexSteal é apresentado como uma loja independente da comunidade, não afiliada à Mojang ou à Microsoft.
