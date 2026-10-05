---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<p class="projects-intro">
  My research covers three areas: <strong>AI security and safety</strong>, making AI systems themselves trustworthy;
  <strong>AI for cybersecurity and online safety</strong>, using AI to protect people and platforms from online harms;
  and <strong>human-centered security</strong>, studying how people experience and perceive online risks.
  Selected papers from each area are summarized below; see <a href="/publications/">Publications</a> for the full list.
</p>

<section class="projects-section projects-section--ai-security-safety">
  <div class="projects-section__header">
    <h2>AI Security and Safety</h2>
    <p>Defending LLMs against jailbreak attacks and measuring the robustness of multimodal models.</p>
  </div>

  <div class="project-showcase-list">
    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>JBShield</h3>
        <p class="project-showcase__tag">USENIX Security 2025</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/jbshield-framework.png" alt="JBShield framework figure showing jailbreak detection and mitigation." />
      </figure>
      <div class="project-showcase__content">
        <p>
          JBShield defends aligned LLMs against jailbreak attacks by looking inside the model instead of filtering prompts. It identifies toxic and jailbreak-related concepts in hidden activations, then intervenes on those concepts to keep the model refusing harmful requests. Concept-aware intervention substantially reduces successful jailbreaks across diverse LLMs.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/JBShield.pdf">[Paper]</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>Multimodal Robustness</h3>
        <p class="project-showcase__tag">SKM 2023</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/MMRobustness.png" alt="Figure from the Multimodal Robustness paper on robustness of vision-language multimodal models." />
      </figure>
      <div class="project-showcase__content">
        <p>
          This paper measures how robust vision-language multimodal models are when their inputs or assumptions shift, identifying where cross-modal systems become brittle before they are used in security-sensitive settings. It laid the groundwork for my later work on multimodal moderation.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/MultimodelRobustness.pdf">[Paper]</a>
        </div>
      </div>
    </article>
  </div>
</section>

<section class="projects-section projects-section--ai-for-cybersecurity">
  <div class="projects-section__header">
    <h2>AI for Cybersecurity and Online Safety</h2>
    <p>Using LLMs, multimodal LLMs, and vision-language models to detect hateful videos, harmful memes, illicit game promotion, and hate speech.</p>
  </div>

  <div class="project-showcase-list">
    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>HVGuard</h3>
        <p class="project-showcase__tag">EMNLP 2025</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/hvguard-framework.png" alt="HVGuard framework figure showing multimodal reasoning and mixture-of-experts fusion." />
      </figure>
      <div class="project-showcase__content">
        <p>
          HVGuard detects hateful videos, where harm is often carried jointly by speech, visuals, sarcasm, and pacing. It feeds transcripts and video frames to a multimodal LLM pipeline that reasons over evidence across modalities, improving detection of implicit, context-dependent hate in short videos.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/HVGuard.pdf">[Paper]</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>HMGuard</h3>
        <p class="project-showcase__tag">NDSS 2025</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/hmguard-framework.png" alt="HMGuard overview figure showing challenge identification, prompt design, and harmful meme detection." />
      </figure>
      <div class="project-showcase__content">
        <p>
          HMGuard detects harmful memes, where a small amount of text and imagery can carry hateful, harassing, or propagandistic intent. It uses multimodal LLMs to reason about how the image, the overlaid text, and their cultural references combine, treating moderation as a meme-understanding task.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/HMGuard.pdf">[Paper]</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>UGCG-Guard</h3>
        <p class="project-showcase__tag">USENIX Security 2024</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/ugcg-framework.png" alt="UGCG-Guard overview figure showing data collection, prompting, VLM detection, and moderation." />
      </figure>
      <div class="project-showcase__content">
        <p>
          UGCG-Guard detects illicit promotion that lures users, especially minors, into unsafe user-generated content games. It uses large vision-language models to screen social posts, screenshots, and game imagery for sexualized or exploitative content, despite platform-specific slang and fast-changing promotion styles.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/UGCG-Guard.pdf">[Paper]</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>NewWave</h3>
        <p class="project-showcase__tag">IEEE S&amp;P 2024</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/newwave-framework.png" alt="HateGuard overview figure from the NewWave paper." />
      </figure>
      <div class="project-showcase__content">
        <p>
          NewWave moderates hate speech that surges around breaking events, when static policies and existing classifiers go stale. It uses chain-of-thought reasoning in LLMs to capture the narratives, slogans, and references tied to each new wave, so detection can adapt without retraining a model for every shift.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/NewWave.pdf">[Paper]</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>LLM4HateSpeech</h3>
        <p class="project-showcase__tag">ICMLA 2023</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/llm4hatespeech-figure.png" alt="Prompting strategy and results figure from the LLM4HateSpeech paper." />
      </figure>
      <div class="project-showcase__content">
        <p>
          LLM4HateSpeech evaluates whether LLMs can detect hate speech in realistic, context-heavy settings. It compares prompting strategies and measures how context, task framing, and external knowledge affect LLM judgments on subtle or ambiguous hateful language, showing where LLMs help and where they remain brittle.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/LLM4HateSpeech.pdf">[Paper]</a>
        </div>
      </div>
    </article>
  </div>
</section>

<section class="projects-section projects-section--human-centered">
  <div class="projects-section__header">
    <h2>Human-centered Security</h2>
    <p>Studying how people, especially children and their parents, perceive and experience risk in online spaces.</p>
  </div>

  <div class="project-showcase-list">
    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>Beyond Age-Based Restrictions</h3>
        <p class="project-showcase__tag">CHI 2026</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/rethinking-ugcg-figure.png" alt="Key risk-distribution figure from the RethinkingUGCG paper." />
      </figure>
      <div class="project-showcase__content">
        <p>
          This study compares how parents and children perceive risk in user-generated content games, and finds a gap between adult oversight and what children actually encounter in these games. It argues for context-aware safety interventions beyond blanket age-based restrictions.
        </p>
        <div class="project-showcase__actions">
          <a class="project-showcase__link" href="/files/papers/RethinkingUGCG.pdf">[Paper]</a>
        </div>
      </div>
    </article>
  </div>
</section>
