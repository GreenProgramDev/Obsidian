## [[CSS]]
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

