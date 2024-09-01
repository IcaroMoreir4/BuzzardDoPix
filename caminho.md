# Estrutura de Pastas do Projeto BuzzardPix

Este documento explica a estrutura de pastas do projeto e o propósito de cada diretório e arquivo, para ajudar na organização e compreensão do código.

## Estrutura de Pastas

```
BUZZARDPIX/
│
├── public/
│   ├── assets/
│   │   └── logo.png
│   ├── css/
│   │   ├── cadastroConta.css
│   │   ├── cores.css
│   │   ├── home.css
│   │   ├── reset.css
│   │   └── tipografia.css
│   ├── js/
│   ├── cadastraConta.html
│   └── home.html
│
├── src/
│   ├── css/
│   │   └── style.css
│   ├── html/
│   │   ├── footer.html
│   │   └── header.html
│   └── js/
│       └── app.js
│
├── .gitignore
├── baixarTailwind.md
├── caminho.md
├── package-lock.json
├── package.json
├── postcss.config.js
├── README.md
└── tailwind.config.js
```

## Descrição das Pastas e Arquivos

### 1. `public/`
- **`assets/`**: Pasta que contém arquivos estáticos como imagens, ícones, etc. 
- **`css/`**: Contém os arquivos CSS utilizados nas páginas HTML dentro da pasta `public`.
  - **`cadastroConta.css`**: Estilos específicos para a página de cadastro.
  - **`cores.css`**: Definições de cores globais do site.
  - **`home.css`**: Estilos específicos para a página principal (home).
  - **`reset.css`**: Estilos que reiniciam as configurações padrões do navegador.
  - **`tipografia.css`**: Estilos relacionados à tipografia do site.

- **`js/`**: (Pasta vazia atualmente, mas destinada a scripts JS que podem ser específicos para páginas HTML no `public`).
  
- **`cadastraConta.html`**: Página de cadastro de conta.
- **`home.html`**: Página principal do site.

### 2. `src/`
- **`css/`**: Contém arquivos CSS relacionados ao desenvolvimento principal. 
  - **`style.css`**: Estilos globais ou base do site, compilados e usados no build final.

- **`html/`**: Contém partes de páginas HTML que podem ser importadas em outras páginas, como cabeçalhos e rodapés.
  - **`footer.html`**: Rodapé reutilizável.
  - **`header.html`**: Cabeçalho reutilizável.

- **`js/`**: Contém scripts JavaScript principais.
  - **`app.js`**: Arquivo JavaScript principal do site.

### 3. Arquivos na Raiz

- **`.gitignore`**: Lista de arquivos e diretórios que o Git deve ignorar ao versionar o código.
- **`baixarTailwind.md`**: Guia de como baixar e instalar o TailwindCSS no projeto.
- **`caminho.md`**: (Arquivo que pode ser usado para descrever caminhos ou outros guias).
- **`package-lock.json`**: Arquivo gerado automaticamente que trava as versões das dependências instaladas.
- **`package.json`**: Lista de dependências do projeto e scripts npm.
- **`postcss.config.js`**: Configurações do PostCSS usadas para processar o CSS, incluindo o TailwindCSS.
- **`README.md`**: Este documento explicativo.
- **`tailwind.config.js`**: Arquivo de configuração do TailwindCSS, onde são definidos temas, plugins e paths para o PurgeCSS.

## Como Iniciar o Projeto

1. Clone o repositório.
2. Execute `npm install` para instalar todas as dependências.
3. Siga as instruções no arquivo `baixarTailwind.md` para configurar o TailwindCSS.
4. Utilize o script `npm run build:css` para gerar o arquivo CSS final a partir do Tailwind.
