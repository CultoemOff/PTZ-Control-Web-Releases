# PTZ Control Web — by Culto em Off

**PTZ Control Web – Controlador gratuito de cámaras PTZ para OBS, vMix y SPresenter**

[Português](README.md) · [English](README.en.md) · [Español](README.es.md)

[⬇️ Descargar para Windows](https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest)

Controla cámaras PTZ directamente desde el navegador, dentro de tu software de producción o como panel independiente.

**PTZ Control Web — by Culto em Off** es una interfaz web local para el control de cámaras PTZ. Fue diseñada para iglesias, transmisiones en vivo, producciones audiovisuales y equipos que necesitan un controlador simple y compacto.

La aplicación se ejecuta localmente en Windows y su interfaz se abre en el navegador. También puede agregarse directamente a **OBS Studio como Custom Browser Dock**.

## 📥 Descarga

Descarga siempre la versión más reciente desde:

https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest

En **Assets**, descarga:

- `PTZ-Control-Web-Setup.exe`
- `SHA256SUMS.txt` — hash SHA-256 para verificar la integridad del instalador.

## 🖥️ Instalación

1. Descarga `PTZ-Control-Web-Setup.exe`.
2. Ejecuta el instalador.
3. Completa la instalación normalmente.
4. PTZ Control Web quedará configurado para iniciarse con Windows.
5. Se creará un acceso directo **PTZ Control Web** para abrir el panel en el navegador.

El servidor se ejecuta localmente en el equipo y no necesita conexión a Internet para controlar cámaras de la red local.

## 🌐 Cómo abrir PTZ Control Web

Después de instalar, abre:

`http://127.0.0.1:8765/obs`

Puedes guardar esta dirección en los favoritos del navegador.

También puedes usar el acceso directo **PTZ Control Web** creado durante la instalación.

> `127.0.0.1` significa que el servidor se ejecuta en el mismo equipo. Por defecto, la interfaz no queda expuesta a otros dispositivos de la red.

## 🎥 Cómo agregarlo a OBS Studio

En OBS Studio, abre:

**Docks → Custom Browser Docks**

Crea un nuevo panel usando:

**Nombre:** `PTZ Control Web`

**URL:** `http://127.0.0.1:8765/obs`

Haz clic en **Apply / Aplicar**. El panel aparecerá dentro de OBS y podrás arrastrarlo y acoplarlo junto a los demás paneles.

## 🎛️ Dónde funciona

- **OBS Studio** como Custom Browser Dock
- **vMix**
- **SPresenter**
- navegador web
- **Bitfocus Companion**
- control USB/Gamepad

Como el controlador funciona mediante un servidor local y una interfaz web, no depende de un plugin interno específico de OBS Studio.

## 🎥 Funciones

- Pan, Tilt y Zoom
- movimiento diagonal
- comando Home
- Focus Near / Far
- Autofocus
- velocidad Pan/Tilt ajustable
- presets con guardar, llamar y nombres personalizados
- soporte para hasta **8 cámaras**
- hasta **4 cámaras por fila**
- interfaz en portugués, inglés, español y alemán
- tema claro y oscuro
- cantidad de presets configurable
- diseño horizontal o vertical
- opción de ocultar controles PTZ
- control mediante Gamepad USB
- integración HTTP con Bitfocus Companion
- configuración guardada localmente
- Auto Tracking en cámaras ONVIF compatibles

## 📷 Protocolos y perfiles de cámara

Protocolos compatibles:

- **VISCA over IP — UDP**
- **VISCA over IP — TCP**
- **VISCA USB / Serial**
- **ONVIF**

Perfiles de fabricante:

- **Genérico**
- **AVer**
- **Telycam**
- **PTZOptics**
- **Sony**

Utiliza el perfil **Genérico** para cámaras compatibles que no aparezcan en la lista.

Algunas funciones, como **Auto Tracking**, dependen del soporte ofrecido por la propia cámara.

## 🎮 Control USB / Gamepad

El mapeo incluye joystick izquierdo para Pan/Tilt, gatillos para Zoom, botones superiores para Focus, D-Pad para seleccionar presets y botones para llamar, guardar y activar Autofocus.

## 🔲 Bitfocus Companion

La integración HTTP permite crear botones en Companion para movimiento, parada, Zoom, Focus, Autofocus, Home, llamada de presets y guardado de presets.

## 🔐 Seguridad

Por defecto, el servidor escucha únicamente en:

`127.0.0.1`

Esto significa que la interfaz y la API solo son accesibles desde el equipo donde PTZ Control Web está instalado.

La configuración de las cámaras se guarda localmente.

## 🔎 PTZ Camera Controller

PTZ Control Web es un controlador gratuito de cámaras PTZ basado en navegador para **OBS Studio, vMix y SPresenter**, con soporte para **VISCA over IP (UDP/TCP)**, **VISCA USB/Serial**, **ONVIF**, presets, Pan/Tilt/Zoom, enfoque, control USB/Gamepad, Auto Tracking en dispositivos compatibles e integración HTTP con **Bitfocus Companion**.

**Keywords:** PTZ controller, PTZ camera controller, PTZ web controller, OBS PTZ controller, VISCA controller, VISCA over IP, ONVIF PTZ, USB PTZ controller, Bitfocus Companion PTZ, vMix PTZ, SPresenter PTZ, church livestream PTZ.

## 🎥 Sobre Culto em Off

**Culto em Off** es un canal creado para compartir conocimiento práctico sobre **audio, video, transmisión y tecnología para iglesias**.

El contenido incluye consolas de audio en vivo, OBS Studio y streaming, cámaras y PTZ, NDI, iluminación y automatización, REAPER, Holyrics, SPresenter, redes, integración de equipos y tutoriales prácticos para equipos técnicos de iglesias.

▶️ **YouTube:** https://www.youtube.com/@CultoemOff

---

**PTZ Control Web — by Culto em Off**

Creado por **Jonas — Brasil 🇧🇷**
