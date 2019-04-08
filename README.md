# OpenWhisk
Repositorio para proyecto Serverless de fin de grado para IES Gonzalo Nazareno por Luis Manuel Raya Bernal 

Documentacion:
[Apache OpenWhisk](https://telegra.ph/Apache-OpenWhisk-en-RaspBerry-PI-3-04-04
)	


```
Instalación con Vagrant
Luis Manuel Raya Bernal - IES Gonzalo Nazareno

Necesitamos VirtualBox y Vagrant v2.2.4 instalados.
Vagrant:


wget -c https://releases.hashicorp.com/vagrant/2.2.4/vagrant_2.2.4_x86_64.deb

sudo dpkg -i vagrant_2.2.4_x86_64.deb



OpenWhisk:


git clone --depth=1 -b lean https://github.com/kpavel/incubator-openwhisk.git openwhisk


cd openwhisk/tools/vagrant

export LEAN=true


./hello


Para averiguar  el usuario y contraseña de OpenWhisk:

Vagrant ssh

wsk property get --auth | cut -c13-
```
