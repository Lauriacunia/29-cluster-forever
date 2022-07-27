"ServidorExpress":{
"scope":"javascript, typescript",
"prefix":"servidor",
"description":"Servidor express",
"body":[
"import express from 'express';",
"",
"const app = express();",
"app.use(express.json());",
"app.use(express.urlencoded({ extended: true }));",
"",
"const PORT=process.env.PORT || 3000",
"const server = app.listen(PORT, () => console.log(`🚀 Server started on port http://localhost:%5C%5C$%7BPORT%7D%60))%22,
"server.on('error', (err) => console.log(err));",
]
},
