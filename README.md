# Bytebank

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<p align="center">
  <a href="">
    <img src="img/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Projeto Bytebank</h3>

  <p align="center">
    Projeto criado para estudo incial do framework Angular
    <br />
  </p>
</p>

<!-- TABELA DE CONTEÚDO -->
<details open="open">
  <summary>Tabela de Conteúdo</summary>
  <ol>
    <li>
      <a href="#sobre-o-projeto">Sobre o projeto</a>
      <ul>
        <li><a href="#construcao">Construído com</a></li>
      </ul>
    </li>
    <li>
      <a href="#comecando">Começando</a>
      <ul>
        <li><a href="#prerequisitos">Pré-requisitos</a></li>
        <li><a href="#instalacao">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#uso">Uso da aplicação</a></li>
    <li><a href="#contribuicao">Contribuição</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contato">Contato</a></li>
    <li><a href="#referencias">Referências</a></li>
  </ol>
</details>

<!-- SOBRE O PROJETO -->

## Sobre o projeto

![Imagem do projeto](/img/img_sistema.png)

O projeto bytebank foi realizado com o intuito de ser um sistema base para entendimento do framework front-end Angular, utilizando componentes, módulos e outros padrões do framework.

Se trata de um sistema simples de transferência, onde atualmente temos apenas a funcionalidade de realizar nova transferencia e de visualizar o extrato. Mantendo o cenário de SPA.

### Constrúido com

Framework e ferramenta utilizadas neste projeto:

- [Angular v10.1.6](https://angular.io/docs)

- [Json-server](https://www.npmjs.com/package/json-server)

## Começando

Para iniciar nosso projeto é preciso ter o Angular v10.1.6 em sua máquina. E em sequência podemos dar ínicio ao projeto.

### Pré-requisitos

- npm

```sh
npm install npm@latest -g
```

- Angular 10.1.6

```sh
npm install -g @angular/cli@10.1.6.
```

### Instalação

1. Clone o repositório em alguma pasta em sua workspace

2. Ative seu terminal apontado para esse determinado diretório

3. Build a aplicação, através do terminal

```sh
ng build
```

4. Inicie o servidor

```sh
ng serve -open
```

## Uso da aplicação

Em nosso projeto iniciamos com o componente de nova transferência, onde colocamos um valor e um destino para transferência:

![Imagem do projeto](/img/Screenshot_6.png)

Após efetuar a transferência iremos chamar o componente de extrato, que contém o nosso histórico de transferência com a adição do timestamp.

![Imagem do projeto](/img/img_sistema.png)

## Contact

Matheus Poda - matskira14@gmail.com

Link do projeto: https://github.com/matskira/angular_bytebank

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/matheus-poda-44663b199/
[product-screenshot]: images/screenshot.png
