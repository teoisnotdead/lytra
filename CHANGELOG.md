# Changelog

Each version in English, then in Spanish. *Cada versión en inglés y luego en español.*

## 0.1.25 · 2026-10-07

**EN**
- Stream quiz: a game for your stream's chat, on the dashboard's new Quiz page. A card's
  ability with its telling words blanked and four cards to pick from; the chat answers
  with `!r a` to `!r d`, the fastest right answer scores the most, and the most points
  after the last question wins. Add `http://127.0.0.1:47730/quiz/` to OBS as a browser
  source, and start, pause, restart a round or end the game from the Quiz page.
- It reads your Twitch or Kick chat, or both, without signing in, and never writes to it.
  The questions come from the game's own cards, in Lytra's language or the one you pick,
  and never about a card that is not out yet.
- The overlay on your stream, and the quiz, now reload by themselves when Lytra updates.
  Refresh your OBS source once after this update; from then on there is no need.
- The dashboard's menu is in three parts: your stats, the stream, and your account.

**ES**
- Quiz para el stream: un juego para el chat de tu stream, en la nueva página Quiz del
  dashboard. La habilidad de una carta con sus palabras clave tapadas y cuatro cartas para
  elegir; el chat responde con `!r a` a `!r d`, la respuesta correcta más rápida suma
  más, y gana quien tiene más puntos tras la última pregunta. Agrega
  `http://127.0.0.1:47730/quiz/` a OBS como fuente de navegador, y empieza, pausa,
  reinicia una ronda o termina la partida desde la página Quiz.
- Lee tu chat de Twitch o de Kick, o los dos, sin iniciar sesión, y nunca escribe en él.
  Las preguntas salen de las cartas del propio juego, en el idioma de Lytra o en el que
  elijas, y nunca de una carta que todavía no ha salido.
- El overlay en tu stream, y el quiz, ahora se recargan solos cuando Lytra se actualiza.
  Actualiza tu fuente de OBS una vez después de esta versión; desde ahí ya no hace falta.
- El menú del dashboard está en tres partes: tus estadísticas, el stream y tu cuenta.

## 0.1.24 · 2026-10-06

**EN**
- Fixed: the opponent's panel could grow a scrollbar as their Thanos Fractured Frontier
  fired and loaded again, above all in the 6 × 2 grid.

**ES**
- Arreglado: el panel del rival podía mostrar una barra de scroll cuando su Thanos
  Fractured Frontier disparaba y volvía a cargar, sobre todo en la grilla de 6 × 2.

## 0.1.23 · 2026-10-06

**EN**
- The overlay on your stream (*Copy OBS link*) now shows the tooltips you open: a card's
  text, a Thanos's Shots, and the cards behind a counter, such as those in hand or
  destroyed.

**ES**
- El overlay en tu stream (*Copy OBS link*) ahora muestra los tooltips que abres: el texto
  de una carta, los disparos de un Thanos y las cartas de un contador, como las que están
  en la mano o destruidas.

## 0.1.22 · 2026-10-06

**EN**
- Public profile: a page of your own at stats.lytra.app, under the name you choose, with
  your Ranked and Conquest decks as the dashboard's Decks page shows them (win rate, cubes,
  Copy code) and the links you add: Twitch, Kick, YouTube, X, Discord. It is off until you
  turn it on, on the dashboard's new Public profile page.
- With *Update after every match* on, each match goes up as it ends; *Update now* sends
  them all again. Hide the page, change its name or delete it at any time: deleting frees
  the name.
- Your opponents never go up: not their names, not their cards.
- The terms say what a profile publishes and how to delete it, and that stats.lytra.app
  shows the game's card art from its own copy.

**ES**
- Perfil público: una página tuya en stats.lytra.app, bajo el nombre que elijas, con tus
  mazos de Clasificatoria y Conquista como los muestra la página de Mazos del dashboard (%
  de victorias, cubos, Copiar código) y los links que agregues: Twitch, Kick, YouTube, X,
  Discord. Está apagado hasta que lo enciendes, en la nueva página Perfil público del
  dashboard.
- Con *Actualizar después de cada partida* encendido, cada partida se sube al terminar;
  *Actualizar ahora* las manda todas de nuevo. Oculta la página, cámbiale el nombre o
  bórrala cuando quieras: borrarla libera el nombre.
- Tus rivales nunca se suben: ni sus nombres ni sus cartas.
- Las condiciones dicen qué publica un perfil y cómo borrarlo, y que stats.lytra.app
  muestra las ilustraciones de las cartas desde una copia propia.

## 0.1.21 · 2026-10-06

**EN**
- The opponent's panel marks a probable bot beside their name: their account sends no
  region and no emote set, and every player's does. "Probable", because the game never says
  so outright.
- The dashboard's Decks page is new: the period's win rate, net cubes and matches up top;
  your decks in the order you choose (recent, most played, cubes per game, win rate); and
  for each deck its cubes per game, a ring of its wins, its record, and its cubes per win
  and per loss.
- Copy code on each deck: the deck as the game copies it, ready to paste in MARVEL SNAP's
  deck editor.
- The dashboard's cards wear Lytra's frame, with the cost and power drawn over the corners.
- Fixed: a Draft match could be kept in your history with the wrong date when Lytra opened
  after it had ended (LY-V6VYYK).
- Fixed: in Spanish, Draft's odds line lost its label.

**ES**
- El panel del rival marca a un bot probable junto a su nombre: su cuenta no trae región ni
  set de emotes, y la de cualquier jugador sí. "Probable", porque el juego nunca lo dice.
- La página de Mazos del dashboard es nueva: arriba, tu % de victorias, cubos netos y
  partidas del periodo; tus mazos en el orden que elijas (recientes, más jugados, cubos por
  partida, % de victorias); y de cada mazo sus cubos por partida, un anillo con sus
  victorias, su récord y sus cubos por victoria y por derrota.
- Copiar código en cada mazo: el mazo como lo copia el juego, listo para pegar en el editor
  de mazos de MARVEL SNAP.
- Las cartas del dashboard llevan el marco de Lytra, con el coste y el poder sobre las
  esquinas.
- Arreglado: una partida de Draft podía quedar en tu historial con la fecha equivocada si
  Lytra se abría después de que terminara (LY-V6VYYK).
- Arreglado: en español, la línea de probabilidades de Draft perdía su etiqueta.

## 0.1.20 · 2026-10-05

**EN**
- In the tray, *Save a bug report* is now *Send a bug report*: it sends what Lytra saw to
  Lytra's author, privately, and copies a code. Post that code in #bug-reports on [Lytra's
  Discord](https://discord.gg/QNSTW2PNqF), with what went wrong — never the file. Offline,
  the report is saved on your Desktop as before, and the dashboard sends it again.
- The dashboard has a Bug reports page: each report's code, when you made it, and the
  version that fixed it, once one does.
- The terms say what a bug report sends, and that it is deleted after 90 days.

**ES**
- En la bandeja, *Save a bug report* ahora es *Send a bug report*: envía lo que vio Lytra a
  su autor, en privado, y copia un código. Publica ese código en #bug-reports del [Discord
  de Lytra](https://discord.gg/QNSTW2PNqF), contando qué salió mal — nunca el archivo. Sin
  conexión, el reporte se guarda en tu Escritorio como antes, y el dashboard lo envía de
  nuevo.
- El dashboard tiene una página de reportes de bugs: el código de cada reporte, cuándo lo
  hiciste y la versión que lo arregló, cuando la haya.
- Las condiciones dicen qué envía un reporte de bug, y que se borra a los 90 días.

## 0.1.19 · 2026-10-05

**EN**
- Draft: beside your run's dots, a heart while you have an extra life to continue after
  your last loss, crossed out once you have used it this run; and the daily bonus for five
  wins: the mystery card while it is still yours to take today, a green check once taken.
  Point at either for the rest: your tokens, and when the bonus renews.
- Draft: a card's augment is in its tooltip, under the card's own text, headed "Draft":
  yours once you draw the card, your opponent's once they reveal it.
- Draft: no more "by end" odds, since a Draft match has no fixed last turn. It read 0% in a
  match's last turns while there were still draws to come.

**ES**
- Draft: junto a los puntos de tu run, un corazón mientras tengas una vida extra para
  continuar tras tu última derrota, tachado cuando ya la usaste en la run; y la
  bonificación diaria por cinco victorias: la carta misteriosa mientras aún puedas sacarla
  hoy, un check verde cuando ya la sacaste. Pasa el puntero por encima para ver el resto:
  tus fichas y cuándo se renueva la bonificación.
- Draft: el efecto extra de una carta aparece en su tooltip, bajo el texto de la carta, con
  el título "Draft": el de las tuyas cuando las robas, el de las de tu rival cuando las
  revela.
- Draft: ya no aparece el % "al final", porque una partida de Draft no tiene un último turno
  fijo. Marcaba 0% en los últimos turnos aunque aún quedaban robos.

## 0.1.18 · 2026-10-04

**EN**
- Draft: your cards wear the variant you set as favorite in your collection, as they do in
  the game.
- On both grids, each cost now leads with its lightest card: spells first, then power from
  low to high. The dashboard shows decks in the same order.
- Thanos Fractured Frontier follows the game's change: it starts the match with no Infinity
  Shot loaded, and its ring appears with the first one it loads.
- At the start of a match, the panels step aside for the avatar menus and show your
  opponent's name right away. In some matches both waited several seconds.
- Lytra is lighter while you play: the panels keep up on busy turns, and Lytra no longer
  searches the game's memory while you are in the menus.
- Opening Lytra and the game together, Lytra finds the game within seconds. It could wait
  five minutes, and your first Draft match then showed your selected deck.
- *Save a bug report* also takes a timeline of how each match started: what we need to find
  out why something came late.

**ES**
- Draft: tus cartas llevan la variante que marcaste como favorita en tu colección, como en
  el juego.
- En las dos grillas, cada coste empieza por su carta más liviana: primero los hechizos,
  luego de menor a mayor poder. El dashboard muestra los mazos en el mismo orden.
- Frontera fracturada de Thanos sigue el cambio del juego: empieza la partida sin ningún
  disparo cargado, y su anillo aparece con el primero que carga.
- Al empezar una partida, los paneles se apartan de los menús de los avatares y muestran
  el nombre de tu rival al instante. En algunas partidas ambos tardaban varios segundos.
- Lytra es más liviano mientras juegas: los paneles no se atrasan en los turnos con mucho
  movimiento, y Lytra ya no busca en la memoria del juego mientras estás en los menús.
- Si abres Lytra y el juego a la vez, Lytra encuentra el juego en segundos. Podía esperar
  cinco minutos, y tu primera partida de Draft mostraba entonces tu mazo seleccionado.
- *Save a bug report* también guarda una línea de tiempo de cómo empezó cada partida: lo
  que necesitamos para saber por qué algo llegó tarde.

## 0.1.17 · 2026-09-30

**EN**
- When a new version of Lytra comes out while you play, your panel says so: an *Update*
  button at the top, where your deck's name goes. Click it and Lytra restarts with the new
  version; the game stays open. Nothing restarts until you click.
- Draft: your run's dots have a W before the wins and an L after the losses, and the
  record beside them is gone: the dots already count it.

**ES**
- Cuando sale una nueva versión de Lytra mientras juegas, tu panel lo avisa: un botón
  *Actualizar* arriba, donde va el nombre de tu mazo. Haz clic y Lytra se reinicia con la
  nueva versión; el juego sigue abierto. Nada se reinicia hasta que hagas clic.
- Draft: los puntos de tu run llevan una V antes de las victorias y una D después de las
  derrotas, y el récord que tenían al lado ya no está: los puntos ya lo cuentan.

## 0.1.16 · 2026-09-30

**EN**
- Draft: the stats under your deck show how your run is going: a dot for each win and each
  loss the event allows, filled as they come, and the record beside them (1–1). When the
  run ends, it says so.
- The panels step aside for an avatar's menu as soon as the game opens it, from the first
  seconds of a match, instead of most of a turn later.
- With the game closed, Lytra waits for it instead of showing your last match.

**ES**
- Draft: las estadísticas bajo tu mazo muestran cómo va tu run: un punto por cada victoria
  y cada derrota que permite el evento, que se llenan a medida que llegan, y el récord al
  lado (1–1). Cuando la run termina, lo indica.
- Los paneles se apartan del menú de un avatar apenas el juego lo abre, desde los primeros
  segundos de la partida, en vez de casi un turno después.
- Con el juego cerrado, Lytra lo espera en vez de mostrar tu última partida.

## 0.1.15 · 2026-09-28

**EN**
- Draft: your panel shows the deck you drafted, for the run you are playing, instead of
  your selected deck. Draft matches are not saved to your stats, and the stats under your
  deck say so.
- Draft: the extra abilities a draft gives a card no longer show up as cards on the
  opponent's grid.
- A deck with two copies of a card counts each copy on its own: drawing one no longer
  marks both.
- Card names and texts follow Lytra's language: in Spanish, the game's own Spanish.
- A deck's card stats show each side as soon as it has 5 matches: the win rate with a card
  drawn no longer waits for 5 matches without it.
- Lytra starts collapsed and opens when a match begins, or right away if you open it
  mid-match. It collapses again when you close the game. With *Hide between matches* on,
  it stays out of sight instead.
- Draw odds know Domino: it is always your turn 2 draw, and never an earlier one.

**ES**
- Draft: tu panel muestra el mazo que armaste en el draft, el de la run que estás jugando,
  en vez de tu mazo seleccionado. Las partidas de Draft no se guardan en tus estadísticas, y
  las estadísticas bajo tu mazo lo indican.
- Draft: las habilidades extra que el draft le da a una carta ya no aparecen como cartas en
  la grilla del rival.
- Un mazo con dos copias de una carta cuenta cada copia por separado: robar una ya no marca
  las dos.
- Los nombres y textos de las cartas siguen el idioma de Lytra: en español, el mismo
  español del juego.
- Las estadísticas de cartas de un mazo muestran cada lado apenas junta 5 partidas: el % de
  victorias con la carta robada ya no espera 5 partidas sin robarla.
- Lytra inicia colapsado y se abre cuando empieza la partida, o de inmediato si lo abres en
  medio de una. Se vuelve a colapsar al cerrar el juego. Con *Hide between matches*
  activado, queda oculto.
- Las probabilidades de robo conocen a Domino: siempre es tu robo del turno 2, y nunca uno
  anterior.

## 0.1.14 · 2026-09-28

**EN**
- The panels take the same share of the screen on every monitor: smaller on a laptop or
  with Windows' scaling up, larger on a 1440p or 4K screen. A 1080p screen at 100% looks as
  before, and so does the stream.
- Cards are framed as the game frames them, in the overlay and the dashboard: the art
  larger, and each name at the game's size, hanging a little over the card's bottom edge.
- Some skins that showed the card's base art now show their own, a Merlin among them.
- Cards drawn wrong are drawn right: Hulk, Quicksilver, Misty Knight, Captain America, Iron
  Man, Spider-Man, Mister Fantastic, The Thing and others no longer show a head or an arm
  out of place, or a piece missing. So the first launch after this update draws every card
  picture again: about a minute, and the panel says so while it works.
- In the tray, *Save a bug report*: one file on your Desktop with what Lytra saw, ready to
  send us on Discord or GitHub. Nothing is sent on its own.
- In the tray, *Deck record* is now *Show deck stats*: it shows or hides the stats under
  your deck.

**ES**
- Los paneles ocupan la misma parte de la pantalla en cualquier monitor: más chicos en un
  notebook o con el escalado de Windows alto, más grandes en una pantalla 1440p o 4K. Una
  pantalla 1080p al 100% se ve igual que antes, y el stream también.
- Las cartas se encuadran como en el juego, en el overlay y en el dashboard: el arte más
  grande y cada nombre del tamaño del juego, asomando un poco sobre el borde inferior.
- Algunas skins que mostraban el arte base de la carta ahora muestran el suyo, un Merlin
  entre ellas.
- Las cartas que se veían mal ahora se ven bien: Hulk, Quicksilver, Misty Knight, Capitán
  América, Iron Man, Spider-Man, Mr. Fantástico, La Mole y otras ya no muestran una cabeza o
  un brazo fuera de lugar, ni les falta una parte. Por eso la primera vez que abras Lytra
  después de actualizar vuelve a dibujar todas las imágenes de las cartas: cerca de un
  minuto, y el panel lo indica mientras trabaja.
- En la bandeja, *Save a bug report*: un archivo en tu escritorio con lo que vio Lytra,
  listo para mandarnos por Discord o GitHub. No se envía nada solo.
- En la bandeja, *Deck record* ahora se llama *Show deck stats*: muestra u oculta las
  estadísticas bajo tu mazo.

## 0.1.13 · 2026-09-27

**EN**
- The overlay on your stream: in the tray, *Copy OBS link*, and paste it in OBS as a
  Browser source the size of your canvas (1920 × 1080 in most setups). It lines up with
  the game from the start, over a transparent background, and follows your overlay: what
  you collapse or hide, and a panel stepping aside for an avatar menu, go on stream too.
- Lytra opens once. Opening it again while it runs brings its overlay back, even hidden or
  collapsed, instead of a second copy drawing a second overlay over the first.

**ES**
- El overlay en tu stream: en la bandeja, *Copy OBS link*, y pégalo en OBS como Fuente de
  navegador del tamaño de tu lienzo (1920 × 1080 en la mayoría). Calza con el juego desde
  el principio, con fondo transparente, y sigue a tu overlay: lo que colapsas u ocultas, y
  un panel que se aparta por un menú de avatar, también en el stream.
- Lytra se abre una sola vez. Si lo abres de nuevo mientras corre, vuelve a mostrar su
  overlay, aunque esté oculto o colapsado, en vez de dibujar una segunda copia encima.

## 0.1.12 · 2026-09-27

**EN**
- Lytra speaks Spanish. Pick the language from Lytra's icon in the tray, under Language:
  System, English or Español. System follows Windows. Card names stay as the game prints
  them.
- Open your avatar to send an emote, or the opponent's to see their info, and the panel on
  that side steps aside until the menu closes.
- The opponent's grid no longer shows a spell of yours, like a Merlin's Once and Future.
- In the dashboard, each match shows its deck by its cards: the four most expensive in the
  row, all twelve when you point at them. The deck filter opens on every deck's twelve.

**ES**
- Lytra habla español. Elige el idioma desde el ícono de Lytra en la bandeja, en Language:
  System, English o Español. System sigue el idioma de Windows. Los nombres de las cartas
  quedan como los escribe el juego.
- Abre tu avatar para mandar un emote, o el del rival para ver su info, y el panel de ese
  lado se aparta hasta que cierres el menú.
- La grilla del rival ya no muestra un hechizo tuyo, como el Once and Future de un Merlin.
- En el dashboard, cada partida muestra su mazo por sus cartas: las cuatro más caras en la
  fila y las doce al pasar el mouse. El filtro de mazos se abre con las doce de cada uno.

## 0.1.11 · 2026-09-27

**EN**
- Switch, edit or clone a deck and the overlay has it at once, skins included.
- The opponent's grid is more accurate: a card they were given, like a Merlin's spell or a
  Prowler's tool, or one of theirs that was transformed, no longer takes a place among
  their twelve.
- In a Conquest duel or a friendly and its rematches, what earlier games showed of their
  deck stays on their grid, even if Lytra restarts. A new challenge starts clean, since it
  can bring another deck.
- If Lytra restarts in the middle of a match, to take an update for instance, it picks up
  where it left off.
- The overlay updates the moment something happens on the board.

**ES**
- Cambias, editas o clonas un mazo y el overlay lo tiene al instante, con sus skins.
- La grilla del rival es más precisa: una carta que le dieron, como un hechizo de Merlin o
  una herramienta de Prowler, o una suya que se transformó, ya no ocupa un lugar entre sus
  doce.
- En un duelo de Conquista o en un amistoso con sus revanchas, lo que las partidas
  anteriores mostraron de su mazo se queda en su grilla, aunque Lytra se reinicie. Un
  desafío nuevo empieza limpio, porque puede traer otro mazo.
- Si Lytra se reinicia en medio de una partida, por ejemplo para instalar una
  actualización, sigue donde quedó.
- El overlay se actualiza apenas pasa algo en el tablero.

## 0.1.10 · 2026-09-27

**EN**
- A new logo: cards arriving one after another, the newest in front. On the app, the
  installer, the tray and the dashboard.
- Every Conquest round is kept in your record: some went missing before.
- A deck you edit or clone is followed at once. The overlay no longer shows the deck from
  before for several matches.
- The opponent's grid: a card they transformed (Polymorph, Klyntar) keeps its place under
  its own name, and a spell they were given, like Merlin's, no longer takes a place among
  their twelve.
- Spells go first among the cards of their cost, on both grids and in the dashboard.
- Tray: *Hide between matches* puts the whole overlay away when a match ends, and the
  next match brings it back.
- Dashboard: "You" and "Opponent" instead of "We" and "They"; the turn each side snapped
  on, in a match's detail, from this version's matches on; a Conquest duel's rounds open
  from a button that says so; and Decks shows each deck as a card, its twelve in full art.
- The overlay's **YOU** is in Lytra's violet.

**ES**
- Un logo nuevo: cartas que llegan una tras otra, la más nueva al frente. En la app, el
  instalador, la bandeja y el dashboard.
- Todas las rondas de Conquista quedan en tu récord: antes faltaban algunas.
- Un mazo que editas o clonas se sigue al instante. El overlay ya no muestra el mazo
  anterior durante varias partidas.
- La grilla del rival: una carta que transformó (Polymorph, Klyntar) conserva su lugar con
  su propio nombre, y un hechizo que le dieron, como los de Merlin, ya no ocupa un lugar
  entre sus doce.
- Los hechizos van primero entre las cartas de su coste, en las dos grillas y en el
  dashboard.
- Bandeja: *Hide between matches* oculta todo el overlay al terminar una partida, y la
  siguiente lo trae de vuelta.
- Dashboard: "You" y "Opponent" en vez de "We" y "They"; el turno en que cada lado hizo
  snap, en el detalle de la partida, desde las partidas de esta versión; las rondas de un
  duelo de Conquista se abren desde un botón que lo dice; y Decks muestra cada mazo como
  una tarjeta, con sus doce cartas en arte completo.
- El **YOU** del overlay va en el violeta de Lytra.

## 0.1.9 · 2026-09-26

**EN**
- Lytra updates itself. When it opens, it installs a newer version if there is one. If
  one comes out while it is open, the tray offers it (*Update to …*) and waits for your
  click, so it never restarts in the middle of a match.
- The tray has *Check for updates*.
- The terms say it: Lytra's one connection is to GitHub, for its own updates. Nothing
  about you is sent.

**ES**
- Lytra se actualiza solo. Al abrirse, instala la versión nueva si la hay. Si sale una
  mientras está abierto, la bandeja la ofrece (*Update to …*) y espera tu clic, así que
  nunca se reinicia en medio de una partida.
- La bandeja tiene *Check for updates*.
- Las condiciones lo dicen: la única conexión de Lytra es con GitHub, para sus propias
  actualizaciones. No se envía nada tuyo.

## 0.1.8 · 2026-09-26

**EN**
- The dashboard, in your browser: an overview of your matches, every match with its
  detail, and your decks with how each card does in them. Open it by clicking **YOU** on
  the overlay, or *Open dashboard* in the tray.
- A new typeface on the overlay.
- The left panel's title reads **YOU** and your deck's name. The mode is on the record
  under your deck.
- Lytra now keeps which location each of your cards was played at.

**ES**
- El dashboard, en tu navegador: un resumen de tus partidas, cada partida con su detalle,
  y tus mazos con cómo rinde cada carta. Se abre con un clic en **YOU** en el overlay, o
  en *Open dashboard* en la bandeja.
- Una tipografía nueva en el overlay.
- El título del panel izquierdo dice **YOU** y el nombre de tu mazo. El modo está en el
  récord bajo tu mazo.
- Lytra ahora guarda en qué locación jugaste cada carta.

## 0.1.7 · 2026-09-25

**EN**
- Card pictures now show on a fresh installation of the game. They were missing, for
  good, on a game installed recently.
- Every card is drawn card-shaped in every grid: 3 × 4 has the full-size card again, and
  6 × 2 smaller ones in proportion, clear of the energy orb.
- A zone's list, over the counters, never shows cards bigger than the grid's.
- After a location swaps the hands (Mindscape), the cards of yours your opponent plays no
  longer appear as theirs, in that round or the next.
- A Kitty Pryde of yours that waits in your hand is no longer counted as one of theirs.

**ES**
- Las imágenes de las cartas aparecen con una instalación nueva del juego. Faltaban, para
  siempre, con un juego instalado hace poco.
- Cada carta tiene forma de carta en todas las grillas: 3 × 4 vuelve a tener la carta de
  tamaño completo, y 6 × 2 cartas más chicas en proporción, lejos del orbe de energía.
- La lista de una zona, sobre los contadores, nunca muestra cartas más grandes que las de
  la grilla.
- Después de que una locación intercambia las manos (Mindscape), tus cartas que juega tu
  rival ya no aparecen como suyas, ni en esa ronda ni en la siguiente.
- Una Kitty Pryde tuya que espera en tu mano ya no cuenta como una de las de tu rival.

## 0.1.6 · 2026-09-25

**EN**
- *Deck record* in the tray shows or hides the record under your deck, and is kept
  across restarts.

**ES**
- *Deck record* en la bandeja muestra u oculta el récord bajo tu mazo, y se mantiene al
  reiniciar.

## 0.1.5 · 2026-09-25

**EN**
- Your deck's record switches between lifetime and this session: click its label.
- The zone lists and the card tooltips open in the right place at every size.

**ES**
- El récord de tu mazo cambia entre total y esta sesión: clic en su etiqueta.
- Las listas de zonas y los tooltips de las cartas se abren en su lugar en todos los
  tamaños.

## 0.1.4 · 2026-09-25

**EN**
- Every match is kept, and your deck's record shows under it: wins, losses, ties and
  cubes with the exact twelve cards you play.
- Cards taken from the other side are marked, on both panels.
- *Grid* (4 × 3, 3 × 4, 6 × 2) and *Size* (Small, Normal, Large) in the tray.
- The overlay picks up a deck you edit between matches.

**ES**
- Cada partida se guarda, y el récord de tu mazo aparece bajo él: victorias, derrotas,
  empates y cubos con las doce cartas exactas que juegas.
- Las cartas tomadas del otro lado se marcan, en ambos paneles.
- *Grid* (4 × 3, 3 × 4, 6 × 2) y *Size* (Small, Normal, Large) en la bandeja.
- El overlay toma los cambios de un mazo que editas entre partidas.

## 0.1.3 · 2026-09-24

**EN**
- Cards that have come out are lit, and those still in your deck are darkened.
- A panel never scrolls sideways.

**ES**
- Las cartas que ya salieron se iluminan, y las que siguen en tu mazo se oscurecen.
- Un panel nunca se desplaza hacia el lado.

## 0.1.2 · 2026-09-24

**EN**
- A copy of one of your cards made by your opponent counts as made, not as one of theirs.

**ES**
- Una copia de una de tus cartas hecha por tu rival cuenta como creada, no como suya.

## 0.1.1 · 2026-09-24

**EN**
- The panels open when a match starts, and say when no deck is loaded or the card
  pictures are still waiting for the game.

**ES**
- Los paneles se abren al empezar una partida, y avisan cuando no hay mazo cargado o las
  imágenes de las cartas todavía esperan al juego.

## 0.1.0 · 2026-09-24

**EN**
- The first test version.

**ES**
- La primera versión de prueba.
