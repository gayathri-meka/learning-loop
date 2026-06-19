# 🔁 learning-loop

A living archive of my learnings through this phase — bootcamps I've worked through and the stories/write-ups that came out of them. Updated as new material lands and the field progresses.

## 📚 Sections

### `bootcamps/`
Hands-on course material and decks.

| File | Topic |
| --- | --- |
| [llm-evaluation-bootcamp.html](bootcamps/llm-evaluation-bootcamp.html) | LLM Evaluation |
| [LLM-Evaluation-Bootcamp.pptx](bootcamps/LLM-Evaluation-Bootcamp.pptx) | LLM Evaluation (slides) |
| [rag-bootcamp.html](bootcamps/rag-bootcamp.html) | RAG |
| [RAG-Bootcamp.pptx](bootcamps/RAG-Bootcamp.pptx) | RAG (slides) |
| [agentic-frameworks-bootcamp.html](bootcamps/agentic-frameworks-bootcamp.html) | Agentic Frameworks |
| [Agentic-Frameworks-Bootcamp.pptx](bootcamps/Agentic-Frameworks-Bootcamp.pptx) | Agentic Frameworks (slides) |

### `stories/`
Narrative write-ups and learnings.

| File | Topic |
| --- | --- |
| [llm-evaluation-story.html](stories/llm-evaluation-story.html) | LLM Evaluation |
| [agentic-systems-story.html](stories/agentic-systems-story.html) | Agentic Systems |
| [rag-story.html](stories/rag-story.html) | RAG |

### `references/`
Reference docs I keep coming back to.

| File | Topic |
| --- | --- |
| [system-design-pm-sa-reference.html](references/system-design-pm-sa-reference.html) | System Design (PM / SA) |

## 🔄 Keeping this updated (monthly)

When new bootcamps or stories show up, add them and push:

```bash
cd ~/learning-loop

# 1. Drop the new file into the right folder:
#    bootcamps/   stories/   references/
cp ~/Downloads/<new-file>  bootcamps/      # or stories/ or references/

# 2. (Optional) add a row to the table above in this README

# 3. Commit & push
git add .
git commit -m "Add <topic> (<month> <year>)"
git push
```

That's it — the repo stays current with each month's learnings.
