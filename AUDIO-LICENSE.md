# Korean female audio provenance

The current 291 course clips are locally synthesized Korean speech using **Supertonic 3, female preset F2**, chosen by the user after comparing F2 and F3 samples. They are not Papago recordings or a clone of Papago's voice. They have not been reviewed sentence by sentence by a Korean native speaker.

- Model: https://huggingface.co/supertone-oss-archive/supertonic-3
- Model revision: `aafc6e32416a594460b32413efc49d7fe4ce6d46`
- Copyright: Supertone Inc.
- Model license: **BigScience Open RAIL-M**, reproduced in `SUPERTONIC-MODEL-LICENSE.txt`.
- Official inference source: https://github.com/supertone-oss-archive/supertonic
- Source revision: `1e9799e964ea4c0dad7cde993b65c3c813a7b373`
- Reference helper code: MIT, reproduced in `SUPERTONIC-CODE-LICENSE.txt`.
- Voice descriptions: https://github.com/supertone-oss-archive/supertonic-py/blob/main/docs/voices.md
- Generation: Korean `ko`, F2 female preset, 8 denoising steps, speed 1.0, 44.1 kHz mono PCM WAV, locally compressed by FFmpeg to MP3 and embedded in HTML data URLs.
- No Papago scraping, voice cloning, cloud synthesis or paid API is involved.

The model repository is archived; the pinned model can still run locally. The license governs model use and includes use restrictions. Consult the full license before reusing or redistributing model assets. Model weights are cached on D drive and are not committed or included in the mobile course package.

`audio-manifest.json` records the exact model, female voice, source text, duration and checksum of every current MP3. The old Meta MMS generation script is retained as legacy source only; current course playback uses the F2 audio described here. Earlier Git commits contain the former MMS audio and its original attribution.

Naturalness and pronunciation quality are subjective and are not established by automated playback checks. The F2 choice reflects the user's listening preference; this project does not claim Papago equivalence or native-speaker certification.
