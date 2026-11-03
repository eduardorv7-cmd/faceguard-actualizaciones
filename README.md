<p align="center"><img src="icono.png" width="128" alt="Ícono de FaceGuard"></p>

# FaceGuard · versiones

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/eduardorv7-cmd/faceguard-actualizaciones?label=versi%C3%B3n" alt="Última versión"></a>
  <a href="../../releases"><img src="https://img.shields.io/github/downloads/eduardorv7-cmd/faceguard-actualizaciones/total?label=descargas" alt="Descargas"></a>
</p>

Aquí se publican los instaladores de **FaceGuard** y la lista de versiones (`appcast.xml`) que usan las
actualizaciones automáticas de la app. El código de FaceGuard no está aquí.

FaceGuard vigila con la cámara de tu Mac (todo se procesa en tu Mac): la bloquea cuando te vas, la abre
cuando vuelves, tapa la pantalla si alguien más la mira y protege tus apps con tu cara. En el notch tiene
además tu música con letra, el clima, el calendario, notas, una bandeja con AirDrop, respuestas rápidas a
tus mensajes, el volumen y el brillo, lo que conectas (AirPods, mandos de PS4, PS5 o Xbox) con su batería, y un
espejo que toma fotos con temporizador o haciendo ✌️ a la cámara.

<p align="center"><img src="notch.png" width="900" alt="El notch de FaceGuard: widgets, reproductor, notas, responder mensajes y una cara desconocida"></p>
<p align="center"><sub>Capturas con datos de ejemplo.</sub></p>

## Instalar

1. Descarga `FaceGuard-<versión>.pkg` de la [última versión](../../releases/latest).
2. Ábrelo. La app no está firmada con una cuenta de desarrollador de Apple: si macOS no la deja abrir, ve a
   **Ajustes del Sistema → Privacidad y seguridad** y toca **Abrir de todas formas**.
3. Después se actualiza sola: baja la versión nueva y la instala apenas sale, para que siempre tengas los
   arreglos de seguridad. Se puede apagar en Ajustes → Comodidad.

Necesita una Mac con Apple Silicon y macOS 14 o más nuevo.

## Problemas

Desde la app: menú de FaceGuard → **Reportar un problema…** (o abajo en Ajustes). Se abre tu
correo con el mensaje listo y tú decides si enviarlo.

## Privacidad

Todo el reconocimiento corre en tu Mac. Si algo falla, y cuando FaceGuard se instala o se actualiza, se envía
un reporte técnico: la versión, el modelo de Mac, el chip, macOS y en qué parte del código pasó. Sin tu nombre,
sin el nombre de la Mac, sin IP ni ubicación, y nada de tu cara, tus fotos o lo que haces. No se guarda: solo se
reenvía por correo. Se apaga en Ajustes → Privacidad.

FaceGuard sí escucha, por tu seguridad, pero solo en un momento: si activas la alarma antirrobo, salta, y le diste
el permiso de Micrófono, graba 10 segundos de sonido para el video que te manda, y así queda registro de quién tocó
tu Mac. En ningún otro momento usa el micrófono. La foto, ese video y la ubicación van solo a tu Telegram y a tu
correo. Sin el permiso, el video sale sin sonido; puedes quitarlo en **Ajustes del Sistema → Privacidad y seguridad
→ Micrófono**.

Si dejas encendido **Seguir a la Mac después de la alarma**, y nadie la abre, se siguen mandando fotos y la ubicación a
tu Telegram y a tu correo: a los 2, 4, 9 y 19 minutos, luego cada 15 minutos hasta un día, y en cuanto cambia de red. Se
acaba al abrirla y se apaga en Ajustes → Perfiles. Las fotos del espejo se quedan en tu Mac salvo que tú las compartas.

## Licencias

FaceGuard (MIT). Lleva dentro DynamicNotchKit (MIT), mediaremote-adapter (BSD-3-Clause), Sparkle (MIT),
YOLOX-tiny (Apache 2.0) y UniFace (MIT); los avisos van en la app, en `Contents/Resources/licencias`.
