# Instalação da ferramenta Scrcpy no Ubuntu 20.04.

Esta ferramenta tem a funcionalidade de espelhar seu celular android em seu SO. 


# Instalação:


Seu Android deve ter a versão 5.0 ou superior e estar com o modo desenvolverdor habilitado

## Em seu Android navegue:

*configuração->Sobre o Telefone->Informações do Software->Número de compilação.*

**Após vizualizar a opção Número de compilação pressione de 5 a mais vezes em cima da opção, isso varia de modelo 
e versão de Android.Outro ponto 
é que no SO baseado em Ubuntu, você precisa de ter instalado o gerenciador de pacotes snap e para sua 
instalação digite:**

`sudo apt-get install snap`

Após a instalação do gerenciador de pacotes snap, instale o scrcpy em seu SO

`sudo snap install scrcpy`

## Verificando dipositivo

Verifique se o dispositivos esta conectado realmente no Computador, no terminal digite  o comando:

`adb devices -l`

Este comando listará os dispositivos conectados

## Agora com o snap intalado e com seu Android conectado, no terminal entre com o comando:

`scrcpy`

Pronto, seu Android será espelhado no SO!

Para mais detalhes:

[scrcpy](https://github.com/Genymobile/scrcpy)
