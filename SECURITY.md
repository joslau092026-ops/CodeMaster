# Seguridad del ejecutor

El código enviado por usuarios NO debe ejecutarse en Electron ni en el proceso de API. El worker debe usar sandbox efímero con: límites CPU/RAM, timeout estricto, filesystem temporal, usuario sin privilegios, red deshabilitada, sin mounts del host, sin Docker socket, sin secretos y destrucción del entorno al terminar. Los tests privados permanecen del lado servidor.

Antes de producción: revisar imágenes, permisos, seccomp/AppArmor, límites de procesos, tamaño de salida y consumo de disco.
