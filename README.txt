SHIELDGUARD
Vishing Detection Using Machine Learning & Natural Language Processing
EUREKA 2026 Online Submission

Participant:
Mohamad Ikmal Hafizi Bin Mohd Amir

Supervisor:
Ts. Dalilah Abdullah

Institution:
Universiti Kuala Lumpur Malaysian Institute of Information Technology (UniKL MIIT)


============================================================
SUBMISSION LINKS
============================================================

Video Presentation (Google Drive):
[PASTE GOOGLE DRIVE VIDEO LINK HERE]

Interactive Pitch Deck (GitHub Pages):
https://h0l3ym0l3h.github.io/PitchDeckEureka/

Pitch Deck Source Repository:
https://github.com/H0l3yM0l3h/PitchDeckEureka


============================================================
NOTE TO THE EUREKA 2026 ORGANISING COMMITTEE AND JUDGES
============================================================

Dear EUREKA 2026 Organising Committee and Judges,

Thank you for taking the time to review my submission.

I would also like to sincerely apologise that my submitted video presentation exceeds the stated five-minute limit by approximately six seconds. I understand the importance of following the competition requirements, and I regret this unintentional overrun. I respectfully hope the committee will still be able to consider the submission, and I appreciate your understanding.

ShieldGuard is a project that means a great deal to me because it brings together two areas I am deeply interested in: cybersecurity and artificial intelligence. I developed this project with the goal of exploring how technology can help ordinary users better recognise and respond to increasingly convincing vishing and social-engineering attacks.

For the online submission, I have provided both the official video presentation through Google Drive and an interactive web-based version of the pitch deck through GitHub Pages. The interactive deck is included as supplementary material so that the project can be explored more clearly beyond the recorded presentation.

I sincerely appreciate the opportunity to present ShieldGuard at EUREKA 2026 and to have the project evaluated alongside other innovations. Regardless of the outcome, I see this competition as an opportunity to learn, improve the system, and continue developing solutions that can make digital interactions safer for users.


============================================================
EXECUTIVE SUMMARY
============================================================

ShieldGuard is an ML-first vishing detection prototype designed to analyse suspicious call content and help users understand whether a conversation may contain indicators of voice phishing.

The system focuses on the content of the conversation rather than relying only on known phone numbers or simple keyword-based rules. Audio can be transcribed into text using speech-to-text technology before the transcript is analysed by a machine-learning detection engine.

At the core of ShieldGuard is a Calibrated Linear Support Vector Machine using TF-IDF word-level and character-level features. The selected model achieved 98.88% accuracy and a 98.69% macro F1-score on the project's clean test dataset, outperforming the Logistic Regression, Random Forest, and character-level neural-network models evaluated during development.

ShieldGuard also integrates a secondary AI-assisted review layer using Retrieval-Augmented Generation and a Large Language Model. This layer is designed to provide contextual explanations, identify possible scam tactics, and generate understandable safety guidance. Importantly, the architecture follows an ML-first approach: the LLM supports explanation and review rather than independently overriding strong machine-learning evidence.

The prototype was developed as a full-stack web application using React, FastAPI, Supabase, speech-to-text, machine learning, and RAG-assisted AI components. The interface presents users with a detection verdict, risk information, transcript analysis, explanations, and recommended actions in a format intended to be understandable even to non-technical users.

Usability testing was conducted with 28 participants. The system achieved a System Usability Scale score of 70.63, an explanation-clarity rating of 4.39/5, an ease-of-use rating of 4.36/5, and a recommendation score of 9.21/10.


============================================================
THE PROBLEM SHIELDGUARD ADDRESSES
============================================================

Vishing attacks use social engineering, impersonation, urgency, fear, and other psychological techniques to manipulate victims during phone conversations. These attacks can be difficult for users to recognise, especially when the conversation sounds convincing or appears to come from a trusted organisation.

ShieldGuard explores a different approach: analyse what is actually being said in the conversation, classify the transcript using machine learning, and then explain the indicators behind the result so that the user can make a better-informed decision.

The objective is not only to detect a potential threat, but also to help users understand why it may be dangerous and what they should do next.


============================================================
KEY INNOVATION
============================================================

1. ML-First Hybrid Detection
   A lightweight machine-learning model performs the primary classification, while a Large Language Model is used as a secondary contextual review and explanation layer.

2. Explainable Detection
   ShieldGuard is designed to provide more than a simple "Safe" or "Vishing" label. It presents reasoning, possible scam indicators, and safety recommendations to help users understand the verdict.

3. Conversation-Content Analysis
   The system focuses on analysing transcribed call content rather than depending solely on phone-number reputation or static blocking lists.

4. Practical Full-Stack Prototype
   ShieldGuard is implemented as a working web-based prototype that combines speech-to-text, machine learning, AI-assisted analysis, user authentication, scan history, and administrative monitoring.


============================================================
VALIDATION AND RESULTS
============================================================

Machine Learning Evaluation:
- Calibrated Linear SVM Accuracy: 98.88%
- Macro F1-Score: 98.69%
- Five-fold cross-validation was used during model development and selection.

Usability Evaluation:
- Participants: 28
- System Usability Scale (SUS): 70.63
- Ease of Use: 4.36 / 5
- Explanation Clarity: 4.39 / 5
- Recommendation Score: 9.21 / 10

System Testing:
- Functional testing completed
- End-to-end integration testing completed
- Security controls tested, including authentication, input sanitisation, rate limiting, prompt-injection handling, and brute-force protection


============================================================
POTENTIAL IMPACT
============================================================

ShieldGuard has potential applications as:

- A public-facing scam-awareness and vishing detection tool
- A cybersecurity education and training platform
- A support tool for organisations handling suspicious calls
- A future API service for fraud-monitoring or call-centre environments

The project is currently a standalone prototype and is not integrated directly with live telecommunications carrier networks. Its current detection scope is primarily transcript-based and based on English-language data. Future development will focus on expanding real-world datasets, supporting Malay and mixed-language conversations, improving real-time audio processing, and conducting broader user testing.


============================================================
WHY I BUILT SHIELDGUARD
============================================================

I believe innovation is most meaningful when it solves a problem people can genuinely experience in their everyday lives.

For me, ShieldGuard is more than an academic requirement. It is an opportunity to apply what I have learned in cybersecurity, machine learning, NLP, AI engineering, and software development to a real problem: helping people recognise digital deception before it causes harm.

The system is still evolving, and I recognise that there is much more that can be improved. That is also what motivates me. I want to continue testing, learning, refining the technology, and exploring how ShieldGuard can become more practical, inclusive, and effective in real-world environments.


============================================================
ACKNOWLEDGEMENT
============================================================

I would like to express my sincere appreciation to my supervisor, Ts. Dalilah Abdullah, Universiti Kuala Lumpur Malaysian Institute of Information Technology, the EUREKA 2026 organising committee, and the panel of judges for providing students and innovators with a platform to present, test, and improve our ideas.

Thank you for reviewing ShieldGuard.


Mohamad Ikmal Hafizi Bin Mohd Amir
Universiti Kuala Lumpur Malaysian Institute of Information Technology (UniKL MIIT)
