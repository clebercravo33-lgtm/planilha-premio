# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie **todo o conteúdo** para a raiz do repositório GitHub.
3. Confirme que `index.html`, `manifest.webmanifest`, `service-worker.js` e a pasta `icons` ficaram na raiz/estrutura indicada.
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**, escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. Abra o endereço HTTPS gerado pelo GitHub Pages. No celular ou navegador compatível, use a opção **Instalar aplicativo** / **Adicionar à tela inicial**.

## Observações
- O arquivo principal já está como `index.html`.
- O pacote inclui manifesto, ícones e service worker para instalação e cache do aplicativo.
- Os dados continuam usando o armazenamento local do navegador e a sincronização Supabase configurada dentro do app.
- Para sincronizar entre aparelhos, configure o Supabase no próprio aplicativo e mantenha as tabelas/permissões necessárias.
- O modo offline depende de os arquivos e bibliotecas terem sido carregados ao menos uma vez com internet.
