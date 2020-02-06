# regexutils
Regex muito úteis que sempre utilizo

## Não tem TITLE em um LINK
`<a(?!.*(title).*)(.*)<\/a>`

Regex que insere o TITLE

`<a title="eu sou um title"$2</a>`
[DEMO](https://regex101.com/r/Hf1JsO/1)

## Não tem ALT em um Link
`<a(?!.*(alt).*)(.*)<\/a>`

Regex que insere o ALT

`<a alt="eu sou um alt"$2</a>`
[DEMO](https://regex101.com/r/xf3bPX/1)

## Não tem ALT e TITLE no link

`<a(?!.*(alt|title).*)(.*)<\/a>`

Regex que insere o ALT e o TITLE

`<a title="eu sou um title" alt="eu sou um alt"$2</a>`
[DEMO](https://regex101.com/r/TpSz7i/1)
