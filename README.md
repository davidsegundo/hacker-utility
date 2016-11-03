Hacker Utility
============

Hacker Utility es una herramienta diseñada para pentesters que trae consigo algunas funcionalidades para la audirtoria web.

Las funcionalidades que **Hacker Utility** trae son:
+ Dos Atack
+ Real IP Cloudflare
+ Downloader Site

### Dos Atack

Basada en los scripts de NMAP. La funcionalidad de **Dos Atack** hacer peticiones masivas a un servidor dejandolo abajo en segundos y así saber cuando un servidor es vulnerable a un ataque DoS o DDoS.

### Real IP Cloudflare

El objetivo de **Real IP Cloudflare** es burlar los *DNS* de *Cloudflare* encontrando así la IP real del servidor y con esto saber cuando la protección de los DNS esta mal configurada o es vulnerable.

### Downloader Site

Al momento de hacer la descarga de un sitio web completo, existen varias restricciones como: *UserAgent* que detectará un número de descargas inusuales por lo que bloquea el acceso, tambien puede existir una restriccion por parte de el archivo *robots.txt* que puede especificar que una aplicación determinada no pueda efectuar la descarga de este mismo.

**Downloader Site** hace la descarga de un sitio web burlando estas restricciones, con esto se puede saber cuando el servidor es vulnerable a descargas de archivos que el administrador no desea que sean descargados.
