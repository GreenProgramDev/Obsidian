---
title: React
tags:
- css
- javascript

author:
- sindey
---
#### o que é?
- **Styled-components é o resultado de nos perguntarmos como poderiamos aprimorar [[CSS]] para estilizar sistemas de componentes [[React]].**
	 Ao focar em um único caso de uso, conseguimos otimizar a experiência para os desenvolvedores, bem como a saída para os usuários finais.


##### O que faz/se comporta >> 
Utiliza literais de modelo marcadas para estilizar seus componentes.
Ele remove o mapeamento entre componentes e estilos. Isso significa que quando você está definindo seus estilos, na verdade está criando um [[componente]] React normal, que tem seus estilos anexados a ele:

 
// The Button from the last section without the interpolations

const Button = styled.button`
  color: #BF4F74;
  font-size: 1em;
  margin: 1em;
  padding: 0.25em 1em;
  border: 2px solid #BF4F74;
  border-radius: 3px;
`;

// A new component based on Button, but with some override styles

const TomatoButton = styled(Button) `
  color: tomato;
  border-color: tomato;
`;

render(
  <div>
    <Button>Normal Button</Button>
    <TomatoButton>Tomato Button</TomatoButton>
  </div>
);

#### O que styled-components oferece:
 - **CSS crítico automático**
	 Styled-components controla quais componentes são renderizados em uma página e injeta seus estilos e nada mais, de forma totalmente automática.

- **Sem erros de nome de classe:** 
	styled-components gera nomes de classe exclusivos para seus estilos. voce nunca precisa se preocupar com duplicação, sobreposição ou erros ortográficos.

- **Exclusão mais fácil de CSS:** 
	pode ser difícil saber se um nome de classe é usado em algum lugar da sua base de código.
	styled-components torna isso óbvio, pois cada parte do estilo está vinculada a um componente específico. Se o componente não for usado (que ferramenta pode detectar) e for excluído todo os seus estilos serão excluidos com ele.

- **Estilo dinâmico simples**:
	adaptar o estilo de um componente com base em seus props ou em um tema global é simples e intuitivo, sem a necessidade de gerenciar manualmente dezenas de classes.

- **Manutenção indolor**:
	você nunca precisa procurar arquivos diferentes para encontrar o estilo que afeta seu componente, portanto, a manutenção é fácil, não importa o tamanho da sua base de código.

- **Prefixação automática do fornecedor**:
	escreva seu CSS no padrão atual e deixe os componentes estilizados cuidarem do resto.
	

#### Como instalar >>
##### [[yarn]] <> [[npm]]
A instalação de styled-components requer apenas um único comando e você está pronto para começar:

```sh
with npm
$ npm install styled-components

 with yarn
$ yarn add styled-components
```

##### Se usar **yarn** [[package.jason]] 
- Se você usar um gerenciador de pacotes como **yarn** que suporta o campo #package-jason "resoluções", também recomendamos que você adicione uma entrada correspondente ao intervalo de versão principal. Isso ajuda a evitar toda uma classe de problemas que surgem de várias versões de componentes estilizados sendo instalados em seu projeto.
```json
{
	"resoluções" : {
		"componentes de estilo" : "^5"
	 }
 }
```

##### OBSERVAÇÃO 
É altamente recomendado (mas não obrigatório) usar também o [[plug-in-Babel]]. Ele oferece muitos benefícios, como nomes de classe mais legíveis, compatibilidade de renederização do lado do servidos, pacotes menores e muito mais.

