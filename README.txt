# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie `index.html`, `manifest.json`, `sw.js` e a pasta `icons` para a raiz do repositório.
3. No GitHub, abra **Settings → Pages** e publique a branch/pasta desejada.
4. Acesse o endereço HTTPS publicado e instale pelo menu do navegador.

## Observações
- O PWA usa armazenamento local do navegador e mantém a lógica do HTML original.
- A sincronização entre aparelhos depende da configuração válida do Supabase dentro do aplicativo e das tabelas/permissões correspondentes. O PWA, sozinho, não compartilha dados entre aparelhos.
- A primeira abertura precisa de internet para carregar as bibliotecas externas usadas pelo sistema. O Service Worker mantém os arquivos principais do aplicativo disponíveis para aberturas seguintes.
- Troque a senha padrão `admin / admin123` após o primeiro acesso.
