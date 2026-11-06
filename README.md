# Go Pool — site

Página de apresentação e download do Go Pool, publicada no GitHub Pages:
**https://bitboxgs.github.io/gopool**

## Atualizar o download a cada build

No começo do `<script>` em `index.html`:

```js
const DOWNLOAD_URL = "https://drive.google.com/file/d/<ID>/view?usp=sharing";
const VERSION = "0.1.6";
const SIZE = "000 MB";
```

O arquivo no Google Drive precisa estar compartilhado como "Qualquer pessoa com o link".

## Textos

O português fica direto no HTML. Inglês e espanhol ficam no objeto `T` do script, com as mesmas chaves `data-i18n`.

## Rodar localmente

```bash
python -m http.server 8766
```

e abrir http://localhost:8766.
