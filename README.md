# Anatomy of a Model

An interactive 3D story in three chapters about how a language model works — built with Three.js, narrated in English and Russian.

**▶ Live:** https://oz-the-magician.github.io/anatomy-of-model/

1. **Training** — corpus, random weights, next-token prediction, a space of meaning, fine-tuning, reinforcement, frozen weights, conversation.
2. **Thought** — what happens inside a single answer: tokens, attention, the residual stream, probabilities, branching and checking.
3. **Image** — how a diffusion model draws: prompt, embeddings, text encoder, latent, noise, denoising, details, decoder.

Controls: chapter bar at the bottom, phase buttons, auto/free camera, settings (brightness, speed, phase length…), RU/EN, voice on/off.
The scenes are simplified illustrations, not exact architectures.

Files: `index.html` (story shell, title cards, voice), `ch1.html`–`ch3.html` (chapters), `voice.js` (narration clips).

---

# Анатомия модели

Интерактивная 3D-история в трёх главах о том, как работает языковая модель. Three.js, озвучка на русском и английском.

**▶ Смотреть:** https://oz-the-magician.github.io/anatomy-of-model/

1. **Обучение** — корпус, случайные веса, предсказание следующего токена, пространство смыслов, дообучение, подкрепление, заморозка, разговор.
2. **Мысль** — что происходит внутри одного ответа: токены, внимание, поток, вероятности, ветвление и проверка.
3. **Картинка** — как рисует диффузионная модель: промпт, эмбеддинги, кодировщик, латент, шум, очистка, детали, декодер.

Сцены — упрощённые иллюстрации, а не точные архитектуры.
