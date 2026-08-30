Hi I'm Danbi Kim, an undergraduate majoring in Artificial Intelligence Convergence Engineering. I study what AI systems actually respond to when they claim to understand people.

Even as technology connects us more tightly than ever, emotional isolation keeps deepening. That gap is what draws me. Most AI research optimizes for performance and efficiency; reading a person's situation and responding to it well remains comparatively underexplored — and it is a hard problem in its own right, one that requires reasoning about context rather than classifying sentiment.

My work so far has converged on a single question from two directions. In ESI-SimPO, I built a dynamic-margin preference optimization framework for Korean emotional support dialogue, intending the model to modulate empathy according to the weight of a situation. It didn't. I traced why: the margin signal saturated during training, and alignment narrowed the variance of responses rather than improving them. I reframed the work as a diagnosis of why domain-specific margin signals fail. In "Judging Status, Not Harm" (submitted to the NeurIPS 2026 TAE workshop), I used a controlled minimal-pair design across three commercial models to show that refusal tracks the institutional standing of a target rather than the severity of harm — and that every informative response silently reframes the request before answering.

Both findings say the same thing: the variable a system appears to respond to is not the variable it actually responds to. That matters most for systems meant to support people, where a fluent answer can hide the absence of understanding entirely.

I'm now interested in extending this to agents that hold context over time — memory, personalization, and sustained interaction — so that emotional support becomes a property of a relationship rather than a single turn. I care about honest negative results and carefully scoped claims, and I'd rather report what a system is actually doing than what we hoped it would do.

-------------------------------------------------------
## Publications
- 표면 어휘와 상황 맥락의 정서적 괴리: 마음 이론 기반의 LLM 감성 강도 보정 프레임워크
  (Sentiment Context Discordance: A Theory of Mind-Based LLM Framework for Affective Intensity Calibration)
-	ESI-SimPO: 한국어 정서 도메인을 위한 동적 마진 기반 적응적 선호도 최적화
  (ESI-SimPO: Adaptive Preference Optimization with Dynamic Margins for Korean Emotional Dialogue)
-	텍스트 데이터 마이닝을 활용한 감정 강도 예측 분석 기법 
  (A sentiment intensity prediction analysis technique using text data mining)
-	온라인 가상환경에서 학습자 패턴 분석을 위한 머신러닝 기반 학습 효과 진단 모델 설계 연구
-	디지털 대시보드를 위한 ChatGPT기반 자연어 질의 인터페이스


-------------------------------------------------------
## Honors & Programs
- LG Aimers (Completed) — participated solo, Top 12% (2025)
- Naver BoostCourse "Python for Everyone" Coaching Study — Team Leader (2022)
-------------------------------------------------------------
## Projects
- Question Generation Model — seq2seq with attention (Coursework, 2025)
- Text-based Emotion Intensity Prediction (Regression Model) (Coursework, 2025)
- Analysis of AI Education Trends via Text Mining (Coursework, 2024)
- Document Clustering with Word2Vec and K-Means (Coursework, 2024)
- Sentiment Analysis (Coursework, 2022)
- AI Speaker (Coursework, 2022)
