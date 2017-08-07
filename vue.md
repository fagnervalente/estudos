## Vue.js

## Primeiras impressões

A primeira vista estou curtindo muito o `Vue.js` pois ele se assemelha muito com o `Angular 1` na forma de se escrever. Isso torna tudo muito mais simples, pois o código fica bem legível e fácil de entender.


### Prós




### Contras


## Detalhes mega importantes

#### Não utilize arrow functions numa instância de propriedade ou callback
<img width="615" alt="screen shot 2017-08-07 at 10 48 23 am" src="https://user-images.githubusercontent.com/1047989/29029428-096862b4-7b5e-11e7-8ecf-68c31e88cd70.png">

#### Filtros são destinados apenas para manipulação de texto na view
<img width="616" alt="screen shot 2017-08-07 at 10 54 56 am" src="https://user-images.githubusercontent.com/1047989/29030180-9a2b594e-7b60-11e7-8c05-767deab52cd6.png">

#### `Computed data` usa cache e `Methods` não
 > Caso o retorno do método do `computed data` não tenha sido alterado a interface que utiliza este valor não será atualizada

#### Prefira usar `Computed date` ao invés de `watch`
