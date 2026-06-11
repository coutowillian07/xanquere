# XANQUERÊ Charcutaria Artesanal — Landing Page

Esta pasta contém a versão redesenhada da landing page da **XANQUERÊ Charcutaria Artesanal**, preparada como site estático para publicação no **GitHub Pages**. A proposta visual trabalha uma identidade premium e artesanal, combinando fundo vinho/espresso, cobre, dourado suave e tons creme para transmitir tradição, cuidado manual e sofisticação.

## Arquivos incluídos

| Arquivo | Função |
|---|---|
| `index.html` | Página principal da landing page, com estrutura semântica, chamadas para WhatsApp e Instagram, seções de filosofia, produtos, galeria e contato. |
| `style.css` | Identidade visual, responsividade, componentes, cards, botões e tratamento de imagens ausentes. |
| `.nojekyll` | Arquivo vazio usado para evitar processamento Jekyll em sites estáticos simples. |
| `original.html` | Cópia do código original enviado, mantida apenas como referência. |

## Como substituir as imagens

A seção de galeria procura os arquivos `foto1.jpg`, `foto2.jpg`, `foto3.jpg` e `foto4.jpg` na mesma pasta do `index.html`. Para usar fotos reais dos produtos, salve as imagens com esses nomes ou altere os caminhos dentro do HTML. Enquanto as imagens não forem substituídas, o layout exibirá um bloco visual de fallback, sem quebrar a página.

| Imagem | Sugestão de conteúdo |
|---|---|
| `foto1.jpg` | Foto das linguiças frescas em close, com boa iluminação e fundo rústico. |
| `foto2.jpg` | Foto do porco no pote, preferencialmente com textura e apresentação artesanal. |
| `foto3.jpg` | Foto da banha no pote ou uso culinário da banha. |
| `foto4.jpg` | Foto do preparo, embalagem, bancada ou composição de produtos. |

## Como publicar no GitHub Pages

O GitHub Pages aceita sites estáticos e procura um arquivo de entrada como `index.html`, `index.md` ou `README.md` no local configurado como fonte de publicação.[1] Para este projeto, a forma mais simples é publicar a partir do branch principal, usando a pasta raiz do repositório como origem.[2]

> A recomendação prática é manter `index.html`, `style.css`, `.nojekyll` e as imagens diretamente na raiz do repositório, pois isso reduz risco de erro de caminho ao publicar.

| Etapa | Ação recomendada |
|---|---|
| 1 | Crie um repositório no GitHub, por exemplo `xanquere-landing` ou `xanquere`. |
| 2 | Envie para a raiz do repositório os arquivos `index.html`, `style.css`, `.nojekyll` e as fotos finais. |
| 3 | No repositório, acesse **Settings** > **Pages**. |
| 4 | Em **Build and deployment**, escolha **Deploy from a branch**. |
| 5 | Selecione o branch `main` e a pasta `/root` ou `/`, depois clique em **Save**. |
| 6 | Aguarde a publicação; a documentação do GitHub informa que alterações podem levar alguns minutos para aparecer no site publicado.[1] |

## Ajustes rápidos de marca

Se quiser ajustar a identidade visual, as cores principais estão centralizadas no início do arquivo `style.css`, dentro de `:root`. Isso permite alterar o tom da marca sem refazer todo o layout.

| Variável | Uso visual |
|---|---|
| `--espresso` | Fundo escuro principal, cabeçalho e rodapé. |
| `--wine` | Profundidade vinho/avermelhada do visual artesanal. |
| `--copper` | Destaques quentes e botões. |
| `--gold` | Detalhes premium, bordas e chamadas de atenção. |
| `--cream` e `--paper` | Fundos claros e contraste editorial. |

## Referências

[1]: https://docs.github.com/pt/pages/getting-started-with-github-pages/creating-a-github-pages-site "GitHub Docs — Criando um site de páginas GitHub"
[2]: https://docs.github.com/pt/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site "GitHub Docs — Configurando uma fonte de publicação para seu site GitHub Pages"
