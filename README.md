# Lytra

A free, fan-made deck tracker for **MARVEL SNAP** on Windows.

*(Versión en español más abajo.)*

**[Download the latest version](https://github.com/teoisnotdead/lytra/releases/latest)** —
the file ending in `-setup.exe`. What changed in each version is in the
[changelog](CHANGELOG.md).

## What it does

- **An overlay beside the board**: your deck on the left — what is left in it, what you
  have drawn and played, your odds of drawing a card — and your opponent's cards on the
  right, as they reveal them.
- **Your record under your deck**: wins, losses and cubes with the exact twelve cards you
  are playing, lifetime or this session.
- **A dashboard in your browser**: every match you played while Lytra ran, your decks and
  how each card does in them. Click **YOU** on the overlay, or *Open dashboard* in the
  tray.
- **A quiz for your stream's chat**: a card's ability with its telling words blanked, and
  your Twitch or Kick chat racing to name the card with `!r a` to `!r d`. On the
  dashboard's Quiz page, shown in OBS as a browser source.
- **Updates itself**: when it opens, it installs a newer version if there is one.

## What it reads, and what it does not

Lytra reads, on your computer only: the game's log, the state files the game writes to
disk, and **the game's memory while the game runs**. It only reads — it does not inject
anything into the game, change it or automate it — and it shows only what the game
already shows you: never your opponent's hand, deck or draws. Card pictures come from
your own installation of the game.

**Nothing about you leaves your computer unless you send it.** Lytra connects to this
page to check for new versions and download them, and to lytra.app only when you choose
*Send a bug report*. While you run the stream quiz it reads your Twitch or Kick channel's
chat, the public one anyone sees, without signing in and without writing to it. Your match
history and the dashboard stay on your computer. No account, no sign-in.

## Installing

Run the `-setup.exe`. It installs for your Windows user only and needs no administrator.
Windows may say it "protected your PC", because the installer is not signed: choose
*More info*, then *Run anyway*. Start MARVEL SNAP, and Lytra finds it.

To stop it, right-click its icon in the taskbar's notification area and choose *Quit
Lytra*. Uninstall it from Windows' *Installed apps*.

## Bugs, ideas and news

On **[Lytra's Discord](https://discord.gg/QNSTW2PNqF)**: new versions in #announcements,
bugs in #bug-reports, and your ideas. Right after a bug happens, choose *Send a
bug report* in Lytra's tray menu: it sends what Lytra saw, privately, and copies a code.
Post that code with what went wrong — never the report's file, which holds your profile
and your opponents' names.

## Not affiliated

Lytra is not affiliated with, endorsed or sponsored by Second Dinner, Nuverse, Marvel or
Disney. MARVEL SNAP, its cards, names and art belong to their owners. MARVEL SNAP's terms
may restrict third-party tools that read the game: whether using Lytra fits the rules of
your account is your call and your risk. The installer shows the full terms.

---

# Lytra (español)

Un tracker de mazos gratuito para **MARVEL SNAP** en Windows, hecho por fans.

**[Descarga la última versión](https://github.com/teoisnotdead/lytra/releases/latest)** —
el archivo que termina en `-setup.exe`. Qué cambió en cada versión está en el
[changelog](CHANGELOG.md).

## Qué hace

- **Un overlay junto al tablero**: tu mazo a la izquierda — lo que te queda, lo que has
  robado y jugado, la probabilidad de robar una carta — y las cartas de tu rival a la
  derecha, a medida que las revela.
- **Tu récord bajo tu mazo**: victorias, derrotas y cubos con las doce cartas exactas que
  estás jugando, en total o en esta sesión.
- **Un dashboard en tu navegador**: cada partida que jugaste con Lytra abierto, tus mazos
  y cómo rinde cada carta en ellos. Haz clic en **YOU** en el overlay, o en *Open
  dashboard* en la bandeja.
- **Un quiz para el chat de tu stream**: la habilidad de una carta con sus palabras clave
  tapadas, y tu chat de Twitch o Kick compitiendo por nombrar la carta con `!r a` a
  `!r d`. En la página Quiz del dashboard, y en OBS como fuente de navegador.
- **Se actualiza solo**: al abrirse, instala la versión nueva si la hay.

## Qué lee, y qué no

Lytra lee, solo en tu computador: el log del juego, los archivos de estado que el juego
escribe en el disco y **la memoria del juego mientras está abierto**. Solo lee — no
inyecta nada en el juego, no lo modifica ni lo automatiza — y muestra solo lo que el juego
ya te muestra: nunca la mano, el mazo ni los robos de tu rival. Las imágenes de las cartas
salen de tu propia instalación del juego.

**Nada tuyo sale de tu computador, salvo lo que tú envías.** Lytra se conecta con esta
página para buscar versiones nuevas y descargarlas, y con lytra.app solo cuando eliges
*Send a bug report*. Mientras usas el quiz del stream lee el chat de tu canal de Twitch o
Kick, el público que ve cualquiera, sin iniciar sesión y sin escribir en él. Tu historial
de partidas y el dashboard se quedan en tu computador. Sin cuenta, sin iniciar sesión.

## Instalar

Ejecuta el `-setup.exe`. Se instala solo para tu usuario de Windows y no pide
administrador. Windows puede decir que "protegió tu PC", porque el instalador no está
firmado: elige *Más información* y luego *Ejecutar de todas formas*. Abre MARVEL SNAP y
Lytra lo encuentra.

Para cerrarlo, haz clic derecho en su icono en el área de notificación de la barra de
tareas y elige *Quit Lytra*. Se desinstala desde *Aplicaciones instaladas* de Windows.

## Bugs, ideas y novedades

En el **[Discord de Lytra](https://discord.gg/QNSTW2PNqF)**: las versiones nuevas en
#announcements, los bugs en #bug-reports, y tus ideas. Justo después de un
bug, elige *Send a bug report* en el menú de Lytra en la bandeja: envía lo que vio Lytra, en
privado, y copia un código. Publica ese código contando qué salió mal — nunca el archivo
del reporte, que tiene tu perfil y los nombres de tus rivales.

## Sin afiliación

Lytra no está afiliado a Second Dinner, Nuverse, Marvel ni Disney, ni cuenta con su
respaldo o patrocinio. MARVEL SNAP, sus cartas, nombres e ilustraciones pertenecen a sus
dueños. Los términos de MARVEL SNAP pueden limitar las herramientas de terceros que leen el
juego: si usar Lytra se ajusta a las reglas de tu cuenta es tu decisión y tu riesgo. El
instalador muestra las condiciones completas.
