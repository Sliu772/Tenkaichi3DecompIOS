# BT3 port iOS

**Dragon Ball Z: Budokai Tenkaichi 3** (PS2, EE. UU., SLUS-21678) corriendo de forma **nativa en iPhone**. No es un emulador: es el propio código del juego, decompilado y compilado para iOS, con una capa nueva de renderizado y controles.

Hecho por **Sliu/LX772**, sobre el trabajo de **z3xox** ([Tenkaichi3Decomp](https://github.com/z3xox/Tenkaichi3Decomp)) y **dfdx047** ([Dragon Rage](https://github.com/dfdx047/Tenkaichi3DecompAndroid)).

**Versión: beta v1.0.1**

## Estado (beta v1.0.1)
- Juego completo probado en iPhone real: menús, modo historia y peleas a la velocidad original (30 fps).
- Controles táctiles y mando (Bluetooth/USB) compatibles.
- Online: salas por código y partidas por dirección. *(quick match: en revisión)*

## Requisitos
- iPhone o iPad con **iOS 15** o superior.
- Tu propia copia del juego: **versión EE. UU. (SLUS-21678)** en `.iso`.
- Una herramienta para instalar IPAs (**Sideloadly**, **AltStore**…): la IPA va sin firmar y se firma con tu certificado al instalarla.
- ⚠️ Este repositorio **no incluye ningún dato del juego**.

## Instalación
1. Descarga **`BT3Online.ipa`** desde la página de **Releases** (beta v1.0.1) o desde el espejo en **[MediaFire](https://www.mediafire.com/file/9nqrxodxkjxyla1/BT3Online.ipa/file)**.
2. Instálala con Sideloadly, AltStore o la herramienta que uses (se firma con tu certificado/Apple ID).
3. En el iPhone: **Archivos → En mi iPhone → BT3 Online** y copia ahí tu ISO (solo `.iso`; si tienes `.bin/.cue`, conviértelo antes).
4. Abre **BT3 Online**: la primera vez prepara los datos del juego con una pantalla de progreso. Cuando termine, ya puedes jugar.

Tus partidas, ajustes y log del juego quedan en esa misma carpeta (`saves/`, `bt3_settings.txt`, `bt3_log.txt`).

## Créditos
- **z3xox y colaboradores — [Tenkaichi3Decomp](https://github.com/z3xox/Tenkaichi3Decomp)**: la decompilación del juego y el port para PC. Su trabajo es lo que hace posible este port iOS — y cualquier otro port. ¡Gracias!
- **dfdx047 — [Dragon Rage](https://github.com/dfdx047/Tenkaichi3DecompAndroid)**: el port para Android sobre el que se construyó este port para iOS.
- **Sliu/LX772 — este port iOS**: código iOS, adaptación y pruebas.

## Contacto y donaciones
- **Sliu/LX772** (Luis Otaño)
- Teléfono / WhatsApp: **+1 (829) 981-2930**
- Telegram: **[@sliuenc](https://t.me/sliuenc)**
- Facebook: **[Luis Otaño](https://www.facebook.com/luis.ogandovalenzuela)**
- Correo: **luisencarnacion772@gmail.com**
- Donaciones (PayPal): **Walkinogando98@gmail.com** — si el port te gustó y quieres apoyarlo, ¡gracias! 🙏

## Licencia
- El código fuente correspondiente a este port está disponible en la rama `ios` de **[Tenkaichi3DecompAndroid](https://github.com/Sliu772/Tenkaichi3DecompAndroid/tree/ios)**: **AGPL-3.0** (ver `LICENSE`, heredado de Tenkaichi3Decomp desde su commit `06e4671`); el código anterior y partes de la app van bajo **MIT** (ver `LICENSE-MIT`). Las bibliotecas de `port/third_party/` mantienen sus propias licencias.
- El código del juego decompilado (`src/`, `include/`) pertenece a los titulares de los derechos de Dragon Ball.
- Este repositorio **no distribuye ningún recurso del juego**: necesitas tu propia copia obtenida legalmente.

## Aviso legal
Proyecto no afiliado ni respaldado por los desarrolladores, distribuidores ni titulares de los derechos del juego. Existe con fines de preservación y estudio. Dragon Ball y todos los nombres relacionados pertenecen a sus dueños.
