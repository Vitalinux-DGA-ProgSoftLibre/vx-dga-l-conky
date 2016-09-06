# Paquete DEB vx-dga-l-conky

Paquete basado en el software Conky que nos permite crear y personalizar un Widget para el Escritorio.

# Usuarios Destinatarios

Se trata de un Widget personalizado que será de gran utilidad a todos los usuarios del sistema.  En concreto informará de Hora y Fecha, el estado de la memoria RAM y la CPU, en HOSTNAME de la máquina y el CID del equipo

# Aspectos Interesantes: Conky
```
El Widget es 100% personalible por el usuario final editando los archivos de conky.  Cuenta también con un lanzador para poder reiniciar el Conky en caso de ser necesario.
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```

# Como Instalar el paquete generado vx-dga-l-lupa*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-conky*.deb
```
