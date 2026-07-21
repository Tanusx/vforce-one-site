# Site — VForce One (Airsoft)

Site institucional de uma página, pronto para publicar gratuitamente no **GitHub Pages**.

## O que tem aqui
- `index.html` — página única com HTML, CSS e JS embutidos (não depende de build, framework ou servidor).

## Como publicar no GitHub Pages (passo a passo)

1. **Crie um repositório novo no GitHub**
   - Acesse https://github.com/new
   - Nome sugerido: `site-airsoft` (pode escolher outro)
   - Deixe como público (necessário para GitHub Pages gratuito em conta pessoal)
   - Não marque "Add a README" (você já vai enviar o seu)

2. **Envie os arquivos deste projeto para o repositório**

   Pelo site do GitHub (mais simples, sem usar terminal):
   - Abra o repositório recém-criado → botão **"Add file" → "Upload files"**
   - Arraste `index.html` e `README.md`
   - Clique em **"Commit changes"**

   Ou pelo terminal, se preferir:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Primeira versão do site"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/site-airsoft.git
   git push -u origin main
   ```

3. **Ative o GitHub Pages**
   - No repositório, vá em **Settings → Pages**
   - Em "Build and deployment" → "Source", selecione **Deploy from a branch**
   - Em "Branch", selecione **main** e a pasta **/ (root)**
   - Clique em **Save**

4. **Acesse o site**
   - Após 1–2 minutos, o GitHub mostra a URL no topo da página de Pages, no formato:
     `https://SEU-USUARIO.github.io/site-airsoft/`

## Pendências antes de publicar

O nome da marca (**VForce One**) já está aplicado no site. Ainda faltam os 3 links de venda — procure por `<!-- TODO -->` dentro de `index.html` (seção "Onde comprar") para achar rapidamente cada um:

- [ ] Link real da loja na **Amazon**
- [ ] Link real da loja no **Mercado Livre**
- [ ] Link real do perfil no **TikTok**

Assim que tiver esses endereços, é só abrir o `index.html`, localizar cada comentário `<!-- TODO -->` e trocar o `href="#"` logo abaixo pelo link correspondente.

Outras personalizações opcionais:
- Ajustar os textos de e-books e quadros fixos se os títulos/temas mudarem.
- Se quiser um domínio próprio (ex: `www.vforceone.com.br`) em vez do endereço `.github.io`, isso também é configurado em **Settings → Pages → Custom domain**, apontando o DNS do seu domínio para o GitHub.

## Sobre o design
Paleta tática (verde-oliva escuro, areia, e um laranja de sinalização como cor de destaque), tipografia condensada para títulos e monoespaçada para dados técnicos — remete a fichas de equipamento e manuais de campo, sem glamourizar armas ou violência. Totalmente responsivo e com foco de teclado visível.
