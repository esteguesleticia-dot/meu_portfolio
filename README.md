# Portfólio — [Seu Nome]

Modelo de portfólio para estudante de Ciências Contábeis. Pronto para publicar gratuitamente no **GitHub Pages**.

## Estrutura do projeto

```
portfolio-contabeis/
├── index.html          → estrutura da página (edite o conteúdo aqui)
├── css/
│   └── style.css        → cores, fontes e layout
├── js/
│   └── script.js         → menu mobile, navegação e animações
├── assets/               → coloque aqui sua foto e outras imagens
└── README.md
```

## Como editar

1. Abra `index.html` e troque tudo que estiver entre `[colchetes]` pelo seu conteúdo (nome, curso, projetos, etc).
2. Para adicionar mais projetos, duplique um bloco `<article class="work-card">...</article>` dentro da seção `#projetos`.
3. Para adicionar mais itens na sua formação, duplique um `<li class="tl-item">...</li>` dentro da seção `#formacao`.
4. Para usar sua foto: coloque o arquivo de imagem na pasta `assets/` e, no `index.html`, troque
   ```html
   <div class="avatar">[sua foto aqui]</div>
   ```
   por
   ```html
   <div class="avatar"><img src="assets/sua-foto.jpg" alt="Seu Nome"></div>
   ```
5. Para mudar as cores, edite as variáveis no topo do `css/style.css` (dentro de `:root`).

## Como publicar gratuitamente no GitHub Pages

1. Crie um repositório novo no GitHub (pode ser público), por exemplo `meu-portfolio`.
2. Envie estes arquivos para o repositório. Pelo site do GitHub: clique em **Add file → Upload files**, arraste a pasta inteira e clique em **Commit changes**.
   - Se preferir usar o terminal:
     ```bash
     git init
     git add .
     git commit -m "primeira versão do portfólio"
     git branch -M main
     git remote add origin https://github.com/SEU-USUARIO/meu-portfolio.git
     git push -u origin main
     ```
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. Aguarde alguns minutos — o GitHub mostrará o link do seu site, algo como:
   ```
   https://SEU-USUARIO.github.io/meu-portfolio/
   ```

Pronto — esse link pode ir no seu currículo, LinkedIn e Lattes.

## Tecnologias usadas

- HTML5 + CSS3 (sem frameworks, sem build — abre direto no navegador)
- JavaScript puro (vanilla), para o menu mobile e as animações de rolagem
- Fontes: [Fraunces](https://fonts.google.com/specimen/Fraunces), [Work Sans](https://fonts.google.com/specimen/Work+Sans) e [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), via Google Fonts
