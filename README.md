# jquery-storage

jquery version based on [store.js](https://github.com/marcuswestin/store.js)

## Examples

```js
// Store 'marcus' at 'username'
$.store.set('username', 'marcus')

// Get 'username'
$.store.get('username')

// Remove 'username'
$.store.remove('username')

// Clear all keys
$.store.clear()

// Store an object literal - store.js uses JSON.stringify under the hood
$.store.set('user', { name: 'marcus', likes: 'javascript' })

// Get the stored object - store.js uses JSON.parse under the hood
var user = $.store.get('user')
alert(user.name + ' likes ' + user.likes)
```