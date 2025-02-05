# Sistemas-operativos-moviles-iOS-Android-
## IOS Act 2 Sistemas operativos móviles (iOS, Android)

### 10 características  del sistema operativo Android

- Código Abierto (Open Source): Android está basado en el kernel de Linux y es de código abierto, lo que permite a los fabricantes y desarrolladores modificar y personalizar el sistema operativo según sus necesidades.

- Interfaz de Usuario Personalizable: Android ofrece una gran flexibilidad en la personalización de la interfaz de usuario, incluyendo widgets, temas, y la capacidad de cambiar la apariencia del sistema mediante la instalación de launchers personalizados.

- Multitarea: Android permite a los usuarios ejecutar múltiples aplicaciones simultáneamente, facilitando la multitarea. Los usuarios pueden cambiar entre aplicaciones fácilmente y algunas aplicaciones pueden funcionar en segundo plano.

- Google Play Store: Android tiene acceso a la Google Play Store, que es una de las tiendas de aplicaciones más grandes del mundo. Ofrece millones de aplicaciones y juegos, así como libros, películas y música.

- Integración con Servicios de Google: Android está profundamente integrado con los servicios de Google, como Gmail, Google Maps, Google Drive, Google Photos y el Asistente de Google, lo que facilita la sincronización de datos y la productividad.

- Notificaciones Mejoradas: Android tiene un sistema de notificaciones robusto y flexible. Las notificaciones se pueden expandir, priorizar y gestionar de manera individual, y también se pueden agrupar por aplicaciones.

- Seguridad y Actualizaciones: Android incluye varias características de seguridad, como cifrado de datos, verificación de aplicaciones, y actualizaciones regulares de seguridad. Sin embargo, la frecuencia de las actualizaciones puede variar según el fabricante del dispositivo.

- Compatibilidad con Varios Dispositivos: Android no está limitado a smartphones; también se utiliza en tablets, smartwatches (Wear OS), televisores (Android TV), automóviles (Android Auto), y otros dispositivos IoT.

- Asistente de Google: Integrado directamente en el sistema, el Asistente de Google permite a los usuarios realizar búsquedas por voz, controlar dispositivos inteligentes, gestionar tareas, y obtener respuestas rápidas a preguntas.

- Conectividad y Compartición: Android facilita la conectividad con otros dispositivos a través de tecnologías como Bluetooth, Wi-Fi Direct, NFC, y USB. Además, incluye funciones de compartición como Android Beam (aunque está siendo reemplazado por Nearby Share) y la capacidad de compartir archivos fácilmente entre dispositivos.

![image](https://github.com/user-attachments/assets/fce6f5ad-8103-458c-8cc2-73fcf3aa4da7)

### Como funciona el sistema operativo Android
  
1. Arquitectura de Android
Android está construido sobre una arquitectura en capas, que incluye:

Aplicaciones: Es la capa más visible para el usuario. Aquí se encuentran las aplicaciones preinstaladas (como Gmail, Chrome, Maps) y las que el usuario descarga desde la Google Play Store.

Marco de Trabajo de Aplicaciones (Application Framework): Proporciona las APIs y herramientas que los desarrolladores utilizan para crear aplicaciones. Incluye componentes como Activity Manager, Content Providers, Notification Manager, y más.

Bibliotecas Nativas (Libraries): Android incluye bibliotecas escritas en C/C++ para tareas específicas, como gráficos (OpenGL), bases de datos (SQLite), y manejo de redes.

Runtime de Android: Incluye las bibliotecas principales de Java y la máquina virtual ART (Android Runtime), que es responsable de ejecutar y optimizar las aplicaciones.

Kernel de Linux: Es la base del sistema operativo. Gestiona el hardware, la memoria, los procesos, la seguridad y los controladores de dispositivos.

2. Proceso de Inicio (Boot Process)
Cuando enciendes un dispositivo Android, sigue estos pasos:

Bootloader: Se ejecuta un pequeño programa que inicia el sistema operativo.

Kernel de Linux: El kernel se carga en la memoria y gestiona el hardware.

Init Process: Es el primer proceso que se ejecuta y lanza otros servicios esenciales.

Zygote: Un proceso que inicia la máquina virtual ART y pre-carga bibliotecas comunes para acelerar el inicio de aplicaciones.

System Server: Inicia servicios clave como Activity Manager, Package Manager, y otros.

Launcher: Finalmente, se carga la interfaz de usuario (launcher) y el dispositivo está listo para usarse.

3. Gestión de Aplicaciones
Máquina Virtual ART (Android Runtime): Ejecuta aplicaciones escritas en Java o Kotlin. ART convierte el código de las aplicaciones en instrucciones que el hardware puede entender.

Procesos y Hilos: Cada aplicación se ejecuta en su propio proceso, lo que mejora la seguridad y estabilidad. Android también permite el uso de hilos para tareas en segundo plano.

Ciclo de Vida de las Aplicaciones: Android gestiona el ciclo de vida de las aplicaciones (por ejemplo, cuándo se inician, pausan o detienen) para optimizar el uso de recursos.

4. Interfaz de Usuario
Launcher: Es la pantalla principal desde donde el usuario accede a las aplicaciones y widgets.

Vistas y Fragmentos: Las aplicaciones usan componentes como Activities (pantallas) y Fragments (secciones de una pantalla) para construir la interfaz.

Sistema de Ventanas: Android gestiona cómo se muestran las aplicaciones en pantalla, ya sea en modo pantalla completa, multitarea o en ventanas flotantes.

5. Gestión de Memoria y Recursos
Android optimiza el uso de memoria RAM y CPU para garantizar un rendimiento fluido.

Usa un sistema de recolección de basura (garbage collection) para liberar memoria no utilizada.

Las aplicaciones en segundo plano pueden ser pausadas o detenidas para ahorrar recursos.

6. Seguridad
Permisos: Las aplicaciones deben solicitar permisos para acceder a funciones del dispositivo (como cámara, micrófono o ubicación).

Sandboxing: Cada aplicación se ejecuta en un entorno aislado (sandbox) para evitar que acceda a datos de otras aplicaciones.

Cifrado: Android cifra los datos del usuario para proteger la privacidad.

Google Play Protect: Escanea aplicaciones en busca de malware y verifica su seguridad.

7. Conectividad
Android soporta múltiples tecnologías de conectividad, como Wi-Fi, Bluetooth, NFC, y redes móviles.

Incluye APIs para que las aplicaciones se comuniquen con dispositivos externos, como wearables o automóviles.

8. Actualizaciones
Las actualizaciones de Android son gestionadas por Google, pero los fabricantes de dispositivos y operadores de red también participan en su distribución.

Las actualizaciones pueden incluir nuevas características, parches de seguridad y mejoras de rendimiento.

9. Personalización
Android permite a los usuarios personalizar su experiencia mediante la instalación de launchers, widgets, temas y aplicaciones de terceros.

Los fabricantes también pueden personalizar Android con sus propias interfaces (como One UI de Samsung o MIUI de Xiaomi).

10. Multitarea
Android permite a los usuarios ejecutar varias aplicaciones al mismo tiempo.

Soporta funciones como modo de pantalla dividida y ventanas flotantes para mejorar la productividad.

![image](https://github.com/user-attachments/assets/c874ae37-efbe-4b34-b764-d5eadf9aad89)

### Realiza un Mapa Conceptual  (características y funciones para Android)

#### Concepto 1: Sistema Operativo y Personalización
- Basado en Linux: Núcleo Linux modificado para dispositivos móviles.
- Código Abierto: Permite personalización por fabricantes y desarrolladores.
- Interfaz Personalizable: Widgets, temas y launchers alternativos.
- ROMs Personalizadas: Instalación de versiones modificadas de Android.

#### Concepto 2: Funcionalidades y Conectividad
- Google Play Store: Acceso a millones de aplicaciones y juegos.
- Integración con Google: Servicios como Gmail, Maps, Drive, etc.
- Conectividad Avanzada: Wi-Fi, Bluetooth, NFC y 5G/4G LTE.
- Multitarea: Ejecución de múltiples aplicaciones simultáneamente.

#### Concepto 3: Seguridad y Desarrollo
- Google Play Protect: Escaneo de aplicaciones en busca de malware.
- Autenticación Biométrica: Huella dactilar y reconocimiento facial.
- Android SDK: Herramientas para desarrolladores.
- APIs Abiertas: Acceso a hardware y servicios del dispositivo.

#### Concepto 4: Innovación y Almacenamiento
- Realidad Aumentada: Soporte para ARCore.
- Asistente de Google: Integración con Google Assistant.
- Almacenamiento Expandible: Soporte para tarjetas microSD.
- Integración con la Nube: Sincronización automática con Google Drive.

#
            Android
       /     |     \     \
      SO     Func   Seg   Innov
     /|\     /|\    /|\    /|\
    Linux  Play  Protect  ARCore
    Código Store  Biomét  Asistente
    Interf Integ  SDK     Almacen
    ROMs  Multit  APIs    Nube

### 10 características  del sistema operativo IOS
1. Interfaz Intuitiva y Fluida
- Diseño limpio y fácil de usar.
- Animaciones fluidas y transiciones suaves.
- Navegación mediante gestos (especialmente en modelos sin botón físico).

2. Integración con el Ecosistema Apple
- Sincronización perfecta entre dispositivos Apple (iPhone, iPad, Mac, Apple Watch, AirPods).
- Funciones como Handoff, Continuity y Universal Clipboard.

3. Seguridad y Privacidad
- Autenticación biométrica (Face ID y Touch ID).
- Cifrado de datos de extremo a extremo.
- Funciones como "Rastreo de Apps" y "Informes de Privacidad".

4. App Store Exclusivo
- Plataforma centralizada para descargar aplicaciones.
- Aplicaciones optimizadas y revisadas para garantizar seguridad y calidad.
- Millones de apps disponibles, muchas exclusivas para iOS.

5. Siri (Asistente Virtual)
- Asistente de voz inteligente para realizar tareas, buscar información y controlar dispositivos.
- Integración con aplicaciones de terceros.
- Funciones como "Hey Siri" y comandos personalizados.

6. Actualizaciones Regulares y Largo Soporte
- Actualizaciones anuales con nuevas funciones.
- Soporte prolongado para dispositivos antiguos (hasta 5-6 años).
- Actualizaciones de seguridad frecuentes.

7. Personalización y Widgets
- Pantalla de inicio personalizable con widgets.
- Biblioteca de apps para organizar aplicaciones.
- Temas de pantalla y opciones de accesibilidad.

8. Rendimiento Optimizado
- Sistema operativo diseñado específicamente para el hardware de Apple.
- Uso eficiente de recursos para maximizar la duración de la batería.
- Procesamiento rápido y sin lag.

9. Funciones de Productividad
- Multitarea en iPad (Split View, Slide Over).
- Herramientas como Notes, Reminders y Files.
- Integración con iCloud para almacenamiento y sincronización de archivos.

10. Innovación Tecnológica
- Soporte para realidad aumentada (ARKit).
- Funciones avanzadas de cámara (modo retrato, Night Mode).
- Integración con tecnologías como AirDrop y Apple Pay.




