# Portfólio · João Pedro Souza Passos

Site pessoal em um único arquivo HTML, sem dependências nem build. As fontes vêm do Google Fonts e as animações são feitas com Canvas e JavaScript puro.

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | A página inteira: HTML, CSS e JavaScript |
| `foto.jpg` | Foto usada no topo da página |

## Rodar no computador

Abra o `index.html` direto no navegador. Se preferir um servidor local:

```bash
python3 -m http.server 8000
# depois acesse http://localhost:8000
```

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub. Se ele se chamar `Jpsoupa1.github.io`, o site fica em `https://jpsoupa1.github.io`. Com qualquer outro nome, por exemplo `portfolio`, fica em `https://jpsoupa1.github.io/portfolio`.
2. Envie os arquivos:

```bash
git init
git add .
git commit -m "Portfólio"
git branch -M main
git remote add origin https://github.com/Jpsoupa1/Jpsoupa1.github.io.git
git push -u origin main
```

3. No repositório, abra **Settings › Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, a branch `main` e a pasta `/ (root)`. Salve.
4. Em um ou dois minutos o endereço aparece no topo da mesma tela.

## Editar

Os textos estão direto no `index.html`. As cores ficam nas variáveis do bloco `:root`, no começo do `<style>`, com uma versão para o tema escuro e outra para o claro.
