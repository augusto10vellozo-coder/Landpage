# Site de serviços — Cezar Vellozo

Landing page de venda de serviços de desenvolvimento web. HTML e CSS puros, sem framework,
sem build e sem dependência externa.

## Arquivos

```
index.html      → estrutura e conteúdo
styles.css      → todo o estilo (comentado por seção)
logo-mark.svg   → símbolo (cabeçalho e favicon)
logo.svg        → versão completa com nome e assinatura
```

Para abrir: duplo clique no `index.html`.

## Publicar no GitHub Pages

1. Crie um repositório público em https://github.com/new (nome sugerido: `site-servicos`).
   Não marque README, .gitignore nem license.
2. No VS Code, abra a pasta com os dois arquivos e rode:
   ```bash
   git init
   git add .
   git commit -m "Landing page de serviços"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/site-servicos.git
   git push -u origin main
   ```
3. No GitHub: **Settings → Pages → Deploy from a branch → main / (root) → Save**
4. Em cerca de 1 minuto o site fica no ar em:
   ```
   https://augusto10vellozo-coder.github.io/site-servicos/
   ```

> Se quiser o endereço curto `augusto10vellozo-coder.github.io`, o repositório precisa se chamar
> exatamente `augusto10vellozo-coder.github.io`.

## O que editar primeiro

| O que | Onde |
|---|---|
| WhatsApp | `index.html`, final do arquivo, variável `numero` (`5554994535730`) |
| Cor de destaque | `styles.css`, variável `--destaque` |
| Nome / marca | `index.html`, bloco `.marca` e rodapé |
| Textos dos serviços | `index.html`, seção `id="servicos"` |
| Projetos | `index.html`, seção `id="projetos"` (título, texto, link e imagem) |
| Perguntas frequentes | `index.html`, seção `id="perguntas"` |

## Imagens dos projetos

As três imagens da seção de projetos são carregadas dos sites que já estão no ar
(`taskbio.com.br`, o demo do painel e o Sabor de Casa). Isso mantém o projeto leve e sem
duplicar arquivos. Se quiser tudo local, baixe as imagens para uma pasta `img/` e troque os
`src` no `index.html`.

## Checklist antes de divulgar

- [ ] Abrir no celular e conferir o menu (três riscos no canto superior direito)
- [ ] Testar todos os botões de WhatsApp — devem abrir com a mensagem pronta
- [ ] Conferir o número no link `wa.me`
- [ ] Testar os três links de projeto
- [ ] Passar o mouse nos links para ver o foco do teclado (`Tab`)
- [ ] Conferir que não há nenhum texto de exemplo sobrando
