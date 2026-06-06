# Horuf
Harmonic Orchestration of Revelation's Unique Frequencies - تبدیل رسم‌الخط قرآن به موسیقی

```markdown
# 🎼 HORUF — Harmonic Orchestration of Revelation's Unique Frequencies

> **«حروف» — جایی که کلام خدا ساز می‌زند.**
>
> *Where the Word of God plays music.*

---

## 🔮 What is HORUF?

**HORUF** is a generative music system that transforms the **written text of the Quran** directly into a **multi-instrumental orchestral piece** — without any human composition, melody writing, or arrangement.

Each of the **28 Arabic letters** is mapped to a specific musical note.  
Each **diacritical mark (harakah)** triggers a different instrument.  
Each **shaddah (ّ)** becomes a percussion hit.  
Each **sukūn (ْ)** introduces a rhythmic pause.

The result is not a human interpretation of the Quran.  
It is the **sound of the revelation itself** — encoded in letters, decoded into music.

---

## 🎯 How It Works

```

Arabic Text → Letter-by-Letter Analysis → Note Mapping → Multi-Track Orchestration → WAV Audio

```

### The Mapping System
| Element | Musical Role | Example |
|:---|:---|:---|
| **Letters (حروف)** | Musical notes (C, D, E...) | ا = C4, ب = D4, س = G5 |
| **Harakat (اعراب)** | Secondary instruments | Fatha = Violin, Kasra = Cello |
| **Shaddah (تشدید)** | Percussion | Double drum hit |
| **Sukūn (سکون)** | Bass / Pause | Low frequency thump |
| **Madd (مد)** | Sustained notes | Longer note duration |

### Rhythmic System (Rhythm of Revelation)
Note durations are not fixed — they follow the **natural prosody (ʿarūḍ)** of Quranic Arabic:
- Letters with **madd** → long notes (whole note)
- Letters with **sukūn** → medium notes (half note)
- Letters with **harakah** → short notes (quarter note)
- Letters with **shaddah** → two rapid notes

This means every surah has its own **unique rhythm** embedded in its text.

---

## 🎧 Listen to Samples

| Surah | Style | Description |
|:---|:---|:---|
| **Al-Fatiha (حمد)** | Epic Cinematic | Full orchestra with choir, brass, and taiko drums |
| **Al-Falaq (فلق)** | Protective Meditation | Tibetan bowls, sub-bass, cave reverb |
| **Al-Muzzammil (مزمل)** | Mystic Night Prayer | Cello, night pads, whisper layer |
| *More coming...* | | |

> 🔊 Audio samples available in the `/audio` folder.

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- NumPy
- SciPy

### Installation
```bash
pip install numpy scipy
```

Generate Your First Audio

```python
python generate.py --surah 1 --style epic
```

---

📂 Project Structure

```
HORUF/
├── README.md           # You are here
├── LICENSE             # MIT License
├── src/
│   ├── mapping.py      # Letter-to-note mapping system
│   ├── rhythm.py       # Quranic prosody rhythm engine
│   ├── instruments.py  # Sound synthesis (orchestra)
│   └── generate.py     # Main generator script
└── audio/              # Sample output files
```

---

🧠 Philosophy

HORUF is built on a simple but profound belief:

If the Quran is the literal Word of God, then its letters — not just its meanings — carry divine order.

By mapping each letter to a frequency, we are not composing music.
We are discovering the music that was already there.

This is not an interpretation.
This is an excavation.

---

🛡️ License & Attribution

This project is released under the MIT License.

Created by [Your Name] — Project HORUF
© 2025 — All rights reserved for the original idea and mapping system.

---

«حروف را ما به نغمه بدل کردیم — این بار، آسمان است که می‌نوازد.»

"We turned the letters into melody — this time, it is the heavens that play."
