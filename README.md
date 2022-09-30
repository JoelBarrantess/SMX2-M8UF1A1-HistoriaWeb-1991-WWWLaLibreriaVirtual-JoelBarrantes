# El protocolo HTTP

*Hecho por Joel Barrantes*

![HTTP](https://media.giphy.com/media/zn4qMNLewG8JSmKZ4y/giphy.gif)
<br />
<br />
# INDICE.
-----------------------

### 1. Tim Berners-Lee, el creador de la web.
### 2. HTTP/0.9 – El protocolo de una sola línea
*****************************
<br />
<br />
<br />

## Tim Berners-Lee, el creador de la web

-Tim Berners-Lee introduce HTTP como una forma para que los clientes (navegadores web) se comuniquen con los servidores. 

<img src="/img/Tim_Berners_Lee.jpg" alt="Tim" width="200"/>



  
## HTTP/0.9 – El protocolo de una sola línea

-El primer borrador, HTTP v0.9, incluye solo un método, una solicitud GET, utilizada por los clientes como una forma de solo lectura para poder ver páginas web; una petición consiste simplemente en una única linea, usando el unico método posible GET, seguido por la dirección del recurso a pedir.

```
GET /miPaginaWeb.html 
```

La respuesta también es muy sencilla: solamente consiste el archivo pedido. 

```
<HTML> Una pagina web muy sencilla </HTML>
```

-Estableció la primera comunicación entre un cliente y un servidor usando el protocolo HTTP en noviembre de 1989. 

<img src="/img/HTTP_0.9.png" alt="http" width="1000"/>

