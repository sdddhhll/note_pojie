# sillygirl-plugin
自写自用傻妞插件

文件已上传github：下载链接

下载到~/wizdata/crack文件夹中

docker run --name wiz --restart=always -it -d -v  ~/wizdata:/wiz/storage -v  /etc/localtime:/etc/localtime -p 8848:80 -p 9269:9269/udp -v ~/wizdata/crack/NodeRSA.js:/wiz/app/wizserver/node_modules/node-rsa/src/NodeRSA.js:ro  wiznote/wizserver



