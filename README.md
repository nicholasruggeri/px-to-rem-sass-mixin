# Px to Rem Sass Mixin

Just a simple Sass mixin to convert ANY pixel value to rem.

```
p {
    font-size: rem(20);     // --> font-size: 1.25rem
    line-height: rem(40);   // --> line-height: 2.5rem
}

div {
    padding: 0 rem(50);         // --> padding: 0 3.125rem
    margin: rem(20) rem(50);    // --> margin: 1.25rem 3.125rem;
}
```