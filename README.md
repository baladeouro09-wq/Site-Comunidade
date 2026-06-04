Dybala Optimizer — site estático

Como usar:

- Abre `D&MComunidade.html` no teu navegador (duplo clique).
- Se quiseres testar localmente com servidor:

  ```bash
  # Python 3
  python -m http.server 8000
  # ou
  npx http-server .
  ```

Arquivos importantes:
- `index.html` — página principal
- `styles.css` — estilos
- `assets/` — logos e favicon
- `.github/workflows/pages.yml` — GitHub Pages deploy automation

Deploy público com GitHub Pages:
1. Cria um repositório novo no GitHub.
2. Adiciona todos os ficheiros do site.
3. Faz `git push` na branch `main`.
4. Vai a `Settings > Pages` e confirma a publicação do branch `main`.

Depois de publicado, o link público será algo como:
`https://seunome.github.io/nomedorepo`

Se precisares, posso também ajudar-te a criar o repositório e configurar a publicação.   
