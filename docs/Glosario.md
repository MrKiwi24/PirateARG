# Terminología General

## FOSS o FLOSS
**Free (Libre) Open Source Software** - Software Libre (no solo grátis) de Código Abierto. FOSS son programas, apps, o cualquier tipo de ejecutable que tiene como propósito ser de código abierto y con una licencia que permite a cualquier persona modificar, y usar el software libremente. Ejemplos populares:

- [Godot](https://godotengine.org/)
- [Blender](https://www.blender.org/)
- [Krita](https://krita.org/es/)

Link a [Wikipedia](https://es.wikipedia.org/wiki/Software_libre_y_de_c%C3%B3digo_abierto) para mas info e historia.

## Descarga Directa / Direct Download / DD

A diferencia de los [[{torrents}|Glosario#torrent-protocolo-bittorrent]], las descargas directas dependen de un servidor. Por lo que no importan los leechers y los seeders, solo si el server que hostea el archivo que quieras descargar está activo, o no.

Los archivos descargados por este método se suelen encontrar divididos en partes, por lo que un gestor de descargas como [JDownloader](https://jdownloader.org/es/download/index) se recomienda.

# Terminología de navegadores (web browsers)

## Chromium

Chromium es un navegador web [[{FOSS}|Glosario#foss-o-floss]] muy popular. Es la base de navegadores modernos como:

- Chromium
- Google Chrome
- Opera
- Opera GX
- Brave
- Microsoft Edge

Que un navegador esté basado en Chromium no es algo inherentemente malo, pero las empresas que usan Chromium como base aprovechan su libertad para llenarlo de cosas que afectan al consumidor, como [Google detectando adblockers y no dejar a usuarios usar Youtube](https://www.genbeta.com/actualidad/youtube-limita-ver-videos-a-que-tengan-adblock-e-internet-estalla-esto-que-aparece-bloqueas-anuncios).

Link de [Wikipedia](https://es.wikipedia.org/wiki/Chromium_(navegador)) para mas info e historia

## Ads

Publicidades en páginas web.

## Pop Up ads

Publicidades mayormente engañosas que buscan sacarte provecho. Se abren en pestañas o ventanas diferentes y suelen ser "Ganaste un sorteo" o "Su PC ha sido infectado con un virus. Llame a ". **NO SON REALES**

## Redirects

Imágenes, gifs, o links potencialmente maliciosos que te redirigen a una página externa. Suelen ser imágenes de botones de descarga, o algún botón medio escondido.

## Adblockers

Los adblockers son extensiones de navegador que buscan bloquear ads, pop ups y redirects. La mas confiable es uBlock Origin.

Google busca inutilizar adblockers con el manifest v3. Para explicarlo de manera simple, modifica qué tipo de información pueden obtener las extensiones, por lo que los adblockers no podrían obtener qué es y no es un ad.


# Terminología de Torrents

## Torrent (protocolo BitTorrent)

Protocolo p2p (peer to peer, punto a punto) que permite y facilita el intercambio de información. No cuenta con un servidor que hostea los archivos, si no que depende de que la gente se comparta los archivos entre ellos. Explicado de manera **muy** simplificada:

Los [[{leechers]|Glosario#leecher]] le piden a los [[{seeders}|Glosario#seeder]] archivos específicos para descargar. El [[{cliente torrent}|Glosario#cliente-torrent]] conecta a ese leecher con todos los seeders disponibles para descargar los archivos.

Una vez que el leecher termina de descargar el archivo, y si se deja el cliente torrent abierto, se transforma en seeder y comparte lo descargado a otros leechers. Es decir que una vez que descargaste un juego, por ejemplo, solo al dejar tu cliente torrent abierto ¡vas a compartírselo a otra gente automáticamente!

Así que, una vez terminada la descarga de un torrent, por cortesía, quedate seedeando el archivo que obtuviste para ayudar al pirata amigo que también lo quiera descargar en un futuro.

Link a [Wikipedia](https://es.wikipedia.org/wiki/BitTorrent) para mas info e historia.


## Leecher

Persona que está descargando un archivo mediante el protocolo bitTorrent. Obtiene los archivos directamente de los seeders. La velocidad de descarga depende de la cantidad de seeders que haya y su velocidad de subida.

## Seeder

Persona que está compartiendo (subiendo) un archivo mediante el protocolo bitTorrent a uno, o varios, leechers. Ser un seeder usa tu velocidad de subida.

## Cliente Torrent

Un programa que se encarga de conectarse con otras PCs para la descarga y subida de archivos específicos. Se suele recomendar [qBitTorrent](https://www.qbittorrent.org/). **NO USAR µTorrent** [hace unos años venía con un bitcoin miner](https://www.genbeta.com/herramientas/el-ultimo-regalito-de-utorrent-que-tu-ordenador-mine-bitcoins-sin-que-te-des-cuenta).

# Scene

La "escena" (scene) se denomina a la gente involucrada en todo lo que es piratería y las noticias que los rodean.

## DRM

Los **D**igital **R**ights **M**anagement son código o software externo al programa que nos interesa cuyo fin es protegerlo de ser copiado y distribuido. Los DRMs pueden ser algo tan simple como un dll (brutamente dicho, un archivo de texto que contiene instrucciones para cierto software) como algo tan complicado como Denuevo.

- Link a [Wikipedia](https://es.wikipedia.org/wiki/Gesti%C3%B3n_de_derechos_digitales) para mas info e historia.

Denuevo se merece una mención especial por cómo funciona y lo que es. En sus últimas versiones es un software que se programa y se incorpora al juego de manera tan intrusiva que no se puede sacar ni desactivar por completo. Solo una persona es capaz de [[{crackearlo}|Glosario#crackers]] (EMPRESS).

- Link a [Wikipedia](https://es.wikipedia.org/wiki/Denuvo) para mas info e historia de Denuevo.

## Crackers

Los crackers son personas que se dedican a romper y/o a bypassear el [[{DRM}|Glosario#drm]] para facilitar la distribución de media. Son los creadores y autores de los [[{cracks}|Glosario#crack]] necesarios para poder usar media protegida.

## Crack

Pieza de software cuyo fin es inutilizar el [[{DRM}|Glosario#drm]].

Si un software está crackeado significa que es posible de utilizar de manera pirata.

## Repackers

Los repackers son personas que se dedican a armar paquetes, llamados "repacks", que contienen lo que se quiere piratear + el [[{crack}|Glosario#crack]] para que el usuario final lo pueda usar de la manera mas sencilla posible.

El repack además de estar todo armado también puede estar MUY comprimido. Esto logra que personas con baja velocidad de internet estén menos tiempo descargando. A cambio, los tiempos de instalación son mucho mas largos por la descompresión necesaria.

Hay repackers que NO comprimen. Esto logra el efecto contrario. Archivos de descarga muy grandes, pero velocidad de instalación rápidos. Si tenés un internet rápido (100Mbps o más) estas opciones te suelen convenir mas que las comprimidas.