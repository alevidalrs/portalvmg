# Portal Venâncio Mil Graus

## Conteúdo
- `index.html`: página e seções do portal.
- `style.css`: identidade visual responsiva.
- `script.js`: menu mobile, ano automático e formulário WhatsApp.
- `config.js`: configuração do WhatsApp.
- `assets/`: imagens recortadas do mockup visual aprovado.

## Antes de publicar
1. Abra `config.js` e substitua `5551999999999` pelo WhatsApp oficial do VMG (55 + DDD + número, somente dígitos).
2. Atualize os links sociais no `index.html` (os links estão como `#` inicialmente).
3. Revise os textos e substitua os recortes conceituais pelas artes/fotografias oficiais quando estiverem disponíveis.

## GitHub Codespaces
1. Copie os arquivos e a pasta `assets` para a raiz do repositório.
2. Confirme que `index.html` está diretamente na raiz.
3. Abra Source Control, escreva `Atualiza layout do portal VMG`, clique em Commit e depois em Sync Changes/Push.

## GitHub Pages
No repositório: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

## Limitações desta versão
O formulário encaminha texto ao WhatsApp. Ainda não recebe nem armazena vídeos/fotos diretamente no site; isso exige integração de backend/armazenamento. As imagens são recortes do mockup aprovado e devem ser trocadas pelas artes originais para o lançamento final.
