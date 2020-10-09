# Recursos

Aunque **no es imprescindible para entender y aprender a crear webs con HTML5, CSS3 y JavaScript**, los siguientes conceptos sí pueden serte útiles si quieres aprender a alojar un sitio web en un servidor tuyo propio.

### Dominios y subdominios

**En este curso no aprenderemos a comprar y configurar un dominio** ya que *no* se ha considerado importante para los objetivos planteados ([hay muchos tutoriales online](https://www.google.es/webhp?ie=UTF-8#q=comprar%20y%20configurar%20un%20dominio) para aprender a hacerlo). 

Dicho esto creo que es interesante conocer qué es un dominio y qué es un subdominio:
- **[Dominios](https://es.wikipedia.org/wiki/Dominio_de_Internet)**: podemos hacer una analogía entre los dominios y los *Accesos directos* del sistema operativo. Para identificar unívocamente una carpeta en nuestro disco duro necesitamos saber la ruta (*p.e: C:\Archivos de programa\Google Chrome\bin\chrome.exe*), pues para identificar nuestros servidores en Internet necesitamos saber su [dirección IP](https://es.wikipedia.org/wiki/Direcci%C3%B3n_IP) (p.e: 213.242.93.227). Pero como recordar todos estos dígitos es muy complejo, hace años se inventaron los dominios (p.e: google.com, rauljimenez.info, etc.) que no son más que nombres que apuntan a estas direcciones (algo así como un "*acceso directo*") y que son más fáciles de recordar para un humano. Nota: los dominios se pueden alquilar por Internet y los precios normalmente varían desde los pocos € o $ hasta cientos de € o $. 
- **[Subdominos](https://es.wikipedia.org/wiki/Subdominio)**: un subdominio es un prefijo que le ponemos al dominio, por ejemplo: mail.google.com, y se puede configurar para que apunte a distintas IPs o "carpetas de nuestro disco duro". Así por ejemplo www sería también un subdominio.

Aunque el [ICANN](https://www.icann.org/) es la organización que gestiona los dominios a nivel mundial, existen multitud de empresas autorizadas para vender dominios.

[Vídeo en inglés: qué son los dominios y los DNS](https://www.youtube.com/watch?v=ip0JSUgU4os)

### Servidores
Como [hemos mencionado anteriormente](servidores_web_y_http.html) un servidor o hosting no es más que "un ordenador" donde guardamos los ficheros y el resto de información que contienen nuestro sitio web.

<small>Recordatorio: **En este curso usaremos nuestra máquina si ningún servidor HTTP ya que no nos hará falta de momento**.</small>

Estos ordenadores no tienen por qué tener nada en especial, nuestra máquina puede hacer de servidor web, pero dado que (entre otras muchas cosas), una web se espera que funcione 24 horas, 7 días a la semana y que nuestra máquina la tenemos que apagar de vez en cuando, normalmente se alquila parte de una máquina (o una máquina completa) a una empresa que se dedica exclusivamente a esto: empresas de [hosting o alojamiento web](https://es.wikipedia.org/wiki/Alojamiento_web).

Se puede acceder y gestionar estas máquinas que alquilamos en remoto de diferentes maneras: usando [clientes FTPs](https://es.wikipedia.org/wiki/Cliente_FTP)/SFTPs, paneles de control web, conexiones/clientes [SSH](https://es.wikipedia.org/wiki/Secure_Shell), etc.

### TCP
**Ignora este apartado si no has estudiado nada relacionado con informática o telecomunicaciones**. Simplemente quería hacer referencia que tanto los protocolos HTTP, como FTP, SSH, [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol), [DNS](https://en.wikipedia.org/wiki/Domain_Name_System), [POP](https://en.wikipedia.org/wiki/Post_Office_Protocol), [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol), etc. están implementados sobre TCP [(+ìnfo)](https://en.wikipedia.org/wiki/Transmission_Control_Protocol).
