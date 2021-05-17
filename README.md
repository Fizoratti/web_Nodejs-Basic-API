# Docker + Node.js

Possui apenas um arquivo Dockerfile e um único arquivo javascript que expõe um endpoint que manda de volta como resposta: `Docker é fácil 🦎`. Então expõe a aplicação usando a porta `8080`.

## Instruções

Para baixar o container execute:
```bash
docker pull fizoratti/nodejs-basic-api
```

Para rodar o container execute:
```bash
docker run -p 3000:8080 d140597039b7
```

Ao abrir `localhost:3000` no navegador, deve ver algo como:

![](https://tva1.sinaimg.cn/large/008i3skNgy1gqm38zirscj30ct08bt8r.jpg)
