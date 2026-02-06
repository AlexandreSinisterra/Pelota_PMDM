# Pelota_PMDM

Para esta tarea he programado un mapa muy simple para practicar, con **4 paredes** y **4 pickups** que se recogen con una bola.

Primero creé el mapa con los paneles. Usando **Ctrl + D** se pueden copiar objetos fácilmente.

Después creé los **pickups**, a los que hay que añadirles un **tag personalizado** y marcar la opción **Is Trigger**, ya que esto significa que cuando los toquemos ocurrirá una acción y no chocaremos contra ellos.  
Por último, añadí un **script** para que roten automáticamente.
<img width="967" height="771" alt="image" src="https://github.com/user-attachments/assets/38aff95e-e235-4fdb-ba51-fb60caa7db22" />

Al **player** le añadí el **tag Player** y un **script** para manejar el movimiento mediante **WASD** y la desaparición de los pickups cuando entra en contacto con ellos.

Por último coloqué la **cámara** en una posición cómoda. Intenté hacer un script para que la cámara siguiera a la bola, pero daba muchos bugs: a veces funcionaba y otras no y cuando lo hacía estaba en una mala posición.

<img width="679" height="499" alt="image" src="https://github.com/user-attachments/assets/a18b5dd7-2d63-404f-a407-ca9a92b8b0e6" />
