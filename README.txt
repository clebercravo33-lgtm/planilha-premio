# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia este ZIP.
2. Envie **todos os arquivos e a pasta `icons`** para a raiz do repositório GitHub.
3. No GitHub, abra **Settings → Pages**.
4. Em *Build and deployment*, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e salve.
5. Abra o endereço HTTPS publicado. No Android/Chrome, use **Instalar app** ou **Adicionar à tela inicial**.

## Observações
- O app mantém os dados locais no navegador (`localStorage`), como no HTML original.
- A sincronização entre aparelhos depende da configuração do Supabase dentro do app.
- O service worker armazena a estrutura do app e tenta guardar bibliotecas externas após o primeiro acesso com internet. Recursos de CDN podem precisar ser carregados online na primeira abertura.
- Para atualizar a versão publicada, substitua os arquivos no GitHub. Se o navegador mantiver uma versão antiga, feche e abra o app novamente.
