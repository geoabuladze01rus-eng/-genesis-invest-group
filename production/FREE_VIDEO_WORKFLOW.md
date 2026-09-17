# GENESIS — Free Local Video Workflow

This workflow avoids paid generation platforms. Cost is limited to local hardware/electricity or any GPU runtime you voluntarily choose.

## Route A — LTX Desktop / LTX-2
1. Install LTX Desktop from the official GitHub releases.
2. Download the local model weights offered by the app.
3. Use an approved GENESIS still as the first keyframe.
4. Generate 4–8 second shots, not long uncontrolled clips.
5. Camera prompts: slow dolly, subtle orbit, pool-water movement, foliage movement, dusk light transition.
6. Never ask the model to redesign the house. Prompt motion, not architecture.
7. Export the best short clips and assemble in FFmpeg / DaVinci Resolve Free.

## Route B — Wan2.2 in ComfyUI
Use image-to-video from an approved still. For architecture, prefer control workflows over free-form text-to-video.

Suggested shot prompts:
- `slow cinematic dolly toward the residence, architecture remains unchanged, subtle tree movement, realistic pool reflections, golden hour, no geometry deformation`
- `slow lateral camera move along terrace, fixed facade geometry, natural landscape motion, soft evening light, architectural visualization, premium real-estate film`
- `gentle aerial reveal, fixed building proportions, mountain landscape, no morphing, no extra windows, no roof deformation`

Negative prompt / QA intent:
- no melting architecture
- no moving windows
- no changing roofline
- no duplicated doors
- no impossible pool geometry
- no sudden vegetation replacement
- no people changing identity or clothing mid-shot

## Shot length
Prefer 4–8 seconds per generated clip. The final film gets rhythm from editing, not from one long AI take.

## Residence film shot list
### G125
1. Approach / exterior reveal
2. One-storey silhouette
3. Living → terrace move
4. Pool edge / landscaping
5. Evening lighting
6. End card

### G175
1. Arrival
2. Panoramic living
3. Dining / family scenario
4. Master privacy
5. Deep terrace / pool
6. Dusk exterior

### G240
1. Best-view lot reveal
2. Signature facade
3. High-volume living
4. Master suite
5. SPA option
6. Large terrace / pool
7. Night aerial

## Audio
### Scratch voice
Use local Russian TTS for timing. Browser SpeechSynthesis on the website is only a prototype.

### Final voice
Male, calm, low/mid-low, 35–50 perceived age, restrained delivery, no advertising shout.

### Music
Website prototype uses an original procedural ambient bed. Final campaign score should be commissioned/created as an original track with Adyghe/Circassian-inspired character and reviewed by a local musician if it is described as culturally authentic.

## FFmpeg assembly example
```bash
ffmpeg -f concat -safe 0 -i shots.txt -c:v libx264 -crf 18 -preset slow -pix_fmt yuv420p genesis_master.mp4
```

Add voice + music:
```bash
ffmpeg -i genesis_master.mp4 -i voice.wav -i music.wav \
-filter_complex "[1:a]volume=1.0[v];[2:a]volume=0.22[m];[v][m]amix=inputs=2:duration=longest[a]" \
-map 0:v -map "[a]" -c:v copy -c:a aac -b:a 256k genesis_master_audio.mp4
```

## Website delivery
Create both:
- MP4 / H.264 for broad browser compatibility
- WebM for efficient modern delivery

Use poster images and `preload="metadata"`. Autoplay only muted. Narration starts only after an explicit click.

## Acceptance gate
A clip is rejected if the house becomes a different house. GENESIS sells a specific product; visual consistency is more important than spectacular AI motion.
