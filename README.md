# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todos os arquivos e a pasta `icons/` mantendo esta estrutura.
3. Em **Settings → Pages**, selecione a branch principal (`main`) e a pasta `/(root)`.
4. Salve e abra o endereço publicado pelo GitHub Pages.
5. No celular, abra o endereço no Chrome e escolha **Instalar app** ou **Adicionar à tela inicial**.

## Arquivos
- `index.html`: aplicativo original com metadados PWA.
- `manifest.webmanifest`: nome, aparência e ícones do aplicativo.
- `sw.js`: cache básico dos arquivos para abertura offline.
- `icons/`: ícones em 192×192 e 512×512.

## Atenção à sincronização entre aparelhos
O PWA não sincroniza dados automaticamente só por ser instalado. Para compartilhar dados entre celulares e computadores, configure o Supabase na área **Config** do aplicativo e confirme que as tabelas e políticas de acesso estão corretamente criadas. O modo offline/cache não garante sincronização offline automática.
