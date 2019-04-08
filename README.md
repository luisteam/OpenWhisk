# OpenWhisk
Repositorio para proyecto Serverless de fin de grado para IES Gonzalo Nazareno por Luis Manuel Raya Bernal 

Documentacion:
[Apache OpenWhisk](https://telegra.ph/Apache-OpenWhisk-en-RaspBerry-PI-3-04-04
)	


```
Instalación de Docker:

sudo apt-get update


sudo apt-get install \

   apt-transport-https \

   ca-certificates \

   curl \

   gnupg2 \

   software-properties-common


curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -


sudo apt-key fingerprint 0EBFCD88


sudo add-apt-repository \

  "deb [arch=amd64] https://download.docker.com/linux/debian \

  $(lsb_release -cs) \

  stable"


sudo apt-get update


sudo apt-get install docker-ce docker-ce-cli containerd.io


Instalacion DockerCompose:


sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose


sudo chmod +x /usr/local/bin/docker-compose


sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose


Instalación OpenWhisk:

git clone -b lean https://github.com/kpavel/incubator-openwhisk-devtools.git

cd docker-compose-lean/docker-compose

make quick-start
```
