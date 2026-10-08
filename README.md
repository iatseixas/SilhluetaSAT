# SilhluetaSAT — PWA

Projeto web original encontrado no Google Drive (`FAMILIA-SAT-PWA.zip`), com as versões SilhluetaSAT v1.3 e Pro v1.3.

- Versão padrão: `/`
- Versão Pro: `/pro/`

## Publicar no GitHub Pages

1. Crie um repositório público `SilhluetaSAT-PWA`.
2. Envie **os arquivos desta pasta**, mantendo `index.html` na raiz e a pasta `pro`.
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/(root)`.
4. Acesse `https://SEU-USUARIO.github.io/SilhluetaSAT-PWA/` e `/pro/`.
5. No Safari do iPhone, toque em **Compartilhar → Adicionar à Tela de Início**.

Os service workers e manifestos usam caminhos relativos, para funcionar sob o subdiretório do GitHub Pages. Para testar os service workers localmente, use servidor HTTP local, não `file://`.
