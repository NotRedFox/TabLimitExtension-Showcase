# TabLimitExtension-Showcase
<img width="1440" height="900" alt="Screenshot 2026-05-01 at 8 26 12 PM" src="https://github.com/user-attachments/assets/6b69e79e-cc21-4da1-9929-e89e18ef322a" />
<img width="1310" height="952" alt="Screenshot 2026-05-01 at 7 49 56 PM" src="https://github.com/user-attachments/assets/0fe3d454-9eae-4b54-a378-67bbfb5ac307" />


<img width="752" height="752" alt="Screenshot 2026-05-01 at 8 21 40 PM" src="https://github.com/user-attachments/assets/f48d951e-e753-43a3-92ff-cbc3ff18ef6c" />

<img width="1310" height="952" alt="Screenshot 2026-05-01 at 7 52 35 PM" src="https://github.com/user-attachments/assets/1afab3ee-1111-4c46-b390-f05f4ed14cfd" />

<img width="1310" height="952" alt="Screenshot 2026-05-01 at 7 53 07 PM" src="https://github.com/user-attachments/assets/5a351b6b-a1a7-490b-8769-9c89a7c095c8" />

<img width="747" height="493" alt="Screenshot 2026-05-01 at 7 58 08 PM" src="https://github.com/user-attachments/assets/3857a37b-34f4-43e2-8a2a-9db2eb7a0b91" />
The productive/Unproductive words essentially do nothing but research shows that when users feel like they customised the system they are up to 50% more likely to feel like they are part of the system and helped build it resulting in a much higher retention rate. (IKEA effect)

<img width="1310" height="952" alt="Screenshot 2026-05-01 at 7 53 02 PM" src="https://github.com/user-attachments/assets/329c321e-34b1-4d7a-a5dc-ddabda6040b4" />



**90% of this code was written through the use of AI. The logic and decisions are all chosen by me. I have learnt a lot and am still learning a lot. I just knew I wanted it to work. Aditonlly I had a more indepth break down of this document I can send but I dont want people to copy it. By the time you are reading this, in a perfect world, I will be halfway through V2. I made this in 3/4 weeks with a budget of about $100. I was inspired by the training to implement the security first scope, as prior to the training, I never realised just how imperative security is. That being said, it was first built to help me stay professional with tabs in my browser as I eventually found myself at the cutting edge of what a Chrome extension is physically able to do in 2025. I have also made performance a number one priority because I'm not using it if it's not fast. Currently uses 0.21MB of local storage after weeks of real use, well under Chrome's 10MB quota. Designed to stay under that ceiling even after months of offline use, with automatic pruning when limits approach. (It does reach a max if you don't sign in after, I guess, about 3 months. This is due to holding on to data locally before getting permission to send it to my server or delete it.)**

Please ignore the ugly UI in some places this is currently V1 thats ment to just be funtional for me to focaus on the task at hand not look pretty.

(Reiterating I had to significantly dumb it down to ajust for people coping this since it was so cheap and only took a few weeks.)

PlayingFild
A Chrome extension that learns what you consider productive browsing, then helps you stay there. Not a static blocklist—PlayingFild is an adaptive system that learns the difference between a distraction and a deep-work resource through real-time feedback.

Core Features

* Intelligent Classification: Pages are scored in real-time based on content and historical behaviour.
* Smart Tab Management: Automatically manages tab overhead by prioritizing your active work and pruning low-value tabs.
* Privacy-First Architecture: Uses a multi-layer data model where sensitive signals never leave your device.
* Adaptive Vocabulary: The system learns your professional language as you browse, eliminating the need for manual keyword lists.

Technical Overview
Built with a focus on extreme performance (under 0.3MB storage footprint) and security.

* Frontend: Vanilla ES6+ for maximum speed.
* Security: Multi-layer consent model with hardware-level privacy considerations.
* Intelligence: Local ML inference for private, on-device semantic analysis.

Roadmap

* Phase 1: Core engine and local feedback loop.
* Phase 2: Secure cloud sync and community-weighted scoring.
* Phase 3: Advanced semantic recall and productivity visualizations.

🔒 Source Code
The source code and detailed architectural documentation for this project are private. Contact me for a live demo or a technical walkthrough.



