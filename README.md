# s02-ex01-websitecelular

## Conceitos HTML:

`HTML` = Hyper Text Markup Language

A marcação/identificação dos elementos é feita utilizando <TAGs>

A estrutura sintática dos elementos no HTML é dada  por:

`<TAG(abertura)  atributo = "valor do atributo"> Conteúdo </TAG(fechamento)>`

Algumas TAGs dispensam fechamento. Ex.: <br>, <meta>

## TAGs utilizadas no exercício (estão explicadas nos comentários do código):

```
<!--Bla--> = Comentário em HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>
<link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">
<link rel="stylesheet" href="css/style.css"> 
<body>
<div>
<h1>
<p>
<a>
 ```

## Conceitos CSS

Display:
 - Block: Ocupam todo o espaço da linha (Ex.: h1, p)
 - Inline: Ocupam apenas o espaço de seu tamanho, ficando alinhados aos outros elementos. Não permitem que suas dimensões sejam alteradas por width, por exemplo. (Ex.: a, img)
 - Inline-block: Ocupam o espaço do bloco alinhado a outros elementos (permitem que os elementos se ajustem às alterações  das dimensões aplicadas )

`/*Bla*/ - Comentário`

No CSS você sempre usa a seguinte estrutura:
```
     seletor{
        propriedade:atributo;
    {
 ```
 * Seletor = elemento ou conjunto de elementos(classes) que vc deseja alterar
 * Propriedade = características que você deseja alterar
 * Atributo = como você deseja que a propriedade se pareça 

## Etapas para realizar o exercício:

1º Passo: Estrutura HTML-  Definir as divs que serão utilizadas ("fatiar") . A princípio será criada uma div para delimitar o texto e os links formando a coluna da esquerda

2º Passo: Criar arquivo CSS e estabelecer o Link no HTML

3º Passo: Estabelecer classes para aplicar ao CSS. É uma boa prática não fazer referencia direta às TAGs usando as classes para cumprir essa função aplicando o método BEM
