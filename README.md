# llm-learning-log

My daily hands-on learning journey through "Hands-on LLMs" — including notes, code, and practical experiments.

## 🧱 Repository Layout

```
llm-learning-log/
│
├── README.md
│
├── daily-log/
│   ├── template.md          ← Copy this for each new day
│   ├── 2025-10-29.md
│   ├── 2025-10-30.md
│   └── ...
│
├── prompts/
│   ├── daily_note_prompt.md
│   ├── weekly_summary_prompt.md
│   ├── project_idea_prompt.md
│   └── code_explainer_prompt.md
│
├── projects/
│   ├── rag-demo/
│   ├── finetune-lora/
│   └── ...
│
└── summaries/
    ├── week01.md
    └── ...
```

### Why This Works

- **`daily-log/`** keeps each day isolated → one commit per learning session
- **`prompts/`** holds all Copilot-ready prompts → you don't have to remember them
- **`projects/`** will later hold your mini implementations
- **`summaries/`** makes weekly synthesis easy

## ⚡ Example Workflow (Simple, Repeatable)

1. **Create new file in `/daily-log/`:**
   ```bash
   cp daily-log/template.md daily-log/2025-10-29.md
   ```

2. **Paste from template.md.**

3. **Add what you read** → raw extract or bullet notes.

4. **Run Copilot on that file** → it fills the "Copilot Notes" section.

5. **Write 2–3 lines of reflection manually.**

6. **Commit:**
   ```bash
   git add .
   git commit -m "log: chapter 2 embeddings notes – Oct 29"
   git push
   ```

7. **End of week** → open `summaries/week01.md`, run `weekly_summary_prompt.md`.

## 📝 Daily Log Template

The template at `daily-log/template.md` includes:
- Raw extract section for your reading notes
- Embedded Copilot prompt for automatic note generation
- Reflection section for personal insights
- Implementation/experiments section for code work
- Summary sentence

## 💬 Copilot Prompts

All prompts are stored in `/prompts/` directory:
- **`daily_note_prompt.md`** — Generate structured study notes
- **`weekly_summary_prompt.md`** — Combine daily logs into weekly summaries
- **`project_idea_prompt.md`** — Generate mini-project ideas
- **`code_explainer_prompt.md`** — Explain code in concept-focused terms

## 🚀 Getting Started

1. Start with `daily-log/template.md`
2. Create your first daily log for today
3. Use the prompts in `/prompts/` with GitHub Copilot
4. Build consistency → one day at a time!
