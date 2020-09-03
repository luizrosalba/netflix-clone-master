# Recriando a página da Netflix 
Neste projeto utilizamos nosso conhecimentos de css , HTML e javascript para recriar um front-end semelhante ao da gigante do streaming Netflix
- Melhora o contraste do texto 
```
 background: linear-gradient(rgba(0,0,0,.50),rgba(0,0,0,.50)100%),  url('../img/capa-house.jpg');
```` 
- Para renderizar o botao da maneira correta independete da plataforma 
-  <button role="button" class="botao">
- display : flex; joga os elementos para linha 
- flex-direction: column ; altera para coluna 
-justify context sempre segue a direção do flex direction 
-align-items: flex-start; alinha pel inicio (a esquerda) do flex column
- uma div filha (que nao é principal, ou seja não é filha direta de um elemento que foi definido como flex) vem criada por padrão com display:  block; 
- https://fontawesome.com/ site para buscar icones , atraves de um js , basta adinicionar o link que ele envia e vc jah pode adicionar o html do icone 
- pading cima baixo 
- pading cima direita baixo esquerda 
- .botao:hover para mudar a pintura quando passa o mouse 
- dentro de botao transition: .3s ease all; dura 3 segundos 

- icone do botao 
```
 <div class="botoes">
                    <button role="button" class="botao">
                        <i class="fas fa-play"></i>
                        ASSISTIR AGORA
                    </button>
                    <i class="fas fa-info-circle"></i>
 </div>
``` 