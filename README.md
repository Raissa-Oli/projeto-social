# 📱 Redes Sociais

Projeto de uma interface que simula um **smartphone com acesso a diferentes redes sociais**, desenvolvido durante os estudos de **HTML5 e CSS3**.

A página possui uma tela central que utiliza um `iframe` para carregar diferentes páginas, permitindo que o usuário navegue entre as redes sociais através dos ícones apresentados ao lado.

## 🌐 Projeto online

Acesse o projeto publicado pelo GitHub Pages:

🔗 **[Visualizar o projeto Redes Sociais](https://raissa-oli.github.io/projeto-social/)**

## 📖 Sobre o projeto

O objetivo do projeto é criar uma interface inspirada em um celular, na qual o usuário pode selecionar diferentes redes sociais e visualizar seus conteúdos dentro da tela principal.

Ao clicar em um dos ícones, a página correspondente é carregada dentro do `iframe`, sem que seja necessário sair da página principal.

Entre as opções disponíveis estão:

* 🏠 Home
* ▶️ YouTube
* 💻 GitHub
* 📷 Instagram
* 🐦 Twitter
* 📘 Facebook

## 🛠️ Tecnologias utilizadas

* **HTML5**
* **CSS3**
* **Iframe**
* **Git**
* **GitHub**
* **GitHub Pages**

## 📂 Estrutura do projeto

```text
projeto-social/
│
├── index.html
├── home.html
├── youtube.html
├── github.html
├── instagram.html
├── twitter.html
├── facebook.html
├── favicon.ico
│
├── estilos/
│   └── style.css
│
└── imagens/
    ├── logo-home.jpg
    ├── logo-youtube.jpg
    ├── logo-github.jpg
    ├── logo-instagram.jpg
    ├── logo-twitter.jpg
    └── logo-facebook.jpg
```

## 🎯 Funcionalidades

### 📱 Interface de smartphone

O projeto possui uma área central que representa a tela de um celular.

O conteúdo das páginas é exibido dentro de um `iframe`, proporcionando uma experiência de navegação semelhante à utilização de um aplicativo.

### 🔗 Navegação entre páginas

Os ícones das redes sociais funcionam como links e utilizam o atributo `target` para determinar que a página deve ser aberta dentro do `iframe`.

Exemplo:

```html
<a href="youtube.html" target="tela">
    <img src="imagens/logo-youtube.jpg" alt="logo-youtube">
</a>
```

Dessa forma, ao clicar no ícone do YouTube, o arquivo `youtube.html` é carregado dentro do elemento com o nome `tela`.

### 🖼️ Utilização de imagens

Cada rede social possui uma imagem utilizada como botão de navegação.

As imagens são organizadas dentro da pasta `imagens`, facilitando a organização dos arquivos do projeto.

## 📚 O que foi praticado

Durante o desenvolvimento do projeto foram praticados conceitos importantes de desenvolvimento web:

* Estrutura básica do HTML5;
* Utilização de links;
* Utilização do atributo `target`;
* Utilização de `iframe`;
* Inserção de imagens;
* Utilização de `alt` em imagens;
* Organização de arquivos e pastas;
* Classes e IDs;
* Estilização com CSS3;
* Criação de interfaces inspiradas em dispositivos;
* Publicação de projetos utilizando GitHub Pages.

## 💡 Aprendizados

Este projeto permitiu praticar principalmente a utilização de **iframes e navegação entre páginas HTML**.

Também ajudou a compreender como diferentes arquivos HTML podem trabalhar juntos em um mesmo projeto e como o CSS pode ser utilizado para criar uma interface visual inspirada em um dispositivo móvel.

## 🚀 Publicação

O projeto foi publicado utilizando **GitHub Pages**, permitindo seu acesso diretamente pelo navegador.

🔗 **[Acessar o projeto](https://raissa-oli.github.io/projeto-social/)**

## 👩‍💻 Autora

**Raissa**

Projeto desenvolvido como parte dos estudos de **Desenvolvimento Web**.
