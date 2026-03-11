---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="projects-hero">
  <p class="projects-hero__eyebrow">Selected Paper Showcases</p>
  <h2 class="projects-hero__headline">My research spans two closely related directions: AI Security and AI for Security.</h2>
  <p class="projects-hero__summary">
    One track asks how we secure AI systems themselves. The other asks how modern AI can be used to protect people, platforms, and online ecosystems. Together, these projects trace a connected agenda around safer intelligent systems and safer digital environments.
  </p>
</div>

<section class="projects-track-map">
  <article class="projects-track-map__card projects-track-map__card--ai-security">
    <p class="projects-track-map__label">Track 01</p>
    <h3>AI Security</h3>
    <p>Defending models, guiding secure code generation, and designing stronger safety mechanisms for AI systems.</p>
  </article>
  <article class="projects-track-map__card projects-track-map__card--ai-for-security">
    <p class="projects-track-map__label">Track 02</p>
    <h3>AI for Security</h3>
    <p>Using multimodal and language models to detect abuse, moderate harmful content, and improve online safety operations.</p>
  </article>
</section>

<section class="projects-section projects-section--ai-security">
  <div class="projects-section__header">
    <p class="projects-section__eyebrow">Track 01</p>
    <h2>AI Security</h2>
    <p>Research on defending AI systems, guiding secure code generation, and rethinking safety policy where AI and platform governance increasingly intersect.</p>
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
          JBShield defends aligned large language models against jailbreak attacks by inspecting what happens inside the model rather than relying only on surface-level prompt filters. The framework identifies toxic and jailbreak-related concepts in hidden activations, then intervenes on those concepts to preserve the model's refusal behavior under adversarial prompting.
        </p>
        <p>
          This makes the defense more mechanistic than keyword blocking or prompt-only safeguards. The paper combines representation-level analysis with mitigation and shows that concept-aware intervention can substantially reduce successful jailbreak attacks across diverse LLMs.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/JBShield.pdf">Read Paper</a>
        </div>
      </div>
    </article>

    <article class="project-showcase">
      <div class="project-showcase__header-block">
        <h3>SCPGraph</h3>
        <p class="project-showcase__tag">arXiv 2025</p>
      </div>
      <figure class="project-showcase__media">
        <img src="/images/papers/scpgraph-framework.png" alt="GRASP overview figure from the SCPGraph paper." />
      </figure>
      <div class="project-showcase__content">
        <p>
          SCPGraph addresses a different security challenge: LLMs that generate functional but insecure code. The project encodes secure coding practices as graph structures and uses those graphs to guide LLM reasoning during code generation, grounding the model in concrete security constraints instead of vague instructions to "write safe code."
        </p>
        <p>
          By operationalizing relationships among secure design rules, the framework helps the model avoid common implementation mistakes and improve secure coding performance on realistic tasks. It offers a practical way to turn security knowledge into structured guidance for AI-assisted software development.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/SCPGraph.pdf">Read Paper</a>
        </div>
      </div>
    </article>

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
          This project examines children's online safety in user-generated content games by comparing how parents and children perceive risk. Rather than assuming age gates alone are enough, the study highlights the gap between adult oversight models and the types of content, interaction, and social exposure children actually encounter inside creator-driven game ecosystems.
        </p>
        <p>
          The paper argues for safety interventions that are more context-aware and experience-driven than blanket age-based restrictions. It connects platform design, moderation policy, and lived user behavior in a way that is directly relevant to safer online game environments.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/RethinkingUGCG.pdf">Read Paper</a>
        </div>
      </div>
    </article>
  </div>
</section>

<section class="projects-section projects-section--ai-for-security">
  <div class="projects-section__header">
    <p class="projects-section__eyebrow">Track 02</p>
    <h2>AI for Security</h2>
    <p>Projects that deploy multimodal LLMs and vision-language models to moderate harmful content, unsafe game ecosystems, and rapidly evolving online abuse.</p>
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
          HVGuard studies hateful video moderation, where harm is often conveyed jointly through speech, visuals, sarcasm, and pacing instead of a single explicit cue. The system combines transcripts and video frames in a multimodal LLM pipeline so the model can reason over cross-modal evidence rather than treating a clip as isolated text or isolated imagery.
        </p>
        <p>
          This makes the approach more effective for implicit and context-dependent hate in real short-video settings. The project shows how structured multimodal reasoning can improve practical moderation for video platforms where harmful intent is often concealed behind humor, editing style, or audiovisual mismatch.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/HVGuard.pdf">Read Paper</a>
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
          HMGuard focuses on harmful memes, a moderation problem where a small amount of text and imagery can hide hateful, harassing, or propagandistic intent. The framework uses multimodal large language models to reason about the relationship between the image, the overlaid text, and the broader social meaning conveyed by the meme.
        </p>
        <p>
          The work treats meme moderation as an understanding problem rather than a pure classification task. That perspective is important for real-world moderation because harmful meaning often depends on cultural references, visual composition, and subtle multimodal cues that standard detectors miss.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/HMGuard.pdf">Read Paper</a>
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
          UGCG-Guard targets promotional content used to lure users into unsafe user-generated content games. The system screens social posts, screenshots, and game-related imagery with large vision-language models to detect sexualized, exploitative, or otherwise illicit promotion before it spreads across the platform ecosystem.
        </p>
        <p>
          The project is designed for the messy moderation setting around creator-driven games, where harmful content mixes platform-native slang, visual signals, and rapidly shifting promotion styles. It shows how LVLM-based moderation can protect vulnerable users, especially minors, in large UGC game communities.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/UGCG-Guard.pdf">Read Paper</a>
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
          NewWave studies hate speech that surges around breaking events, where static moderation policies and older classifiers quickly go stale. The paper introduces an LLM-based reasoning framework that captures the narratives, slogans, and contextual references tied to newly emerging hate waves triggered by real-world events.
        </p>
        <p>
          Instead of assuming that the target classes are fixed, the project treats moderation as a continual adaptation problem. The result is a more responsive way to track event-driven abuse and update detection strategies without retraining a new model from scratch for every shift in online discourse.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/NewWave.pdf">Read Paper</a>
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
          LLM4HateSpeech examines whether large language models can reliably detect hate speech in realistic, context-heavy settings. The work compares prompt strategies and studies how contextual clues, task framing, and external knowledge affect LLM judgments on subtle or ambiguous hateful language.
        </p>
        <p>
          Its contribution is diagnostic as much as empirical: the paper identifies where LLMs help, where they remain brittle, and which prompting strategies make them more useful for moderation. That makes it a strong foundation for later projects on LLM-based online safety systems.
        </p>
        <div class="project-showcase__actions">
          <a class="btn project-showcase__button" href="/files/papers/LLM4HateSpeech.pdf">Read Paper</a>
        </div>
      </div>
    </article>
  </div>
</section>
