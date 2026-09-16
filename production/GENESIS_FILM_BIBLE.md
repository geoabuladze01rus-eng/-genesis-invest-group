# GENESIS Film Bible — Open Production Stack

## Purpose
Create one flagship 75–90 sec brand film plus three 35–50 sec residence films (G125 / G175 / G240) without dependence on paid SaaS subscriptions. The website must distinguish real Adygea photography from concept architecture visualizations.

## Free / open-source production stack
- Video generation: Wan2.1 image-to-video / text-to-video. Use locally or on available GPU runtime. Prefer I2V from approved GENESIS keyframes for architectural consistency.
- Voice prototype: Silero V5 CIS Base / nostress models. Test a calm Russian male speaker; `ru_kbd_eduard` can be auditioned as one regional-timbre option, but must not be marketed as an “Adyghe voice”. Final selection is based on listening quality.
- Edit / mastering: FFmpeg; optional Blender for camera moves and compositing; optional DaVinci Resolve free edition for final human finishing.
- Music: original score only. No copied folk recording. Brief: cinematic ambient with restrained Circassian/Adyghe-inspired modal character, soft frame-drum pulse, sparse plucked-string texture, low drone, water/forest sound design. Cultural authenticity claims require a local musician review.

## Flagship film — 80 sec
### 0–12 sec · Origin
Visual: real Lago-Naki, dawn, aerial horizon, mist, limestone relief.
Voice: “Есть места, где природа говорит тише — но звучит сильнее.”
Sound: air, distant water, one low sustained note.

### 12–24 sec · Water / memory
Visual: real Belaya River, Rufabgo waterfall, dolmen detail.
Voice: “Адыгея — это энергия камня и воды, река Белая, плато Лаго-Наки, водопады и следы истории, которая началась задолго до нас.”
Music: introduce subtle plucked motif, no tourist-folk cliché.

### 24–42 sec · GENESIS appears
Visual: transition from real landscape to clearly labeled GENESIS concept visualization; house exterior, approach, terrace, pool, warm evening light.
Voice: “Именно здесь рождается GENESIS. Не просто дом в горах — частная среда, где архитектура, технология и ландшафт работают как одно целое.”

### 42–58 sec · Product
Visual: G125 → G175 → G240, pool water, planting, façade detail, panoramic living, owner arrival.
Voice: “Три формата резиденций. Собственный бассейн. Панорамное остекление. Умные инженерные сценарии. Сервис и инфраструктура, рассчитанные на жизнь, отдых и долгосрочное владение.”

### 58–70 sec · Asset logic
Visual: owner weekend → guest-ready setup → operator/service layer; tasteful investment graphics, no guaranteed-return iconography.
Voice: “Вы можете жить здесь сами, возвращаться в любое время года или, при выбранной модели управления, использовать резиденцию для аренды. Дом остаётся домом — и одновременно становится активом с потенциалом коммерческого использования.”

### 70–80 sec · Brand close
Visual: sunset mountain silhouette, GENESIS mark, subtle lights of settlement.
Voice: “GENESIS Invest Group. Новая культура горного девелопмента: природа, архитектура, технологии и дисциплина капитала.”
Endline: “GENESIS — дом, которым вы живёте. Актив, который может работать.”

## Voice direction
- Male, 35–50 perceived age.
- Calm low / mid-low register; no radio-announcer push.
- 0.88–0.94 normal conversational speed.
- Deliberate pauses after short sentences.
- Emotion: confidence, restraint, wonder; never urgency.
- Pronounce GENESIS cleanly; Russian narration with occasional English product names only where useful.
- Avoid words such as “guaranteed”, “risk-free”, “always grows”, “crazy return”.

## Music direction
Tempo 62–72 BPM. Minor/modal center. Sparse instrumentation, low dynamic range under narration. Suggested structure: 0–12 sec drone/air; 12–42 sec plucked motif + soft percussion; 42–70 sec wider strings/pads; 70–80 sec resolve on open fifth. Blend river/forest ambience at -28 to -34 LUFS under score. Narration should remain dominant.

## G125 film — 40 sec
Theme: Compact freedom.
Shots: approach → one-storey silhouette → living-to-terrace move → pool edge → landscaped privacy → evening lights → title card.
Voice core: “G125 — компактная горная резиденция без ощущения компромисса. Простая логика, собственный бассейн, терраса и ландшафт. Формат для личных поездок и, при профессиональном управлении, гостевого использования.”
Endline: “G125. Compact form. Complete freedom.”

## G175 film — 45 sec
Theme: Family life, elevated.
Shots: arrival → panoramic living → family dining → master privacy → deep terrace → pool → dusk exterior.
Voice core: “G175 — сердце коллекции GENESIS. Семейный формат, в котором общественное пространство раскрывается к горному виду, а приватная часть остаётся действительно приватной. Дом для долгих выходных, сезонов и круглогодичной жизни.”
Endline: “G175. The center of GENESIS.”

## G240 film — 50 sec
Theme: Signature horizon.
Shots: best-view lot → façade reveal → high-volume living → master suite → optional SPA → large pool/terrace → night aerial.
Voice core: “G240 — Signature Residence. Больше света, пространства и приватных сценариев. Архитектура для лучших видовых участков, где панорама становится частью интерьера, а дом — редким продуктом внутри коллекции.”
Endline: “G240. The summit of the collection.”

## Website integration
- Nature page: interactive real-photo film remains available even before final MP4 production.
- Homepage: Nature CTA, real Lago-Naki / Belaya photography, and cinematic residence links.
- Residence pages: current slow-camera CSS sequences act as lightweight cinematic previews; later replace/augment with MP4/WebM poster-video blocks.
- Video autoplay: muted only; narration starts after explicit user action (“Watch with sound”).
- Provide captions/subtitles for every narrated film.
- Lazy-load video and use poster images to protect mobile performance.

## Production quality gate
Do not publish a generated house clip if geometry visibly warps, pool edges melt, windows shift, or landscaping changes impossibly between frames. Architectural consistency beats motion. If I2V fails, use controlled 2.5D camera moves over approved stills rather than visibly synthetic deformation.

## Legal / commercial language
Rental use is presented as an option, not a guaranteed yield. Final financial performance depends on demand, ADR, occupancy, OPEX, taxes, operator terms and regulation. Architectural imagery is concept visualization until the site and working design are approved.
