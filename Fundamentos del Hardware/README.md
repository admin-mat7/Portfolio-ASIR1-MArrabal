# Fundamentos del Hardware (FH)

Este módulo abarca el estudio de la arquitectura física de los computadores, la gestión y optimización de los sistemas de almacenamiento, el análisis de las infraestructuras de alimentación eléctrica y los fundamentos de la virtualización tanto en entornos locales como en la nube.

---

## Evidencias Destacadas

### 1. Implementación de Directivas de Copias de Seguridad y Almacenamiento Redundante
* **Descripción:** Configuración de un entorno de pruebas basado en una máquina virtual con Windows 11 para la gestión avanzada de almacenamiento. Se realizó el aprovisionamiento de discos virtuales adicionales de 5 GB y 10 GB a través del hipervisor. Posteriormente, se inicializaron las unidades en el Administrador de discos de Windows para establecer un volumen reflejado (RAID 1), garantizando la tolerancia a fallos mediante la duplicación de datos en espejo. Sobre esta infraestructura se desplegó el software Uranium Backup para planificar, ejecutar y monitorizar tareas automatizadas de copias de seguridad completas, diferenciales e incrementales de estructuras de directorios locales.
* **Competencias:** Gestión de almacenamiento lógico, configuración de arrays redundantes en sistemas operativos de escritorio, automatización de respaldos y políticas de retención de datos.

### 2. Aprovisionamiento y Despliegue de Infraestructura de Computación en la Nube (Microsoft Azure)
* **Descripción:** Estudio teórico y práctico sobre los conceptos clave de la virtualización empresarial en entornos cloud, abarcando el análisis de familias de tamaños de instancias, almacenamiento desagregado (HDD Estándar, SSD Estándar y Premium), regiones de red, zonas de disponibilidad y dominios de fallo para mitigar interrupciones de hardware localized. La fase práctica consistió en la creación de una máquina virtual Linux (Ubuntu 24.04 LTS) dentro de la suscripción Azure for Students, asociando el recurso a un grupo de seguridad de red (NSG) configurado con reglas estrictas de firewall para permitir el tráfico perimetral exclusivamente a través del puerto 22 (SSH). El proceso concluyó con la verificación de la conectividad mediante una consola de comandos local empleando direccionamiento IP público.
* **Competencias:** Arquitectura en la nube, administración de seguridad perimetral (Firewall/NSG), aprovisionamiento de recursos bajo demanda y administración remota de sistemas GNU/Linux.

### 3. Sistemas de Alimentación y Continuidad Eléctrica en Entornos Críticos
* **Descripción:** Trabajo de investigación técnica centrado en las fuentes de alimentación conmutadas y los Sistemas de Alimentación Ininterrumpida (SAI) como barreras de defensa fundamentales ante anomalías en el suministro eléctrico (picos de tensión, microcortes, oscilaciones prolongadas y ruido armónico). Se analizaron las diferencias operativas y de coste entre las topologías de SAIs Off-Line, Line-Interactive y On-Line de doble conversión, evaluando criterios de compra para datacenters como el cálculo de potencia en Voltio-Amperios con un margen de seguridad del 25%, la transición hacia baterías de iones de litio y las tecnologías de integración IoT vigentes en el mercado actual.
* **Competencias:** Continuidad de negocio, protección de infraestructuras críticas, eficiencia térmica y dimensionamiento eléctrico de servidores.

### 4. Anatomía, Evolución y Análisis del Mercado de Arquitecturas Gráficas
* **Descripción:** Análisis técnico sobre el funcionamiento interno de las tarjetas gráficas (GPU) y su rol en la liberación de carga de cálculo geométrico respecto al procesador central. El estudio profundizó en componentes esenciales de la placa lógica (VRAM GDDR6, VRM, buses PCI Express, Frame Buffer y RAMDAC) y en métricas de rendimiento visual como la tasa de refresco (Hz), resolución y tasas de fotogramas por segundo (FPS). Adicionalmente, se elaboró una comparativa de mercado estructurada por gamas de rendimiento entre los principales fabricantes del sector (NVIDIA, AMD e Intel), evaluando la introducción de tecnologías de reconstrucción de rayos y generación de fotogramas asistida por Inteligencia Artificial (DLSS y FSR).
* **Competencias:** Evaluación de rendimiento de hardware, arquitectura interna de componentes multimedia y análisis de viabilidad tecnológica.
