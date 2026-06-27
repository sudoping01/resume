<table>
  <tr>
    <td width="200" valign="top">
      <img src="profile.jpeg" alt="Seydou DIALLO" width="180">
    </td>
    <td valign="top">
      <h1>SEYDOU DIALLO</h1>
      <strong>Software Developer | AI/NLP Enthusiast | Linux Administrator | Community Builder</strong>
      <ul>
        <li><strong>Address:</strong> Somone, Senegal</li>
        <li><strong>Email:</strong> <a href="mailto:mail.seydou.diallo@gmail.com">mail.seydou.diallo@gmail.com</a></li>
        <li><strong>GitHub:</strong> <a href="https://github.com/sudoping01">sudoping01</a></li>
        <li><strong>HuggingFace:</strong> <a href="https://huggingface.co/sudoping01">sudoping01</a></li>
        <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/seydou-diallo-08ab311ba/">seydou diallo</a></li>
      </ul>
    </td>
  </tr>
</table>


---

## PROFILE

Software developer and AI/NLP researcher building speech and language technology for African languages - ASR, TTS, machine translation, and LLMs. Founder of MALIBA-AI and co-founder of DJELIA, where I take models from data collection through production deployment. First-author work on Bambara language technology published at peer-reviewed venues, with open-source models released on Hugging Face and developer SDKs in production.

---

## EDUCATION

**Dakar American University of Science and Technology** | Dakar, Senegal  
*Computer Science*  | 2024 - Present

**Ecole Normal D'Enseignment Technique et Professional** | Bamako, Mali  
*Electronic Engineering* | 2023 - 2024

**Technical Baccalaureate in Electronic Engineering** | Bamako, Mali  
*Industrial Sciences and Technologies*  | July - 2022

**First National** in Malian Technical Baccalaureate session <br>
**Specialization**: Electronic Engineering

---

## PUBLICATIONS

**BambaraMLLM: A Unified Multilingual Multimodal Large Language Model for Comprehensive Bambara Language Processing**  
*Seydou Diallo, Allahsera Auguste Tapo, Kevin Assogba, Christopher Homan* - **First author**  
- Unified multimodal model covering ASR, machine translation, text generation, and TTS for Bambara in a single framework
- Built a linguistically informed instruction-data framework injecting Bambara morphology, syntax, and cultural context to generate 2M+ conversational instruction examples
- [Paper](https://openreview.net/pdf?id=XQXAxrIz9k)

**Where Are We At with Automatic Speech Recognition for the Bambara Language?**  
*Seydou Diallo, Yacouba Diarra, Mamadou K. Keita, Panga Azazia Kamaté, Adam Bouno Kampo, Aboubacar Ouattara* - **First author**  
- Introduced the first standardized ASR benchmark for Bambara, built on professionally recorded Malian constitutional text with manual segmentation, alignment, and quality review
- Evaluated 37 systems and released a public leaderboard for transparent Bambara speech-technology evaluation
- arXiv: [2602.09785](https://arxiv.org/abs/2602.09785)

**InstructLR: A Scalable Approach to Create Instruction Dataset for Under-Resourced Languages**  
*Mamadou K. Keita, Sebastien Diarra, Christopher Homan, Seydou Diallo* - Co-author  
- Framework combining LLM generation, RAG-based correction, and human-in-the-loop validation to build high-quality instruction datasets for low-resource languages
- Produced the 50k-scale BambaraInstruct, ZarmaInstruct, and FulfuldeInstruct benchmarks
- arXiv: [2512.02213](https://arxiv.org/abs/2512.02213)

**GAIFE: Generative AI for Education** (NAACL 2025 Findings) - Co-author  
- Human-in-the-loop workflow using LLMs, machine translation, and linguistic tools to produce culturally grounded children's reading materials in Bambara, a low-resource language
- Built a learning library of 174 illustrated books (~4,000 pages, 850+ original images), multiplying Bambara children's content online roughly tenfold
- Pilot reading programs achieved a 67% reduction in children unable to read Bambara
- [Paper](https://aclanthology.org/2025.findings-naacl.442/) | [Library](https://bloomlibrary.org/RobotsMali)

---

## PROFESSIONAL EXPERIENCE

### Co-Founder | [DJELIA](https://djelia.cloud)  
*2024 – Present*  
- Own the full AI model lifecycle for Bambara - data collection, training, evaluation, and deployment
- Built and maintain production-grade ASR, TTS, MT, and LLM models for Bambara, served via cloud APIs
- Shipped Python and JavaScript SDKs so third-party applications can integrate Djelia's language models
- Turned research-stage language models into reliable, documented services for local developers


### Founder | [MALIBA-AI Community](https://maliba-ai.org)  
*2025 – Present*  
- Founded and lead a community-driven AI initiative for indigenous Malian languages, owning research from data collection to final model
- Built and maintain ASR, TTS, LLM, and MT models across multiple Malian languages
- Released inference SDKs and serving infrastructure so developers and communities can integrate MALIBA-AI models directly
- Designed speech-first interfaces for primarily oral languages, expanding AI access in education, healthcare, agriculture, and local business


### Software Developer & AI Engineer | [Caytu Robotics](https://caytu.ai)  
*2024 – Present*  
- Built and maintain a scalable IoT ecosystem for remote control, real-time video streaming, and data monitoring
- Developed Caytu Avatar, a multimodal AI agent enabling natural-language interaction with any REST API, including the Caytu IoT ecosystem
- Created tools and SDKs for integrating AI services, automation workflows, and assistant features



### Robotics Team Member | Malian National Team  
*2021, 2023*
- Represented Mali in international robotics competitions
- Collaborated on complex engineering projects and problem-solving challenges



## RESEARCH PROJECTS

### **Large Language Models**


**MALIBA-LLM** | Lead Developer | MALIBA-AI

* Built **MALIBA-LLM**, the first open-source large language model for Bambara (Bamanankan), fine-tuned from google/gemma-3n-E2B-it
* Supports Bambara ↔ French/English code-switching, instruction following, translation, and Mali-specific knowledge
* Reduced validation loss to **0.4952** (93.4% lower than the 7.4595 starting point)
* Released on Hugging Face for education, translation, and conversational use: [maliba-llm](https://huggingface.co/sudoping01/maliba-llm)

### Speech Synthesis 

**Bambara Text-to-Speech** | Lead Developer | MALIBA-AI

- Open-source Bambara TTS system rated **4.2/5.0** for quality and **4.1/5.0** for naturalness by 10 native Bambara speakers
- Targets the digital exclusion affecting millions of non-literate adults in sub-Saharan Africa
- Released on Hugging Face - **8,712 downloads** as of October 2025: [MALIBA-AI/bambara-tts](https://huggingface.co/MALIBA-AI/bambara-tts)

**MALIBA-TTS: Multilingual Speech Synthesis for Malian Languages** | *Lead Contributor*  
- Developed **text-to-speech (TTS) models** for six Malian languages: **Bambara, Boomu, Dogon, Pular, Songhoy, and Tamasheq**  
- Based on **Meta’s MMS-TTS** and **VITS**, optimized for **CPU inference** and **real-time synthesis**  
- Enables **voice interfaces, education, and accessibility tools** across Mali  
- Promotes **language inclusion and digital accessibility** under the *MALIBA-AI* initiative  
- Models: [huggingface.co/MALIBA-AI/malian-tts](https://huggingface.co/MALIBA-AI/malian-tts)


### GAIFE: Generative AI for Education  
*Co-Author | Bill & Melinda Gates Foundation Grand Challenges | RobotsMali*
- Co-developed a novel methodology combining generative AI and automatic translation to produce educational content at scale for Bambara, a low-resource language
- Co-author on the resulting peer-reviewed paper (NAACL 2025 Findings)
- Applied the methodology to build a library of 174 published illustrated books, contributing Bambara linguistic review for accuracy, fluency, and cultural relevance
- [Paper](https://aclanthology.org/2025.findings-naacl.442/) | [Library](https://bloomlibrary.org/RobotsMali)

### Bayelemabaga: Bambara Machine Translation
*Data Processing | RobotsMali | RIT Partnership*
- Contributed to the first machine translation model for the Bambara–French language pair
- Handled extraction, cleaning, and alignment of the parallel corpora behind the model
- [Project Details](https://www.rit.edu/lpi/research)
- [Dataset](https://huggingface.co/datasets/RobotsMaliAI/bayelemabaga)

### Automatic Speech Recognition Systems

**Wolof ASR Models** | Lead Developer | CAYTU ROBOTICS
- Built **whosper-large-v2** and **whosper-large**, open-source Wolof ASR models
- Handle multilingual input across Wolof, French, and English
- whosper-large-v2 reached **24% WER** and **11% CER** on a 9-hour evaluation set
- **3,893 downloads** (whosper-large-v2) and **679 downloads** (whosper-large) in first week
- Models:  [whosper-large-v2](https://huggingface.co/CAYTU/whosper-large-v2) | [whosper-large](https://huggingface.co/CAYTU/whosper-large)

**Bambara ASR Models** | Lead Developer | MALIBA-AI
- Built the **maliba-asr** series for Bambara ASR
- maliba-asr-v2 reached **24.33% WER** and **12.45% CER** on a 3-hour evaluation set
- Handles Bambara–English code-switching
- Latest Model : [bambara-asr-v1](https://huggingface.co/MALIBA-AI/bambara-asr-v1)

**Songhay ASR Model** | | Lead Developer | MALIBA-AI
- Built **songhay-asr-v1**, an ASR model for the Songhay language
- Reached **16.58% WER** and **4.63% CER** on the test set
- Supports bilingual Songhay–French transcription
- Model: [songhoy-asr-v1](https://huggingface.co/sudoping01/songhoy-asr-v1-ic)



### IoT Assistant in Local Languages  
*Lead Developer | Caytu Robotics*
- Built an IoT assistant operating fully in Wolof
- Designed a scalable IoT ecosystem with remote control and real-time streaming
- Added workflow automation and multilingual support
- [Platform: caytu.link](https://caytu.link/)
- Open-sourced architecture at Ndabax Senegal 2024

---

## OPEN SOURCE CONTRIBUTIONS

### Software Development Kits (SDKs)

**NabooPay Payment Gateway SDKs** | *Lead Developer & Maintainer*
- Python SDK for Senegalese mobile money payments (Wave, Orange Money, Free Money)
- Node.js SDK in TypeScript with full type definitions and automatic retry logic
- Transaction management and cashout operations, with both sync and async support
- Code Source: [Python SDK](https://github.com/naboopay/naboopay-python-sdk) | [Node.js SDK](https://github.com/naboopay/naboopay-nodejs-sdk)

**Djelia AI Language Platform SDKs** | *Lead Developer & Maintainer*
- Python SDK: Complete SDK for Bambara language AI (translation, ASR, TTS) with streaming support
- JavaScript SDK: Modern implementation for web and Node.js environments
- Features: Multi-language translation, real-time transcription streaming, natural TTS with speaker descriptions
- Code Source: [Python SDK](https://github.com/djelia-org/djelia-python-sdk) | [JavaScript SDK](https://github.com/djelia-org/djelia-js-sdk)

**MALIBA-AI Bambara TTS SDK** | *Lead Developer & Maintainer*
- Inference SDK for Bambara text-to-speech synthesis
- Production-ready inference system with 10 authentic speaker voices
- Optimized for educational platforms, accessibility tools, and voice interfaces
- Comprehensive documentation with usage examples and best practices
- Code Source: [GitHub Repository](https://github.com/MALIBA-AI/bambara-tts)

### Infrastructure & Deployment Tools

### Realtime Video/Audio WebRTC Streaming  
- Enterprise-grade streaming solution containerized for easy deployment
- Enables low-latency cloud transmission from various sources
- Applications in remote monitoring, surveillance, telehealth, industrial IoT
- Code source: [GitHub](https://github.com/sudoping01/aws-kvs-webrtc-stream) | [Docker Hub](https://hub.docker.com/r/sudoping01/aws-kvs-webrtc-stream)

### Wolof TTS Inference Server  
- Deployment server for a Wolof speech synthesis system
- Makes voice technology available for Wolof, a primary language of Senegal
- Code Source: [GitHub Repository](https://github.com/sudoping01/wolof-tts)

### Adia_TTS Segmentation Algorithm  
- Turned a research model into a production-ready system
- Removed character-length limits while preserving voice quality
- Merged into the official model documentation
- Code Source: [GitHub](https://github.com/sudoping01/adia-inference-server) | [HuggingFace Discussion](https://huggingface.co/CONCREE/Adia_TTS/discussions/3#67d94d89fbc8ceeb878ba261)

**Additional projects:** [GitHub Profile](https://github.com/sudoping01)

---

## PREVIOUS VENTURES

### KAALISI | Founder  
*AI-powered investment evaluation platform*
- Developed scoring models assessing startups on financial performance, environmental impact, pandemic resilience, and youth employment
- Aimed to democratize access to capital through intelligent matchmaking

### JAYAS Drone | Co-Founder  
*Drone-as-a-Service platform*
- Built ready-to-fly drones and service infrastructure

---

## TECHNICAL SKILLS

**Programming Languages:** Python, JavaScript, C/C++, Bash, Java

**AI/ML Frameworks:** PyTorch, Hugging Face Transformers, Whisper, FastAPI, Unsloth, Axolotl

**Technologies:** Docker, WebRTC, IoT, AWS, GCP, Linux Administration, git, Github

**NLP Specializations:** Speech Recognition (ASR), Text-to-Speech (TTS), Machine Translation (MT), Large Language Model (LLM)

**Languages:** Bambara (Native), French (Fluent), English (Fluent)

---

## COMMUNITY LEADERSHIP

**MALIBA-AI** - Founder & Lead  
Building an AI ecosystem for indigenous Malian languages, centered on speech-first technology and accessibility, with applications across education, healthcare, and business.

[Introduction to MALIBA-AI](https://github.com/MALIBA-AI/blogs/blob/main/introduction_to_maliba_ai.md) | [Hugging Face Community](https://huggingface.co/MALIBA-AI) | [Github](https://github.com/orgs/djelia-org/dashboard)

---

### References  

**Sebastien DIARRA** - ML/AI Researcher  
 [sebastien.diarra@gmail.com](sebastien.diarra@gmail.com)  

**Michael Leventhal** - Founder & President, RobotsMali  
 [m.leventhal@robotsmali.org](m.leventhal@robotsmali.org)  

 **Allahsera Auguste Tapo**- NLP Researcher, RIT <br>
 [aat3261@g.rit.edu](aat3261@g.rit.edu)

 **Sidy Ndao** Founder & President, Dakar American University of Science and Technology <br>
  [sndao@daust.org](sndao@daust.org)

**Abdoulaye Faye** - Co-Founder & CTO, CAYTU Robotics  
 [afaye@caytu.com](afaye@caytu.com)