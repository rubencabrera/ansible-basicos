# Rol de ansible para instalar paquetes preferidos.

Rol para la configuración inicial y mantenimiento básico de equipos.

La rama master está dedicada a servidores sólo accesibles por ssh.
La rama desktop va orientada a equipos de desarrollo. No necesariamente con
entorno gráfico, pero se sobreentiende que sí. 


## Known issues / Roadmap:

### Rama desktop

- ansible (si lo queremos en localhost, hay que hacer un script en bash)
- ansible.cfg con `roles_path` y ruta `inventory`
- kubernetes

