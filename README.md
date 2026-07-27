# Leitor de Etiquetas

App web (PWA) para escanear código de barras de etiquetas de material, totalizar por código de produto e exportar para Excel / Google Sheets.

## Como publicar no GitHub Pages (grátis, com HTTPS — necessário para a câmera funcionar)

1. Entre em [github.com](https://github.com) e crie uma conta, se ainda não tiver.
2. Clique em **New repository**. Dê um nome, por exemplo `leitor-etiquetas`. Marque como **Public**. Crie.
3. Dentro do repositório, clique em **Add file → Upload files**.
4. Arraste os dois arquivos desta pasta (`index.html` e este `README.md`) e clique em **Commit changes**.
5. Vá em **Settings** (aba do repositório) → **Pages** (menu lateral).
6. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
7. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
8. Aguarde 1–2 minutos. Atualize a página — vai aparecer um link no topo, algo como:
   `https://SEU_USUARIO.github.io/leitor-etiquetas/`
9. Abra esse link no navegador do celular (Chrome no Android, Safari no iPhone). Agora o site é HTTPS de verdade, então o navegador vai pedir permissão de câmera normalmente.
10. Opcional: no menu do navegador, use **Adicionar à tela inicial** para abrir como se fosse um app.

## Atualizações futuras

Sempre que eu (Claude) fizer um ajuste no app, é só repetir o passo 3–4 (Upload files, substituindo o `index.html`) — o link continua o mesmo.

## Dados

Os itens escaneados ficam salvos no navegador do próprio aparelho. O envio para o Google Sheets é feito manualmente pelo app (aba Config), enviando só os itens ainda não enviados.
