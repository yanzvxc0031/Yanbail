# Baileys WhisykeySocket
<p align='center'>
  <img src="https://files.catbox.moe/8jurck.jpg" width="202">
</p>

--- 

## Usage
```json
"depencies": {
  "xatabail": "github:Bealllevey62/xatabail"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('xatabail');
```


## Tutorial !
```javascript
const {
  default: makeWASocket,
  fetchLatestWAWebVersion
} = require('xatabail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: false,
  version: fetchLatestWAWebVersion()
  // Other options
});
