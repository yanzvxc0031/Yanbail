# Baileys WhisykeySocket
<p align='center'>
  <img src="https://files.catbox.moe/6b68hu.jpg" width="500">
</p>

--- 

## Usage
```json
"depencies": {
  "Yanbail": "github:yanzvxc0031/Yanbail"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('Yanbail');
```


## Tutorial !
```javascript
const {
  default: makeWASocket,
  fetchLatestWAWebVersion
} = require('Yanbail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: false,
  version: fetchLatestWAWebVersion()
  // Other options
});
