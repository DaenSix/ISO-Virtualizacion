# ISO-Virtualizacion
# Virtualización

## Índice
1. [Introducción](#1)  
2. [Conceptos básicos](#2)  
3. [Tipos de virtualización](#3)  
4. [Ventajas y desventajas](#ventajas-y-desventajas)  
5. [Ejemplos y usos actuales](#ejemplos-y-usos-actuales)  
6. [Conclusión](#conclusion)  
7. [Licencia](#licencia)

---

## Introducción
La **virtualización** es una técnica que permite crear una versión virtual de un recurso físico, como un servidor, sistema operativo, dispositivo de almacenamiento o red.  
Gracias a esta tecnología, un solo equipo físico puede ejecutar varios entornos independientes al mismo tiempo, mejorando la eficiencia y reduciendo costes.  

Este concepto surgió en la década de 1960 con los grandes ordenadores (*mainframes*), pero se ha popularizado en las últimas décadas con la expansión de los **centros de datos**, la **computación en la nube** y las necesidades de desarrollo de software moderno.

---

## Conceptos básicos
Antes de profundizar, es importante conocer algunos términos clave:

- **Host (anfitrión):** equipo físico que proporciona los recursos (CPU, RAM, disco, red) a las máquinas virtuales.  
- **Guest (invitado):** máquina virtual que se ejecuta dentro del host, con su propio sistema operativo y aplicaciones.  
- **Hipervisor:** programa o capa de software que permite crear, ejecutar y administrar máquinas virtuales.  
- **Snapshot:** copia instantánea del estado de una máquina virtual, útil para pruebas o recuperación de errores.  
- **Virtual Machine (VM):** sistema operativo completo que funciona de manera independiente dentro del host.  
- **Contenedor:** entorno ligero que comparte el mismo sistema operativo del host, pero mantiene aislamiento entre aplicaciones.

---

## Tipos de virtualización
Existen varios tipos de virtualización, según el recurso o nivel al que se aplique:

### 1. Virtualización de hardware
Permite ejecutar varios sistemas operativos en un solo equipo físico.  
Ejemplo: ejecutar **Windows** y **Linux** al mismo tiempo en un PC usando **VMware**, **VirtualBox** o **Hyper-V**.

### 2. Virtualización de sistema operativo
Permite crear múltiples entornos aislados dentro de un mismo sistema operativo, compartiendo el núcleo.  
Ejemplo: **Docker** o **LXC**, que se usan ampliamente en desarrollo y despliegue de aplicaciones.

### 3. Virtualización de red
Consiste en crear redes virtuales que funcionan sobre el hardware físico, pero de manera independiente.  
Ejemplo: **VLANs** o **SDN (Software Defined Networking)**.

### 4. Virtualización de almacenamiento
Combina varios dispositivos de almacenamiento físico (discos duros, SSD, NAS) en un único sistema lógico, simplificando la gestión.  
Ejemplo: **RAID**, **NAS**, o **SAN**.

### 5. Virtualización de escritorio
Permite acceder a un entorno de escritorio remoto desde cualquier dispositivo.  
Ejemplo: **Citrix**, **VMware Horizon**, o **Microsoft Remote Desktop**.

---

## Ventajas y desventajas

### Ventajas
- **Ahorro de costes:** se reduce el número de servidores físicos.  
- **Mejor aprovechamiento del hardware:** los recursos se reparten de forma más eficiente.  
- **Facilidad de administración:** las máquinas virtuales son fáciles de crear, mover o eliminar.  
- **Entornos de prueba seguros:** se pueden realizar pruebas sin afectar al sistema principal.  
- **Recuperación ante desastres:** las copias o snapshots facilitan la restauración rápida.

### Desventajas
- **Requiere recursos potentes:** el host debe tener suficiente CPU, RAM y almacenamiento.  
- **Dependencia del hipervisor:** si este falla, puede afectar a todas las máquinas virtuales.  
- **Rendimiento inferior al hardware nativo:** aunque la diferencia es mínima con los hipervisores modernos.  
- **Configuración inicial compleja:** sobre todo en entornos empresariales o en la nube.

---

## Ejemplos y usos actuales
Hoy en día, la virtualización está presente en casi todos los ámbitos de la informática:

- **Educación:** permite a los estudiantes practicar con sistemas operativos sin riesgo.  
- **Empresas:** se crean servidores virtuales para correo, bases de datos o aplicaciones internas.  
- **Desarrollo de software:** los programadores usan contenedores o máquinas virtuales para probar sus programas.  
- **Computación en la nube:** servicios como **AWS**, **Azure** o **Google Cloud** utilizan virtualización a gran escala para ofrecer recursos bajo demanda.  
- **Ciberseguridad:** se usan entornos virtuales para analizar malware sin comprometer el sistema real.

---

## Conclusión
La virtualización es una de las tecnologías más importantes del mundo moderno.  
Permite optimizar recursos, reducir costes y mejorar la seguridad al separar los entornos de trabajo.  
Además, es la base de otras tecnologías como la **nube**, los **contenedores** y la **infraestructura como servicio (IaaS)**.  
En resumen, comprender cómo funciona la virtualización es esencial para cualquier profesional de la informática actual.

---

## Licencia
Este documento está disponible bajo la licencia **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.  
Puedes copiarlo, modificarlo y compartirlo libremente, siempre que se reconozca la autoría y se mantenga la misma licencia.  

© 2025 Francisco Joaquín López Romano

