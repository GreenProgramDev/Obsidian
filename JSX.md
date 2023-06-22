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