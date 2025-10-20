# Non-commercial Rule-based Chat Assistant (offline, Android)

A compact offline chat assistant built on rules — lightweight and designed to run on low-end devices (currently Android). The system is split into two complementary parts that produce synergy:

- **Engine (runtime)** — the app/handler that runs dialogue logic.  
- **Models (template sets)** — collections of rules and patterns that define the bot’s behavior.

---

## Key engine features

1. **Limited contextual understanding** — supports synonyms, simple paraphrases, basic topic tracking, and respects punctuation and case.  
2. **Partial memory & adaptive behavior** — stores user parameters (preferences, interests) and adapts responses based on past interactions.  
3. **Typo and simple error handling** — understands inputs like `how you are? hello!` as intent-equivalent to `hello, how are you?`.  
4. **Model file separation for efficiency** — structured model files reduce memory and speed up lookups.  
5. **TTS (text-to-speech)** — local speech synthesis for answer playback.  
6. **Response variability** — multiple phrasings per scenario for naturalness.  
7. **Flexible model customization** — easily create models for different domains (e.g., mental health support, school tutoring). You can keep unlimited distinct models to optimize behavior per domain.  
8. **Unlimited characters / mascots** — switchable personas and voices.  
9. **Privacy-focused design** — sensitive data stays local. Note: if a device is rooted, system security depends on the device/firmware.  
10. **Integration potential** — theoretical support for syncing with other apps.  
11. **Language-agnostic engine** — works with rule models in any language.

…and other features depending on the model content.

---

## Why rule-based?

Rule-based assistants provide:
- predictable, controllable behavior;  
- full offline operation on limited hardware;  
- simple, focused configuration for narrow domains;  
- much lower compute/memory requirements vs LLMs.

This project does **not** aim to replace LLMs — large models are inherently more capable. The goal is to deliver a safe, compact, and usable assistant where internet or offline LLMs are unavailable, or where deterministic replies and resource constraints are important.

**Tip:** combine this assistant with an LLM for broader coverage and higher quality.

---

## Privacy & liability

We aim to provide a safe, private environment: most data is stored locally. **Do not use the bot to create illegal or harmful instructions.** Authors are not responsible for misuse, third-party modifications, device damage, or other consequences arising from use of this software. Use at your own risk.

---

## License

Project is distributed under Apache-2.0.

---

## Note

The assistant’s effectiveness depends strongly on the quality of the models (the “content”). A well-designed model makes a rule-based bot practical and reliable in its target (or universal) domain.
