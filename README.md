# War of the Ring: Java Client

**Isengard Edition.** The Java client this community has played on for over 15 years,
continued from the original source code by Sean McCarthy and Andrew Poulter. The Isengard
Edition is a nod to Rafamir: the first edition with his *Treason of Isengard*.

**For players who own the physical game.** Friendly games for now.

## Download

### ➜ **[Download the latest version](../../releases/latest)**

Unzip and run: **Java is included** (Windows, macOS Intel and Apple Silicon, Linux x64),
nothing else to install. One download, works on every system. Your old logs and saved games
load exactly as before.

**Download once, then it updates itself.** The game checks for a new version when it starts (and once a day while it is open) and offers it in a small window, never in the middle of a network game. Most updates are a **quick update of about 2 MB**: digitally signed, checked before use, and one click to restart onto the new version, with small card-text, picture and sound fixes riding along. Only when a version changes a lot of the game's pictures or sounds will it ask you for the full download again. It keeps its own built-in Java up to date too (**Help → Update bundled Java**), so security fixes such as the recent Java 21 one reach you without a new download.

*Releases marked "quick update" are the small automatic ones; new players should take the latest **Full** release (the button above).*

---

## The big ones

Everything below is new in the Isengard Edition. Take the illustrated **Welcome Tour** (it opens from What's New, or **Help → New Features Tour**) for a walk through it.

- **It updates itself.** The game checks for a new version at startup and once a day and offers it in a small window, never in the middle of a network game. Most updates are a **quick update of about 2 MB**, digitally signed and checked before use, with card-text, picture and sound fixes riding along; **Restart now** brings you straight back on the new version. The built-in Java keeps itself patched too, and double-clicking **wotr.jar** now works even if your computer's own Java is old: it reopens the game on its built-in Java.
- **Four victory endings.** A Military Victory raises a painting of Barad-dûr (or, for the Free Peoples, Théoden facing the Witch-king's fell beast) out of the map while war-map arrows creep out to every Settlement that won it. A Ring Victory replays the whole journey: the Ring-bearers walk from the Shire to Rivendell and on along the way they really went to the Cracks of Doom. A Shadow Ring Victory ends with the Eye of Sauron. Each comes with about 17 seconds of music. Type **anim spmv**, **anim sprv**, **anim fpmv** or **anim fprv** to see them.
- **The story so far, as a film.** Type **anim history** (or **anim replay**) and the board goes back to the start of the game, then every move slides along at a steady pace: crossed swords over each battle, banners as Nations go to war, the Eye on the Ring-bearers. Click the map to stop.
- **The map moves.** Every Companion, Minion, Nazgûl and Eagle moved in an action leaves a trace until the action ends: flight arcs for Nazgûl and Eagles, walking routes with a circled step count that turns red past their Level, and a STOP sign on any Shadow Stronghold the route enters. A Nation going At War raises its banner over its lands; an Eye tile brings the red Eye to search over the Ring-bearers. **Separate...** in the Preview Pane shows where Companions may go. All of it can be turned off (View › Options › Map animations).
- **The Fellowship's route, shown.** A reveal or a declaration logs the exact route ("Reveal: Hollin -> Moria -> Dimrill Dale") and draws it on both screens, with the Ring-bearers walking it; when routes touch different places, the Free Peoples choose, so the Stronghold and Balrog tiles are exact.
- **Agreed Play: Comfortable or Strict.** Agree at the start how much the client helps (optional-ability prompts such as the White Rider, the Sorcerer and Gandalf's Guide draw); illegal plays are blocked in both, and the choice is logged.
- **The Current Action tray.** When the map is zoomed in and the Current Action strip is off screen, a copy slides into the corner with the Hunt Box and both sides' VP, and works like the real one.
- **Cards that do their own work.** Servants of Sauron, His Will and His Malice, Her Own Offspring, A Great Fleet, Craft of Shelob, By Chance or by Foresight, The Union of All Our Strength and more pick and place for you; Challenge of the King and Premonition of Danger draw their tiles one by one onto the table. The Hunt panel knows all eight special Hunt tiles.
- **Solo just flows, and starts in one click.** On a fresh game, turning Solo on (Game › Solo Game, or saying yes when DRAW CARDS offers it) offers a **quick start**: both sides draw their turn 1 cards, Gandalf is the Guide, one Eye goes in the Hunt Box, both sides roll, and the Free Peoples act first (Lords of Middle-earth uses every variant Companion; the Battle of Five Armies gets its draws). Type **quick-solo** for the same. From then on the client hands the table to whichever side acts next: after END ACTION, PASS or Esc, after the Action Roll, whenever one side is waiting on the other, and through every step of a battle and a Hunt. A small fading note says when it switched; Act as still lets you switch by hand.
- **Gandalf the White and Aragorn in one click.** With a Will of the West die being played, click Gandalf the Grey in the casualties to bring in Gandalf the White (only the legal places are offered: Fangorn or an unconquered Elven Stronghold), or click Strider in Minas Tirith, Dol Amroth or Pelargir to crown Aragorn, Gondor activated with him.
- **Point things out.** Type **pointer** and click places on the map to draw a route both players see; **pointer flying** draws a flight arc; **pointer bofa** (also **range-bofa**) measures the Battle of Five Armies range finder from an exact point to a region and says In range or Out of range. End Action clears them.
- **More cards and rules handled.** The Grey Company, House of the Stewards, Fathers of Trees, The Dead Men of Dunharrow (with its attack roll), Swords in Eriador, Rangers of the North, Éomer, the Musterings and the Elven musters place their units; Tom Bombadil and A Power Too Great keep Shadow Armies out; Wormtongue holds Rohan passive; a card reveal through a Shadow Stronghold such as Moria opens the Hunt panel for just its Stronghold tiles; Gandalf the Grey Wanderer's Guide draw is offered even after a card that draws.
- **More life on the map.** The Elven Rings drift and burn when used, Corruption slides, a portcullis drops on a siege, the Balrog breathes fire, Gandalf the White shines and Aragorn is crowned, a fallen Companion fades, over-stacked regions flash red, and each new turn gets a banner. The history film draws trails and routes, with pause and speed keys.
- **Help level: Normal or Expert.** Expert keeps every rule enforced but drops the explanations: no pop-ups for things the client has already done and logged, shorter Hunt steps. Normal explains each step for players still learning.
- **"Not done" notes, not pop-ups.** When your own client refuses something (a card with no die to play it, Choose with nothing selected, Esc during an unfinished Hunt or battle), an amber note appears over your hand for a few seconds instead of a window to click away.
- **Characters speak.** New voice lines for Gandalf (the Grey, Keeper of Narya, the White), Strider, Aragorn, Saruman, the Witch-king and the Mouth of Sauron as they enter play or become the Guide.
- **Reference sheets in the box.** The updated **War of the Ring Almanac** and **Almanac, Expansions**, plus the **Warriors of Middle-earth One-page Summary** and **All Companions and Minions** (by roysubs), ready in the Almanacs folder, the Bookshelf and the "?" menu.
- **Quick Save, your name.** File → Quick Save proposes a name you can change, and never overwrites a different save by accident.
- **Play online, step by step.** Play on Network now walks you through it in order: your game, then pick a way to connect (ZeroTier, Hamachi, Radmin VPN or the same home network, with what is installed and an Install button for what is not), then host or join. Hosting copies your IP and the waiting box shows it big, so you can always give it out.
- **Voice chat built in.** Push-to-talk on F6 or open mic, each player's own choice; the mic turns green only once voice really connects, and hovering it shows your opponent's mode.
- **Your shortcuts, by mouse.** The Preview Pane offers buttons where they apply: Upgrade / Downgrade, Flip, Random Companion, WWSAT discard and Use Ring (click the Elven Ring label to see the rings together). The turn button reads END ACTION while your die is in play, and a Palantír beside the mic opens the Event Cards.
- **Hear a card.** A small ♪ button in the Card View plays the card's sound clips in order, only on your computer.
- **Any character's card in one click.** Ctrl+Shift+click a Companion or Minion in the Preview Pane and his Character card appears, word for word as printed, with his Level, Leadership and Action die. Every card of the base game and Lords of Middle-earth, plus Treebeard and Treason of Isengard's own reworked cast, and it follows the figure: Strider or Aragorn, Gandalf the Grey or the White, Sméagol or Gollum, a Captain or a Champion.
- **Character musters by the rules.** Saruman, both Witch-kings, both Mouths of Sauron, the Balrog, Gothmog, Gandalf the White, Elrond and Galadriel are checked the moment they enter play, with a one-click Take him back or Move him. Strider, Dúnadan's Guide die goes to the Fellowship Box as the card says.
- **The Fellowship phase, guided.** The FELLOWSHIP button declares the Fellowship and applies the healing and Nation activation for you, marks the farthest regions it can reach (or healing places, or the way to Mordor) as dots, borders or whole regions, offers **Enter Mordor** at Morannon or Minas Morgul, and on turn 1 lets you choose the turn 1 Guide.
- **The Guide is always right.** Whenever the Fellowship is left without a Guide, a picker shows each Companion with their Level and only the highest Level can be chosen. Gollum steps in by himself, Sméagol is always the Guide as his card says, and **We Shall Get It** enters play whenever he leaves, except when Gollum replaces him. AD ROLL waits until the Guide is right.
- **Reveal the Fellowship, step by step.** A Reveal tile offers **Reveal the Fellowship?**; the reveal window opens on both screens, greys the regions it cannot enter and refuses an illegal move. A Hunt can be **hidden and resumed later**, like a paused battle, and on the Mordor Track every move draws a tile, even with no dice in the Hunt Box.
- **The Random Companion is the Shadow's pick,** as the rules say: the Free Peoples ask, the Shadow chooses from a list that hides Lords of Middle-earth versions, and the casualty is shown on the table for both players.
- **Elven Rings enforced.** One ring per player per turn (the Keepers' own abilities apart), the used ring flips and passes to the Shadow, and the rule shows only to you.
- **Political Track buttons.** Advance a Nation or move it to At War from the Preview Pane, and the Shadow's **Stormcrow** button appears only when the card is on the table and the Nation is not At War. Upgrade and Downgrade refuse when the replacements have run out.
- **Lords of Middle-earth, in order.** Special dice after the Action roll (an Eye goes to the Hunt Box, two or more open a picker), the Balrog's political advance and his optional Sauron unit, the starting Guide after the Council of Rivendell, and the Almanac's order of play after a declaration or reveal, with Worn with Sorrow and Toil discarded for you.
- **The rulebooks come with the game.** War of the Ring, Lords, Warriors, Kings and Sieges of Middle-earth, The Battle of Five Armies, both Rules References and The Breaking of the Fellowship all open from Books (Ctrl+/), with the updated War of the Ring Almanac.
- **New Game tells you everything.** Hover any expansion, extra or scenario for a full tip that stays up while you read: every Faction by name, the card counts, the new dice, who made each scenario, its story and how to win.
- **Dark Chieftain forfeits in the Battle box:** the Shadow picks the forfeit in the box, a button for each Dark Chieftain in this battle plus No forfeit.
- **The Free Peoples' battle-stoppers.** Play **Scouts** as a field defender and the Battle box offers **Scouts: retreat** (or **into siege** at a Stronghold) before the Combat roll; play **The Forest Is Rising** or **The Terror of the Dead** and it offers to end the battle at round end. Never when the card was cancelled (Swarm of Bats, Lord of the Bats, either Brand), and a cancelled card is struck through with what cancelled it.
- **The rules that bite, enforced exactly.** **Captain of Despair** works as the card says: from the action after it is played, every Shadow Character die goes to the Hunt Box; it can only be played with the Witch-king in play and Gollum not the Guide; and both players are told the moment it must be discarded. **The Black Captain waits for war**, and `att` refuses an Army that is not At War, like the Preview Pane.
- **No die, no card.** Double-click a card with no Action die in Current Action and nothing happens, with a private note only you see, so an off-turn slip never shows your opponent a card.
- **Over 50 ways to play, from one New Game window.** Every expansion alone or together, the official scenarios and the fan-made variants: over 50 unique game combinations, and over 100 with the optional extras such as Cities.
- **Solo plays like the real thing.** In a Kings of Middle-earth solo game, Act as the Free Peoples and the Hunt Pool shows only tile backs; Act as the Shadow and you see the faces, exactly as each side sees it online.
- **Type anywhere, and Ctrl+Space.** The chat line is a command line: `find fang` flashes Fangorn on the map, `att lorien` starts a battle, `#valinor` opens an Event card with its Almanac notes, `!valour` shows a Combat card's ruling. **Ctrl+Space** opens a palette of every command; **View → Chat Commands** has a Getting Started page.
- **One button for the whole turn.** **NEW TURN** recovers your dice and draws your cards, then becomes **AD ROLL** (rolls your Action dice; the Shadow's Eyes go straight to the Hunt Box), then **PASS** whenever you hold fewer unused dice than your opponent. Tiny **C / S / F / F+** buttons draw a card in one click.
- **Your dice, right every turn.** The extra dice for Gandalf the White, Aragorn, Saruman, the Witch-king and the Mouth of Sauron join by themselves, and a popup explains every die you have and why, with the Hunt Allocation minimum and maximum for the Shadow.
- **The rules people forget, handled.** Empty Event decks are skipped (never reshuffled), an empty Faction deck is reshuffled, and in Mordor the Ring-bearers take their Corruption if the Fellowship did not try to move or hide (it asks first).
- **Battle Resolution, rebuilt.** One click rolls the current step, the Leader re-roll offers 0 to 5, a Post-Combat roll waits its turn, and White Rider, the Sorcerer, Brand and the Mouth of Sauron sit with the Combat cards, lit only at their moment. A Dark Chieftain's synergy forfeit glows gold.
- **The Hunt Resolution helper (Ctrl+M).** Hunt Level, the number to hit and re-rolls worked out from the board, damage in rulebook order. The Fellowship-move die now follows the rules: it goes into the Hunt Box at Esc, after the move.
- **Attack and Hunt buttons** in the Preview Pane: pick a neighbouring enemy Army to attack, with both sides' strength shown.
- **Cards only go where they belong.** Hands and decks refuse the wrong pieces, with the reason; the Faction Cards Temporary Hand takes only Faction cards.
- **Sound.** A clash of swords as battle opens, a Grond roar, character voices, and a volume slider for each kind of sound.
- **Make it yours.** Responsive Options in columns, a regrouped View menu, and Gandalf the White standing or on Shadowfax, whatever the game.
- **All three expansions, one system.** Play LOME, WOME and KOME alone, in pairs, or all three at once, with every special die handled for you, each in a floating overlay that stays out of your way.
- **End a game the right way.** When the game is over, both players agree the result and the clients swap hand keys automatically, so each side keeps a log that replays with every card showing, and the result goes into the statistics. Perfect for tournaments and reviews.
- **No Java to install, on every system.** Built in, for Windows, macOS (Intel and Apple Silicon) and Linux. Download, unzip, run.
- **Watch it, and tell its story.** Replays with a replay bar and Ira mode, the Chronicle written for you turn by turn, full statistics, and one Reference window for every rule and card (Ctrl+/).
- **Fair play, locked down.** Both serious exploits from V8 are closed, and a tampered client still can't cheat you: dice and draws can't be steered, forged Corruption tiles are caught, your hand is sealed with a key only you hold, and anything a dishonest copy sends is refused and logged.

---

## A guided tour

- **The Welcome Tour, rebuilt.** Twenty-eight illustrated pages on the things you will use every game: the View menu and Options, themes, every expansion and variant and their Helpers, chat commands and the Ctrl+Space palette, a whole battle typed from the chat box, the rules the client enforces, online play, the Game Clock, self-updating, the one-button turn, the Battle and Hunt helpers, cards and the Almanac, solo play, replays and more, most with a **Try it** button that opens the real feature. It opens from the What's New window (**Take the tour**), or any time from Help › New Features Tour.

## Start each turn in one click

- **NEW TURN button.** Beside Casualties on each side's tab. It lights up once every Action die on both sides has been used, then one click recovers that side's Action dice (any die gained or lost is handled for you), draws a Character and a Strategy card (and a Faction card with Warriors of Middle-earth), and shows which Action dice you now have, and why. For the Shadow it also states the Hunt Allocation minimum and maximum for this turn (with the Keeper-die exception in Lords of Middle-earth). Its tooltip lists all six phases of the turn.
- **One button for the whole turn: NEW TURN, AD ROLL, PASS.** After NEW TURN the button becomes **AD ROLL** and rolls your Action dice (never the Hunt Box; the Shadow's Eyes go straight to the Hunt Box). During Action Resolution it becomes **PASS** whenever you hold fewer unused Action dice than your opponent and no die is in Current Action. Dwarven and Hunt tokens are never counted as dice.
- **The extra Action dice arrive by themselves.** Recovering your dice now tops up the plain dice to what the rules give: one more each for Gandalf the White, Aragorn, Saruman (the Treason of Isengard Saruman too), the Witch-king and the Mouth of Sauron, taken from the Reinforcements; a die whose Character has gone goes back. The dice that count this turn are shown in your side's colour.
- **Forgotten rules, handled at the turn start.** An empty Character or Strategy deck is skipped, as spent decks are never reshuffled; an empty Faction deck is reshuffled from its discards. In Mordor, if the Free Peoples did not try to move or hide the Fellowship, NEW TURN adds the 1 Corruption (it asks first).
- **One-click draw buttons.** Tiny **C** and **S** buttons (and **F** and **F+** with Warriors of Middle-earth) beside NEW TURN draw a Character, Strategy or Faction card, exactly like the F-keys. A draw still waiting on your opponent is never silently lost.
- **Act as switches your hand too.** In a solo game, Act as FP or SP now also opens that side's hand.
- **One tidy row.** In a narrow side panel the Force Pool and Casualties pictures shrink a little, so NEW TURN and the draw buttons stay on the same line beside them.

## Sound comes to the board

- **Battle and card sound.** A sword-clash as a battle opens and a Grond roar on the Grond card, plus a voice line as a major Character comes into play or takes the Guide (Galadriel, Elrond, the Mouth of Sauron, the Witch-king, Saruman, Gothmog, the Balrog, Gandalf the White, Sméagol and more). Card plays have their own sounds across base game and every expansion, the same on both clients, and it all ships as MP3 at a tenth of the old size.
- **A mixer for every kind of sound.** View › Options has a volume slider each for board effects, Free Peoples cards, Shadow cards and character voices, from off to full.
- **More moments with sound:** a Nation going to War, a siege, the Fellowship revealed, Corruption rising, an Eye tile, the special Hunt tiles, Sovereigns awakening or falling to corruption, Dark Chieftains arriving, and a fanfare for each kind of victory.

## The Hunt Resolution helper

- **Ctrl+M opens it.** Moving the Fellowship raises the Hunt Resolution panel (when there are dice in the Hunt Box), with the Hunt Level, the success number and the re-rolls all worked out from the board. Roll from the panel or with Ctrl+1 to 5, correct the hit count if a factor is off, and draw the tile.
- **Rules, never advice.** It walks the mechanical spine of a Hunt and states the rules in order: resolve the damage first (take a casualty, the Guide or a random Companion that the Shadow draws, then Use the Ring to advance the Corruption counter on the Fellowship Track), and the reveal happens last (move the Ring-bearers figure, then reset the Fellowship Progress counter). It never tells you which card or ability to play: that knowledge is your own, and part of the game.
- **Draw another tile** for the reveal, Stronghold and Balrog extra tiles; a free move with no dice in the Hunt Box just says so instead of opening the panel; and Sméagol becoming the Guide is offered, and now plays his voice.

## Muster cards place the troops

- **Recruit Event cards muster for you.** Over twenty muster cards, Free Peoples and Shadow (A New Power Is Rising, the Elven cards, Grimbeorn, Guards of the Citadel, Imrahil, Dáin's Guard, The Red Arrow, King Brand's Men, Riders of Théoden, Éomer, Orcs Multiplying Again, Monsters Roused, Musterings of Long-planned War, The King is Revealed, Shadows on the Misty Mountains, Horde from the East, Half-orcs, Olog-hai, Great Winged Creatures and more), show exactly what they will place before anything moves: every mix of Elites and Regulars the Force Pool allows, a warning when the best muster is not there, Back out on every screen. Regions held by the enemy are skipped, Stronghold recruits join a besieged Army in its box, the card's own conditions (At War, Aragorn in play, Gondor active) are checked, and the Strategy card or Rohan's Political step happens where the card says. The Kings of Middle-earth versions offer their Sovereign alternative, and the few cards not yet automated show their text and let you place by hand.

## Richer board tooltips

- **Army tooltips in Nation colours.** Hover an Army and each Nation's forces show in its own colour, greyed if that Nation is not yet at War, as a single clean line or a full breakdown, in a lightweight tip tied to the board.

## Battle Resolution

- **A full, opt-in combat helper** that walks both sides through a battle in rulebook order: the rearguard, the Combat cards (the attacker declares first), the Pre / Combat / Leader / Post rolls, retreat into a siege or to an adjacent region, and the advance. The to-hit number and the leader re-rolls are worked out for you each round.
- **Every expansion ability at the moment it matters:** White Rider, the Dark Chieftain forfeits (Lord of the Bats, Red Wrath, I Command) and Brand's (Heir of Bard, Shadows in the North), the Black Captain's Sorcerer draw, the Mouth of Sauron's Evil Knowledge, the Champions and the Balrog's extra dice. Each shows its text, its initiative and the Almanac notes.
- **Drive it any way you like:** the buttons, the keyboard (Ctrl+1..5 to roll), or short words typed anywhere in the chat line. A pause word (`xx`) stops all dice rolling so both players can stop and talk.
- **It blocks the genuinely illegal plays** and explains why (a Shadow card that needs Nazgûl Leadership while White Rider negates it), but never a merely weak one. End-of-action and Clear-cards are held while the box is open, so a battle is never left half-finished, and an undo rolls the box back together with the board.
- **Faster rolls.** One click rolls the current step. The Leader re-roll offers 0 to 5, with a yellow 0 when you have no leadership, so there is no more "No more rolls" step, and a Post-Combat roll waits for the other side to catch up.
- **Abilities sit with the cards.** White Rider, the Sorcerer, Brand and the Mouth appear under the Combat cards like cards on the table: grey until their moment, amber when you can use them, with the full text on hover. A Dark Chieftain's synergy forfeit is picked out in gold. The Black Captain's **Sorcerer** lights with the Shadow's round-end decision and asks for it first, then draws, in the Almanac's order.
- **Tall battles scroll** instead of running off the bottom of the screen.
- **A one-line battle summary** written into the log, so a replay always shows what each battle was, plus a per-round Battle Stats tracker.

## Type anywhere

- **The chat line is a command surface.** A plain letter typed over the board jumps there, and Up / Down recall what you last sent, like a terminal. The game-log pane can no longer steal your focus, and you can still select and copy from it.
- **`att <region>`** opens a battle from an adjacent Army, matched by part of the name or its initials (`att mt` = Minas Tirith).
- **The command palette: Ctrl+Space.** Every chat command in one list (map, reference, Battle box and Hunt panel words). Type to filter, Up / Down to choose, and Enter puts the command in the chat line, ready to finish and send. Ctrl+Shift+Space works too, View › Chat Commands has the palette and a Getting Started page, and typing `cmds` opens it too.
- **Find any region.** Type `find fang`, `show fang` or `where fang` and the map scrolls to Fangorn and flashes it blue for a few seconds. Several matches all flash, and `att` flashes its target too.
- **Reference at a keystroke:** `alm` / `almex` open the Almanacs, `init` / `rulers` / `hunt` and more open that page, `#<title>` pops an event card with its Almanac, and `!<name>` shows a combat card's text, initiative and rulings. Type `cmds` for the list.

## The Chronicle, reconstructed from the log

- **The whole game told back to you** (View › Statistics, now at the top of the menu). Every line is worked out from the log, so it is identical on both clients and in a replay.
- **Each turn's opening roll,** one line per side in plain letters, “Free Peoples rolled W P W P”, “Shadow put 1 Eye to the Hunt Box, and then rolled C P E H H E C P (2 more Eyes to the Hunt Box)”
- **Place names everywhere:** “Gandalf came into play in Fangorn”, “Aragorn crowned in Minas Tirith”, and an Army retreating under siege reads “Free Peoples Army besieged in Woodland Realm”
- **The whole battle on one line:** who attacked and where (“Shadow attacks Lórien Stronghold”), each round's card pair attacker-first (“Deadly Strife vs Sudden Strike; No Card vs Elven Cloaks”), and both sides' casualties as Regulars/Elites/Leaders with named Characters, including the Shadow's losses, which go back to the Force Pool to regenerate
- **The Fellowship in Mordor,** told in full: “The Fellowship reached Step 1, Morgai/Udún, an Eye was drawn, and Strider was eliminated. Legolas is the new Guide”
- **Cards that matter:** an Elven Ring passing to the Shadow, Athelas and Candles of Corpses with the Guide state and the dice they rolled, and a card that seeds its own special Hunt tile folded into one line

## Victory points, done properly

- **Captured by occupation, not just by a marker:** a Stronghold or City held by an enemy Army with no defender left counts for its Victory points even when no control marker was dropped, matching how real games are played
- **Capture is sticky, with recapture:** a side keeps a place (and the points) after its Army marches on, until the other side's Army actually moves back on. A besieged garrison still holding out in its box is never mis-counted as lost. Captures and recaptures are announced with their value (“Lórien captured for 2 VP”)
- **Control markers kept honest:** at the end of each action the client drops or lifts the physical markers to match what the armies hold, an enemy Army on a City or Town, or on a Stronghold with an empty siege box, is marked captured; a marker comes off the moment the owner retakes the place. Both directions, Towns included (they block the enemy mustering), a log line each time. It only tidies the board; the points are still the sticky occupation count

## More rules handled, so lazy tables stay legal

- **Nothing lost in a card pile.** Card decks and discard piles take only cards, and each pile only its own kind (no Strategy card in the Faction discard); the Faction temporary hands, F+ and S+, take only Faction cards. A wrong drop is stopped, with the reason.
- **Special Hunt tiles placed for you:** play the Event card that brings one of the eight special tiles into play and the client offers to put the tile where it belongs, the Hunt Pool if the Fellowship is in Mordor, else set aside until it gets there. Entering Mordor offers the “Create a new Hunt Pool” step, returning every set-aside special and Eye tile at once
- **The Hunt panel knows the table:** it lists every Play-on-the-table card bearing on this Hunt, Flocks of Crebain, We Shall Get It, We Won't Go Back, The Gates are Closed, Worn with Sorrow and Toil; Wizard's Staff, Mithril Coat and Sting, Axe and Bow, Horn of Gondor, Fool of a Took!, each tagged with the side that may use it and when. Uglúk (KOME) now correctly gives +1 to hit on re-rolls, the opening roll and every re-roll show together, you can correct the hit count, and a **Mis-roll?** button fixes a wrong dice count
- **The Black Captain musters them to war:** when the Witch-king, the Black Captain enters play, the Shadow is offered to activate every passive Free Peoples Nation on the Political Track, except Rohan while Wormtongue is on the table
- **Spear of Terror (LOME):** when the Chief of the Ringwraiths is with the Fellowship and the Shadow plays a Character card, the Shadow is offered to draw a Character card at once, with the Palántir of Orthanc one-or-the-other reminder
- **Captain of Despair** sends a used Shadow Character die to the Hunt Box (kept as a Character, so KOME tells it from a Corruption die), while the card is on the table and the right Witch-king is in play
- **Gandalf the Grey Wanderer** draws a matching card: play a Free Peoples Event card with Gandalf the Grey as the Guide and he draws to match, Character, Strategy, or (under WOME) Faction, checked at the end of the action (so a mid-action separation that makes him the Guide still counts), the base Grey Wanderer only, and it stays quiet if you already drew it (or warns if you drew the wrong type)
- **The Palantír of Orthanc** (Saruman): at the end of the action, if Saruman is still in play, he may draw one card from **any** deck, a button for Character, Strategy, and Faction under WOME. Skipped if the Shadow already drew that action, so it is the Palantír or Spear of Terror, never both

## Replays, much better

- **Always from the start:** loading a replay drops you cleanly at the beginning, never on top of the last game
- **Skip the setup** and land where play begins, at a watchable speed; **truly fast** fast-forward (1000x now flies); and **Replay a Ladder Game** saves each one with a readable name
- **Old and foreign logs play too,** with the cards shown on the table even when their seals cannot be checked, and translated menus for every language
- **Space to play/pause from anywhere:** pressing **Space** (play/pause) or **Left/Right** (speed) during a replay now works regardless of whether you clicked the board, the game log, an empty chat box, or a floating card preview

## Board helpers

- **Region tooltips** (View › Hover tips): hover any region and a tooltip shows its name and Nation, a teaching aid, exact at every zoom. Over a City, Town or Stronghold it also shows the **type and VP value** (e.g. “Minas Tirith (Gondor - Stronghold, 2 VP)”)
- **Keepers & Minions, rebuilt**: the LOME strip is now a vertical card like the Kings card, a row per character under a Free Peoples / Shadow heading with its **Level & Leadership** and its die, and now including **Strider (the Dúnadan)** and the **Witch-king (Chief of the Ringwraiths)**
- **Compact card popup** (**Ctrl+[** Free, **Ctrl+]** Shadow): a tall list of the card names, **click or Enter pops a card out into its own small, always-on-top window** you can leave over the game to check a wording ◀▶ / wheel to spin through, Esc closes. The Toolkit way; Ctrl+/ still opens the full Reference. KOME cards now follow the list convention, Name (type), Combat card (initiative)
- **Colour-blind control markers** (View › Letter the control markers): bakes a bold **F** / **S** onto the Free / Shadow control markers, so the two sides read by letter, not just blue-vs-red. Off by default
- **Keyboard Shortcuts popup** (**Ctrl+K**): an instant, small, flexible list of every hotkey, grouped by menu, built live from the menu bar, so it is always up to date, plus the handy board keys (drag to pan, Ctrl+wheel zoom, flip, Esc). Ctrl+K or Esc closes it
- **Dice-face hover help:** hover an Action die in either dice bar and the tooltip names its face and what it does, Character, Army, Muster, Army/Muster, Event, Will of the West, and the Shadow Eye. For the special dice (Gothmog, the Balrog, the Faction and Ruler dice, the Rings’ dice) it also tells you **why it is in the pool this turn**. Same toggle as the region tips
- **VP markers move themselves** (View › Move VP markers on End turn, on by default): when you press ESC to end your action, the two Victory-point markers slide to match the total the client works out from the control markers. Only the side ending the turn moves them, so there is no tug-of-war, and it is a normal logged move, so it syncs and replays. There is still a manual **Snap VP markers** if you want it
- **Cleaner VP readout:** the on-board total is now just two bold coloured numbers, **blue** Free Peoples over **red** Shadow, no labels. When a side reaches its winning score (4 for the Free Peoples, 10 for the Shadow) its own action-die symbol **flashes** after the number, the **Will of the West** for the Free Peoples, the **Eye** for the Shadow: a thematic reminder they are ahead on points but still have to *hold* it to the end of the turn
- **Shadow past 10:** if the Shadow total runs over 10 the marker flips to its **+10** side and sits on slot 1 or 2 (11 or 12), exactly as on the real board
- **Auto-Fit Layout fixed:** “Optimize Layout” now fills the map to your actual window (it binary-searches the largest zoom that fits) instead of snapping to a coarse size, and it no longer shrinks a maximised window
- **Side-aware Army selection:** left-clicking a region that holds both sides now selects only your own pieces, so the Shadow will no longer accidentally drag the Fellowship or Free Peoples Companions when moving an Army, and the Free Peoples will not pick up Shadow units

## Timed games: an optional chess clock

- **A floating Game Clock** (View › Game Clock), styled like the Kings card: drag it, or fold it to a slim bar that still shows whose time is running, **blue** for the Free Peoples, **red** for the Shadow
- **Time-control models** (None / Sudden death / Fischer, base + increment), with remaining time and a flag when a side runs out, a friendly warning by default, an opt-in loss for rated games
- **Pause** both clocks for a break (button, Pause key or Ctrl+Shift+P), an **F1 battle hold** that freezes both clocks for a combat, and **Adjust** to hand time back after a forgotten pause, all synced to your online opponent
- It is a **proposal**, not a ruling: the whole design, and the open question of what “running out” should mean for a 6–25-turn game, is in the Ctrl+/ *Timed Games* page for the community to argue over

## A sharper board and tidier table

- **Pin-sharp map text at any resolution:** the board is now drawn at your display's real pixel resolution, so the region names stay crisp instead of being blurred by Windows / Retina display scaling, a big difference on 4K and high-DPI screens, and it keeps zooming fast
- **Faster high zoom (400–600%):** at those zooms the crisp overlay already covers the whole board, so the client no longer decodes the 43-megapixel master just to hide it, the hidden base is scaled the light, fast way instead. Same picture, much less lag when you zoom right in
- **Piece size, Auto fine-tune:** nudge the Auto figure size 50–150% to taste, and the strength numbers (and faction counts) now sit under the figures and grow with them, so they stay readable at any size
- **Card preview tidied:** the big card sits flush under the title with no wasted margin, and the scrollbar only shows when a card is genuinely zoomed past the pane
- **Quieter and cleaner:** removed two old debug lines that printed hashing details to the launch console

## Talk while you play

- **Voice chat, built in:** talk to your opponent inside the client, no Discord, no extra app
- **Push-to-talk, mute, or always-on;** the mic is off until you turn it on
- **A mic button in the hand-tab strip** that shows its state: grey off, orange armed, green live, red muted
- Turn the mic on **mid-game**, even if you had none plugged in when the game started

## Playing online, made easier

- **The Play-on-Network dialog, redrawn:** your client version, game type and voice state shown at a glance
- **A copyable virtual-LAN IP box,** and a foldable *Direct connection* section for router-forwarders
- **ZeroTier / Hamachi install status** shown, with a clickable link to set one up
- **A red warning if a commercial VPN** (Surfshark, NordVPN and the like) is running and could block the connection
- Enter hosts or joins, Esc closes; a voice log is kept for troubleshooting

## Make the table your own (View menu)

- **Options that fit your window.** View › Options re-flows into two or three columns as you widen it, and the descriptions re-wrap to fit.
- **Choose your Gandalf the White.** View › Theme lets you always show the standing figure or the one on Shadowfax (or match the game, the default), each with its shining side for White Rider.
- **Full Screen (Alt+Enter):** borderless, covers the taskbar; every shortcut (Ctrl+1–5, Ctrl+Z/Y…) keeps working in it, and Esc stays a game key
- **Side panel on left:** put the side panel on whichever side you like
- **Dice below the map:** move the Free Peoples / Shadow dice under the board, at normal size
- **Language:** pick the client's language from the View menu, with a first-run picker

## Smoother, sharper, bigger

- **Zooming is much faster**, the board no longer re-crunches a 43-megapixel image on every zoom, so it stays snappy even on older laptops
- **Extra crisp zoom levels** filled in at 160 / 170 / 180 / 190%
- **View › Piece size:** draw the army and character figures bigger, up to Giant, or **Auto**, so they scale with the board zoom, handy on big, high-resolution screens and at high zoom
- **Crisper enlarged figures:** when pieces are drawn bigger they now render from hi-res art instead of blowing up the little token, so they stay sharp instead of going blocky
- **Everything scales together:** the tokens too, Elven Ring and Sovereign counters, Dwarven Rings, control & leadership markers, and the Political / Fate / Fellowship tracks, VP markers, action dice and the table slots now all grow and sharpen with Piece size / Auto, not just the figures
- **German, Italian and Russian maps** updated to the 16-slot table, keeping every translated place-name

## Updates, the safe way

- **Jar-only auto-update:** fetch just the new program, verified by SHA-256 and only with your say-so, then relaunch
- Help goes amber when a newer version is out; **Check for updates at startup** is yours to switch off

## The client watches the rules for you

- **A new Reference page, “Rules the client checks”,** listing every check as it ships
- **Reminders that never block you:** moving into a nation not yet at War, and *Worn with Sorrow and Toil*
- **Enforced:** a used Elven Ring always passes to the Shadow's ring slots, never to casualties
- **Book-keeping:** Victory points tallied on the board; the Faction die comes and goes by itself
- **Explain the Action dice** (Help menu): how many dice each side has this turn, and why each one is there

## More to play

- **Second Breakfast** scenario: fold in the big expansions' Event cards, including the Kings of Middle-earth promo cards, without their figures
- **Mix a scenario with Treason of Isengard:** the Erebor, Smaug Lives! and Return of the King set-ups now combine with the variant
- **Kings of Middle-earth Event cards** are now in the Reference card library, browsable like all the rest

## Reference window, reorganised

- **Event Cards moved up,** right under What's New
- **Two drill-down tabs, Expansions and Variants & Scenarios,** gather the many pages behind a tidy menu; Esc steps back

## Watching your rolls

- **Battle Stats** round tracker: your rolls captured per round, tagged by phase
- **Roll statistics** gathered to a CSV as you play, for the dice-luck sceptics
- **Launchers named for your system:** *War of the Ring (Win).cmd*, *(Mac).command*, *(Linux).sh*

## Kings, Warriors and Lords of Middle-earth
- Every expansion has a floating overlay that never gets in your way, with everything you need to manage it, alone or together
- Expansion cards in small windows: drag anywhere, fold, resize; all 16 table slots stay free (up from 14)
- Kings card: Sovereigns' Level and Resistance, awakened silver, corrupted black, a square per Corruption tile
- Factions card: each Faction asleep, ready, in play (with its figures) or out, from the board
- Keepers and Minions strip: each special die and Elven Ring as it lies
- Click a name on any card for its rules and state in the side panel
- Every special die comes and goes by itself: Faction, Ruler, Keeper and Lesser Minion dice
- A Helper for each expansion when a game starts (one window, a tab each)
- KOME: Corruption tiles really hidden from the Free Peoples; every draw a secure roll
- KOME: both tournament rules
- KOME: Ctrl+F swaps a Sovereign's figure: ordinary, awakened, corrupted
- KOME: draw onto a Sovereign with Ctrl+Shift+H, double-click the tile to keep
- KOME: "He is corrupted" and "It Is Not So Dark Here" in one click
- KOME: the Sovereign view: his tiles and summary
- KOME: Kings tiles go into the Hunt Pool with LOME or WOME too
- KOME: Reference › Kings: In this client, for every awkward rule
- WOME: follows the rulebook exactly, Call to Battle cards set aside until battle time
- WOME: right-click your Faction to pick up its Call to Battle cards; Esc puts them back
- WOME: Faction figures on the map with their count, red over the stacking limit
- WOME: Factions entering play and leaving in the chronicle
- LOME: the Council of Rivendell at the start; each Elven Ring has its own menu item
- LOME: a Keeper's die stays to the end of the turn after he leaves play, as the rules say

## Promos, scenarios and variants
- New Game window: every game in one place, with the rulebook covers of the expansions you tick
- Each scenario with its own cover
- Official scenarios: The Breaking of the Fellowship, The Fall and Fate of Erebor (+KOME)
- Fan-made: Treason of Isengard, Second Breakfast, The Ring of Doom, Smaug Lives!, Return of the King
- Fan-made variants credit their authors
- Scenarios can carry their own rules, shown in the game
- Éowyn promo card (My Name Is Dernhelm), in any Second Edition game
- Treebeard promo card
- Return of the King scenario (Ituralde): the first turn's dice set, Aragorn crowned

## Replays
- Replay bar: play / pause, step, next turn, speed, when the last action ended
- Drag the replay bar anywhere; make it see-through; close it
- Armies at a glance: each nation's Regulars, Elites, Leaders on the board, in the pool, lost
- **Ira mode** (View menu or the replay bar), after Ira's War of the Ring videos: the dice large above the map (double-click one to play it) and big army numbers, for watching, videos or playing; the side panel's dice fold away
- Space play / pause, Tab one step, ← / → slower / faster (AltGr too)
- Real times in the log: every end of an action and every turn
- Loading a log into the wrong kind of game is caught, with the right one offered
- A log that cannot fully replay loads as far as it can and says what it skipped

## The Chronicle and Statistics
- The Chronicle: the story of your game, turn by turn
- Battles and the combat cards played, Companions leaving and lost
- Characters entering play, nations falling, overrun, rallying and liberated
- Strongholds and Settlements taken; the Fellowship into Mordor and how the Quest ends
- Copy chronicle: a game report in one click
- Dice against expectation: was it really that unlucky?
- Cards drawn, played and discarded, with each side's discard pile
- The Hunt turn by turn
- Time per action and per side, in the title and across sittings and computers
- Statistics say which game and which client a log is from
- A .stats file with all of it next to every log

## Saving, logs and ending a game
- File › Save suggests a name with the date and both players
- **Game › End Game:** agree the result, swap hand keys, and both players get the log saved so it replays with every card showing, plus the result in the .stats
- File › Add Passwords to a Log, for tournament games afterwards
- Logs record which game they belong to

## The Reference window (Ctrl+/)
- One window, pages down the left; Tab changes page, Esc closes
- What's New, also when a new version first starts
- Keys: every shortcut, in the WOTR Toolkit's layout
- Rules refreshers: the Hunt, Combat, the turn
- Almanac sheets: combat cards by initiative, Companions, KOME Rulers, Dark Chieftains, WOME Factions
- Every event card, by what it does or A to Z, shown large (Ctrl+[ and Ctrl+])
- The War of the Ring Almanac and Expansion Almanac, kept up to date
- Your Ares rulebooks opened from the game folder
- Tournaments: Dwarven Rings bidding, Muster Points
- Ctrl+scroll zooms every page, pictures included

## Fair play
- All known exploits fixed
- Dice and card draws cannot be steered by a tampered copy
- Every command from the other side is checked; anything an honest client never sends is refused and recorded
- Forged Corruption tiles caught
- Your hand is protected by a strong key the game makes: nothing to type
- Every game's key is remembered and found again by itself when you reload it, however many games you have going; Game › My Hand Key to continue on another computer
- Observers can chat, not play (unless you allow it)
- When you connect, the chat says which client your opponent uses

## Looks and comfort
- Light, Dark (the default) and the original Classic theme
- Classic or new action-dice art
- Fonts change live: board and chat size, font, bold
- Draggable dividers, all remembered
- Fit Map to Window; board and pieces line up at every zoom
- Card zoom: use the − / + to zoom a viewed card from 50% to 300%
- Hand tabs on one row, in their side's colour; red over the hand limit

## The same on Windows, macOS and Linux
- No more Java Hell: no hunting for the right Java version: it is built in, so it just works, every time
- Also playable in German, Italian, Russian, Spanish and Chinese menus, with more language support on the way
- Sharp on high-resolution screens and Windows display scaling
- Full macOS support: Mac menu bar, Dock name and icon, Mac keys
- Linux: a launcher and an applications-menu entry
- The same card keys on every system
- Help › Check for Updates

## Quality
- Hundreds of bug fixes, including long-standing freezes
- Tested on Windows, macOS and Linux; 217 saved games replayed after every change

## Coming soon
A taste of what is next, built and being finished, not playable in this build yet:
- **War of the Jewels (beta).** hekmo's original fan scenario: the War of the Ring system taken back to the First Age, the wars of the Silmarils across Beleriand. The board, the armies, the Champions and Shadow Minions with their cards, and the four event decks are all in; still beta.
- **Treason of Isengard 3.0 (pre-release).** Rafamir's expansion, with Gríma, his Whisperings, the new cards and the on-table tableau already in the client; the last details are being settled with Rafamir.
- **3 and 4 player team games.** Real multiplayer, two players a side, built the proper server-client way: one authoritative host, the others join. Switched off until it is rock solid.
- **Voice chat in the client.** Talk to your opponent as you play, carried over the same networking. In progress.

---

*A fan-made client for a game published by Ares Games. Ownership of the original board game is
required. Images and card texts are © Ares Games Srl, Sophisticated Games. Characters, names and
events are © Middle-earth Enterprises. Not for sale.*
