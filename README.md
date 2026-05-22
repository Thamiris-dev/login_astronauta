# Login do astronauta

Tela de login com tema de astronauta desenvolvida como estudo prático de **HTML5** e **CSS3**, inspirada nos exercícios e projetos do **Curso em Vídeo**.

O objetivo do projeto é praticar a criação de uma interface de login responsiva, usando formulário, imagem temática, ícones, fontes externas e Media Queries.

> Projeto de estudo. A tela representa uma interface visual de login, mas não possui backend de autenticação.

## Sobre o projeto

O `login_astronauta` apresenta uma tela de login com visual temático, usando uma imagem de astronauta e um layout adaptável para diferentes tamanhos de tela.

A página contém:

- Área visual com imagem;
- Título da tela;
- Texto introdutório;
- Campo de login/e-mail;
- Campo de senha;
- Botão de entrada;
- Link visual de recuperação de senha.

## Tecnologias utilizadas

- HTML5
- CSS3
- Media Queries
- Google Fonts
- Boxicons

## Estrutura do repositório

```text
login_astronauta/
├── estilos/
│   ├── style.css
│   └── media_query.css
├── imagens/
│   └── astronauta.png
├── .gitattributes
├── LICENSE
└── index.html
```

## O que tem dentro

### `index.html`

Arquivo principal do projeto. Ele contém a estrutura da tela de login, os campos do formulário, a importação dos estilos, a fonte externa e os ícones usados nos campos.

### `estilos/style.css`

Arquivo de estilização principal. Define a aparência da página, incluindo cores, fonte, posicionamento, formulário, botões e área de imagem.

### `estilos/media_query.css`

Arquivo usado para deixar a tela responsiva. Ele muda a organização do layout em telas maiores, permitindo que a tela de login se adapte melhor a tablets e desktops.

### `imagens/astronauta.png`

Imagem temática utilizada na composição visual do projeto.

## Como executar o projeto

1. Baixe ou clone este repositório:

```bash
git clone https://github.com/thamiscoder/login_astronauta.git
```

2. Acesse a pasta do projeto:

```bash
cd login_astronauta
```

3. Abra o arquivo `index.html` no navegador.

Também é possível executar usando a extensão **Live Server** no Visual Studio Code.

## Observação sobre o formulário

O formulário aponta para:

```html
<form action="login.php" method="post" autocomplete="off">
```

Mas o repositório não possui um arquivo `login.php`. Por isso, o foco deste projeto é o aprendizado de interface, responsividade e organização visual, não o processamento real de login.

## Aprendizados praticados

- Criação de tela de login;
- Uso de HTML semântico;
- Formulários com campos obrigatórios;
- Estilização com CSS;
- Layout responsivo;
- Uso de imagem temática;
- Organização de arquivos por pastas;
- Integração de ícones externos.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
