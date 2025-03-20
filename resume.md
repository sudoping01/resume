## Seydou DIALLO
**Software Developer | AI Enthusiast | Linux Administrator | Community Builder | Social Impact Interested | Co-founder of Djelia**

Passionate about Computer Science and latest Technologies, especially Artificial Intelligence,more precisely Natural Language Processing. </br>
* Student in Computer Science Engineering at Dakar American University of Science and Technology </br>
* First National of the Malian Technical  Baccalaureate session of July 2022 in Industrial Sciences and Technologies, more precisely in Electronic Engineering </br>
* Malian Robotics team member in 2023 and 2021

## Research Projects 
- **GAIFE**: Generative AI for Education  
  With pilot funding from the Bill & Melinda Gates Foundation Grand Challenges program, as Co-Author, we have developed a methodology using generative AI and automatic translation to produce children's books and supporting pedagogical material in the most widely spoken national language of Mali, Bambara.
  
  Here is the link to the [library](https://bloomlibrary.org/RobotsMali)

- **Bayelemabaga**: First Machine Translation model in Bambara  
    As its title indicates, this project was the first machine translation model to translate Bambara text to French and vice versa. I was mostly involved in the data processing, extracting, cleaning and aligning in pairs of Bambara-French or French-Bambara.

    For more details, here is information on RIT [website](https://www.rit.edu/lpi/research)

- **Automatic Speech Recognition**:
    - **Wolof**: Senegal's primary language, considered as an extremely low-resource language and a spoken language, not fully existing in technological spaces. 
        For contribution to African NLP advancement and technology access for Wolof speakers, I [Alone] have worked on two ASR models for Wolof speech recognition. I have developed two good ASR models in Wolof considered [at the moment of writing this resume] the most accurate open-source ASR for Wolof existing. Named whosper-large derived from whisper-large and Wolof, both models demonstrate impressive results in Wolof speech recognition when mixed with French or English. They are able to transcribe spoken Wolof accurately into text while maintaining their multilingual capabilities, performing well in French and English while excelling in Wolof.

        In one week, whosper-large-v2 got 796 and whosper-large got 255 downloads.

        You can find both models and their cards (metrics and all details) here:

        [whosper-large-v2](https://huggingface.co/CAYTU/whosper-large-v2), [whosper-large](https://huggingface.co/CAYTU/whosper-large)

    - **Bambara**: Mali's primary language considered as an extremely low-resource language spoken by millions of people across Mali and West Africa. 

        For contribution to African NLP advancement and technology access for Bambara speakers, I [Alone] have worked on ASR models for Bambara speech recognition. At the moment of writing this resume, I have developed several good ASR models in Bambara that outperform all existing open-source Bambara ASR models. Named maliba-asr derived from "Great Mali" [Mali Ba], these models demonstrate impressive results with the latest version (maliba-asr-v2) achieving a WER of 24.33% and a CER of 12.45% on evaluation datasets [6 hours]. These models perform very well on English but have limited performance in pure French, while excelling in code-switching scenarios. For now, they are still on my personal repository on Huggingface [sudoping01](https://huggingface.co/sudoping01). By the end of the experimentation, all of these models will be moved to the [MALIBA-AI](https://huggingface.co/MALIBA-AI) repository.

    - **Songhay**: Language mainly spoken in Mali in the Gao region.  
        For contribution to African NLP advancement and technology access for Songhay speakers, I [Alone] have developed songhay-asr-v1, the first ASR model for the Songhay language, distinct from the MMS initiative.This model achieves impressive results with a Test WER of 16.58% and a Test CER of 4.63% on the test dataset. The model supports both Songhay and French, making it valuable for Songhay speakers in their multilingual context. 
        You can find the model: [shongoy-asr-v1-ic](https://huggingface.co/sudoping01/songhoy-asr-v1-ic)


    - **Multilingual ASR for Malian languages** (Ongoing)  
        As the main contributor, along with Penga Azazia under the umbrella of MALIBA-AI, we are investigating multilingual ASR for Malian language speech recognition. At the time of writing this resume, we have collected data for 11 languages: 10 Malian languages plus French. Currently, our experiments have not yet yielded completely successful results, as we have just begun this ambitious project. Our goal is to create a unified model capable of recognizing and transcribing multiple Malian languages, making technology more accessible to all Malians regardless of their native language. The challenges include limited training data, dialectal variations, and complex morphological structures of these languages.


- **IoT Assistant in local language**

    For my first year of school, I wanted to create an IoT assistant that we can control in local languages, which paved my path to Caytu Robotics. In one year of dedicated work, the vision was transformed into reality. After designing and building a scalable IoT ecosystem with remote control capabilities and real-time video and data streaming, borned the world's first IoT assistant that understands and operates fully in Wolof, capable of managing IoT systems, handling workflow automation, and providing custom support while communicating in local languages. The assistant is accessible through the [Caytu platform](https://caytu.link/). I have shared the architecture as open source during 2024 Ndabax Senegal to contribute to technological advancement.


## Open Source Projects

 - **Realtime Video/Audio WebRTC Streaming** </br>
    An open-source solution that simplifies real-time video and audio streaming to the cloud. This project makes enterprise-grade streaming technology accessible to developers and organizations without requiring deep expertise in video streaming protocols. By containerizing the streaming infrastructure, users can quickly deploy reliable, low-latency video transmission from various sources (like security cameras, webcams, or industrial monitoring devices) to AWS cloud services. The solution emphasizes ease of use, cross-platform compatibility, and security while maintaining high performance even on resource-constrained devices. Code source  available on [github](https://github.com/sudoping01/aws-kvs-webrtc-stream-dockerised) and contenair avaialbe on [Docker Hub](https://hub.docker.com/r/sudoping01/aws-kvs-webrtc-stream), this project has helped democratize access to real-time streaming capabilities for applications in remote monitoring, surveillance, telehealth, and industrial IoT.

- **Inference Server for the first wolof open source TTS**

    An accessible deployment solution for the first Wolof speech synthesis system, enabling developers to easily integrate natural-sounding Wolof voice into applications. This democratizes access to voice technology for Senegal's primary language, supporting education, accessibility, and digital services for Wolof-speaking communities while requiring minimal technical expertise to implement. Code source available [here on github](https://github.com/sudoping01/wolof-tts)

- **Segmentation algorithm with Inference Server support for Adia_TTS**:

    Adia TTS is the most accurate Wolof open-source TTS existing at the moment of writing this resume, it but has a character limitation making it impractical for real-world use.
    The segmentation algorithm developed, transforms this research model into a production-ready system by implementing text processing pipeline that breaks long content at natural speaking points and seamlessly reconstructs the audio. This overcomes the fundamental limitation while preserving the high-quality voice characteristics. The pepiline is now part of the official documentation of the model, at the moment of writinf this resume, I'm working with them to integrate it in their documentation, follow discussion in [here](https://huggingface.co/CONCREE/Adia_TTS/discussions/3#67d94d89fbc8ceeb878ba261). 

    The containerized system provides a simple API that developers can integrate with minimal code, enabling practical applications in conversational AI, education, and accessibility services for Wolof speakers who previously lacked access to this fundamental voice technology. Source code available on [here](https://github.com/sudoping01/adia-inference-server).

    NB: You can find more open source initiative under my personal repo on github [sudoping01](https://github.com/).


## Entrepreneurship Initiative

- **DJELIA**: Co-Founder </br>
DJELIA is a startup providing Bambara language models (ASR, TTS, MT) through its API, enabling local developers to integrate Bambara language into applications. As the first AI platform dedicated to Bambara, we offer text-to-speech, translation, and transcription in a secure platform, making technology accessible to Bambara speakers.


- **KAALISI**: Founder (Failed) </br>
    KAALISI was an intelligent investment platform that evaluated startups to predict their chances of success. The platform assessed businesses on financial performance, environmental impact, pandemic resilience, and youth employment, making investment opportunities more accessible through AI-powered scoring models. By connecting promising ventures with investors, KAALISI aimed to democratize access to capital while promoting sustainable business practices.
  
- **JAYAS Drone**: Co-Founder (failed)
    The main idea of JAYAS Drone was actually to build ready to fly drone and provide them as service.


## Social Impact

- **MALIBA-AI**: </br>
    MALIBA-AI is a community-driven initiative developing AI systems in indigenous Malian languages like Bambara, Fulfulde, and Songhay. By creating speech-first technology interfaces for languages that are primarily oral, we're making digital tools accessible to all Malians regardless of literacy or formal education. Our work focuses on language models, speech technologies, and accessibility solutions that bridge the digital divide, ensuring no Malian is left behind by technological advances and democratizing access to AI's benefits in education, healthcare, agriculture, and business.

    You can find more detail : 
    
    - [Introduction to MALIBA-AI](https://github.com/MALIBA-AI/blogs/blob/main/introduction_to_maliba_ai.md)

    - [Hugging Face Community Card](https://huggingface.co/MALIBA-AI)









