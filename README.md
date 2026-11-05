# Repertório e Abajur

Dois jogos feitos só com HTML, sem servidor nem banco de dados:

- `repertorio/`: quiz de conhecimentos gerais (216 fichas, 9 classes, 3 níveis)
- `abajur/`: brincadeiras lentas para a hora de dormir

## Como publicar no GitHub Pages

1. No GitHub, crie um repositório **público** (por exemplo, `jogos`).
2. Na página do repositório, clique em **Add file → Upload files** e arraste tudo o que está dentro desta pasta: `index.html`, `README.md` e as pastas `repertorio` e `abajur`. Confirme em **Commit changes**.
3. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, depois a branch **main** e a pasta **/ (root)**, e clique em **Save**.
4. Em alguns minutos o site fica no ar em `https://SEU-USUARIO.github.io/jogos/`.

Para atualizar um jogo depois, envie o novo `index.html` para a mesma pasta pelo **Upload files**.

O progresso de cada pessoa fica salvo no navegador dela (localStorage). Nada é enviado para servidor nenhum.
