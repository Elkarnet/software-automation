# software-automation
EUSKARAZ
========

Euskadiko Lanbide Heziketako ikastetxeetatik abiatzen dugun ekimena da, baina edozeinek erabili ahal izango ditu hemen publikatuko diren scriptak. Eduki guztia CC-SA lizentziapean publikatzen da.

Helburua: Gure sareetako Windows PCetan instalatzen ditugun hainbat programa teknikoen "silent" moduko instalazio automatikoak egin ahal izatea.

Programak azpikarpetetan antolatuko ditugu. Eskema honetan programak instalatzeko behar diren instalazio karpetak sareko "file server" edo fitxategi zerbitzari batean daudela suposatzen dugu. Script-etan INST_SHARE aldagaia erabiliko dugu, gero bakoitzak hau bere sarean duen IP\SHARE Jarri beharko du.

Suposatzen dugu ere SHARE horretan programa bakoitza instalatzeko behar den guztia karpeta edo PATH zehatz batean egongo dela, beraz INST_PATH aldagaia erabiliko dugu hau zehazteko.

Programa bakoitzak bere berezitasun propioak izango dituenez, bere karpetan azalduko dira instalazio konkretu horretarako kontutan hartu beharrekoak.

ESPAÑOL
=======

Esta es una iniciativa impulsada desde los centros de Formación Profesiona de Euskadi, pero los scripts que aquí se publican pueden ser utilizados por quien quiera. Todo el contenido se publica bajo licencia CC-SA.

Objetivo: Poder instalar en modo "silent" los distitos programas técnicos que instalamos en los PCs de nuestras redes.

Los programas estarán organizados por carpetas. En este esquema suponemos que las carpetas necesarias para intalar los distintos programas estarán ubicados en un servidor local. En los scripts utilizaremos la variable FILESERVER, que luego cada uno tendrá que personalizar a la IP o nombre de servidor propio.

Suponemos además, que dentro de ese FILESERVER los ficheros necesarios para instalar cada programa estarán bajo una capeta o PATH específico, que será personalizado en la variable INSTFOLDER.

Dado que cada programa tendrá sus particularidades, en cada carpeta se definiran los temas a tener en cuenta para esa instalación en particular.

ENGLISH
=======

To do.
