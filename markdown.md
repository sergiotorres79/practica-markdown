# Introducción a Ubuntu Server
## Conceptos Básicos

Ubuntu Server es una distribución de Linux fundamental en la administración de sistemas. Es crucial dominar la consola para gestionar los **permisos de usuario**, configurar la red y editar ficheros de forma *rápida*. Un comando muy utilizado a diario es el `ls -l` para listar los archivos de un directorio.

### Ejemplo de configuración de red
```bash
sudo nano /etc/netplan/00-installer-config.yaml
sudo netplan apply

