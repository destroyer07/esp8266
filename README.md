# ESP8266

Testes com o ESP8266.

## Preparando o ambiente

Os builds e flashs do projeto utilizam o [esp-open-sdk](https://github.com/pfalcon/esp-open-sdk).

Em um Linux baseado em Debian, os comandos para as configurações são:

```
sudo apt-get install make unrar autoconf automake libtool gcc g++ gperf flex bison texinfo gawk ncurses-dev libexpat-dev python python-serial sed git help2man libtool-bin python-dev
git clone --recursive https://github.com/pfalcon/esp-open-sdk.git
cd esp-open-sdk/
make STANDALONE=y
```

Após a instalação, é necessário adicionar o caminho dos binários ao path. Use os comandos a seguir, substituindo <<Usuario>> pelo nome do seu usuário:

```
$ sudo echo "PATH=/home/destroyer/esp-open-sdk/xtensa-lx106-elf/bin:\$PATH" >> /home/<<Usuario>>/.bashrc
$ sudo echo "PATH=/home/destroyer/esp-open-sdk/xtensa-lx106-elf/bin:\$PATH" >> /root/.bashrc
```


## Referências

- [Instalando o SDK do ESP8266 da forma ainda mais fácil](http://pedrominatel.com.br/pt/ferramentas/instalando-o-sdk-do-esp8266-da-forma-ainda-mais-facil/)
- [Programando de forma nativa no ESP8266 em C](http://pedrominatel.com.br/pt/esp8266/programando-de-forma-nativa-no-esp8266-em-c/)
