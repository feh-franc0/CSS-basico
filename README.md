<h1>CSS BÁSICO</h1>

## 1.Introdução - CSS Básico
### Vamos aprender a modificar e estilizar os elementos HTML com CSS.
    

### CSS INLINE
 - No CSS inline vamos criar nosso codigo CSS dentro de um atributo html,usando o style



### CSS INTERNO
 - No CSS interno vamos por nossos codigos CSS nostyle que fica dentro do head do codigo html.



### CSS EXTERNO
 - No CSS externo a gente move o nosso codigo CSS para outro arquivo,tendo um arquivo so pra CSS que é utilizado por um arquivo separado sendo somente HTML

---
## 2.CSS inline
### para usar o Css Inline é preciso por um atributo no elemento html chamado style="" e dentro dos parenteses por os codigos CSS normalmente
    <p style="color:red"> paragrafo </p>
    
---
## 3.CSS interno
### para usar o Css interno crie a tag 'style', o 'style' tem que estar dentro do 'head'
    codigo de exemplo:
    <html>
        <head>
            <style>
                p{
                    color:blue;
                }
            </style>
        </head>

        <body>
            <p> paragrafo </p>
        </body>
    </html>

---
## 4.CSS externo
### CSS externo fica em um arquivo diferente/separado do HTML,mas usando uma tag voce consegue fazer a ligação entre o HTML e o CSS,por padrao o arquivo CSS recebe o nome de 'style.css' e o arquivo HTML recebe o nome de 'index.html'
    Para fazer a ligação entre os arquivos use a Tag <link rel="stylesheet" href="style.css"> dentro da tag 'head' do HTML:

    index.html,use:
        <html>
            <head>
                <link rel="stylesheet" href="style.css">
            </head>
            <body>
                <h1> Titulo do site </h1>
            </body>
        </html>

 
    
    style.css,use:
        h1{
            color:yellow;
        }