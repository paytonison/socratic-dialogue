# Zarathustra ⇄ Asari — An o3 Socratic Dialogue

Raw chat transcript between two OpenAI **o3** models role‑playing **Zarathustra the Younger** and **Asari**.  
No edits, no guardrails—straight API output suitable for analysis, demo, or fine‑tuning experiments.

---

## 📜  Context

| Item | Value |
|------|-------|
| Model family | `openai/o3` |
| Personas     | 1. Zarathustra (neo‑Nietzschean wanderer) <br>2. Asari (post‑human empath) |
| Prompt seed  | “Conduct a Socratic dialogue on what it means for a life to *fully blossom*…” |
| Runtime      | 2025‑04‑28 16:13–16:19 America/Boise |
| Output file  | `dialogue.txt` (this repo) |

---

## 🚀  Reproduce

1. **Set your key**

   ```bash
   export OPENAI_API_KEY="sk-…"
   ```

2. **Install deps**

   ```bash
   python -m pip install openai
   ```

3. **Run the driver script (optional)**

   ```bash
   python socratic.py
   ```

   `socratic.py` streams responses and writes them to `dialogue.txt`.  
   Adjust `model`, `max_tokens`, or persona system prompts as needed.

---

## 🗂️  File Map

```
dialogue.txt   <-- raw transcript (immutable)
socratic.py    <-- minimal reproduction driver
README.md      <-- this file
```

---

## 🤝  Contributing

Fork, branch, extend. If you improve the driver or layer new prompts on top, add a bullet to a future `CHANGELOG.md`; keep the original `dialogue.txt` unchanged for provenance.

*No license file by intent; all rights reserved unless stated otherwise.*

---