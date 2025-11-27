# Cod Reducere Farmec

O colecție de coduri de reducere Farmec. Le folosim pentru testarea cuvintelor cheie cod reducere Farmec, voucher Farmec, cupon Farmec, și cod promotional Farmec de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-farmec` prin NPM:

```bash
npm install cod-reducere-farmec
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-farmec')

console.log(codes)

// [
//   {
//     site: 'https://www.farmec.ro',
//     cod_reducere: 'FARMEC10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-farmec a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://www.cuponescu.ro

