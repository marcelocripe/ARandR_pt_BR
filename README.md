Repositório oficial do programa "ARandR"

https://github.com/chrysn/arandr/


Traduções revisadas por marcelocripe:

https://hosted.weblate.org/projects/arandr/translations/pt_BR/
e
https://github.com/marcelocripe/ARandR_pt_BR/blob/main/arandr_pt_BR.po

https://github.com/marcelocripe/ARandR_pt_BR/blob/main/arandr.desktop

Para utilizar o arquivo "arandr_pt_BR.po" e o "arandr.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados e aplique os comandos.

"arandr_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt arandr_pt_BR.po -o arandr.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp arandr.mo /usr/share/locale/pt_BR/LC_MESSAGES

"arandr.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp arandr.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
