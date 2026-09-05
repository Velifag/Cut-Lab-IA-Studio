<p align="center">
  <img src="Drift_icon.png" alt="Icono de CutLabIA Studio" width="128" height="128">
</p>

<h1 align="center">CutLabIA Studio</h1>

<p align="center">
  <strong>El editor de video de escritorio gratuito que hace que tus videos se vean terminados — no "suficientemente buenos".</strong>
</p>

<p align="center">
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest"><img src="https://img.shields.io/github/v/release/Velifag/Cut-Lab-IA-Studio?label=release" alt="Última versión"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0-blue.svg" alt="Licencia: GPL-3.0"></a>
  <img src="https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS%20%7C%20Android-lightgrey" alt="Plataformas: Linux | Windows | macOS | Android">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.pt-BR.md">Português (Brasil)</a> ·
  <a href="README.es.md"><strong>Español</strong></a>
</p>

<p align="center">
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio">GitHub</a> ·
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest">Descargar</a> ·
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/issues">Issues</a> ·
  <a href="LICENSE">Licencia</a>
</p>

CutLabIA Studio es un editor de video de escritorio — un fork de [Drift](https://github.com/CutWire-Studios/Drift)
de CutWire Studios, distribuido bajo la misma licencia GPL-3.0. Importa tus clips, agrega efectos,
subtítulos, stickers y música, y exporta un video con acabado profesional — **sin suscripción, sin
marca de agua y sin necesidad de cuenta**.

Está hecho para las ediciones que la gente realmente hace: Reels y Shorts, clips de videojuegos,
trabajos escolares, tutoriales, demostraciones de producto, memes y todo lo que quieras que se vea
bien sin vivir dentro de un navegador ni pagar una suscripción mensual.

Lo que ves en la vista previa es lo que exportas. Un solo compositor, un solo resultado, sin
sorpresas.

## Descargar

Descarga la versión para tu plataforma desde la
[última release](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest):

| Plataforma | Paquete |
|----------|---------|
| Linux | [AppImage](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| Windows | [Instalador (.exe)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [Versión portátil (zip)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| macOS | [Imagen de disco (.dmg, Apple Silicon)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| Android | [APK (arm64-v8a)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [APK (armeabi-v7a)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [APK (x86_64)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |

En un teléfono, descarga `Drift-*-arm64-v8a.apk` desde la última release e instálalo (o usa
`adb install Drift-*-arm64-v8a.apk`). Usa la versión `x86_64` para emuladores.

Consulta [todas las releases](https://github.com/Velifag/Cut-Lab-IA-Studio/releases) para versiones
anteriores y changelogs completos.

<!-- Aún no distribuido en Flathub bajo este nombre — ese listado (org.cutwire.Drift) pertenece a
     CutWire Studios. Una publicación en Flathub para este fork necesitaría su propio app id y
     revisión. -->

## Capturas de pantalla

<p align="center">
  <img src="docs/screenshots/main-window.png" alt="El editor CutLabIA Studio: biblioteca de medios a la izquierda, vista previa de video en el centro, inspector de propiedades a la derecha, línea de tiempo abajo" width="900">
</p>

<p align="center"><em>Todo en una sola ventana — medios, vista previa, inspector y línea de tiempo</em></p>

<p align="center">
  <img src="docs/screenshots/timeline.png" alt="Línea de tiempo con cuatro pistas apiladas: dos superposiciones de imagen, un título y una pista de video mostrando miniaturas en tira de película" width="900">
</p>

<p align="center"><em>Una línea de tiempo multipista real, con superposiciones, títulos y miniaturas en tira de película</em></p>

<table>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/effects-panel.png" alt="Explorador de efectos mostrando vistas previas en miniatura en vivo de presets de glitch y distorsión" width="380"><br>
      <strong>Efectos que venden el look</strong><br>
      Cada preset se previsualiza sobre un fotograma real
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/transitions-panel.png" alt="Explorador de transiciones con vistas previas animadas de presets de fundido cruzado, wipe y push" width="380"><br>
      <strong>Transiciones que se sienten caras</strong><br>
      Colócala donde se superponen dos clips
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/stickers-panel.png" alt="Explorador de stickers con emojis agrupados por categoría" width="380"><br>
      <strong>Stickers y emojis al instante</strong><br>
      Busca, arrastra y suéltalos en el lienzo
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/text-styles.png" alt="Presets de estilo de texto incluyendo neón, karaoke, fondo de palabra y manuscrito" width="380"><br>
      <strong>Títulos que realmente se ven</strong><br>
      Neón, karaoke, resaltados y estilos de palabra llamativos
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/templates-panel.png" alt="Explorador de plantillas mostrando looks con múltiples efectos como Beat Drop y Glitch Cut" width="380"><br>
      <strong>Plantillas de look en un clic</strong><br>
      Combos sincronizados con la música como Beat Drop y Glitch Cut
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/audio-effects.png" alt="Explorador de efectos de audio con EQ, compresor, limitador, noise gate, de-esser y nivelador de voz" width="380"><br>
      <strong>Audio que suena intencional</strong><br>
      EQ, compresor, gate, de-esser y herramientas de voz
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/speed-fade.png" alt="Inspector de velocidad y fundido con presets de velocidad, reversa y deslizadores de fade in/out" width="380"><br>
      <strong>Velocidad, reversa y fundidos</strong><br>
      Cámara lenta, rampas, reversa y entradas/salidas limpias
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/subtitle-editor.png" alt="Editor de subtítulos listando líneas de subtítulo cronometradas, con la línea en el cabezal de reproducción resaltada" width="380"><br>
      <strong>Subtítulos generados a partir del propio audio</strong><br>
      Genéralos y luego edita cada línea
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/subject-cutout.png" alt="Diálogo de recorte de sujeto con un marcador de clic en la persona y el sujeto aislado resaltado" width="380"><br>
      <strong>Haz clic en el sujeto. Quédate solo con eso.</strong><br>
      Aísla a una persona u objeto en su propio clip
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/export-dialog.png" alt="Diálogo de exportación con presets de reducción de resolución y ajustes avanzados del codificador" width="420"><br>
      <strong>Exportación igual a la vista previa</strong><br>
      Presets simples a mano, control extra cuando lo quieras
    </td>
  </tr>
</table>

## Funciones que realmente aparecen en la edición

**Una línea de tiempo que se comporta como un editor de verdad.** Recorta, divide, ajusta (snap),
haz ripple, silencia u oculta pistas, y deshaz cualquier cosa. Apila superposiciones, títulos y
B-roll en lugar de pelear con un juguete de una sola pista.

**Looks en segundos, no en horas.** Efectos por GPU, transiciones con estilo y plantillas de look
reutilizables — para que un clip pase de material bruto a un resultado terminado sin abrir otra
aplicación.

**Texto, stickers, emojis y formas en el lienzo.** Títulos neón, subtítulos estilo karaoke, stickers
de reacción y llamadas de atención se quedan en el mismo editor que el corte.

**Subtítulos automáticos que realmente puedes corregir.** El habla se convierte en líneas de
subtítulo cronometradas. Edita el texto, ajusta el tiempo y exporta con subtítulos que coinciden con
cómo la gente ve videos en silencio.

**Recortes, máscaras y chroma key.** Haz clic en un sujeto y aíslalo en su propio clip. Enmascara
partes de una toma, o quita un fondo verde cuando necesites una composición más limpia.

**Movimiento que sigue el ritmo.** Rampas de velocidad, reversa, fundidos y cortes que encajan con
la música — el tipo de ritmo que hace que un clip se sienta diseñado, no improvisado.

**Herramientas de audio que limpian la mezcla.** Volumen, fundidos, EQ, compresión, limpieza de
ruido y efectos de voz, para que la narración y la música convivan en lugar de competir.

**Multicámara para cuando una cámara no es suficiente.** Mira todos los ángulos a la vez, cambia
entre cámaras y guarda el resultado como un corte limpio — sin reconstruir la línea de tiempo a
mano.

**Paquetes de proyecto para compartir y respaldar.** Empaqueta un proyecto con sus medios para que
toda la edición viaje contigo, en lugar de romperse en cuanto cambia una ruta de archivo.

**Exportación igual a la vista previa.** MP4 con presets de calidad, bucles GIF y exportación por
rango desde un área de trabajo de entrada/salida. Lo que aprobaste es lo que obtienes.

## Acceso de agente — deja que una IA edite contigo

CutLabIA Studio tiene un **servidor MCP** integrado para herramientas de IA locales. Activa el
acceso de agente y Cursor, Claude Code, u otro agente compatible puede trabajar en el proyecto
abierto: importar medios, colocar y recortar clips, cambiar efectos, capturar una imagen fija de la
composición y exportar.

Esto es un gancho de editor real, no un chatbot pegado a una página web. El agente ve la línea de
tiempo y puede hacer ediciones que puedes deshacer.

El acceso de agente permanece **desactivado hasta que lo actives**, y solo escucha en tu propia
computadora. La configuración completa y las notas de seguridad están en la
[guía de MCP](docs/MCP.md).

## Addons, sin inflar la instalación

Fuentes, stickers, efectos extra y modelos de transcripción de voz se descargan dentro de
CutLabIA Studio cuando los necesitas. Mantén la aplicación liviana y descarga solo los paquetes que
coincidan con el video que estás haciendo.

Abre el Gestor de Addons desde el encabezado, o sigue el aviso de instalación cuando una función
necesite un paquete.

## Por qué elegir CutLabIA Studio

La mayoría de los editores "gratuitos" quieren una cuenta, una marca de agua o una suscripción en
cuanto el video empieza a verse bien. CutLabIA Studio es lo contrario: **tuyo, en tu computadora,
GPLv3, sin muro de inicio de sesión.**

Es lo bastante rápido para un corte de redes sociales de 30 segundos y lo bastante completo para un
proyecto real — subtítulos, efectos, audio, recortes, multicámara y una línea de tiempo asistida por
IA si la quieres.

## Ayúdanos a traducir Drift

[![Translation status](https://hosted.weblate.org/widget/cutwire-drift/drift-desktop/multi-auto.svg)](https://hosted.weblate.org/engage/cutwire-drift/)

## Para desarrolladores

La compilación, el empaquetado, la arquitectura y el protocolo del agente están en `docs/`:

- [Compilación, pruebas, empaquetado y arquitectura](docs/BUILDING.md)
- [Efectos por GPU](docs/gpu-effects.md)
- [Transiciones por GPU](docs/gpu-transitions.md)
- [Arquitectura de Time Echo](docs/time-echo-architecture.md)
- [Acceso de agente / MCP](docs/MCP.md)

## Ayuda y comentarios

¿Encontraste un error o tienes una idea? Abre un
[issue en GitHub](https://github.com/Velifag/Cut-Lab-IA-Studio/issues).

## Licencia

GPLv3 — consulta [LICENSE](LICENSE).

## Historial de estrellas

<a href="https://www.star-history.com/?repos=Velifag%2FCut-Lab-IA-Studio&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&legend=top-left" />
   <img alt="Gráfico de historial de estrellas" src="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&legend=top-left" />
 </picture>
</a>
