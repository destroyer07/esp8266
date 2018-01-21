# ESP8266

Testes com o ESP8266.

## Preparando o ambiente

O ambiente utilizado para o build do projeto foi criado apartir do blog do Pedro Minatel, [neste link](http://pedrominatel.com.br/pt/ferramentas/instalando-o-sdk-do-esp8266-da-forma-ainda-mais-facil/). Porém, alguns pacotes extras foram necessários.

Utilizando um Linux baseado em Debian, os comandos para a instalação são:

```
sudo apt-get install make unrar autoconf automake libtool gcc g++ gperf flex bison texinfo gawk ncurses-dev libexpat-dev python python-serial sed git help2man libtool-bin python-dev
git clone --recursive https://github.com/pfalcon/esp-open-sdk.git
cd esp-open-sdk/
make STANDALONE=y

```
