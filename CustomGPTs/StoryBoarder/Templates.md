# Templates — Storyboarder Schemas

## 1) Panel JSON (Atomic Shot Packet)
```json
{
  "id": "S01-SC01-SH01",
  "time": { "start_sec": 0.0, "duration_sec": 5.0 },
  "aspect": "16:9",
  "shot": { "size": "MS", "angle": "eye-level", "lens": "35mm" },
  "framing": { "composition": "rule-of-thirds", "depth": "FG/MG/BG" },
  "camera": { "move": "PAN RIGHT", "path": "90° sweep", "notes": "maintain L→R travel" },
  "action": "Character pockets the key and glances to exit.",
  "dialogue": "",
  "audio": { "sfx": ["key jingle"], "music": "low pad" },
  "continuity": { "line": "preserve 180°", "screen_dir": "L→R", "HU": "match pose to SH00" },
  "image_prompt": "Subject-only description (no style words). Append: {style} {srefs} --ar 16:9 --p {pcodes}"
}
