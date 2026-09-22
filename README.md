# Hi, I'm Purunjay 👋

I build voice agents and LLM systems that work outside the demo: real-time voice AI, RAG, LLM tool calling, and document AI, mostly in Python.

- 🎓 Final-year B.Tech CSE (AI & ML) at **VIT Bhopal** ('27)
- 💼 Previously **AI/ML Intern at Sify Technologies**, building applied NLP and LLM systems for an enterprise platform
- 🔭 **Open to AI/ML engineering roles.** Reach me at [purun2004@gmail.com](mailto:purun2004@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/purunjay-pratap-singh-b1350928a)
- 🎮 Fun fact: I play competitive games and have helped run tech fests

## What I've built

| Project | What it does | Proof |
| --- | --- | --- |
| 📞 [**Bilingual Voice Agent**](https://github.com/DemonBeastop/Real-Time-Bilingual-Voice-Agent-Telephony) | A phone agent that places live calls, switches from English to Hindi mid-sentence, answers from a knowledge base, and books meetings | In production for a client · streaming TTS saves **200–300 ms per sentence** |
| 🧾 [**Invoice Extractor**](https://github.com/DemonBeastop/invoice-extractor) | Vision-LLM that turns any invoice or PO PDF, scanned or digital, into a 9-field line-item CSV with no templates | Validated on invoices from **3 countries** · a local-OCR page filter cuts inference cost |
| 🛒 [**Mandi**](https://github.com/DemonBeastop/voice-shopping-assistant) | A voice shopping list in English, Hindi, and Hinglish (*"do kilo aloo add karo"*) | **86%** of commands handled with zero LLM calls · **99.6%** accuracy |
| 📍 [**Address Matcher**](https://github.com/DemonBeastop/fuzzy-address-matcher) | Matches messy Indian addresses to known facilities with no ML and no geocoding API | **~3 ms** per query |

## At Sify Technologies

- An address matching engine with **96% accuracy at under 100 ms**, with CPU use cut by **38%** through profiling
- A rebuilt RAG support chatbot that uses **70% fewer tokens** per query and is tested against prompt injection and XSS
- A vision-LLM invoice extraction service that fails loudly instead of making up data

## How I work

Measure before optimizing. Use deterministic code when it's enough. Write evals before claiming accuracy. Make AI fail loudly instead of guessing.

## Stack

**Python** · FastAPI · asyncio · WebSockets · PyTorch · scikit-learn · Sentence-Transformers · OpenCV · PostgreSQL · vector search · RAG · LLM tool calling · STT/TTS · Docker · Next.js
