# Chicken Point — App de Reposição de Estoque

Pasta pronta para publicar. Não precisa programar nada.

## Como publicar (Netlify, grátis, 2 minutos)

1. Baixe esta pasta inteira no seu computador ou celular.
2. Acesse **netlify.com** e crie uma conta grátis (pode entrar com Google).
3. No painel, procure a área que diz algo como **"Add new site" → "Deploy manually"**.
4. Arraste a pasta `chicken-point-app` (com todos os arquivos dentro) para essa área.
5. Em segundos o Netlify te dá um link, tipo `https://chicken-point-123.netlify.app`.

Pronto — esse link já é o app funcionando na internet.

## Como instalar no celular

**Android (Chrome):**
1. Abra o link do Netlify no Chrome.
2. Vai aparecer um aviso "Adicionar Chicken Point à tela inicial" (ou toque no menu ⋮ → "Instalar app").
3. Confirme. Fica um ícone na tela como qualquer outro app, abre em tela cheia.

**iPhone (Safari):**
1. Abra o link no Safari (tem que ser Safari, não funciona no Chrome do iPhone).
2. Toque no ícone de compartilhar (quadrado com seta pra cima).
3. Toque em **"Adicionar à Tela de Início"**.
4. Confirme. Vira um ícone que abre em tela cheia, sem barra de navegador.

## O que funciona

- Catálogo por categoria, lista de compras, marcar como comprado — tudo igual ao que já testamos.
- Os dados ficam salvos no próprio celular (mesmo se fechar o app ou desligar o Wi-Fi).
- Funciona offline depois da primeira vez que abrir (o app fica em cache).
- O sino no topo ativa lembretes do navegador para itens atrasados.

## Sobre os lembretes automáticos — leia isso

O botão de sino ativa notificações **enquanto o app está aberto ou instalado e o celular está ligado**. Isso é diferente de notificação de app de verdade tipo WhatsApp, que chega mesmo com o app fechado há dias.

Notificação de verdade em segundo pleno (mesmo com o app fechado por dias) exige um servidor rodando por trás (chamado "push notification server") — isso já é um projeto bem maior, tipo um mini-backend. Se no futuro isso virar importante pro seu dia a dia (por exemplo, você esquecer de abrir o app), me avisa que a gente monta essa parte.

## Se quiser trocar o link por um domínio próprio

No painel do Netlify, em "Domain settings", dá pra apontar um domínio que você já tenha (tipo `estoque.chickenpoint.com.br`) ou comprar um novo. Não é obrigatório — o link `.netlify.app` já funciona normalmente.
