# Anime-term-
English:

A link extractor from animeflv or jkanime (it works by the same way)

It works in the following way, the first argument is the name of the anime that you wanna
watch, and the second one is the number of the chapter you wanna get.

The script throws the links from that chapter. It has a list of the servers who are more 
stable. From this servers it extract the m3u8 file and launch it with VLC visualizer.

Example:
(data base from anime flv):
 ---    animeflv naruto 5

(base base from jkanime):
 ---    animejk naruto 5

Español:

Un extractor de links de animeflv o de jkanime (funciona de la misma manera)
El primer argumento es el nombre del anime que quieres ver y el segundo es el número 
del capítulo del que quieres obtener los links

El script te muestra los links disponibles. Sobre estos links se filtran los más estables
y se extrae el archivo m3u8 y se ejecuta con VLC player.
 

Ejemplo:
(base de datos de anime flv):
 ---    animeflv naruto 5

(base de datos de jkanime):
 ---    animejk naruto 5

Install dependencies:

Remember actualize your system to install the dependencies ;)

-Arch:

 ---   sudo pacman -S vlc grep awk sed grep wget

-Debian based:

 ---   sudo apt install vlc grep awk sed grep wget

Installation: 

 ---   chmod +x anime

