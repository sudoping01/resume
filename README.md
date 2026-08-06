<style>
  .profile-container {
    text-align: center;
    margin-bottom: 2rem;
  }
  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  .profile-name {
    font-size: 1.6rem;
    font-weight: 700;
    margin: 1rem 0 0.2rem;
    letter-spacing: 0.02em;
  }
  .profile-tagline {
    color: #6a737d;
    font-size: 0.95rem;
    margin: 0 0 0.6rem;
  }
  .profile-links {
    font-size: 0.9rem;
  }
  .profile-links a {
    margin: 0 6px;
    white-space: nowrap;
  }

  .timeline {
    position: relative;
    width: 100%;
    margin: 2rem 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  }

  .timeline::before {
    content: '';
    position: absolute;
    left: 105px;
    top: 5px;
    bottom: 0;
    width: 2px;
    background: #e1e4e8;
  }

  .timeline-item {
    position: relative;
    margin-bottom: 40px;
    display: flex;
    align-items: flex-start;
  }

  .timeline-year {
    width: 90px;
    text-align: right;
    font-size: 0.9rem;
    color: #6a737d;
    padding-top: 2px;
    flex-shrink: 0;
  }

  .timeline-dot {
    width: 12px;
    height: 12px;
    background-color: #e1e4e8;
    border: 2px solid #fff;
    border-radius: 50%;
    position: absolute;
    left: 100px;
    top: 6px;
    z-index: 1;
  }

  .timeline-content {
    margin-left: 40px;
    display: flex;
    align-items: flex-start;
    width: 100%;
  }

  .timeline-logo {
    width: 60px;
    height: 60px;
    margin-right: 20px;
    flex-shrink: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.6rem;
  }

  .timeline-logo img {
    max-width: 100%;
    max-height: 100%;
    border-radius: 4px;
  }

  .timeline-text {
    font-size: 1rem;
    line-height: 1.6;
    flex-grow: 1;
  }

  .timeline-text ul {
    padding-left: 20px;
    margin-top: 8px;
  }
  .timeline-text li {
    margin-bottom: 6px;
  }
  .timeline-meta {
    color: #6a737d;
    font-size: 0.9rem;
  }

  .tags {
    margin: 0.6rem 0 1.4rem;
    line-height: 2.2;
  }
  .tag {
    background: #f6f8fa;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 3px 10px;
    font-size: 0.85rem;
    color: #24292e;
    white-space: nowrap;
  }
  .tag-label {
    display: block;
    color: #6a737d;
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    margin-top: 0.8rem;
  }

  @media (max-width: 620px) {
    .timeline::before, .timeline-dot { display: none; }
    .timeline-item { display: block; }
    .timeline-year { width: auto; text-align: left; margin-bottom: 6px; }
    .timeline-content { margin-left: 0; }
    .timeline-logo { display: none; }
  }
</style>

<div class="profile-container">
  <img src="profile.png" alt="Seydou Diallo" class="profile-pic" width="150" height="150">
  <!-- <div class="profile-name">Seydou Diallo</div>
  <div class="profile-tagline">Software Developer · AI/NLP Researcher · Somone, Senegal</div> -->
  <div class="profile-links">
    <a href="mailto:mail.seydou.diallo@gmail.com">email</a> ·
    <a href="https://github.com/sudoping01">github</a> ·
    <a href="https://huggingface.co/sudoping01">huggingface</a> ·
    <a href="https://www.linkedin.com/in/seydou-diallo-08ab311ba/">linkedin</a>
  </div>
</div>

I'm Seydou DIALLO, Software Engineer, AI researcher, and open-source contributor. My work runs from applied AI R&D (training, fine-tuning, and serving models at scale and on-premise) to the DevOps and MLOps that put them in production. I enjoy building systems that solve real-world problems, contributing to developer tools, and advancing machine learning, speech recognition, and natural language technologies for underrepresented and low-resource languages through accessible, open-source technology.

---

# Experience

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-year">2025 - Present</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/maliba-ai-logo.png" alt="MALIBA-AI"></div>
      <div class="timeline-text">
        <b>Founder</b> @ <a href="https://maliba-ai.org">MALIBA-AI Community</a>
        <ul>
          <li>Founded and lead a community-driven AI initiative for indigenous Malian languages, owning research end to end from data collection to the final model.</li>
          <li>Built and maintain ASR, TTS, LLM, and MT models across multiple Malian languages.</li>
          <li>Released inference SDKs and serving infrastructure so developers and communities can integrate MALIBA-AI models directly.</li>
          <li>Designed speech-first interfaces for predominantly oral languages, expanding AI access in education, healthcare, agriculture, and local business.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2024 - Present</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/djelia.png" alt="DJELIA"></div>
      <div class="timeline-text">
        <b>Co-Founder &amp; Head of AI Development</b> @ <a href="https://djelia.cloud">DJELIA</a>
        <ul>
          <li>Own the full AI model lifecycle for Bambara data collection, training, evaluation, and deployment.</li>
          <li>Built and maintain production-grade ASR, TTS, MT, and LLM models for Bambara, served via cloud APIs.</li>
          <li>Shipped Python and JavaScript SDKs so third-party applications can integrate Djelia's language models.</li>
          <li>Turned research-stage language models into reliable, documented services for local developers.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2024 - Present</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/caytu.png" alt="Caytu Robotics"></div>
      <div class="timeline-text">
        <b>Software Developer &amp; AI Engineer</b> @ <a href="https://caytu.ai">Caytu Robotics</a>
        <ul>
          <li><b>IoT infrastructure</b>: design and maintain the Caytu IoT ecosystem, a fleet of containerized services for remote device control, telemetry, and automation over <b>MQTT</b> and <b>AWS IoT Core</b>, plus a <b>WebRTC / Amazon KVS</b> video streaming platform and a protocol-bridge layer for third-party hardware (<b>DLMS</b>, <b>Ajax</b>, <b>HikVision AX</b>, <b>Victron</b>, <b>Zigbee</b>).</li>
          <li><b>Device security &amp; licensing</b>: encrypted on-device credential store and <b>fail-closed license enforcement</b>, injected at build time and compiled into each service binary.</li>
          <li><b>Fleet tooling</b>: <b>Caytu CLI</b> for automatic device <b>enrollment</b>, <b>provisioning</b>, deployment, and operations, distributed as per-architecture signed binaries through a <b>GPG-signed APT repository</b> and public <b>ECR</b> / <b>S3</b> image and template channels.</li>
          <li><b>Agent framework</b>: <b>Caytu Avatar</b>, a config-driven framework that lets any service stand up its own agent operating across its APIs, exposing <b>REST / OpenAPI</b> and <b>MCP</b> tools through a semantic tool selector on a provider-agnostic LLM backend.</li>
          <li><b>Robotics &amp; Physical AI</b>: contribute to the <b>ROS 2</b> robot stack (robot-controller, robot-stream) and build <b>Caytu-Nav</b>, an <b>LLM-driven autonomous navigation</b> agent for unknown, dynamic environments.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2021, 2023</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🤖</div>
      <div class="timeline-text">
        <b>Robotics Team Member</b> @ Malian National Team
        <ul>
          <li>Represented Mali in international robotics competitions.</li>
          <li>Collaborated on complex engineering projects and problem-solving challenges.</li>
        </ul>
      </div>
    </div>
  </div>

</div>

---

# Publications

* **BambaraMLLM: A Unified Multilingual Multimodal Large Language Model for Comprehensive Bambara Language Processing**.
  *Seydou Diallo, Allahsera Auguste Tapo, Kevin Assogba, Christopher Homan* **first author**. [Paper](https://openreview.net/pdf?id=XQXAxrIz9k)
  <br>A single framework covering ASR, machine translation, text generation, and TTS for Bambara, trained on 2M+ instruction examples generated by a linguistically informed data framework that injects Bambara morphology, syntax, and cultural context.

* **Where Are We At with Automatic Speech Recognition for the Bambara Language?** (2026).
  *Seydou Diallo, Yacouba Diarra, Mamadou K. Keita, Panga Azazia Kamaté, Adam Bouno Kampo, Aboubacar Ouattara* **first author**. [arXiv](https://arxiv.org/abs/2602.09785)
  <br>The first standardized ASR benchmark for Bambara, built on professionally recorded Malian constitutional text with manual segmentation, alignment, and quality review. 37 systems evaluated, with a <a href="https://huggingface.co/spaces/MALIBA-AI/bambara-asr-leaderboard">public leaderboard</a>.

* **InstructLR: A Scalable Approach to Create Instruction Dataset for Under-Resourced Languages** (2025).
  *Mamadou K. Keita, Sebastien Diarra, Christopher Homan, Seydou Diallo.* [arXiv](https://arxiv.org/abs/2512.02213)
  <br>LLM generation, RAG-based correction, and human-in-the-loop validation combined to build the 50k-scale BambaraInstruct, ZarmaInstruct, and FulfuldeInstruct benchmarks.

* **GAIFE: Generative AI for Education** (NAACL 2025 Findings).
  [Paper](https://aclanthology.org/2025.findings-naacl.442/) | [Library](https://bloomlibrary.org/RobotsMali)
  <br>A human-in-the-loop workflow producing culturally grounded children's reading materials in Bambara: 174 illustrated books (~4,000 pages, 850+ original images), roughly a tenfold increase in Bambara children's content online. Pilot reading programs cut the share of children unable to read Bambara by 67%.

---

# Projects

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-year">LLMs</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/maliba-ai-logo.png" alt="MALIBA-AI"></div>
      <div class="timeline-text">
        <b>MALIBA-LLM</b> <span class="timeline-meta"> Lead Developer @ MALIBA-AI</span>
        <ul>
          <li>The first open-source large language model for Bambara (Bamanankan), fine-tuned from <code>google/gemma-3n-E2B-it</code>.</li>
          <li>Supports Bambara ↔ French/English code-switching, instruction following, translation, and Mali-specific knowledge.</li>
          <li>Reduced validation loss to <b>0.4952</b>, 93.4% below the 7.4595 starting point.</li>
          <li>Extended into <b>BambaraMLLM</b>, the unified multimodal model behind the paper below, released as <a href="https://huggingface.co/sudoping01/multimodal-bambara-llm">multimodal-bambara-llm</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Speech<br>Synthesis</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/maliba-ai-logo.png" alt="MALIBA-AI"></div>
      <div class="timeline-text">
        <b>Bambara TTS &amp; MALIBA-TTS</b> <span class="timeline-meta"> Lead Developer @ MALIBA-AI</span>
        <ul>
          <li>Open-source Bambara TTS rated <b>4.2/5.0</b> for quality and <b>4.1/5.0</b> for naturalness by 10 native speakers <b>9,158 downloads</b> as of August 2026: <a href="https://huggingface.co/MALIBA-AI/bambara-tts">MALIBA-AI/bambara-tts</a></li>
          <li>Extended to six Malian languages Bambara, Boomu, Dogon, Pular, Songhoy, and Tamasheq on top of Meta's MMS-TTS and VITS, optimized for CPU inference and real-time synthesis: <a href="https://huggingface.co/MALIBA-AI/malian-tts">MALIBA-AI/malian-tts</a></li>
          <li>Targets the digital exclusion affecting millions of non-literate adults in sub-Saharan Africa, powering voice interfaces, education, and accessibility tools.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">ASR</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/maliba-ai-logo.png" alt="MALIBA-AI"></div>
      <div class="timeline-text">
        <b>Wolof, Bambara &amp; Songhay ASR Models</b> <span class="timeline-meta"> Lead AI Developer @ MALIBA-AI / Caytu Robotics</span>
        <ul>
          <li><b>whosper-large-v2</b> and <b>whosper-large</b>, open-source Wolof ASR handling Wolof, French, and English. v2 reached <b>24% WER / 11% CER</b> on a 9-hour evaluation set, with <b>3,893</b> and <b>679</b> downloads in their first week, now <b>6,143</b> and <b>1,363</b> all-time: <a href="https://huggingface.co/CAYTU/whosper-large-v2">whosper-large-v2</a> | <a href="https://huggingface.co/CAYTU/whosper-large">whosper-large</a></li>
          <li>The <b>maliba-asr</b> series for Bambara; v2 reached <b>24.33% WER / 12.45% CER</b> on a 3-hour set and handles Bambara–English code-switching: <a href="https://huggingface.co/MALIBA-AI/bambara-asr-v1">bambara-asr-v1</a></li>
          <li><b>songhay-asr-v1</b>, bilingual Songhay–French transcription at <b>16.58% WER / 4.63% CER</b> on the test set: <a href="https://huggingface.co/sudoping01/songhoy-asr-v1-ic">songhoy-asr-v1</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Education</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/robotsmali.png" alt="RobotsMali"></div>
      <div class="timeline-text">
        <b>GAIFE: Generative AI for Education</b> <span class="timeline-meta"> Co-Author @ RobotsMali · Bill &amp; Melinda Gates Foundation Grand Challenges</span>
        <ul>
          <li>Co-developed a methodology combining generative AI and automatic translation to produce educational content at scale for Bambara.</li>
          <li>Applied it to build a library of 174 published illustrated books, contributing Bambara linguistic review for accuracy, fluency, and cultural relevance.</li>
          <li><a href="https://aclanthology.org/2025.findings-naacl.442/">Paper</a> | <a href="https://bloomlibrary.org/RobotsMali">Library</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">MT</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/robotsmali.png" alt="RobotsMali"></div>
      <div class="timeline-text">
        <b>Bayelemabaga: Bambara Machine Translation</b> <span class="timeline-meta"> Data Processing @ RobotsMali · RIT Partnership</span>
        <ul>
          <li>Contributed to the first machine translation model for the Bambara–French language pair.</li>
          <li>Handled extraction, cleaning, and alignment of the parallel corpora behind the model.</li>
          <li><a href="https://www.rit.edu/lpi/research">Project details</a> | <a href="https://huggingface.co/datasets/RobotsMaliAI/bayelemabaga">Dataset</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Speech<br>Platform</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/djelia.png" alt="DJELIA"></div>
      <div class="timeline-text">
        <b>Djelia: Production Speech &amp; Language Platform</b> <span class="timeline-meta">Head of AI Development @ Djelia</span>
        <ul>
          <li><b>Data lifecycle</b>: own the pipeline end to end, from raw <b>data collection</b> through <b>preprocessing</b>, <b>augmentation</b>, and dataset preparation.</li>
          <li><b>Model training</b>: build the <b>training pipelines</b> and train Djelia's production <b>ASR</b> and <b>TTS</b> models for Bambara.</li>
          <li><b>Serving</b>: deliver the inference servers that host the trained models, integrated with the production infrastructure behind Djelia's cloud APIs.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">IoT<br>Infra</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/caytu.png" alt="Caytu Robotics"></div>
      <div class="timeline-text">
        <b>Caytu IoT Controller &amp; Streaming Platform</b> <span class="timeline-meta"> Lead Developer @ Caytu Robotics</span>
        <ul>
          <li><b>IoT infrastructure</b> for remote device control, telemetry, and automation: a fleet of containerized services communicating over <b>MQTT</b> and <b>AWS IoT Core</b>, orchestrated per device from a single configuration.</li>
          <li><b>Video streaming platform</b> (caytu-iot-stream) delivering low-latency <b>WebRTC / Amazon KVS</b> streams for remote monitoring, and a <b>protocol-bridge layer</b> integrating third-party hardware: <b>DLMS</b> smart meters, <b>Ajax</b> and <b>HikVision AX</b> alarm panels, <b>Victron</b> energy systems, and <b>Zigbee</b> devices.</li>
          <li>Hardened the runtime with an encrypted on-device credential store and <b>fail-closed license enforcement</b> compiled into each service binary.</li>
          <li>Platform: <a href="https://caytu.link/">caytu.link</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">AI<br>Agent</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/caytu.png" alt="Caytu Robotics"></div>
      <div class="timeline-text">
        <b>Caytu Avatar: Config-Driven Agent Framework</b> <span class="timeline-meta">Lead Developer @ Caytu Robotics</span>
        <ul>
          <li>An <b>agent framework</b> that lets any service stand up its own agent operating across that service's own APIs, so a new integration is added by <b>configuration</b> alone.</li>
          <li>Turns <b>REST / OpenAPI</b> endpoints and <b>MCP</b> servers into callable tools, selected at runtime by an <b>LLM-enriched semantic tool selector</b> that scales to arbitrary tool sets.</li>
          <li>Provider-agnostic LLM backend, <b>RAG</b> over documents (vector search), speech-to-text and text-to-speech, and concurrent multi-service orchestration with live background context.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Fleet<br>Tooling</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/caytu.png" alt="Caytu Robotics"></div>
      <div class="timeline-text">
        <b>Caytu CLI</b> <span class="timeline-meta">Lead Developer @ Caytu Robotics (internal)</span>
        <ul>
          <li>Single command-line tool for the full device lifecycle across the IoT and robotics fleets: automatic <b>enrollment</b>, <b>provisioning</b>, deployment, remote access, and operations.</li>
          <li>Owns the <b>device security model</b>: encrypted on-device credential store and <b>license enforcement</b>, injected at build time and compiled into each service binary.</li>
          <li>Ships as per-architecture (amd64, arm64) compiled binaries in <b>GPG-signed <code>.deb</code></b> packages on an <b>S3 APT repository</b>, installable and upgradable with plain <code>apt</code>; container images and compose templates distributed publicly via <b>ECR Public</b> and <b>S3</b>.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Physical<br>AI</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/caytu.png" alt="Caytu Robotics"></div>
      <div class="timeline-text">
        <b>Caytu-Nav: LLM-Driven Autonomous Navigation</b> <span class="timeline-meta">Lead Developer @ Caytu Robotics (internal)</span>
        <ul>
          <li><b>Physical AI</b> navigation agent on <b>ROS 2</b>: takes a natural-language goal and executes it autonomously, fusing camera, lidar, and odometry to perceive, plan, and act.</li>
          <li>Targets autonomy in <b>unknown, dynamic environments</b>, building its own understanding of the space and adapting as it changes rather than following a pre-mapped route.</li>
        </ul>
      </div>
    </div>
  </div>

</div>

---

# Open Source

Almost everything I build ships publicly. Across my own namespace and the organisations I work in ([MALIBA-AI](https://huggingface.co/MALIBA-AI), [CAYTU](https://huggingface.co/CAYTU)), that currently comes to **81 models and 37 datasets on Hugging Face**, roughly **24,600 model downloads** and **14,800 dataset downloads** all-time, plus published packages on PyPI and npm.

**Published packages**

* **[`djelia`](https://pypi.org/project/djelia/)** (PyPI, v3.1.1) and **[`djelia`](https://www.npmjs.com/package/djelia)** (npm) Python and JavaScript SDKs for the Djelia platform: multi-language translation, real-time transcription streaming, and natural TTS with speaker descriptions. Source: [Python](https://github.com/djelia-org/djelia-python-sdk) · [JavaScript](https://github.com/djelia-org/djelia-js-sdk)
* **[`maliba-ai`](https://pypi.org/project/maliba-ai/)** (PyPI) Bambara text-to-speech inference SDK with 10 authentic speaker voices, built for educational platforms, accessibility tools, and voice interfaces. Source: [MALIBA-AI/bambara-tts](https://github.com/MALIBA-AI/bambara-tts)
* **[`naboopay`](https://pypi.org/project/naboopay/)** (PyPI) and the [Node.js/TypeScript SDK](https://github.com/naboopay/naboopay-nodejs-sdk) Senegalese mobile money (Wave, Orange Money, Free Money): transaction management, cashouts, sync and async support, full type definitions, automatic retries. Source: [Python](https://github.com/naboopay/naboopay-python-sdk)
* **[`whosper`](https://pypi.org/project/whosper/)** (PyPI) inference package for the Wolof ASR models, with a companion [inference server](https://github.com/sudoping01/whosper-inference-server).

**Language tooling**

* **[Bambara ASR Leaderboard](https://huggingface.co/spaces/MALIBA-AI/bambara-asr-leaderboard)** the public evaluation leaderboard behind the Bambara ASR benchmark paper, with the [benchmark dataset](https://huggingface.co/datasets/MALIBA-AI/bambara-asr-benchmark) released alongside it ([source](https://github.com/MALIBA-AI/bambara-asr-leaderboard)).
* **[`bambara-text-normalizer`](https://pypi.org/project/bambara-text-normalizer/)** (PyPI) text normalization and inverse text normalization for Bambara, the preprocessing layer under the ASR and TTS pipelines. Source: [MALIBA-AI/bambara-text-normalization](https://github.com/MALIBA-AI/bambara-text-normalization).
* **[instructions-gen](https://github.com/sudoping01/instructions-gen)** generating high-quality instruction datasets for low-resource languages from linguistic structure and reasoning, the tooling behind the instruction work in BambaraMLLM.
* **Demos** [Malian TTS](https://huggingface.co/spaces/MALIBA-AI/MalianTTS) and [Bambara Translator](https://huggingface.co/spaces/MALIBA-AI/BambaraTranslator) Spaces.

**Infrastructure & deployment**

* **[Realtime WebRTC Video/Audio Streaming](https://github.com/sudoping01/aws-kvs-webrtc-stream-dockerised)** containerized low-latency cloud streaming for remote monitoring, surveillance, telehealth, and industrial IoT ([Docker Hub](https://hub.docker.com/r/sudoping01/aws-kvs-webrtc-stream)).
* **[Wolof TTS Inference Server](https://github.com/sudoping01/wolof-tts)** deployment server making speech synthesis available for Wolof, a primary language of Senegal.
* **[Adia_TTS Segmentation Algorithm](https://github.com/sudoping01/adia-inference-server)** turned a research model into a production system, removing character-length limits while preserving voice quality; [merged into the official model documentation](https://huggingface.co/CONCREE/Adia_TTS/discussions/3#67d94d89fbc8ceeb878ba261).
* **[ONVIF IP-camera controller](https://github.com/sudoping01/onvif-ipcam-controller-python)** and **[Garmin GPS18x driver](https://github.com/sudoping01/garmin-gps18x-usb-python)** Python device-control libraries from the Caytu IoT work.
* **[OpenConverse](https://github.com/room4-2/OpenConverse)** (contributor) an open-source real-time voice-assistant server in Go bridging web and Twilio phone calls to Google's Gemini Live API. Built the DevOps and release engineering: containerization (Docker, dev and prod compose), CI/CD for automated Docker Hub image build and publish on push and release, a Go code-quality workflow (golangci-lint), pre-commit and gitleaks secret scanning, a Makefile, and the contribution and community setup.

More at my [GitHub profile](https://github.com/sudoping01) and [Hugging Face profile](https://huggingface.co/sudoping01).

---

# Blog

Some things don't fit in a paper or a model card, so I write them down instead. Posts live in [`blogs/`](https://github.com/sudoping01/resume/tree/main/blogs) in this repo.

* **[An Introduction to MALIBA-AI](https://github.com/sudoping01/resume/blob/main/blogs/MALIBA-AI.md)**
  <br>Why I started MALIBA-AI: Mali is missing the AI wave, and beneath the connectivity numbers the real barrier is language. Most Malians don't speak French or English, and the languages they do speak Bambara, Fulfulde, Songhay are primarily oral, so even text interfaces exclude them. The post argues that requiring a colonial language to use AI builds a two-tier society, lays out the initiative's philosophy of non-profit community R&D, its three fields of interest (language models, speech technologies, accessibility solutions), and what it would mean for education, agriculture, healthcare, and business if a farmer in Sikasso could build a website by talking to a machine in Bambara. Also mirrored at [MALIBA-AI/blogs](https://github.com/MALIBA-AI/blogs/blob/main/introduction_to_maliba_ai.md).

---

# Education

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-year">2024 - Present</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo"><img src="./assets/daust.png" alt="DAUST"></div>
      <div class="timeline-text">
        <b>Computer Science</b> @ <a href="https://daust.org">Dakar American University of Science and Technology</a>
        <div class="timeline-meta">Dakar, Senegal</div>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2023 - 2024</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">EN</div>
      <div class="timeline-text">
        <b>Electronic Engineering</b> @ Ecole Normale d'Enseignement Technique et Professionnel
        <div class="timeline-meta">Bamako, Mali</div>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2022</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🎓</div>
      <div class="timeline-text">
        <b>Technical Baccalaureate</b> Industrial Sciences and Technologies, Electronic Engineering
        <div class="timeline-meta">Bamako, Mali ranked <b>first nationally</b> in the Malian technical baccalaureate session</div>
      </div>
    </div>
  </div>

</div>

---

# Awards & Honors

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-year">Jul 2023</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🏆</div>
      <div class="timeline-text">
        <b>Excellence Award from the President of the Transition</b>
        <div class="timeline-meta">H.E. Colonel Assimi Goïta, President of the Transition of the Republic of Mali</div>
        <ul>
          <li>Awarded for performances in international robotics competitions Pan African Robotics Competition 2021 (Makers league), Pan African Robotics Competition 2023 (Engineers league), and the International Festival of Science and Technology.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">Jul 2022</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🥈</div>
      <div class="timeline-text">
        <b>Vice Best Student, Competition of Excellence 2022</b>
        <div class="timeline-meta">ENI-ABT, the national engineering school</div>
        <ul>
          <li>A national competition bringing together the best high school students across the country.</li>
          <li>Same year, ranked <b>first nationally</b> in the Malian technical baccalaureate session.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2021</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🥈</div>
      <div class="timeline-text">
        <b>Silver Medals in international robotics &amp; science competitions</b>
        <ul>
          <li><b>Silver Medal, PARC 2021</b> (Jul 2021) second place in the Makers category at the Pan African Robotics Competition, as a member of the Mali National Robotics Team.</li>
          <li><b>Silver Medal, IFEST-2</b> (Nov 2021) International Festival of Science and Technology, Tunisia.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-year">2019</div>
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <div class="timeline-logo">🎖️</div>
      <div class="timeline-text">
        <b>Early academic distinctions</b>
        <ul>
          <li><b>Prize of Professor Mamadou Lamine Traoré</b> (Sep 2019) computer science competition, awarded by President of the Republic Ibrahim Boubacar Keïta.</li>
          <li><b>Roll of Honor</b> (Oct 2019) Bamako Rive-Droite Teaching Academy (AE-BKO-RD), for performance in the fundamental studies diploma examination, July 2019 session.</li>
          <li><b>Best Student Award</b> (Aug 2019) Hamsetou Bah MAIGA Foundation, best student of Camp Lapantha.</li>
          <li><b>Roll of Honor</b> (Apr 2019) best student in the competition of excellence of the Youth Association for the Culture of Excellence in Mali (A.J.C.M).</li>
        </ul>
      </div>
    </div>
  </div>

</div>

---

# Skills

<div class="tags">
  <span class="tag-label">Programing Languages</span>
  <span class="tag">Python</span>
  <span class="tag">JavaScript</span>
  <span class="tag">C/C++</span>
  <span class="tag">Bash</span>
  <span class="tag">Java</span>

  <span class="tag-label">AI / ML</span>
  <span class="tag">PyTorch</span>
  <span class="tag">Hugging Face Transformers</span>
  <span class="tag">Whisper</span>
  <span class="tag">Unsloth</span>
  <span class="tag">Axolotl</span>
  <span class="tag">Fine-tuning</span>
  <span class="tag">LoRA / QLoRA</span>
  <span class="tag">Quantization</span>

  <span class="tag-label">NLP</span>
  <span class="tag">ASR</span>
  <span class="tag">TTS</span>
  <span class="tag">Machine Translation</span>
  <span class="tag">LLMs</span>
  <span class="tag">VLMs</span>
  <span class="tag">VLA</span>

  <span class="tag-label">MLOps &amp; Model Serving</span>
  <span class="tag">vLLM</span>
  <span class="tag">llama.cpp</span>
  <span class="tag">On-premise serving</span>
  <span class="tag">Serving at scale</span>
  <span class="tag">GPU inference</span>
  <span class="tag">FastAPI</span>

  <span class="tag-label">DevOps &amp; CI/CD</span>
  <span class="tag">Docker</span>
  <span class="tag">GitHub Actions</span>
  <span class="tag">CI/CD</span>
  <span class="tag">systemd</span>
  <span class="tag">Debian packaging</span>
  <span class="tag">Linux Administration</span>
  <span class="tag">Git</span>

  <span class="tag-label">Infrastructure &amp; Cloud</span>
  <span class="tag">AWS</span>
  <span class="tag">GCP</span>
  <span class="tag">WebRTC</span>
  <span class="tag">IoT</span>
  <span class="tag">MQTT</span>
  <span class="tag">ROS 2</span>

  <span class="tag-label">Spoken</span>
  <span class="tag">Bambara (native)</span>
  <span class="tag">French (fluent)</span>
  <span class="tag">English (fluent)</span>
</div>

---

# Community & Previous Ventures

**MALIBA-AI** Founder & Lead. Building an AI ecosystem for indigenous Malian languages, centered on speech-first technology and accessibility, with applications across education, healthcare, and business.
[Introduction to MALIBA-AI](https://github.com/MALIBA-AI/blogs/blob/main/introduction_to_maliba_ai.md) | [Hugging Face](https://huggingface.co/MALIBA-AI) | [GitHub](https://github.com/MALIBA-AI)

**KAALISI** Founder. An AI-powered investment evaluation platform scoring startups on financial performance, environmental impact, pandemic resilience, and youth employment, aiming to democratize access to capital through intelligent matchmaking.

**JAYAS Drone** Co-Founder. A drone-as-a-service platform, building ready-to-fly drones and the service infrastructure around them.



# References

* **Sebastien Diarra** ML/AI Researcher · [sebastien.diarra@gmail.com](mailto:sebastien.diarra@gmail.com)
* **Michael Leventhal** Founder & President, RobotsMali · [m.leventhal@robotsmali.org](mailto:m.leventhal@robotsmali.org)
* **Allahsera Auguste Tapo** NLP Researcher, RIT · [aat3261@g.rit.edu](mailto:aat3261@g.rit.edu)
* **Sidy Ndao** Founder & President, Dakar American University of Science and Technology · [sndao@daust.org](mailto:sndao@daust.org)
* **Abdoulaye Faye** Co-Founder & CTO, Caytu Robotics · [afaye@caytu.com](mailto:afaye@caytu.com)
