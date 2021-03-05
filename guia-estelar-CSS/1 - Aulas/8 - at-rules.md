# At-rules

* Está relacioando ao comportamento do CSS
* Começa com o sinal de `@` seguido do identificador e valor

## Exemplos comuns

- @import       /* incluir CSS externo */
- @media        /* regras condicionais para dispositivos */
- @font-face    /* fontes externas */
- @keyframes    /* Animation */

``` css
@import url("http://local.com/style.css");

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}

```