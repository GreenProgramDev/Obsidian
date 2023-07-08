## [[CSS]]
### #Conventional-Commit

- **`feat` (nova funcionalidade),**
- **`fix` (correção de bug),**
- **`docs` (documentação),**
- **`chore` (tarefas de manutenção),**
- **`style` (formatação de código)**
- `build: adiciona uma configuração nova`


1. Verifique o status dos arquivos modificados e não rastreados no seu repositório Git usando o comando `git status`. Você deve ver uma lista dos arquivos modificados e não rastreados.
    
2. Adicione os arquivos modificados para prepará-los para o commit usando o comando `git add <arquivo>` ou `git add .` para adicionar todos os arquivos modificados e não rastreados de uma vez. Por exemplo, você pode usar `git add package-lock.json package.json src/App.jsx src/index.css tailwind.config.js src/assets/image\ 7.png src/components/` para adicionar todos os arquivos listados no seu caso.
    
3. Verifique novamente o status usando o comando `git status` para garantir que todos os arquivos modificados estejam prontos para o commit e apareçam em verde.
    
4. Realize o commit com a mensagem usando o padrão convencional. O padrão convencional geralmente segue a estrutura `<tipo>(<escopo>): <mensagem>`, onde `<tipo>` pode ser **`feat` (nova funcionalidade),** **`fix` (correção de bug),** **`chore` (tarefas de manutenção),** **`docs` (documentação),** **`style` (formatação de código)** e assim por diante. Por exemplo, você pode usar `git commit -m "feat: Adicionar novos componentes e atualizar arquivos"` para realizar um commit com uma nova funcionalidade.
    

Após realizar o commit, você pode fazer o push das suas alterações para o repositório remoto usando o comando `git push`.

Lembre-se de ajustar a mensagem do commit de acordo com as alterações que você realizou no código.



1. Use verbos no tempo presente: A descrição deve começar com um verbo no tempo presente, indicando a ação que está sendo realizada. Por exemplo: "Adiciona", "Corrige", "Atualiza", "Remove".
   
2. Seja claro e específico: Descreva brevemente o objetivo da alteração de uma maneira que seja compreensível para outros colaboradores do projeto. Evite termos ambíguos ou genéricos. Seja o mais específico possível para que os outros entendam claramente o propósito da alteração.

3. Se necessário, inclua o escopo: Se a alteração estiver relacionada a um componente específico do projeto, você pode adicionar o escopo entre parênteses. Por exemplo: "(Barra de navegação)", "(API de autenticação)".
   
4. Evite referências a problemas específicos: É uma boa prática referenciar problemas ou tarefas relacionadas usando uma seção de rodapé ou tags específicas fornecidas pelo sistema de controle de versão ou ferramenta de gerenciamento de problemas. Evite incluir números de problema ou referências no início da descrição do commit.



 Conventional Commit
### #Root - var( --color-)
``` css
:root {

--color-primary: #74d3ae;

--color-secondary: #a6c48a;

--color-highlight: #fff;

--color-danger: #b80c09;

--color-light: #f6e7cb;

--color-sucess: #98CE00 ;

  
  

/* Dark shades */

--color-shade: #556;

--color-darkish: #223;

--color-dark: #112;

--color-darkest: #001;

}

```


### #Responsividade @media
```css
/* Estilos padrão para todos os dispositivos */ 
body {
	font-size: 16px; 
} 

/* Estilos para dispositivos móveis */

@media (max-width: 767px) {

body {

font-size: 14px;

}

  
  

}

  

/* Estilos para tablets e desktops */

@media (min-width: 768px) {

body {

font-size: 18px;

}

  
  

}

  

/* Estilos para monitores maiores */

@media (min-width: 1280px) {

body {

font-size: 20px;

}

  
  

}
```


### #README-md 
```md
# Title

<p align="center">
  <img src="path img or video" alt="name of the Header that represents the img">
</p>

"Description from project"

---
## Features "done in project"

- Functional Components in React
- Project Organization using React and TypeScript
- Responsive and Modern Design using CSS3
- Flexbox and Layout Fundamentals
- Usage of CSS Variables for Theme Creation
- Custom Hooks Creation
- Commits using Conventional Commits
- Typing using TypeScript
- Creation of Utilities

## Live Version

You can play the game by visiting the live version hosted at 
[here put a text that will become clickable](https://here put the URL of the Deploy done/).

## Video Tutorial

You can follow the step-by-step instructions on how to create this project by watching the [here put a text that will become clickable](https://here put the URL of the Deploy done/) (language that the video was made).

## Installation

To use this project, you need to follow these steps:

1. Clone the repository: `git clone https://here put the URL of the repositorie`
2. Install the dependencies: `npm install` or `yarn`
3. Run the application: `npm run dev` or `yarn`

Note: This project uses "Vite" to run locally. Make sure to run the project using `npm run dev` instead of `npm start`.

## Used Tools

This project uses the following tools:

- [React](https://reactjs.org/) and [ReactDOM](https://reactjs.org/docs/react-dom.html) for building the UI
- [TypeScript](https://www.typescriptlang.org/) for typing and safer development
- [Vite](https://vitejs.dev/) for fast development and production builds
- [@octokit/core](https://www.npmjs.com/package/@octokit/core) and [axios](https://axios-http.com/) for communication with the GitHub API
- [react-icons](https://react-icons.github.io/react-icons/) for UI icons

## Theme

This project uses CSS variables to set up the theme. Here are the variables used and their descriptions:

- `--color-primary`: Primary color used for headings and buttons
- `--color-secondary`: Secondary color used for background and borders
- `--color-highlight`: Highlight color used for interactive elements
- `--color-danger`: Color used to indicate errors or warnings
- `--color-light`: Light color used for text and background
- `--color-shade`: Darker shade used for text and background
- `--color-darkish`: Darkish color used for text and background
- `--color-dark`: Dark color used for text and background
- `--color-darkest`: Darkest color used for text and background

To customize the theme, simply modify the values of the variables in the `src/app.css` file.

## Usage

After the application is running, the game will start automatically. The user must choose between the two repositories presented on the screen, and the game will display the result. The user can play again by clicking the "Play Again" button.

## Contributing

To contribute to this project, please follow these guidelines:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them using Conventional Commits
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

---
## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Credits

This project was created by [arthur404dev](https://github.com/arthur404dev).
And custom by [Sidney Lima](https://github.com/GreenProgramDev).

``` Readm.md
