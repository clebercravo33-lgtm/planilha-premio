PREMIAÇÃO GRUPO NICO — PWA v81

PUBLICAR NO GITHUB PAGES
1. Extraia este ZIP.
2. Envie TODOS os arquivos e a pasta icons para a raiz do repositório GitHub.
3. No GitHub, abra Settings > Pages.
4. Em Build and deployment, selecione Deploy from a branch.
5. Escolha a branch main e a pasta /(root), depois salve.
6. Aguarde a publicação e abra o endereço HTTPS no celular.
7. No navegador, use "Adicionar à tela inicial" / "Instalar app".

ARQUIVOS
- index.html: aplicativo original preparado para PWA.
- manifest.json: identificação e configuração de instalação.
- sw.js: cache para abertura offline dos arquivos já carregados.
- icons/: ícones 192x192 e 512x512.

OBSERVAÇÕES
- O app mantém os dados locais no armazenamento do navegador. Para sincronizar
  entre aparelhos, configure o Supabase dentro do aplicativo.
- Bibliotecas externas (XLSX, gráficos e PDF) precisam ser carregadas ao menos
  uma vez com internet para ficarem disponíveis no cache.
- A instalação PWA exige publicação em HTTPS (GitHub Pages atende).
