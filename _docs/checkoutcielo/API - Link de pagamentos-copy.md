---
title: Checkout LightBox 
category: CHECKOUT CIELO
order: 1
---

### O QUE É O CHECKOUT LIGHTBOX

É uma maneira de integrar o Checkout via lightbox, permitindo que ele seja renderizado sobre o site do lojista.


### Integração com Checkout Lightbox

Para utilizar o Checkout Lightbox, é necessário referenciar a biblioteca checkout.min.js.
A biblioteca disponibiliza o namespace checkout, contendo as seguintes operações:

open(url) – Abre o Checkout Lightbox com a url recebida. A url deve ser a mesma que retorna no nó settings.checkoutUrl da resposta do PreOrder Post.
closing(handler) – recebe uma função que será executada no momento em que o Checkout Lightbox for fechado.
Finalized(handler(data)) – recebe uma função que será executada no momento em que o Checkout for finalizado. A função receberá como parâmetro o resultado da operação de checkout. (exemplo de retorno: {data:{success:true}})
