##### o que é e o que faz
 No contexto do React, os eventos em JavaScript são usados para lidar com a interação do usuário, como cliques, digitação de teclado, passagem do mouse e muito mais. O React possui seu próprio sistema de eventos, que funciona de maneira semelhante ao JavaScript tradicional, mas com algumas diferenças importantes.

 No React, os eventos são anexados aos elementos JSX usando uma sintaxe semelhante ao HTML, usando atributos especiais começando com "on". Por exemplo, para lidar com o evento de clique em um botão, você pode usar o atributo `onClick`. 
	 Veja um exemplo:
	 
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