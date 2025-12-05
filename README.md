# proiect-tw-rosoga
Materie: Tehnologii web Profesor: Sabou Gabriel Cristian Tema proiect: Aplicație web acordarea de feedback continuu Membrii:Rosoga-David Stefan-Gabriel 
probleme vizibile:
$ node server.js
[dotenv@17.2.3] injecting env (0) from .env -- tip: ⚙️  enable debug logging with { debug: true }
node:internal/errors:542
      throw error;
      ^

TypeError [ERR_INVALID_ARG_TYPE]: The "url" argument must be of type string. Received undefined
    at Url.parse (node:url:177:3)
    at Object.urlParse [as parse] (node:url:148:13)
    at new Sequelize (C:\Users\stef\Desktop\proiect tw rosoga\feedback-continuum\node_modules\sequelize\lib\sequelize.js:57:28)
    at Object.<anonymous> (C:\Users\stef\Desktop\proiect tw rosoga\feedback-continuum\models\feedback-frontend\server.js:20:19)
    at Module._compile (node:internal/modules/cjs/loader:1761:14)
    at Object..js (node:internal/modules/cjs/loader:1893:10)
    at Module.load (node:internal/modules/cjs/loader:1481:32)
    at Module._load (node:internal/modules/cjs/loader:1300:12)
    at TracingChannel.traceSync (node:diagnostics_channel:328:14)
    at wrapModuleLoad (node:internal/modules/cjs/loader:245:24) {
  code: 'ERR_INVALID_ARG_TYPE'
}

Node.js v24.11.1
