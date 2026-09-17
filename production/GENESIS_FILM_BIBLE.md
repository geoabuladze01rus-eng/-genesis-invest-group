# GENESIS Film Bible — Free / Open Production Stack

## Purpose
Create one flagship 75–90 sec brand film plus three 35–50 sec residence films (G125 / G175 / G240) without dependence on paid video-generation SaaS. The website must always distinguish real Adygea photography from concept architecture visualizations.

## Production stack — no paid SaaS required

### Primary video route
- **LTX-2 / LTX Desktop** — preferred first route for local image-to-video and controlled cinematic motion. LTX-2 supports synchronized audio/video generation and is integrated with ComfyUI; LTX Desktop provides a free/open desktop workflow for local generation where hardware permits.
- **Wan2.2 in ComfyUI** — second route for architecture shots and motion control. Use I2V from approved GENESIS stills rather than unconstrained T2V whenever geometry must stay stable.
- **Fallback: 2.5D camera animation** in Blender / FFmpeg over approved renders. If generative motion warps windows, roof lines, pool geometry or landscaping, controlled 2.5D beats synthetic motion.

### Voice
- **Final production:** local/open TTS prototype (Silero or another Russian local model) → then human male voice if/when a final campaign master is produced.
- Website prototype may use browser SpeechSynthesis only as a zero-cost demonstration layer. It is not the final advertising voice.
- Voice direction: male, perceived 35–50, calm low/mid-low register, no radio-announcer pressure, 0.88–0.94 conversational speed, deliberate pauses.

### Music
- **Original score only.** No copied commercial folk recording.
- Website prototype uses a tiny procedural ambient score generated in-browser with Web Audio API: low drone + sparse plucked motif. It costs nothing and creates no third-party music dependency.
- Final campaign music brief: cinematic ambient with restrained Circassian/Adyghe-inspired modal character, soft frame-drum pulse, sparse plucked-string texture, low drone, water/forest sound design.
- Do **not** call the prototype “traditional Adyghe music.” Cultural-authenticity claims require review/participation of an Adyghe musician.

### Edit / mastering
- FFmpeg for assembly, codecs, captions and delivery masters.
- Blender for camera moves, compositing and render-based parallax.
- DaVinci Resolve Free for optional final human finishing.

## Quality principle
Architectural consistency is more important than motion. Reject any clip where:
- roof/facade geometry melts or changes between frames;
- pool edges deform;
- window modules shift;
- terraces change depth;
- landscape appears/disappears impossibly;
- furniture scale or room proportions drift;
- the house no longer matches the approved G125/G175/G240 reference.

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
Visual: owner weekend → guest-ready setup → operator/service layer; restrained investment graphics, no guaranteed-return iconography.
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
- Avoid “guaranteed”, “risk-free”, “always grows”, “crazy return”.

## Music direction
Tempo 62–72 BPM. Minor/modal center. Sparse instrumentation, low dynamic range under narration. Suggested structure: 0–12 sec drone/air; 12–42 sec plucked motif + soft percussion; 42–70 sec wider strings/pads; 70–80 sec resolve on open fifth. Blend river/forest ambience quietly under score. Narration remains dominant.

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

## Website integration already in place
- Nature page: interactive 5-scene film using real Adygea imagery plus clearly labeled GENESIS concept imagery.
- Nature film: keyboard/swipe controls, fullscreen, optional browser voice, original procedural ambient soundtrack.
- Residence pages: interactive tour bar, scene navigation, optional browser voice and procedural ambient soundtrack.
- Autoplay remains silent; sound/voice begin only after explicit user action.
- Real regional photographs and concept visualizations are labeled differently.

## Next production step
1. Approve one final hero still for each G125 / G175 / G240.
2. Lock façade geometry and landscape palette.
3. Generate short I2V shots locally in LTX-2 and Wan2.2.
4. Reject unstable generations; use Blender 2.5D where necessary.
5. Generate scratch Russian voice locally.
6. Assemble 16:9 master + 9:16 / 1:1 cutdowns in FFmpeg/Resolve.
7. Add subtitles and disclosure card where investment language appears.
8. Replace website prototype sequences with lightweight WebM/MP4 when final masters pass QA.

## Legal / commercial language
Rental use is an option, not a guaranteed yield. Final financial performance depends on demand, ADR, occupancy, OPEX, taxes, operator terms and regulation. Architectural imagery remains concept visualization until the site and working design are approved.

## Reference projects / software
- LTX-Video / LTX-2: https://github.com/Lightricks/LTX-Video
- LTX Desktop: https://github.com/Lightricks/LTX-Desktop
- ComfyUI Wan2.2 workflows: https://github.com/Comfy-Org/docs
