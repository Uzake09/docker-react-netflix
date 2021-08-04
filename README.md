TODOS na pasta raiz

1º PASSO 
docker build -t node-image -f Dockerfile . 


2º PASSO
docker run -d -v ${pwd}/home/node/app -p 3000:3000 -d node-image
