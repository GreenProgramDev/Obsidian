---
author :
- Sidney Lima
Tags: 
- EC6
- JavaScript
---
### #Variaveis

### #Operadores

####  Num
![[Pasted image 20230624010242.png]]
- **Números decimais** -> usa-se o " . " (ponto) => 3.14.
- **Exponencial** -> 2e10 => que dizer que apos o " e " o valor digitado sera o numero de " 0 ".  
- **Limite de digitos** -> 15, após isso ele arredonda.

####  Operadores Aritméticos
![[Pasted image 20230624010917.png]]
- **Expoente** -> 2 ** 4 => **2 * 2 * 2 * 2** = 16
- **Modulo** -> 14 % 5 => vai da uma divisão não exata no entando usando (% -> modulo) ele ira pegar o ultimo numero proximo que seria = 3 pois seria 2.8 e o inteiro mais proximo para cima é o 3

####  Operadores Aritméticos ***(Strings)***
![[Pasted image 20230624012235.png]]
- **Soma** -> ele vai concatenar pois nao existe soma de *String* com  *Num*
- **Subtração** -> sim ele ira subtrair pois ele converte porém so pode ter *números* dentro da *string*.
- **Divisão** -> ele ira dividir ***String*** por ***Num*** se tiver apenas **numeros**, caso tenha characters diferentes ele ira dar ***NaN***. 

####  A ordem Importa
![[Pasted image 20230624013041.png]]

####  Operadores Aritméticos Unários
![[Pasted image 20230624015504.png]]
- **+** idade -> o ato de colocar o sinal de **+** na frente da *string* fara com que a **soma** aconteça por que ele passa a conhecer como ***num***, ele aceita ter **espaços** dentro da ***string*** mas não permite que tenha outros tipo de caracter que não seja ***num*** então saira NaN

####  Operador Lógico de Negação
![[Pasted image 20230624024744.png]]
***OBS.:*** o mesmo serve para o contrario, sempre que tiver o operador " ***!*** " ele ira tornar o contrario.

####  Operador de comparação
![[Pasted image 20230624025608.png]]
***obs.:*** nunca usar " ***= >*** " pois e reservado para o uso da ***Arrow Function***
![[Pasted image 20230624025840.png]]
***obs.:*** 
- se tiver so " = " chama-se de ***atribuir, atribuição ou recebe*** 
-  o Ideal e sempre utilizar ***" === "*** quando for ***verificar*** se e **Identico** e usar " == " para ***verificar*** se e **igual** e nao **iden
- tico**


####  Operador Lógicos &&
![[Pasted image 20230624031620.png]]
- o ***primeiro*** **falso** que for **encontrado** sera *Retornado*
- se ***não*** encontrar nenhum valor *falso* ele *retorna* o **ultimo** ***Verdadeiro***
- no caso das 2 strings ele vai retornar o ultimo valor pois a string nao esta vazia
- no caso da subtracao e da soma ele retorna falso por que " 0 " e um valor falso
- na expressao ele retornou true por que foi uma uma comparação de maior e menor

####  Operador Lógicos ||
![[Pasted image 20230624032444.png]]
- sempre retorna o **primeiro** ***verdadeiro*** que ele encotrar, caso nao encontre ele retorna o ultimo falso.
- mesmo que a primeira condição for false ele ira verificar a segunda ou demais condições para verificar se existirar um verdadeiro para retornar.
	-> se apos a **condição** vier o ***&&*** a regra que valera de *verificação* sera a de ***&&*** ele ira *retornar* o primeiro ***falso***, afinal a primeira *condição* ja foi lida e a segunda passou a ser feita por outro *operador* *logico*.



### #Condicional
####  Boolean
![[Pasted image 20230624022610.png]]
- Usado para Testar Coisas
- Retornar Verdadeiro => *true* **or** Falso => *false*
![[Pasted image 20230624024420.png]]
![[Pasted image 20230624024524.png]]



#### If e Else "basico"
![[Pasted image 20230624022645.png]]
![[Pasted image 20230624023226.png]]

- 


#### Switch
![[Pasted image 20230624035306.png]]

### #Funções
![[Pasted image 20230624040625.png]]
Obs.: qualquer nome que tiver um ( ) ao lado e uma funcao
ex.: contador( ), data( ), newData( )

![[Pasted image 20230624041107.png]]

#### Parametros e Argumentos 
![[Pasted image 20230626192626.png]]

#### Evento
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
