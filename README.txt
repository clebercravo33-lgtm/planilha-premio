PREMIAÇÃO GRUPO NICO — PWA v65

COMO PUBLICAR NO GITHUB PAGES
1. Extraia todos os arquivos deste ZIP.
2. Envie index.html, manifest.webmanifest, service-worker.js e a pasta icons para a raiz do repositório GitHub.
3. No GitHub, abra Settings > Pages e habilite a publicação da branch/pasta desejada.
4. Acesse o endereço HTTPS publicado e instale pelo menu do navegador (Adicionar à tela inicial / Instalar app).

IMPORTANTE
- O Service Worker e a instalação PWA exigem HTTPS (GitHub Pages fornece HTTPS) ou localhost.
- O aplicativo mantém seus dados locais no navegador e usa Supabase se configurado. O modo offline não substitui a configuração/sincronização do Supabase.
- Bibliotecas externas são armazenadas em cache após serem carregadas com internet; a primeira abertura deve ocorrer online para garantir o cache dessas bibliotecas.
- O login padrão exibido pelo próprio aplicativo é admin / admin123. Troque a senha após o primeiro acesso.
