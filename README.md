# NICO Premiação — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie `index.html`, `manifest.webmanifest`, `service-worker.js`, a pasta `icons/` e este README para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch (normalmente `main`) e a pasta `/ (root)`, depois salve.
5. Aguarde a publicação e abra o endereço HTTPS do GitHub Pages no celular.
6. No navegador, use **Adicionar à tela inicial** ou **Instalar app**.

## Observações
- O app mantém os dados locais no navegador (`localStorage`) e possui integração Supabase configurável dentro do próprio sistema.
- A instalação PWA e o cache do aplicativo exigem HTTPS; GitHub Pages fornece HTTPS.
- O cache permite abrir a estrutura do app offline depois da primeira visita. Bibliotecas externas podem precisar ter sido carregadas antes de ficar sem internet.
- Não apague os arquivos `manifest.webmanifest`, `service-worker.js` ou a pasta `icons/`.
