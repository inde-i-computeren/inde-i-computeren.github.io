# 5 - Deklarative sprog

Der findes deklarative, imperative og precedurale sprog.
Deklarativ betyder oplysende og forklarende. Det vil sige at sproget i højere grad anvendes til at fortælle hvad man gerne vil gøre mere end hvordan.


[https://dev.to/adnanbabakan/declarative-programming-with-javascript-2h97](https://dev.to/adnanbabakan/declarative-programming-with-javascript-2h97)
Almindelig imperativ programmering
```js
let n = [-9, 87, 72, 452, 32, -9]
for(let i = 0; i < n.length; i++) {
    console.log(n[i])
}
```

Deklarativ programmering
```js
let n = [-9, 87, 72, 452, 32, -9]
n.forEach(v => console.log(v))
```


