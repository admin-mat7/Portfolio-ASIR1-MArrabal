# Proyecto de Planificación y Administración de Redes (PAR)

Este repositorio reúne el conjunto de prácticas de laboratorio correspondientes al módulo de Planificación y Administración de Redes. El trabajo abarca desde la conectividad básica y compartición de recursos hasta la administración avanzada de interfaces, diagnóstico profundo de protocolos, enrutamiento multi-nodo y segmentación de redes locales.

## Herramientas Utilizadas

* VMware Workstation Pro / Oracle VirtualBox: Entornos de virtualización avanzados para el despliegue de topologías de red multi-sistema y aislamiento de tráfico.
* Wireshark: Analizador de protocolos de red para la captura e inspección detallada de paquetes de datos a nivel de trama.
* Netplan / NetworkManager: Herramientas de gestión y configuración de red para el direccionamiento y persistencia de interfaces en entornos GNU/Linux.
* Git y GitHub: Control de versiones local y remoto para la gestión del código de red, scripts y documentación técnica.

---

## Bloques Temáticos y Prácticas de Laboratorio

### 1. Conectividad Básica y Compartición de Recursos
Despliegue inicial de comunicaciones directas y transferencia de datos entre plataformas heterogéneas:
* Interconexión Física: Configuración de conectividad directa entre estaciones de trabajo mediante cableado cruzado y directo.
* Transferencia Multiplataforma: Establecimiento de canales de comunicación y transferencia de archivos Windows-Android a través de conexiones USB.
* Entornos Virtuales Compartidos: Implementación de carpetas compartidas bidireccionales entre sistemas operativos anfitriones e invitados utilizando open-vm-tools.

### 2. Servidores Multimedia en Red Local
Instalación y administración de servicios de streaming y distribución de contenido en arquitecturas locales:
* Protocolos de Difusión: Configuración e implementación de servidores basados en el estándar DLNA bajo entornos Windows 11.
* Servidores Ligeros Linux: Despliegue y optimización del servicio miniDLNA en sistemas Ubuntu para el streaming eficiente de recursos.
* Plataformas de Entretenimiento: Instalación, gestión de bibliotecas y auditoría de rendimiento de los centros multimedia Plex y Kodi en red.

### 3. Configuración de Red y Gestión de Interfaces en Linux
Administración de los subsistemas de red en arquitecturas de escritorio y entornos de servidor dedicados:
* Modos Gráficos y CLI: Configuración de direccionamiento estático e interfaces dinámicas por DHCP mediante Network Manager en entornos de escritorio, y a través de /etc/network/interfaces en sistemas clásicos.
* Declaración Persistente: Definición y aplicación de topologías de red en formato YAML utilizando la herramienta Netplan en Ubuntu Server.
* Puentes de Red: Creación, asignación de interfaces físicas y puesta en marcha de dispositivos de puente (Bridges) virtuales.

### 4. Diagnóstico, Análisis de Tráfico y Segmentación CLI
Auditoría interna de redes, captura de tramas y aislamiento de tráfico mediante comandos nativos:
* Diagnóstico de Conectividad: Uso de herramientas de verificación de estado y descubrimiento de hosts en entornos locales mediante ping, arp y fping.
* Análisis de Paquetes: Captura de flujos de datos en tiempo real mediante tcpdump en modo consola e inspección detallada de peticiones ARP y mensajes ICMP con Wireshark.
* Inspección de Sockets y VLANs: Monitoreo activo de conexiones y puertos con la utilidad ss, y segmentación de red mediante el etiquetado de tramas bajo el estándar IEEE 802.1q (VLANs).

### 5. Enrutamiento Avanzado y Topologías Complejas
Diseño, configuración de rutas y habilitación del reenvío de paquetes en redes segmentadas multi-salto:
* Topología en Anillo (PARP604): Simulación e interconexión de una red cerrada utilizando 3 routers basados en Linux Server y 3 clientes Ubuntu Desktop independientes, configurando el reenvío de paquetes (ip_forward) y tablas de rutas estáticas.
* Escenarios Mixtos (PARP605): Implementación de un entorno de enrutamiento libre combinando pasarelas basadas en Windows Server y Ubuntu Server para garantizar la interoperabilidad de clientes en subredes aisladas.

### 6. Diseño de Infraestructura de Cableado Estructurado
Planificación técnica y normalización de sistemas de cableado e instalaciones de telecomunicaciones comerciales:
* Aplicación de Normativas: Diseño estructural de redes locales en base a los estándares internacionales TIA/EIA.
* Subsistemas de Red: Dimensionamiento de áreas de trabajo (WA), cableado horizontal, cableado vertical o backbone, y diseño logístico del cuarto de telecomunicaciones (TR).
* Componentes y Costes: Selección de categorías de cableado (Cat6/Cat6A), distribución de armarios de conexiones (Racks), paneles de parcheo (Patch Panels), canalizaciones y elaboración del presupuesto técnico.
