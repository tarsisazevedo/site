+++
draft = true
title = "how to have tsuru + services"
date = "2016-10-12T23:54:04-02:00"
+++


## Instalando o tsuru

DISCLAIMER: se vc ja tem uma instalação do tsuru, pode pular para a proxima seção.

Antes de começar temos que criar uma instalação de tsuru. Para facilitar isso,
criamos um comando no nosso client para subir uma instalação all-in-one.  Para
instalar o client do tsuru, seguir os comandos abaixo.

Mac OS:

    $ brew tap 
    $ brew install --devel tsuru

Linux:

    $ sudo apt-add-repository ppa/tsuru
    $ sudo apt-get update
    $ sudo apt-get install tsuru

## Instalando postgres api

## Integrando tudo

