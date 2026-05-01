# TabLimitExtension-Showcase

Tab:
<img width="1310" height="952" alt="Screenshot 2026-05-01 at 11 14 43 PM" src="https://github.com/user-attachments/assets/3bc99283-ed0d-4596-b1e2-1cd3084bc860" />

Injected pop up:
<img width="1310" height="952" alt="Screenshot 2026-05-02 at 2 10 44 AM" src="https://github.com/user-attachments/assets/6da93a98-f7fe-426d-9d38-ce589d56f62e" />

Tutorial:
<img width="1440" height="900" alt="Screenshot 2026-05-01 at 11 13 52 PM" src="https://github.com/user-attachments/assets/8cc96e38-2506-4af0-a16f-6c2f9e63ac55" />

Advanced settings + more:
<img width="1310" height="952" alt="Screenshot 2026-05-01 at 11 22 21 PM" src="https://github.com/user-attachments/assets/45f83a26-ec80-4386-b1c6-1e31ba84adc3" />
<img width="1310" height="952" alt="Screenshot 2026-05-01 at 7 53 07 PM" src="https://github.com/user-attachments/assets/1e64d948-ad71-4634-b8a7-09838665c4b4" />
<img width="747" height="493" alt="Screenshot 2026-05-01 at 7 58 08 PM" src="https://github.com/user-attachments/assets/b468ba66-9b18-4490-9284-86ce5b3fe5a8" />
The productive/Unproductive words essentially do nothing but research shows that when users feel like they customised the system they are up to 50% more likely to feel like they are part of the system and helped build it resulting in a much higher retention rate. (IKEA effect)

Backend:
<img width="752" height="752" alt="Screenshot 2026-05-01 at 11 17 16 PM" src="https://github.com/user-attachments/assets/2918d38b-c8db-44e4-9da1-11505e75e6e1" />
<img width="752" height="752" alt="Screenshot 2026-05-01 at 11 31 46 PM" src="https://github.com/user-attachments/assets/f06a8ad2-bdf6-4cae-9535-c59ac77eb07a" />


**90% of this code was written through the use of AI. The logic and decisions are all chosen by me. I have learnt a lot and am still learning a lot. I just knew I wanted it to work. Additionally the full architectural breakdown and source are private I would be more then happy to explain why and how to different things I added. By the time you are reading this, in a perfect world, I will be halfway through V2.**

**I made this in 3/4 weeks with a budget of about $100. I was inspired by the training to implement the security first scope, as prior to the training, I never realised just how imperative security is. That being said, it was first built to help me stay professional with tabs in my browser as I eventually found myself at the cutting edge of what a Chrome extension is physically able to do in 2025.**

**I have also made performance a number one priority because I'm not using it if it's not fast. Currently uses 0.21MB of local storage after weeks of real use, well under Chrome's 10MB quota. Designed to stay under that ceiling even after months of offline use, with automatic pruning when limits approach. It does reach a max if you don't sign in after, I guess, about 3 months. This is due to holding on to data locally before getting permission to send it to my server or delete it.**

Please ignore the ugly UI in some places this is currently V1 thats meant to just be funtional for me to focus on the task at hand not look pretty.

PlayingFild
A Chrome extension that learns what you consider productive browsing, then helps you stay there. Not a static blocklist PlayingFild is an adaptive system that learns the difference between a distraction and a deep-work resource through real-time feedback.

Core Features

* Intelligent Classification: Pages are scored in real time based on content and historical behaviour.
* Smart Tab Management: Automatically manages tab overhead by prioritising your active work and pruning low value tabs.
* Privacy-First Architecture: Uses a multi layer data model where sensitive signals never leave your device.
* Adaptive Vocabulary: The system learns your professional language as you browse, eliminating the need for manual keyword lists.

Technical Overview
Built with a focus on extreme performance (under 0.3MB storage footprint) and security.

* Frontend: Vanilla ES6+ for maximum speed.
* Security: Multi-layer consent model with on device signal isolation.
* Intelligence: Local ML inference for private, on-device semantic analysis.

Roadmap

* Phase 1: Core engine and local feedback loop.
* Phase 2: Secure cloud sync and community-weighted scoring.
* Phase 3: Advanced semantic recall and productivity visualisations.

🔒 Source Code
The source code and detailed architectural documentation for this project are private. Contact me for a live demo or a technical walkthrough.



