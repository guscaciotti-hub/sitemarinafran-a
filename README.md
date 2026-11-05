# Marina França · link na bio

Página de links do Instagram [@marinafrancaparamedica](https://www.instagram.com/marinafrancaparamedica/).
HTML, CSS e JavaScript puros, em um único arquivo. Sem build.

```
vercel.json          <- redireciona / para /links e define cabeçalhos
links/index.html     <- a página
links/assets/        <- logo, retrato, favicon, selos (MEC, SBT, VTV, UNISA) e og.jpg
README.md
```

## Como editar

Abra `links/index.html` e procure o bloco `CONFIG` no fim do arquivo. Lá ficam:

- o número do WhatsApp e a mensagem pronta de cada botão;
- o link da agenda online (se ficar vazio, o botão abre o WhatsApp);
- os links de curso, mentoria, reportagem, entrevista e redes sociais;
- o caminho da logo.

Textos dos botões ficam no HTML, logo acima, cada um com título (`.title`) e subtítulo (`.sub`).

Caminhos de imagem precisam ser absolutos (`/links/assets/...`), porque a página é
servida em `/links` sem barra no fim.

## Como publicar

O projeto está conectado à Vercel. Todo push na branch publicada vai ao ar sozinho.
