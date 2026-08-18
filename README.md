# LMA Consultoria — Site estático

Este site não requer Node.js, banco de dados ou processo de build. Ele é composto apenas por HTML, CSS, JavaScript e imagens estáticas.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie o conteúdo desta pasta para a branch `main`.
2. No repositório, acesse **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/(root)`; depois clique em **Save**.
5. Aguarde a publicação. O GitHub mostrará a URL pública do site.

O arquivo `.nojekyll` garante que o GitHub entregue os arquivos exatamente como foram criados. Os caminhos dos estilos, scripts e logo são relativos, portanto o site também funciona em URLs no formato `https://usuario.github.io/nome-do-repositorio/`.
