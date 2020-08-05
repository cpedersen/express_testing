# Summary
This is an Express playground area for the Node --> Integration Testing part of Thinkful's coursework.

## How To
* mkdir express_testing && cd $_
* npm init -y
* npm install express morgan
* npm install mocha chai supertest nodemon -D
* touch app.js
* edit package.json
<code>
  "scripts": {
    "test": "mocha",
    "start": "node app.js",
    "dev": "nodemon app.js"
  },
</code>
* create app.js
* npm run dev