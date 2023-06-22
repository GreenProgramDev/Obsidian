---
title: react
tags:
- javascript
- html

author:
- sindey
---
##### Conceitos
- React Element
	Todo elemento React é criado com a função [[createElement]]. O [[Babel]] é o responsável por transformar o elemento criado com [[JSX]] (que se parece com [[HTML]]) em funções de React. 
	![[Pasted image 20230620022229.png]]

#### [[componente]] 
**permite dividir a interface em pequenos elementos. São criados através de funções que retornam elementos React** 

Ex.:
	![[Pasted image 20230620022830.png]]

#### [[JSX]]
dentro do jsx podemos utilizar as { } para executar expressões de Javascript e mostrar o resultado no DOM.
ex.:
![[Pasted image 20230620030247.png]]
podendo tambem executar funções dentro do elemento HTML 
<button> {produto1} - R$ {Math.random() *100} </button>

#### [[Evento]] 
pode ser atribuido eventos diretamente aos elementos.
ex.:
![[Pasted image 20230620031329.png]]
no exemplo acima temos o evento [[onClick]] que manipulara a DOM quando o usuario clicar no elemento [[button]] no caso referido