# PWA — Premiação Grupo NICO

Pacote preparado para publicação no GitHub Pages.

## Arquivos
- `index.html`: aplicação original adaptada como PWA.
- `manifest.webmanifest`: identificação e configuração de instalação.
- `service-worker.js`: cache do aplicativo para abertura posterior.
- `icons/`: ícones 192×192 e 512×512.

## Publicar no GitHub
1. Crie ou abra um repositório no GitHub.
2. Envie **todos os arquivos e a pasta `icons`**, mantendo essa estrutura.
3. Em **Settings → Pages**, selecione a branch principal e a pasta `/ (root)`.
4. Aguarde a publicação e abra o endereço HTTPS gerado pelo GitHub Pages.

## Instalar no celular
Abra o endereço publicado no Chrome e use o menu ⋮ → **Instalar app** ou **Adicionar à tela inicial**.

## Observação importante sobre os dados
O aplicativo original utiliza armazenamento local do navegador e possui integração opcional com Supabase. O PWA não sincroniza dados entre aparelhos por si só: para compartilhar os mesmos dados entre celulares e computadores, configure corretamente o Supabase na tela **Config** e confira as permissões/políticas das tabelas. O cache offline guarda os arquivos do aplicativo, não substitui a sincronização dos dados.

O HTML original foi mantido; foram acrescentados apenas os arquivos e referências necessários ao PWA.
