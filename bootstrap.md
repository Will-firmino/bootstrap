# UTILIZANDO GRID E BREAKPOINTS NO BOOTSTRAP

## BREAKPOINTS
NONE -> <576 `[Menor que 576px]`. é o padrão utilizado do bootstrap, que possui o padrão de projetos `mobile first`.
SM -> >=576 <=767 `[Maior ou igual a 576px e menor ou igual a 767px]`. é utilizado normalmente para telas de celulares maiores.
MD -> >=768 <=991 `[Maior ou igual a 768px e menor ou igual a 991px]`. é utilizado normalmente para telas de tablets.
XXL -> >=1400 `[Maior ou igual a 1400px]`. é utilizado para telas de desktop.

## SISTEMA GRID
=> Por padrão, quando você aplica o sistema grid, o bootstrap divide a tela em `12 colunas`. Depois, você precisa informar quantas colunas o componente vai ocupar.
`row` -> classe do bootstrap utilizada para informar que você irá trabalhar com o sistema de grades. Faz com que os componentes dentro dele se alinhem na horizontal.
`col` -> classe do bootstrap que informa como aquele componente vai se comportar dependendo da tela que está acessando.
* Pode ser utilizada com os breakpoints e com a quantidade de colunas que o componente ocupa. Ex: `col-md-6`
`container` -> classe do bootstrap que informa que você irá encapsular outros componentes ou tags.




# Desafio
1. Quando o dispositivo acessado for um desktop acima de 1400px, deverá ser apresentado 4 cards na tela por linha.

2. Quando o dispositivo acessado for um tablet acima de 768px, deverá ser apresentado 3 cards ne tela por linha.