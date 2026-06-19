# Proyecto de Implantación de Sistemas Operativos (ISO)

Este repositorio reúne el conjunto de prácticas de laboratorio correspondientes al módulo de Implantación de Sistemas Operativos. El trabajo abarca desde la virtualización básica y configuración de red hasta la administración avanzada del almacenamiento mediante particionado clásico y gestión de volúmenes lógicos.

## Herramientas Utilizadas

* VMware Workstation Pro: Entorno de virtualización avanzado para despliegues de sistemas de escritorio y servidores.
* Oracle VirtualBox: Plataforma de virtualización de código abierto para pruebas multiplataforma.
* Git y GitHub: Control de versiones local y remoto para la gestión del código y documentación.
* GParted / fdisk / parted: Herramientas de administración de estructuras de disco en entornos GNU/Linux.

---

## Bloques Temáticos y Prácticas de Laboratorio

### 1. Virtualización e Instalación de Sistemas Operativos
Despliegue inicial de entornos operativos en plataformas virtuales compartimentadas para pruebas seguras:
* Creación paso a paso de máquinas virtuales utilizando perfiles personalizados (memoria, CPU, almacenamiento, firmware UEFI y Secure Boot).
* Instalación y configuración de sistemas de escritorio: Windows 11 (ediciones de evaluación y educación) y Ubuntu Desktop 24.04 LTS.
* Interconexión mediante traducción de direcciones de red (NAT) y configuración de credenciales de usuario locales.

### 2. Localización y Configuración Regional
Adaptación de entornos operativos multiidioma tanto en arquitecturas de escritorio como orientadas a servidores:
* Windows y Windows Server: Instalación de paquetes de idioma adicionales, reconfiguración del entorno gráfico para mostrar el sistema y configuración de opciones de entrada y teclados.
* Ubuntu y Ubuntu Server: Gestión del sistema de localización en terminal mediante comandos específicos. Reconfiguración del entorno regional interactivo con la herramienta dpkg-reconfigure para la generación e implementación de locales.

### 3. Administración del Almacenamiento Estructurado
Operaciones de bajo y alto nivel para la preparación, división y mantenimiento de unidades de almacenamiento masivo:
* Particionado Tradicional (fdisk): Creación, activación (flag de arranque) y eliminación de particiones primarias, extendidas y unidades lógicas a través de la línea de comandos en discos virtuales de prueba.
* Entornos Gráficos de Gestión (GParted): Replicación de topologías de disco mediante interfaz visual, asignación de etiquetas y formateo seguro con sistemas de archivos nativos (ext4, linux-swap).
* Instalación Multi-disco: Configuración avanzada del instalador de Linux segmentando directorios del sistema en múltiples discos duros físicos virtuales diferenciados (separación de directorios para arranque, raíz, variables del sistema y datos de usuario).

### 4. Conectividad, Resolución de Nombres y Seguridad en Red
Configuración del direccionamiento y control de tráfico de datos en entornos Windows y GNU/Linux:
* Direccionamiento IP: Asignación estática de parámetros IPv4, máscaras de subred, puertas de enlace predeterminadas y servidores DNS en entornos gráficos y mediante edición de archivos YAML con la herramienta Netplan en modo consola.
* Nombres de Equipo: Modificación del hostname local para la correcta identificación de los nodos en redes corporativas.
* Firewalls y Control de Tráfico: Gestión de políticas del cortafuegos nativo UFW en sistemas Linux y uso de utilidades avanzadas de filtrado de paquetes (Simplewall) en plataformas de escritorio Windows.

### 5. Gestión Avanzada de Almacenamiento (LVM)
Implementación de la arquitectura del Administrador de Volúmenes Lógicos (LVM) en servidores Linux para la flexibilización del espacio en disco:
* Volúmenes Físicos (PV): Inicialización de dispositivos de bloques y ficheros de bucle (loopback) para su integración en el sistema de almacenamiento.
* Grupos de Volúmenes (VG): Unificación de los volúmenes físicos en un pool común de almacenamiento dinámico.
* Volúmenes Lógicos (LV): Creación y dimensionamiento de unidades lógicas con configuraciones específicas de tamaño, extensiones y entrelazado (striping).
* Operaciones LVM Avanzadas: Formateo con sistemas de archivos tradicionales (ext2, ext3, ext4), ampliación en caliente de volúmenes sin pérdida de datos y generación de instantáneas (snapshots) del estado del sistema utilizando módulos del núcleo.

### 6. Control de Versiones y Repositorios Remotos
Fundamentos de la gestión de proyectos de infraestructura de sistemas mediante herramientas de desarrollo:
* Git Local: Inicialización de repositorios, configuración de variables de identidad global, control del ciclo de vida de los archivos y confirmación de cambios (commits) en la máquina de trabajo.
* GitHub Remoto: Vinculación de repositorios locales con repositorios remotos en la nube mediante claves y URLs, carga de historiales de versiones y publicación de documentación técnica.
