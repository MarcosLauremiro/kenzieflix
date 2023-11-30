# Kenzieflix

Bem-vindo ao Kenzieflix, um projeto simples de página inicial para gerenciar perfis de usuários. Esta aplicação web básica é destinada a fornecer uma interface intuitiva para identificar quem está assistindo e gerenciar perfis.

## Conteúdo

### Estrutura do HTML

O arquivo HTML (`index.html`) contém a estrutura básica da página, incluindo cabeçalho, conteúdo principal e elementos para gerenciar perfis.

### Cabeçalho
```html
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kenzieflix</title>
    <link rel="stylesheet" href="css/style.css">
</head>
```
O cabeçalho define o conjunto de caracteres, a compatibilidade com o navegador, a configuração da viewport, o título da página e inclui um link para o arquivo de estilo externo.

### Logo
```html
<header class="flex logo">
    <img src="img/logo.png" alt="Kenzieflix">
</header>
```
O cabeçalho contém o logotipo (logo.png) do Kenzieflix.

### Perfis
```html
<nav class="nav-perfis direction-row">
    <!-- ... -->
</nav>
```
A seção de perfis exibe uma lista de perfis com suas imagens e nomes.

### Botão de Gerenciamento de Perfis
```html
<div class="botao flex">
    <button class="gerenciar-perfis" type="submit">Gerenciar Perfis</button>
</div>
```
O botão "Gerenciar Perfis" permite a interação do usuário para gerenciar perfis.

## Estilos CSS

Os estilos CSS estão organizados no arquivo `style.css` e são vinculados ao HTML para estilizar a aparência da página.

## Estrutura Flexível

A estrutura do HTML utiliza flexbox para criar um layout flexível e responsivo.

## Como Contribuir

Se você quiser contribuir para este projeto ou sugerir melhorias, sinta-se à vontade para fazer um fork do repositório e enviar suas pull requests.

Obrigado por explorar o Kenzieflix!
