# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia este ZIP.
2. Envie **todos os arquivos e pastas** para a raiz do repositório GitHub.
3. Em **Settings → Pages**, selecione a branch principal e a pasta `/ (root)`.
4. Aguarde a publicação e abra o endereço HTTPS gerado.
5. No celular, abra o site no Chrome e escolha **Instalar app** ou **Adicionar à tela inicial**.

## Observações
- O PWA possui cache básico do aplicativo para permitir abrir a interface offline após o primeiro acesso.
- Bibliotecas externas (XLSX/PDF) e sincronização Supabase dependem de internet.
- Os dados salvos em `localStorage` ficam no aparelho/navegador. Para compartilhar dados entre aparelhos, configure o Supabase dentro do aplicativo e confira as permissões/tabelas do projeto.
- O login padrão exibido no próprio HTML é `admin` / `admin123`. Altere a senha após entrar.
