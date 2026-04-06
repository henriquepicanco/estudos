# Boilerplate HTML

Toda página HTML tem uma estrutura inicial, um *boilerplate*, um **esqueleto**.

Começa com uma declaração DOCTYPE, então uma *tag* `<html>` que tem dois elementos primordiais: um `<head>` e um `<body>`.

Dentro de `<head>`, geralmente existem elementos `<title>`, `<meta>` e `<link>`, que adicionam configurações como título da página, identificar o *charset* do conteúdo e até carregar o arquivo externo CSS usado na página.

Já todo o conteúdo visível da página é adicionado dentro do elemento `<body>`.

```html
<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<title>Hello, world!</title>
		<link rel="stylesheet" href="./assets/css/style.css" />
	</head>
	
	<body>
		<p>Lorem ipsum.</p>
	</body>
</html>
```

#HTML