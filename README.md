[EN] ENGLISH — GITHUB RELEASE DESCRIPTION (v3.0.0)

CJ MARS PMST v3.0.0 — Physical Media Mastering & Stress-Test Suite (Free PRO Edition)

**Owner, Concept & DSP Architect:** **Serhii Makarenko (CJ Mars)**  
**License:** Free Professional Edition — all PRO features 100% unlocked free of charge for both personal and commercial studio use (subject to the built-in EULA protecting authorship and DSP algorithms against unauthorized resale or code/algorithm extraction).

**CJ MARS PMST v3.0.0** is a ground-up architectural rewrite of the Physical Media Stress-Test console. Compared to v2.x, **v3.0** introduces a completely redrawn photorealistic hardware UI, a re-engineered and optimized multi-threaded DSP & AudioWorklet metering engine, and upgraded offline audio rendering and codecs.

### What's New & Rebuilt in v3.0.0

1. **Completely Redrawn Photorealistic Hardware UI**
   - **LP-01 VINYL LATHE:** Animated 33⅓ RPM strobe platter, dynamic cutting-radius tonearm (`CUTTING LATHE` outer-to-inner tracking), live **X-Y Lissajous Groove Velocity Scope**, and independent `PHASE SKIP` & `THERMAL 10K` alerts.
   - **TP-02 REEL TAPE:** Dual brushed-aluminum 10.5" NAB reels with speed-accurate rotation (`15 IPS` / `30 IPS`), calibrated **Mastering VU Meters** (`0 VU = -9.5 dBFS` with smooth magnetic soft-knee ballistics), and `-1.8 dBFS` `PEAK` LEDs.
   - **TP-03 CASSETTE:** Stationary-axis spinning hubs inside a smoked-glass shell that adapts to `Type I Ferric (120µs)`, `Type II Chrome (70µs)`, and `Type IV Metal (70µs)`, paired with neutral **`TAPE NR`** hiss suppression.
   - **New Post-Module `OUT-04 MASTER` Output Section:** Measures the actual signal *after* the active physical module (or `BYPASS` / `DELTA`), featuring 3 distinct visual scales (**`PK/RMS`** `-60..0 dBFS`, **`LUFS`** `-36..0` with `-14 LUFS` target line, **`dBTP`** `-24..+3 dBTP`), smooth eye-friendly ballistics, clickable `CLIP` latch, and **`MASTER GAIN`** (`-12..+6 dB`).

2. **Re-Engineered & Optimized Audio/DSP Engine**
   - Built on **TypeScript + React 19 + Multi-Threaded Web AudioWorklet + OfflineAudioContext**.
   - Parallel phase-coherent bus routing with independent per-module **`BYPASS`** toggles for instant A/B comparison.
   - Sample-accurate **`DELTA LISTEN`** mode (with automatic `3.0 ms` Tape and `1.2 ms` Cassette delay compensation) to isolate physical coloration, saturation, and losses.
   - 320-column **Multi-Spectral Stress Heatmap** with click/drag seek and drag-and-drop file loading (`WAV`, `MP3`, `FLAC`, `AIFF`, `OGG`, `M4A`).
   - Keyboard **`Spacebar` Play / Pause** transport shortcut.
   - Offline LP-01 physics pre-computation (`scheduleOfflinePhysics`): phase groove skips and 7 kHz cutter thermal smears translate accurately into offline renders.

3. **Optimized Codecs & Pro Exporters (`BOUNCE AUDIO` & Reports)**
   - **WAV Encoder**: uncompressed **24-bit PCM** and **32-bit IEEE Float**.
   - **MP3 Encoder**: optimized `1152`-sample frame encoding (`128 / 192 / 320 kbps`) with optional **`-1.0 dBTP`** peak normalization.
   - **PDF Mastering Report** (high-resolution Heatmap capture, A–F press-safety grading, and physical transfer recommendations) and timestamped **TXT Stress Log**.

4. **Trilingual Localization, Built-In GitHub Update Checker & First-Launch EULA**
   - Full UI and User Manual localized in **German (`DE`)**, **Ukrainian (`UA`)**, and **English (`EN`)**.
   - Integrated lightweight GitHub Release update checker targeting **`https://github.com/cjmars75/CJ_MARS_PMST`** (zero background telemetry, strictly read-only version lookup via **`UPDATES`** button).
   - Integrated **End-User License Agreement (EULA)** presented on first launch.

5. **Available Installers (`v3.0.0`)**
   - `CJ MARS PMST-3.0.0-arm64.dmg` & `CJ MARS PMST-3.0.0-arm64-mac.zip` (macOS Apple Silicon)
   - `CJ MARS PMST Setup 3.0.0.exe` (Windows x64 NSIS Installer)
   - `CJ MARS PMST-3.0.0.AppImage` (Linux x86_64)

  [UA] УКРАЇНСЬКА — ОПИС РЕЛІЗУ ДЛЯ GITHUB (v3.0.0)
--------------------------------------------------------------------------------

# CJ MARS PMST v3.0.0 — Physical Media Mastering & Stress-Test Suite (Free PRO Edition)

**Автор, концепція та архітектура DSP:** Сергій Макаренко (**Serhii Makarenko / CJ Mars**)  
**Ліцензія:** Безкоштовна PRO-версія з відкритими професійними інструментами (детальні умови вбудованої ліцензійної угоди EULA у програмі — безкоштовна як для некомерційного, так і для комерційного студійного використання; заборонено перепродаж самої програми та копіювання алгоритмів).

**CJ MARS PMST v3.0.0** — це повністю перероблене з нуля третє покоління професійного перевірочного стенда фізичних носіїв. Порівняно з версіями v2.x у версії **3.0** кардинально перемальовано весь графічний інтерфейс, заново побудовано та оптимізовано внутрішній аудіо-рушій, систему телеметрії, кодеки офлайн-експорту та анімовану фізику приладів.

### Що перероблено та додано у v3.0.0

1. **Повністю перемальований фотореалістичний студійний інтерфейс**
   - **LP-01 VINYL LATHE (Вініловий різець):** анімована 33⅓ об/хв стробоскопічна платформа, рухомий тонарм (реагує на радіус нарізки *Inner Groove*), реальний **X-Y Lissajous осцилограф** швидкості канавки та окремі індикатори `PHASE SKIP` і `THERMAL 10K`.
   - **TP-02 REEL TAPE (Студійний бобінний магнітофон):** подвійні шліфовані алюмінієві котушки NAB 10.5" із реалістичною зміною швидкості обертання (`15 IPS` / `30 IPS`) та калібровані **Mastering VU-метри** (`0 VU = -9.5 dBFS`, м'яке магнітне коліно без залипання на +3 VU) + пікові діоди `PEAK` (`> -1.8 dBFS`).
   - **TP-03 CASSETTE (Касетна дека):** перероблений корпус із фіксованими осями обертання касетних сердечників, миттєва зміна оформлення під тип стрічки (`Type I Ferric 120µs`, `Type II Chrome 70µs`, `Type IV Metal 70µs`) та нейтральний регулятор шумоподавлення **`TAPE NR`**.
   - **Нова пост-модульна майстер-секція `OUT-04 MASTER`:** відображає реальний вихідний рівень *саме після* активного модуля (або `BYPASS` / `DELTA`), має 3 візуальні шкали з різними балістиками (`PK/RMS` `-60..0 dBFS`, `LUFS` `-36..0` із лінією `-14 LUFS`, `dBTP` `-24..+3 dBTP`), плавну студійну балістику, індикатор кліпінгу `CLIP` із скиданням по кліку та фейдер `MASTER GAIN` (`-12..+6 dB`), що рендериться і в офлайн-файл.

2. **Новий оптимізований внутрішній аудіо-рушій та телеметрія**
   - Стек: **TypeScript + React 19 + багатопотоковий Web AudioWorklet + Web Audio API + OfflineAudioContext**.
   - Повністю перероблена фазокогерентна маршрутизація з індивідуальними кнопками **`BYPASS`** у шапці кожного модуля (`LP-01`, `TP-02`, `TP-03`).
   - Високоточний режим **`DELTA LISTEN`** із компенсацією затримки тракту (`3.0 ms` для бобіни та `1.2 ms` для касети) для прослуховування виключно спотворень, сатурації та частотних втрат носія.
   - 320-сегментний **Multispectral Stress Heatmap** для 100% сканування треку, перемотки кліком/перетягуванням та підтримки `Drag & Drop` (`WAV`, `MP3`, `FLAC`, `AIFF`, `OGG`, `M4A`).
   - Швидке керування транспортом **`PLAY / PAUSE` клавішею `Пробіл (Space)`** на клавіатурі.
   - Попередньо обчислений офлайн-аналіз фізичних подій `LP-01` (`scheduleOfflinePhysics`): фазові зриви голки та теплові просадки різця на 7 кГц точно відтворюються не лише наживо, а й під час рендеру у файл.

3. **Оптимізовані кодеки та професійний експорт**
   - **Офлайн-рендер (`BOUNCE AUDIO`)** активного фізичного носія з точними параметрами всіх регуляторів:
     - **WAV**: нестиснений **24-bit PCM** та **32-bit IEEE Float**.
     - **MP3**: оптимізований поблоковий енкодер (`1152` семплів, `128 / 192 / 320 kbps`) із опціональною піковою нормалізацією **`-1.0 dBTP`**.
   - **PDF-звіт (`PDF Report`)** із високороздільним знімком Heatmap, оцінкою безпеки пресування (`Grade A–F`) та технічними рекомендаціями.
   - **TXT-протокол (`Stress Log`)** із таймкодами небезпечних зон (протифазний бас, ВЧ-сибілянти, перевантаження піків).

4. **Тримовність, перевірка оновлень GitHub та вбудована угода EULA**
   - Повний переклад інтерфейсу та Посібника користувача трьома мовами: **Німецька (`DE`)**, **Українська (`UA`)**, **Англійська (`EN`)**.
   - Вбудована легка перевірка нових версій через офіційний GitHub API репозиторію **`https://github.com/cjmars75/CJ_MARS_PMST`** (без фонового навантаження на систему та без передачі будь-яких персональних даних; кнопка **`ОНОВЛЕННЯ`** у шапці програми).
   - Вбудована Ліцензійна угода (**EULA**) при першому запуску програми.

5. **Доступні збірки (`v3.0.0`)**
   - `CJ MARS PMST-3.0.0-arm64.dmg` / `CJ MARS PMST-3.0.0-arm64-mac.zip` (macOS Apple Silicon)
   - `CJ MARS PMST Setup 3.0.0.exe` (Windows x64 інсталятор)
   - `CJ MARS PMST-3.0.0.AppImage` (Linux x86_64)
  
     [DE] DEUTSCH — GITHUB-RELEASE-BESCHREIBUNG (v3.0.0)
--------------------------------------------------------------------------------

# CJ MARS PMST v3.0.0 — Physische Mastering-Prüfbank (Kostenlose PRO-Edition)

**Urheber, Konzept & DSP-Architektur:** **Serhii Makarenko (CJ Mars)**  
**Lizenz:** 100 % kostenlose PRO-Edition für private sowie kommerzielle Tonstudio- und Mastering-Tätigkeiten (gemäß integrierter EULA zum Schutz des Urheberrechts sowie gegen unbefugten Weiterverkauf oder das Kopieren der DSP-Algorithmen).

**CJ MARS PMST v3.0.0** wurde von Grund auf neu entwickelt. Im Vergleich zu v2.x bietet Version **3.0** eine vollständig neu gezeichnete fotorealistische Hardware-Oberfläche, eine grundlegend überarbeitete und optimierte interne Audio- und Telemetrie-Engine sowie optimierte Offline-Codecs für den Export.

### Neuerungen & Überarbeitungen in v3.0.0

1. **Komplett neu gezeichnetes Hardware-Studio-Interface**
   - **LP-01 VINYL LATHE:** Rotierender 33⅓-U/min-Stroboskop-Plattenteller, dynamischer Tonarm passend zum Schneidradius (*Inner Groove Distortion*), Echtzeit-**X-Y-Lissajous-Oszilloskop** sowie getrennte `PHASE`- und `THERM 10K`-Warn-LEDs.
   - **TP-02 REEL TAPE:** Bewegliche 10,5"-NAB-Metallspulen mit realistischer Geschwindigkeitsumschaltung (`15 IPS` / `30 IPS`), kalibrierte **Mastering-VU-Meter** (`0 VU = -9,5 dBFS`, weiches Übersteuerungsknie) und `PEAK`-LEDs (`> -1,8 dBFS`).
   - **TP-03 CASSETTE:** Achsentreue, rotierende Kassettenwickelkerne im rauchgrauen Gehäuse für `Typ I Ferrit (120µs)`, `Typ II Chrom (70µs)` und `Typ IV Metall (70µs)` mit neutraler Rauschunterdrückung **`TAPE NR`**.
   - **Neue Post-Modul-Ausgangssektion `OUT-04 MASTER`:** Zeigt stets den realen Ausgangspegel hinter dem aktiven Modul (bzw. `BYPASS` / `DELTA`), mit 3 umschaltbaren Skalen (**`PK/RMS`**, **`LUFS`** inkl. `-14 LUFS`-Referenz, **`dBTP`** `-24..+3 dBTP`), augenfreundlicher Ballistik, klickbarer `CLIP`-Anzeige und **`MASTER GAIN`** (`-12..+6 dB`).

2. **Neu entwickelter, optimierter Audio- & Telemetrie-Kern**
   - Technologie-Stack: **TypeScript + React 19 + Multi-Threaded Web AudioWorklet + OfflineAudioContext**.
   - Individuelle **`BYPASS`**-Schalter je Modul (`LP-01`, `TP-02`, `TP-03`) für latenzfreie A/B-Vergleiche.
   - Phasenkorrigierte **`DELTA-ABHÖRE`** (inkl. Laufzeitausgleich von `3,0 ms` bei Tonband und `1,2 ms` bei Kassette).
   - 320-Punkt-**Multispektral-Heatmap** mit Klick-/Zieh-Navigation und Drag-&-Drop-Dateiimport (`WAV`, `MP3`, `FLAC`, `AIFF`, `OGG`, `M4A`).
   - **Leertaste (`Space`)** zum komfortablen Starten und Pausieren der Wiedergabe.
   - Vorausberechnung von Nadelsprüngen und thermischem 7-kHz-Schneidkopf-Schutz auch im Offline-Rendering.

3. **Optimierte Audio-Codecs & Technischer Export**
   - **Offline-Audio-Bounce**: unkomprimiertes **24-Bit PCM** / **32-Bit Float WAV** sowie optimiertes blockweises **MP3** (`128 / 192 / 320 kbps`) mit optionaler Spitzenpegel-Normalisierung auf **`-1,0 dBTP`**.
   - **PDF-Mastering-Bericht** (inkl. hochauflösendem Heatmap-Schnappschuss & Presssicherheitsnote `A–F`) sowie **TXT-Belastungsprotokoll**.

4. **Dreisprachige Oberfläche, GitHub-Update-Prüfung & Integrierte EULA**
   - Vollständig lokalisiert in **Deutsch (`DE`)**, **Ukrainisch (`UA`)** und **Englisch (`EN`)** inklusive ausführlichem Benutzerhandbuch und Lizenzvereinbarung beim ersten Programmstart.
   - Integrierte schlanke Update-Prüfung über GitHub Releases (**`https://github.com/cjmars75/CJ_MARS_PMST`**) über die Schaltfläche **`UPDATES`** (ohne Telemetrie oder Datenübertragung).

5. **Installationspakete (`v3.0.0`)**
   - `CJ MARS PMST-3.0.0-arm64.dmg` / `CJ MARS PMST-3.0.0-arm64-mac.zip` (macOS Apple Silicon)
   - `CJ MARS PMST Setup 3.0.0.exe` (Windows x64 Installer)
   - `CJ MARS PMST-3.0.0.AppImage` (Linux x86_64)
