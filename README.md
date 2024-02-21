# Kuai.js
A fast simple client side history router - used in vader.js

#Usage 

```js
import Kuai from '/src/router.js' 
const kuai = new Kuai() 
import Component from './test/index.js'
kuai.get('/test', (ctx) => {
   render(Component, document.getElementById('root'))
})
kuai.get('/home/:param', (ctx)=> ctx.html('<h1> hello world</h1>'))
kuai.listen()
```
