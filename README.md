### alex
---
https://github.com/get-alex/alex

```
npm install alex --global
yarn global add alex
alex example.md

npm install alex --save
```

```js
alex('We've confirmed his identity.').message

alex.html('<p class="black">He walked to class.</p>').message

alex('The `boogeyman`.').messages
alex.text('The `boogeyman.`.').messages
```

```
{
  "scripts": {
    "test-api": "ava",
    "test-doc": "alex",
    "test": "npm run test-api && npm run test-doc"
  }, 
  "devDependencies": {
   "alex": "^1.0.0",
   "ava": "^0.1.0"
  }
}
```
