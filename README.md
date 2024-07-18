# webproject
quero exibir aqui transmissao de webrtc
atraves do navegador estou preste
a fazer  meu site de transmissao de
conteudo, porem uso o obstudio nao
estou trabalhando com o objetivo de usar
gstreammer, porem ainda nao, falta ajustar
os comandos, porem com obstudio consigo
um melhor uso da tela e outras funcoees,
estou tentando integrar com android 
studio, ja funciona porem precisa de ajustes.

Uso o projeto de outra pessoa, porem fiz o site
html onde passei os comandos necessarios para integrar
com obstudio.

## Instalacao
docker run --rm -it --network=host bluenviron/mediamtx:latest

## Chamar o servidor

docker run --rm -it \
-e MTX_PROTOCOLS=tcp \
-e MTX_WEBRTCADDITIONALHOSTS=192.168.x.x \
-p 8554:8554 \
-p 1935:1935 \
-p 8888:8888 \
-p 8889:8889 \
-p 8890:8890/udp \
-p 8189:8189/udp \
bluenviron/mediamtx

-e MTX_WEBRTCADDITIONALHOSTS=192.168.x.x \ aqui o ip da maquina server
no meu caso 192.168.1.67

http://192.168.1.67:8889/mya/whip
transmitir para o server o mya eu que coloquei voce pode botar outro/
porem o whip nao especifico olha agora

estou ajustando com objetivo de abrir direto como fosse um programa

vou parar por aqui posso botar outras paradas
