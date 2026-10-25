# Hi, I'm Andrii Hlybovets

I'm a student who mostly writes backend in Python. I like building services that pull data from lots of different APIs, put it together and turn it into something people can actually use. Lately I've also been working with LLMs: making several providers work as one, keeping model answers tied to real data, and writing skills that teach Claude a whole workflow.

## Projects

- [AI investment committee for biotech](https://github.com/LizzieZador/ai-meetups-hackaton-unobio-track) — AI due diligence for biotech

  A hackathon project from the UNIBIO track, built with team Oseledez. You give it a target and an indication, and it collects data from about a dozen public sources (PubMed, ClinicalTrials.gov, openFDA, EMA and more), runs it through LLM agents and returns an Invest / Conditional / Do Not Invest verdict with evidence-backed report cards.

  My part was a large share of the backend: the Flask server and API, pipeline orchestration, the LLM layer (ChatGPT → Gemini → Claude fallback with a disk cache and token tracking), a chat assistant that answers only from loaded data, the report cards and program views, and fetchers for openFDA (Drugs@FDA, labels, FAERS), FDA Orange/Purple Book, EMA, CMS Medicare, Lens.org and SEC EDGAR.

- [vertical-virual-video-claude-skill-ua](https://github.com/AAndrHlyb/vertical-virual-video-claude-skill-ua) — Claude skill for vertical videos

  A Claude skill for 9:16 story videos in Ukrainian (TikTok, Reels, Shorts), drawn with code on canvas instead of generated. It walks through every step from measuring a reference video to the final mp4, with automated per-frame QA checks before rendering.

## Stack

Python · Flask · REST APIs · OpenAI / Gemini / Claude APIs · Claude Skills · Git
