# Maurício AI Video — interface melhorada

Inclui interface responsiva para celular, biblioteca temporária de imagens de personagens, montagem de cenas, prompt de vídeo, copiar e baixar .txt.

## Limitação atual
Esta é a interface do criador, ainda sem geração real de vídeo. As imagens selecionadas ficam apenas na sessão do navegador e não são enviadas a nenhum servidor. Para geração integrada, configure um provedor de vídeo e um backend (por exemplo, Cloudflare Worker). Guarde a chave da API como secret no backend; nunca no `app.js`, `index.html` ou em arquivo público.

## Publicar com segurança
1. Faça uma cópia de segurança dos arquivos atuais.
2. Extraia o ZIP.
3. No repositório GitHub, substitua `index.html`, `styles.css` e `app.js` pelos arquivos desta pasta, na raiz publicada.
4. Faça Commit changes e aguarde a publicação.
5. Se não atualizar, recarregue ou teste em aba anônima.

Não exclua o repositório nem as configurações do GitHub Pages.