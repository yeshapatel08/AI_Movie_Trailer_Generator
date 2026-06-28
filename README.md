# AI_Movie_Trailer_Generator

# 🎬 The Alchemy of Cinema: Crafting "Glass Memory" with AI

Every great film begins with a spark—a simple title, a fleeting genre, an unspoken feeling. But what happens when we invite artificial intelligence to sit in the director's chair? 

This repository is an exploration of programmatic storytelling. By weaving together a pipeline of Large Language Models, voice synthesis, and image generation, this project automates the entire multi-stage creative process of traditional movie trailer production into a single, seamless pipeline. 

---

## ✨ The Creative Journey

Instead of giving the AI a single, massive task, the project is structured like a real Hollywood production crew, passing the creative baton from one step to the next:

* **The Writer’s Room (Storyboarding):** The pipeline takes a basic concept—like our mysterious thriller *Glass Memory*—and asks the AI to conceptualize a deep, 200-word cinematic world. It breathes life into characters like Elara, an artisan crafting physical sculptures out of fragile human memories.
* **The Screenwriter (Prompt Chaining):** The core story is broken down into structured scenes. The AI shifts roles from author to director, dividing the narrative into visual shots, pacing cues, and underlying mood descriptions.
* **The Voice Actor (Narration Isolation):** The pipeline programmatically extracts pure dialogue from the script, sweeping away technical direction cues, and feeds it into voice synthesis engines to generate a crisp, haunting narration track.
* **The Cinematographer (Visual Synthesis):** The visual scene descriptions are automatically translated into precise text-to-image prompts, feeding creative diffusion models to generate rich, atmospheric stills that fit the mood perfectly.
* **The Editor (Video Assembly):** Using code to splice, time, and overlay audio onto visual layers, the pipeline automatically stitches everything together into a final cinematic `.mp4` video.

---

## 🛠️ The Toolkit

Behind the magic is a carefully orchestrated setup of modern Python frameworks and generative models:
* **Brain & Logic:** Google Gemini (`gemini-2.5-flash`), driven by the intuitive `google-genai` SDK.
* **Voiceover:** Text-to-Speech synthesis tools for the voice layer.
* **Composition:** `MoviePy` and `Pillow` handling the heavy lifting of image frames, pacing, and audio blending.

---

## 🌌 The Result: Glass Memory

> *"Memories... they define us. They shape our world. My art captures them. But what if the memories aren't yours alone? What if they're not what you remember at all?"*

This repository doesn't just hold code; it holds a blueprint for the future of interactive multi-media creation. Feel free to explore the notebook, run the pipeline with your own titles, and create your own cinematic universes!
