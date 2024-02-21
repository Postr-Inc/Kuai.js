# Kuai
<b>Kuai- Means fast in Chinese(快)</b> - kuai is a fast lightweight,simple router for SPA

```js
import Kuai from 'Kuai' 
let kuai = new Kuai(); 
 
kuai.get('/:hello', (c) => {
     c.html(`<h1>Hello Kuai</h1`)
 })
kuai.use('/:hello', () => console.log('Middleware'))
kuai.listen()

```
 
