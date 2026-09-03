# 📱 Mapa Conceptual y Funcional: mySmartWindow

A continuación tienes el mapa estructural de la aplicación en formato "árbol" (totalmente libre de códigos) para que lo puedas ver de un solo vistazo. Debajo se encuentra la documentación detallada.

## 🌳 Estructura Visual de la App

```text
📱 mySmartWindow (App Android)
│
├── 🔝 Barra Superior (Navegación Global)
│   ├── 🏠 Inicio (Retorno al menú principal desde cualquier pantalla)
│   ├── 👤 Usuario Activo (Popup con el email autenticado)
│   └── ⋮ Menú Oculto
│       ├── Cambiar / Eliminar Usuario
│       ├── Actualizar Vivienda
│       ├── Lista de Asociados
│       ├── Reiniciar App
│       ├── Soporte y Comunicaciones
│       ├── Información, Licencias y Acerca de
│       └── Salir
│
├── 🎛️ Panel Principal (Menú de Esferas)
│   ├── 🏘️ Viviendas (Gestión y opciones directas)
│   ├── 🚪 Habitaciones (Separación de dispositivos)
│   ├── 🪟 Ventanas (Acceso a modificaciones y control visual)
│   ├── ⚙️ Ajustes (Wifi, Asociados, Reinicio, Accesos)
│   ├── ⚠️ Alertas (Modos y activación)
│   ├── 🔗 Integración (Alexa, Google Home)
│   ├── ⏰ Programador (Automatización horaria)
│   ├── 👥 Grupos (Agrupación para control conjunto)
│   └── 💬 Mensajes (Noticias, Firmware, Servicios)
│
├── 🪄 Asistente de Vinculación (Burbuja Varita Mágica)
│   └── ⚙️ Guía para configurar dispositivos nuevos
│
└── 🌐 Barra Inferior (Conectividad)
    ├── ☁️ Conexión Cloud (Servidor remoto)
    └── 📶 Conexión Local (Red Wi-Fi directa)
```

---

## 📝 Documentación Detallada

### 🔝 Barra Superior (Navegación Global)
*Visible permanentemente en la parte superior de la app.*
* **🏠 Inicio (Icono Casa):** Si estás en cualquier página de la aplicación, lo que puedes hacer es irte al menú principal donde están todas las opciones.
* **👤 Usuario Activo (Perfil):** Símbolo de un monigote. Al pulsarlo te muestra el mensaje "Su Usuario Activo" y te indica el correo del usuario que está autenticado.
* **⋮ Menú Oculto (3 Puntos):** Ubicado a la derecha. Despliega diversas opciones del sistema:
  * Cambiar Usuario
  * Eliminar Usuario
  * Actualizar Vivienda
  * Lista de Asociados – [Video de perfiles de usuario](https://youtu.be/xgwksfNHRGU)
  * Reiniciar App
  * Soporte
  * Envío de comunicaciones
  * Acerca de mySmartWindow
  * Información de fabricante
  * Licencias de terceros
  * Salir

### 🪄 Asistente de Vinculación
*En la parte de abajo de las primeras filas de burbujas aparece una burbuja con una varita mágica.*
* **Configuración de Dispositivos:** Sirve para configurar dispositivos nuevos. Tiene una pequeña guía para que se puedan configurar con las nuevas opciones.

### 🎛️ Panel Principal (Esferas)
*Menú principal central de la aplicación.*

* **🏘️ Viviendas:** En la pantalla principal aparecen tus viviendas. Al seleccionar una vivienda tienes varias acciones: subir o bajar todas las persianas de esa vivienda, y un ícono de lápiz que permite editar la configuración y el nombre de la vivienda. Además, al pulsar la vivienda se despliegan opciones específicas para cada dispositivo asociado.
* **🚪 Habitaciones:** En la parte inferior puedes crear nuevas habitaciones para organizar los dispositivos. Esto permite separar, por ejemplo, 3 persianas en tu habitación y 2 en la de tus padres, facilitando un manejo más granular.
* **🪟 Ventanas:** En la sección superior se muestra la clasificación por habitación; los dispositivos aparecen según la habitación a la que pertenecen. Aquí puedes modificar cualquier dispositivo y, al seleccionar uno, se muestra una representación gráfica que permite subir o bajar persianas o ventanas.
* **⚙️ Ajustes:** Sirve para tareas de gestión como invitar a un asociado, cambiar la configuración Wi‑Fi, reiniciar la vivienda o consultar los datos de acceso.
* **⚠️ Alertas:** Permite activar o desactivar alertas y configurar sus modos según tus preferencias.
* **🔗 Integración:** Facilita la integración de los dispositivos con servicios externos como Amazon Alexa y Google Home.
* **⏰ Programador:** Programa acciones automáticas, por ejemplo: "a las 7 AM levantar la persiana 1 de la habitación 2".
* **👥 Grupos:** Agrupa varios dispositivos para controlarlos conjuntamente.
* **💬 Mensajes:** Notifica actualizaciones de la aplicación, firmware, nuevos servicios y otra información relevante.
* **🚪 Habitaciones:** En la parte de abajo puedes generar más habitaciones para separar los dispositivos de tu vivienda. Por ejemplo, si tienes 3 persianas en tu habitación y 2 en la de tus padres, la mejor opción es separar los dispositivos por habitaciones para un mejor manejo.
* **🪟 Ventanas:** En la parte superior aparece la clasificación por cada habitación, saliendo los dispositivos dependiendo de la habitación en la que estén. Aquí se puede cambiar o acceder a todas las modificaciones de los dispositivos. Si entras a uno, te sale la representación gráfica para bajar y subir ventanas/persianas.
* **⚙️ Ajustes:** Sirven para cuando queremos invitar a un asociado, cambiar el WiFi, reiniciar la vivienda, o ver cuáles son los datos de acceso.
* **⚠️ Alertas:** Tiene opciones para activar o desactivar alertas, y configurar los modos de las alertas.
* **🔗 Integración:** Su funcionalidad es poder integrar nuestros dispositivos en servicios como Alexa y Google Home, entre otras cosas.
* **⏰ Programador:** Sirve para decirle a la app que, por ejemplo, "a las 7 de la mañana quiero que se levante la persiana 1 de la habitación 2".
* **👥 Grupos:** Lo que hace es poder agrupar varios dispositivos en un mismo grupo; así mismo, se pueden controlar los dispositivos del grupo conjuntamente.
* **💬 Mensajes:** Recibe mensajes de actualización de la app y de firmware, nuevos servicios y otra información relevante.

### 📺 Videos y enlaces por sección

- **Lista de Asociados**: [Perfiles de usuario](https://youtu.be/xgwksfNHRGU)
- **Ventanas**:
  - [Modos de luz LED y bloqueo](https://www.youtube.com/watch?v=ZR6m4Hwod6A)
  - [Reset del Connect vía app](https://www.youtube.com/watch?v=yhQVNuBkd1Y)
  - [Servicio Offline Connect‑2](https://youtu.be/N3D8QNu1Qhs)
  - [Servicio persiana dispositivos Connect](https://www.youtube.com/watch?v=LmwEcjnx4oY)
  - [Activación del candado](https://youtu.be/rczgOO8Upmc)
  - [Menú edición Connect‑1](https://www.youtube.com/watch?v=vc7TpbaN5Bo)
  - [Configuración multi‑WiFi](https://youtu.be/i1Dm_qvKTkY)
- **Integración**:
  - [Bajar persiana al anochecer (Google Home)](https://youtu.be/4_YDkKKsEsU)
  - [Tarea programada persianas (Google Home)](https://youtu.be/vWD91q1BPN8)
  - [Tarea programada persiana (Alexa)](https://youtu.be/kgfnaKl2jFk)
  - [Vincular cuenta Alexa](https://youtu.be/QbPyzlBy3rU)
  - [Vincular Google Home](https://youtu.be/hebELentU-Y)
- **Programador**:
  - [Abrir ventana abatible sin conexión](https://youtu.be/vg5kFWU5xTQ)
  - [Bajar persiana sin conexión](https://youtu.be/Vj3Be0UmtCE)

- **Grupos**:
  - [Crear Virtual Room (agrupación)](https://youtu.be/RBG4mA61NYM)
  - [Editar Virtual Room](https://www.youtube.com/watch?v=JgkaWAWd7Ng)
  - [Eliminar Virtual Rooms](https://www.youtube.com/watch?v=qHCkBllnGC8)
  - [Acciones persiana virtual rooms](https://youtu.be/jFGnha7Wo6Q)
  - [Acciones abatibles virtual room](https://youtu.be/lCAtGiUZDtA)
- **Asistente de Vinculación**:
  - [Multivinculación Dispositivo Connect](https://www.youtube.com/watch?v=KidyF4ZpdAE)
  - [Vinculación Punto a Punto Connect](https://www.youtube.com/watch?v=ItsojJBE0P4)
  - [Vinculación C WALL Shutter](https://www.youtube.com/watch?v=myijKC5RsZU)
  - [Vinculación Bluetooth](https://www.youtube.com/watch?v=TrPkktXX-dM)
  - [Vinculación AP de C-Pulsar](https://www.youtube.com/watch?v=j7V8uHqqbq0)
  - [Vinculación Multicast C-Pulsar](https://www.youtube.com/watch?v=3xq4dhMhpd0)
- **Instalaciones**:
  - [Instalar pulsar en cajón de persiana](https://youtu.be/W1nKbomm8jI)
  - [Instalar Connect‑2](https://www.youtube.com/watch?v=tZ1aSM4zxdI)
  - [Instalar Connect‑1](https://www.youtube.com/watch?v=G7_DOCulUfQ)
  - [Instalar ventana motorizada](https://www.youtube.com/watch?v=1jnmia28Odg)
  - [Instalar C‑WALL SHUTTER](https://www.youtube.com/watch?v=mxnSQ1yJokk)
  - [Instalar Connect‑smart Pulsar](https://www.youtube.com/watch?v=R7Y946H0nxs)
  - [Instalar Pulsar en cajón](https://www.youtube.com/watch?v=W1nKbomm8jI)
  - [Activar modo manual / hard reset C‑PULSAR](https://www.youtube.com/watch?v=CbytOk28RA8)
  - [Indicador sensor de apertura](https://www.youtube.com/watch?v=ciZx_U1ycLk)
  - [Reset físico Connect‑1](https://www.youtube.com/watch?v=3_0JS2wHc8Y)
  - [C‑WALL sky funcionamiento](https://www.youtube.com/watch?v=V7KDo5NCLjg)
  - [IFTTT explicación](https://youtu.be/fJ20WneNgXU)
  - [Activar sirena con Alexa](https://www.youtube.com/watch?v=lSqxdRcBJ-A)
  - [Soporte y solución de problemas de vinculación](https://youtu.be/Qvya35g8D_o)
  - [Configurar router](https://youtu.be/RoWQK-J5JII)
  - [Router Orange y Jazztel](https://youtu.be/Iczsri-nuYg)
  - [Preguntas frecuentes](https://youtu.be/2RlnQIekOcc)

### 📄 Documentación PDF

<details open>
<summary>🗂️ Perfiles de usuario</summary>

| Tipo | Enlace |
|------|--------|
| PDF | [Perfiles de usuario](https://www.iotfenster.com/wp-content/uploads/2024/06/Perfiles_de_usuario-MySmartWindow.pdf) |
| Tarjeta | [Tarjeta Perfiles de usuario](https://www.iotfenster.com/wp-content/uploads/2024/06/Perfiles_de_usuario_tarjeta.pdf) |
</details>

<details>
<summary>❓ Preguntas frecuentes</summary>

| Tipo | Enlace |
|------|--------|
| PDF | [Preguntas frecuentes](https://www.iotfenster.com/wp-content/uploads/2024/06/Preguntas-frecuentes-MySmartWindow-1.pdf) |
| Tarjeta Dispositivo | [Tarjeta Dispositivo](https://www.iotfenster.com/wp-content/uploads/2024/06/Pregunta-frecuentes-dispositivo-MSW-1.pdf) |
| Tarjeta Conectividad y vinculación | [Tarjeta Conectividad y vinculación](https://www.iotfenster.com/wp-content/uploads/2024/06/Pregunta-frecuentes-conectividad-y-vinculacion-MSW-1.pdf) |
| Tarjeta Tipos de motor | [Tarjeta Tipos de motor](https://www.iotfenster.com/wp-content/uploads/2024/06/Preguntas-frecuentes-tipos-de-motor-1.pdf) |
</details>

<details>
<summary>🔗 Multiconectividad / Multi‑WiFi</summary>

| Tipo | Enlace |
|------|--------|
| PDF | [Manual Multi‑WiFi](https://www.iotfenster.com/wp-content/uploads/2025/10/ES_-Conectividad_Multiwifi_Documentacion-MySmartWindow.pdf) |
</details>

<details>
<summary>📶 Cobertura & Wi‑Fi</summary>

| Tipo | Enlace |
|------|--------|
| PDF | [Cómo ampliar mi cobertura](https://www.iotfenster.com/wp-content/uploads/2024/05/Conectividad_Como-ampliar-mi-cobertura_Documentacion-MySmartWindow.pdf) |
| PDF | [Compartir red Wi‑Fi desde Android](https://www.iotfenster.com/wp-content/uploads/2026/09/Manual_Android_WiFi_IoT_FENSTER_MySmartWindow.pdf) |
</details>

<details>
<summary>🌐 Ecosistemas</summary>

| Tipo | Enlace |
|------|--------|
| Alexa – Vinculación | [Manual Alexa Vinculación](https://www.iotfenster.com/wp-content/uploads/2025/09/Manual-Alexa-Vinculacion-con-MySmartWindow.pdf) |
| Alexa – Tarea programada | [Manual Alexa Tarea programada](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Alexa-Tarea-Programada-MySmartWindow.pdf) |
| Google Home – Bajar persianas al anochecer | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%F0%9F%92%9ABajar_persianas_al_anochecer_Tarea-Programada-MySmartWindow.pdf) |
| Google Home – Subir persianas | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%F0%9F%92%9AManual-Google-Home-Tarea-Programada-MySmartWindow.pdf) |
| IFTTT – Integración | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Integracion-IFTTT-Tarea-Programada-MySmartWindow.pdf) |
| IFTTT – Qué es | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%C2%BFQue-es-IFTTT-MySmartWindow.pdf) |
</details>

<details>
<summary>🔧 Hard Reset / Reset Software</summary>

| Tipo | Enlace |
|------|--------|
| Hard reset Connect‑1 | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Dispositivo_botones_-MySmartWindow.pdf) |
| Tarjeta Hard reset Connect‑1 | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Hard_reset_connect1-Dispositivos.pdf) |
| Reset software Connect | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Reset_Software_-MySmartWindow.pdf) |
</details>

<details>
<summary>⚙️ Instalación</summary>

| Tipo | Enlace |
|------|--------|
| Connect‑1 | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Instalacion-Connect-1-MySmartWindow.pdf) |
| Connect‑2 | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Instalacion-Connect-2-MySmartWindow-1.pdf) |
| Sensor de apertura | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Indicador-del-sensor-de-apertura-Instalacion.pdf) |
| C‑PULSAR | [PDF](https://www.iotfenster.com/wp-content/uploads/2026/06/Instalacion-C-PULSAR-MySmartWindow-1.pdf) |
| Fabricación C‑PULSAR | [PDF](https://www.iotfenster.com/wp-content/uploads/2026/07/Manual-fabricacion-Cajon-RTX-La-VIUDA.pdf) |
| C‑WALL | [PDF](https://www.iotfenster.com/wp-content/uploads/2026/04/Instrucciones-CWALL-1.pdf) |
| C‑EVO | [PDF](https://www.iotfenster.com/wp-content/uploads/2026/07/Instalacion-EVO-MySmartWindow-1_compressed.pdf) |
</details>

<details>
<summary>🔗 Vinculación</summary>

| Tipo | Enlace |
|------|--------|
| Punto a Punto | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Vinculacion-MySmartWindow-1.pdf) |
| Multivinculación | [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Manual-de-Multivinculacion-MySmartWindow-1_compressed.pdf) |
| Multivinculación C‑WALL | [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Manual-de-Multivinculacion_C-Wall-MySmartWindow.pdf) |
</details>

<details>
<summary>🃏 Tarjetas de Vinculación</summary>

| Tipo | Enlace |
|------|--------|
| Punto a Punto | [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Vinculacion-punto-a-punto_tarjeta.pdf) |
| C‑Wall | [PDF](https://www.iotfenster.com/wp-content/uploads/2025/08/Vinculacion-c-wall.pdf) |
| Multivinculación | [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Vinculacion-Multivinculacion.pdf) |
</details>

---

#### Perfiles de usuario
- PDF: [Perfiles de usuario](https://www.iotfenster.com/wp-content/uploads/2024/06/Perfiles_de_usuario-MySmartWindow.pdf)
- Tarjeta: [Tarjeta Perfiles de usuario](https://www.iotfenster.com/wp-content/uploads/2024/06/Perfiles_de_usuario_tarjeta.pdf)

#### Preguntas frecuentes
- PDF: [Preguntas frecuentes](https://www.iotfenster.com/wp-content/uploads/2024/06/Preguntas-frecuentes-MySmartWindow-1.pdf)
- Tarjeta Dispositivo: [Tarjeta Dispositivo](https://www.iotfenster.com/wp-content/uploads/2024/06/Pregunta-frecuentes-dispositivo-MSW-1.pdf)
- Tarjeta Conectividad y vinculación: [Tarjeta Conectividad y vinculación](https://www.iotfenster.com/wp-content/uploads/2024/06/Pregunta-frecuentes-conectividad-y-vinculacion-MSW-1.pdf)
- Tarjeta Tipos de motor: [Tarjeta Tipos de motor](https://www.iotfenster.com/wp-content/uploads/2024/06/Preguntas-frecuentes-tipos-de-motor-1.pdf)

#### Multiconectividad / Multi‑WiFi
- PDF: [Multi‑WiFi Manual](https://www.iotfenster.com/wp-content/uploads/2025/10/ES_-Conectividad_Multiwifi_Documentacion-MySmartWindow.pdf)

#### Cobertura & Wi‑Fi
- PDF: [Cómo ampliar mi cobertura](https://www.iotfenster.com/wp-content/uploads/2024/05/Conectividad_Como-ampliar-mi-cobertura_Documentacion-MySmartWindow.pdf)
- PDF: [Compartir red Wi‑Fi desde Android](https://www.iotfenster.com/wp-content/uploads/2026/09/Manual_Android_WiFi_IoT_FENSTER_MySmartWindow.pdf)

#### Ecosistemas
- Alexa Vinculación: [Manual Alexa Vinculación](https://www.iotfenster.com/wp-content/uploads/2025/09/Manual-Alexa-Vinculacion-con-MySmartWindow.pdf)
- Alexa Tarea programada: [Manual Alexa Tarea programada](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Alexa-Tarea-Programada-MySmartWindow.pdf)
- Google Home Bajar persianas al anochecer: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%F0%9F%92%9ABajar_persianas_al_anochecer_Tarea-Programada-MySmartWindow.pdf)
- Google Home Subir persianas: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%F0%9F%92%9AManual-Google-Home-Tarea-Programada-MySmartWindow.pdf)
- IFTTT Integración: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Integracion-IFTTT-Tarea-Programada-MySmartWindow.pdf)
- IFTTT Qué es: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/%C2%BFQue-es-IFTTT-MySmartWindow.pdf)

#### Hard Reset / Reset Software
- Hard reset Connect‑1: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Dispositivo_botones_-MySmartWindow.pdf)
- Tarjeta Hard reset Connect‑1: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Hard_reset_connect1-Dispositivos.pdf)
- Reset software Connect: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Reset_Software_-MySmartWindow.pdf)

#### Instalación
- Connect‑1: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Instalacion-Connect-1-MySmartWindow.pdf)
- Connect‑2: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Instalacion-Connect-2-MySmartWindow-1.pdf)
- Sensor de apertura: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Indicador-del-sensor-de-apertura-Instalacion.pdf)
- C‑PULSAR: [PDF](https://www.iotfenster.com/wp-content/uploads/2026/06/Instalacion-C-PULSAR-MySmartWindow-1.pdf)
- Fabricación C‑PULSAR: [PDF](https://www.iotfenster.com/wp-content/uploads/2026/07/Manual-fabricacion-Cajon-RTX-La-VIUDA.pdf)
- C‑WALL: [PDF](https://www.iotfenster.com/wp-content/uploads/2026/04/Instrucciones-CWALL-1.pdf)
- C‑EVO: [PDF](https://www.iotfenster.com/wp-content/uploads/2026/07/Instalacion-EVO-MySmartWindow-1_compressed.pdf)

#### Vinculación
- Punto a Punto: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/05/Manual-Vinculacion-MySmartWindow-1.pdf)
- Multivinculación: [PDF](https://www.iotfenster.com/wp-content/uploads/2024/06/Manual-de-Multivinculacion-MySmartWindow-1_compressed.pdf)
- Multivinculación C‑WALL: [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Manual-de-Multivinculacion_C-Wall-MySmartWindow.pdf)

#### Tarjetas de Vinculación
- Punto a Punto: [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Vinculacion-punto-a-punto_tarjeta.pdf)
- C‑Wall: [PDF](https://www.iotfenster.com/wp-content/uploads/2025/08/Vinculacion-c-wall.pdf)
- Multivinculación: [PDF](https://www.iotfenster.com/wp-content/uploads/2025/09/Vinculacion-Multivinculacion.pdf)

---
### 🔧 Canal de youtube
* 🔗 **Video:** [Control Total Overview](https://www.youtube.com/channel/UCOYzORrjwX-krZhyK9-NqBQ)
### 🌐 Barra Inferior (Conectividad)
* **☁️ Conexión Cloud (Globo):** Conectado al servidor remoto.
* **📶 Conexión Local (Icono Casa+WiFi):** Conectado directamente en la red local.
