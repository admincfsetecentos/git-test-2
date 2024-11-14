# git-test-2

**Descrição:**

O código cria uma página simples com um formulário. Ele começa com a definição do tipo de documento `<!DOCTYPE html>`, que indica que é uma página HTML5. Dentro da tag `<html>`, o atributo `lang="pt"` especifica que o conteúdo é em português.

**Estrutura do HTML:**

- No `<head>`, há três elementos principais:
  - O `<meta charset="UTF-8">` define a codificação de caracteres, garantindo que os caracteres especiais, como acentos, sejam exibidos corretamente.
  - O `<meta name="viewport">` ajusta o layout para dispositivos móveis.
  - O `<title>` define o título da página, que aparecerá na aba do navegador.

- A seguir, o `<link>` carrega um arquivo externo de estilo CSS, chamado "styles.css", que define o visual da página.

**Corpo da página (`<body>`):**

O corpo da página contém um formulário (`<form>`), com dois campos de entrada:
  - Um para o nome (tipo "text").
  - Outro para o e-mail (tipo "email").

Ambos os campos possuem o atributo `required`, o que significa que o usuário deve preenchê-los antes de enviar o formulário. Também há um botão de envio `<button>`.

**Mensagem de Agradecimento:**

Abaixo do formulário, há uma mensagem (`<p>`) com o texto "Obrigado!", mas ela está oculta inicialmente, usando `style="display: none;"`.

**JavaScript:**

Por fim, o código inclui um arquivo JavaScript externo, "script.js", que será carregado e executado. Esse arquivo pode controlar interações ou comportamentos na página, como exibir a mensagem de agradecimento após o envio do formulário.
