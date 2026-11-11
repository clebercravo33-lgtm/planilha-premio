# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste pacote.
2. Envie `index.html`, `manifest.webmanifest`, `service-worker.js` e a pasta `icons` para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch principal e a pasta **/(root)**.
5. Abra o endereço publicado em HTTPS no celular. Use o menu do navegador e escolha **Instalar app** ou **Adicionar à tela inicial**.

O aplicativo mantém os dados locais no navegador e usa Supabase somente se URL e chave forem configuradas no próprio app. O modo offline pode abrir a aplicação e recursos externos já carregados anteriormente; a primeira instalação e o primeiro carregamento das bibliotecas externas exigem internet.
