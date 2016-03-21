# Messaging Dapp light clients


## Configuration
You need to install first the [MessagingDapp](https://github.com/fix/messagingDapp) on your local LISK testnet.

Then, copy your Dapp Id and be sure to update the source files with the correct Dapp Id:
in `desktop/index.html` and `mobile/www/index.html` find the line with :
```javascript
var dappId = "105601020317470892";
```
and update accordingly.

## Desktop
Assuming you have installed NPM.
```
cd desktop/
npm install && npm start
```

![Desktop App](http://i.imgur.com/SfRZLkE.gif)

## Mobile
Assuming you have installed and configured cordova properly.
```
cd mobile/
cordova add platform android
cordova run
```

[![Android App](https://img.youtube.com/vi/oSR85IyBHxk/0.jpg)](https://www.youtube.com/watch?v=oSR85IyBHxk)

#### License
The MIT License (MIT)

Copyright (c) 2016 Sigmeus  
