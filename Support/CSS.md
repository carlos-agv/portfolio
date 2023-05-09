
# CSS

[CSS](https://developer.mozilla.org/es/docs/Web/CSS).

``` CSS
/* Ejemplo */
#animaDIV {
    width: 100px;
    height: 100px;
    background-color: blue;
    position: relative;
    animation-name: moverDIV;
    animation-duration: 2s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
}

@keyframes moverDIV {
    from {
        left: 0px;
    }
    to {
        left: 200px;
    }
}
```
