# regexutils
Regex muito úteis que sempre utilizo

## Não tem TITLE em um LINK
`<a ((?!.*(title).*).*)>(.*)<\/a>`

Regex que insere o TITLE

`<a $1 title="title do link">$3</a>`

## Não tem ALT em um Link
`<a ((?!.*(alt).*).*)>(.*)<\/a>`

Regex que insere o ALT

`<a $1 alt="alt do link">$3</a>`

## Não tem ALT e TITLE no link

`<a ((?!.*(alt|title).*).*)>(.*)<\/a>`

Regex que insere o ALT e o TITLE

`<a $1 alt="alt do link" title="title do link">$3</a>`
