---
title: react
tags:
- javascript
- html

author:
- sindey
---
### #Conceitos
- React Element
	Todo elemento React é criado com a função [[createElement]]. O [[Babel]] é o responsável por transformar o elemento criado com [[JSX]] (que se parece com [[HTML]]) em funções de React. 
	![[Pasted image 20230620022229.png]]

### #JSX

##### o que é e onde usa
 JSX ([[JavaScript]] [[XML]]) é uma extensão de sintaxe usada principalmente no desenvolvimento de aplicações web com a biblioteca React. Ela permite que você escreva código HTML-like dentro do JavaScript, combinando o poder do JavaScript com a facilidade de uso e expressividade do HTML.

 No JSX, você pode criar elementos HTML e componentes React usando uma sintaxe semelhante ao HTML. Por exemplo, você pode escrever um componente simples de botão da seguinte maneira:
 
```jsx
	import React from 'react';
	 function MeuBotao() { 
		 return ( <button onClick={() => console.log('Clicou no botão')}>
		  Clique aqui 
		  </button> 
		  );
	 }
```

dentro do jsx podemos utilizar as { } para executar expressões de Javascript e mostrar o resultado no DOM.
ex.:
![[Pasted image 20230620030247.png]]
podendo tambem executar funções dentro do elemento HTML 
<button> {produto1} - R$ {Math.random() *100} </button>

### #Evento 
##### o que é e o que faz
 No contexto do React, os eventos em JavaScript são usados para lidar com a interação do usuário, como cliques, digitação de teclado, passagem do mouse e muito mais. O React possui seu próprio sistema de eventos, que funciona de maneira semelhante ao JavaScript tradicional, mas com algumas diferenças importantes.

 No React, os eventos são anexados aos elementos JSX usando uma sintaxe semelhante ao HTML, usando atributos especiais começando com "on". Por exemplo, para lidar com o evento de clique em um botão, você pode usar o atributo `onClick`. 
 Veja um exemplo:
 ```jsx
	 import React from 'react';
	 
	  function MeuBotao() { 
		  const handleClick = () => {
			console.log('Clicou no botão');
		}; 
		return ( 
			<button onClick={handleClick}>
				Clique aqui 
			</button> 
		); 
	}
```
pode ser atribuido eventos diretamente aos elementos.
ex.:
![[Pasted image 20230620031329.png]]
no exemplo acima temos o evento [[onClick]] que manipulara a DOM quando o usuario clicar no elemento [[button]] no caso referido
### #componentes
##### o que é e como usar
**permite dividir a interface em pequenos elementos. São criados através de funções que retornam elementos React** 

Ex.:
![[Pasted image 20230620022830.png]]
no exemplo acima ela está retornando um elemento HTML <button> tornando ela uma função react, caso ela não retornar um elemento HTML será apenas uma função normal JavaScript

Sempre começar o nome de um componente com letra MAIUSCULA
ex.: Button, MainNav, App

permite dividir a interface em pequenos elementos. São criados através de funções que retornam elementos React

