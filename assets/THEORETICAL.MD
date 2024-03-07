## Propriedades Fundamentais 

todo grid é composto de dois principais grupos
`container: o pai` e `item(s): o(s) filhos`

---
### CONTAINER (pai)

- display: grid;

- grid-template: 
  - grid-template-rows;
  - grid-template-colomns;
  -grid-template-areas;

---
### ITENS (filhos) 

- grid-colomn: 
  - grid-colomns-start ;
  - grid-colomns-end ;

- grid-row:
  - grid-row-start ;
  - grid-row-end ;

- grid-area;


---
### PROPRIEDADES DE ALINHAMENTO

Existem 9 propriedades fundamentais

*6 aplicadas em containers*

`align-content`  * posiciona o proprio elemento no eixo y *
`justify-content`* posiona o elemento no eixo x *
`place-content` * trabalha com os dois ao mesmo tempo *

`align-items`  * trabalha o eixo y, vertical *
`justify-items` * tarabalha o eixo x, horizontal *
`place-items` * trabalha com os dois ao mesmo tempo *

*3 aplicados em items*
`align-self`
`justify-self`
`place-self`

Então podemos separar em 3 grupos:
`align`,`justify`,`place`

E cada um deles irá observar ou o 
  - conteudo do elemento
  - item do elemento
  - o próprio elemento
---


### PROPRIEDADE AUTO 

- grid-auto-flow *fluxo automatico de espaçamentos, row ou colomn*
- grid-auto-rows       *espaçamaneto entre linha*
- grid-auto-columns    *espaçamento entre colunas*