# Sofia Froes — UGC Creator

Landing page standalone para a frente de UGC Creator, na mesma linguagem
visual do site principal (sofiafroes.com): branco, preto absoluto, amarelo
sol como accent, serif editorial + sans limpa.

## Estrutura

Página única (`index.html`), sem dependências além das Google Fonts
(Playfair Display + DM Sans). HTML/CSS/JS puro — nada a compilar.

## Publicar no Vercel

1. Criar repositório novo no GitHub (ex: `sofiafroes/ugc-creator`) e enviar
   este conteúdo para o branch `main`.
2. Em vercel.com → **Add New Project** → importar esse repositório.
3. Framework preset: **Other** (é HTML estático — não precisa de build
   command nem output directory).
4. Deploy. Qualquer novo commit em `main` faz redeploy automático.

## Editar

- Copy: procurar diretamente no `index.html`, secções comentadas por bloco
  (`hero`, `signature`, `porque`, `para-quem`, `formatos`, `cta`).
- Cores: variáveis CSS no `:root` no topo do `<style>`.
- Formulário de contacto: atualmente só mostra um alerta local
  (`onsubmit` no `<form>`). Ligar a Mailerlite/Formspree/etc. quando
  quiseres recolher os pedidos a sério.

## Domínio

Depois do deploy, associar um subdomínio próprio em Vercel → Settings →
Domains (ex: `ugc.sofiafroes.com`).
