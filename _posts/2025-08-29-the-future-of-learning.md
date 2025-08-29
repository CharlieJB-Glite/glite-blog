---
layout: default
title: "The Future of Learning"
date: 2025-08-29
desc: "In an era where knowledge is expanding exponentially and traditional education systems struggle to keep pace, AI offers transformative solutions. The recent AI-Powered Education Meetup in London explored how machine learning, particularly Knowledge Tracing (KT), can revolutionise personalised learning."
image: ''
---

# The Future of Learning

August 29, 2025

By Peter Romov

In an era where knowledge is expanding exponentially and traditional education systems struggle to keep pace, AI offers transformative solutions. The recent AI-Powered Education Meetup in London explored how machine learning, particularly Knowledge Tracing (KT), can revolutionise personalised learning.
Benjamin Bloom’s seminal 1984 research, known as the 2 Sigma Problem, revealed that one-on-one tutoring improves student performance by two standard deviations compared to group learning. However, scaling human tutoring is impractical. Enter AI: by leveraging advanced models like Deep Knowledge Tracing (DKT) and Attentive Knowledge Tracing (AKT), we can replicate the benefits of personalised tutoring at scale.

---

## The 2 Sigma Problem: Why Personalised Learning Matters

Bloom’s research demonstrated that students receiving one-on-one tutoring outperformed 98% of their peers in group settings. However, human tutoring is costly and unscalable. AI-driven **Intelligent Tutoring Systems (ITS)** aim to bridge this gap by:

- Adapting to individual learning paces.
- Identifying knowledge gaps dynamically.
- Offering real-time feedback.

![3 curves on a graph where the x-axis is summative achievement score and the y-axis is implied to be total count. '1-to-1 tutorial' is showed to have a higher number of high achievement scores compares to 'conventional' and 'mastery learning' 1-to-30 methods.](/assets/images/article_imgs/bloom_study.png)

_Benjamin Bloom (1984) The 2 sigma problem: The search for methods of group instruction as effective as one-to-one tutoring. Bloom’s study showed one-on-one tutoring (far right) drastically outperforms conventional classroom learning._

---

## The Unprecedented Pace of Knowledge Growth

One of the most pressing challenges in modern education is the **exponential growth of knowledge**. As highlighted in the AI-Powered Education Meetup, data from IBM suggests that by 2020, knowledge was doubling every **11–12 hours**—a staggering acceleration compared to historical benchmarks:

![A curve showing an exponential increase in kowledge between the years 1900 and 2020](/assets/images/article_imgs/knowledge_shift.png)

This rapid expansion means that **static curricula are obsolete**. Students can no longer rely on a fixed set of subjects; instead, they require dynamic, personalised learning systems that evolve alongside global advancements.

---

## Building Student Mind Profiles: The Key to Personalised Learning

A student mind profile is a dynamic, AI-powered model that captures a learner’s unique educational journey. Unlike traditional report cards—which only show grades—a mind profile tracks:

- Current knowledge state – What the student knows (and doesn’t know).
- Learning preferences – How they learn best (e.g., visual, hands-on).
- Strengths & weaknesses – Specific topics needing improvement.

## The Limitations of LLMs — And the Hybrid Solution

While LLMs like ChatGPT demonstrate remarkable language understanding, they hit a wall when tasked with building _true_ student mind profiles. Their reliance on broad, public datasets means they miss the nuances of individual learning patterns—exactly where Knowledge Tracing (KT) models excel.

This gap isn’t just theoretical. In practice, LLMs struggle to:

- Track a student’s progress over months or years (due to context limits).
- Personalize recommendations without access to private learning histories.
- Adapt to _unseen_ questions or concepts outside their training data.

![A simple digram of a persons head with a graph network where the brain is](/assets/images/article_imgs/network.png)

## The Solution? Combine the Best of Both Worlds

By integrating LLMs with Knowledge Tracing, we create hybrid systems that:

1. Understand content deeply (via LLMs like BERT).
2. Track long-term progress (via KT models like AKT).

For example, fine-tuned BERT embeddings can encode _the meaning of questions_ (e.g., “Solve for x in 2x + 5 = 15”), while KT models map how a student’s mastery evolves over time. Together, they overcome the limitations of standalone approaches—delivering truly adaptive learning.

---

## The Evolution of Knowledge Tracing: From Psychometrics to Deep Learning

The journey to modern knowledge tracing systems began decades before the AI revolution, rooted in educational psychology and psychometrics. Understanding this progression reveals why today's hybrid models represent such a breakthrough.

### 1. The Foundation: Rasch Models (1960s)

The earliest knowledge tracing systems borrowed from an unlikely source - chess ranking systems. Psychologist Georg Rasch developed probabilistic models that:

- Assigned each student an _ability parameter_ (θ)
- Rated each question with a _difficulty parameter_ (β)
- Predicted success using: `P(correct) = e^(θ - β) / (1 + e^(θ - β))`

![A formatted version of the formula previously mentioned](/assets/images/article_imgs/rasch_model.png)

**Limitation:** Like chess ratings, it treated knowledge as one-dimensional - impossible for complex subjects.

### 2. First-Generation AI: Bayesian Knowledge Tracing (1990s)

Early intelligent tutoring systems introduced:

- Knowledge Components: Breaking subjects into discrete skills
- Mastery Learning: Tracking each skill separately
- Bayesian Updates: Adjusting beliefs about student knowledge

### 3. The Deep Learning Revolution (2010s)

| Model         | Innovation            | Impact                                |
|---------------|-----------------------|---------------------------------------|
| DKT (2015)    | First use of RNNs     | Tracked knowledge state transitions   |
| DKVMN (2017)  | Memory networks       | Modeled concept relationships         |
| AKT (2020)    | Attention mechanisms  | Captured long-term dependencies       |

![2 diagrams showing a recurrent neural network and an attentive one](/assets/images/article_imgs/nn_architecture.png)

### 4. The Transformer Era (2020s)

Modern systems now leverage:

- Context Windows: Tracking months of learning history
- Multimodal Inputs: Processing text, diagrams, and more
- Zero-Shot Capabilities: Handling unseen questions

**Why This Matters**: Each innovation solved specific limitations - from Rasch's one-dimensional view to today's holistic learning profiles. The next frontier? Unifying these approaches into _foundational knowledge models_ that learn across subjects and languages.

---

## How Hybrid Models Work: A Technical Breakdown

The most advanced education systems today leverage a powerful dual-architecture approach that combines natural language understanding with sophisticated progress tracking. At the core lies a **language understanding layer** powered by models like BERT, which transform educational content—whether math problems, vocabulary questions, or science concepts—into rich semantic vectors that capture actual meaning rather than just question IDs. This enables the system to comprehend content at a deep level and handle multiple languages seamlessly. Working in tandem, the **knowledge tracing layer** employs specialized models like Attentive Knowledge Tracing (AKT) that continuously monitor each student's learning journey, adapting to their unique pace and predicting future performance with remarkable accuracy. Together, these components create an intelligent system that doesn't just present information, but truly understands both the material and the learner—enabling personalized education at unprecedented scale.

## Proven Results: Case Studies That Demonstrate Impact

Real-world applications of hybrid AI models are already delivering transformative results. In one breakthrough case, a language learning app tackling the challenge of tracking knowledge across 70,000+ words implemented a novel solution: using BERT to encode word meanings and feeding these embeddings into a knowledge tracing model. The results were striking—while known words achieved an excellent 0.89 AUC prediction score, the system's ability to handle unseen words improved dramatically from 0.67 to 0.88 AUC after fine-tuning. _“When we paired a language model with knowledge tracing, performance on unseen words jumped dramatically,”_ the developer reported. Similarly promising outcomes emerged from a 2024 mathematics education study, where researchers developed a Language Model-KT (LKT) system that processed actual math problem text (rather than relying on question IDs) and used special tokens to track correct/incorrect responses. This approach consistently outperformed traditional Deep Knowledge Tracing models, demonstrating the power of combining semantic understanding with personalized progress tracking in real educational settings.

### The Competitive Edge: Hybrid vs. Other Approaches

| Approach  | Strengths                          | Weaknesses                     | Best For                |
|-----------|------------------------------------|--------------------------------|-------------------------|
| LLM Only  | Deep language understanding        | No memory of student progress  | General Q&A             |
| KT Only   | Excellent progress tracking        | Can't handle new questions     | Fixed curriculum        |
| Hybrid    | **Both understanding + tracking**  | Higher compute needs           | **Adaptive learning**   |

### The Power of Attentive Knowledge Tracing (AKT)

At the cutting edge of personalized learning systems, Attentive Knowledge Tracing (AKT) represents a significant leap beyond traditional approaches by incorporating transformer-style attention mechanisms - the same architecture that powers modern large language models. At its core, AKT enhances standard knowledge tracing through sophisticated Rasch-based embeddings that simultaneously encode question difficulty, concept relationships, and individual response patterns.

![A diagram showing the Rasch model-based embeddings](/assets/images/article_imgs/rasch_embeddings.png)

Unlike simpler models that process questions in isolation, AKT's attention mechanism dynamically weights the importance of each previous interaction based on its relevance to the current learning moment, mirroring how human tutors selectively focus on pertinent aspects of a student's history. This architecture enables remarkably precise predictions with exceptional accuracy. The performance gains are quantifiable - benchmark results (see image below) show AKT achieving an AUC of 0.8306 compared to DKT's 0.8149 on standard datasets, with even more pronounced advantages (0.8033 vs 0.7689) on complex problem-solving tasks.

![A table comparing the performance of different models](/assets/images/article_imgs/pykt_library.png)

_Liu, Zitao, et al. pyKT: a python library to benchmark deep learning based knowledge tracing models. NeurIPS (2022)_

What makes AKT particularly powerful is its ability to not just predict performance, but to identify which specific historical learning moments most influence current knowledge gaps, enabling targeted remediation that addresses the root causes of misunderstandings rather than just their symptoms. This attention-powered approach represents the current state-of-the-art in balancing computational efficiency with educational insight, though as the transcript notes, properly tuned recurrent models can sometimes match its performance for specific applications.

### Overcoming Implementation Challenges

While knowledge tracing systems offer transformative potential, deploying them at scale presents several practical hurdles that developers must address. The computational demands of advanced models remain significant making real-time implementation challenging for resource-constrained educational institutions. Data requirements pose another barrier - systems need extensive, high-quality interaction data to achieve accurate predictions, exemplified by the vocabulary app's approach of releasing a dedicated test (See image below) to gather initial training data.

Perhaps most critically, these systems must navigate complex privacy considerations when handling sensitive student learning data which is "often private and rarely documented in public datasets." These challenges collectively underscore the importance of developing efficient model architectures, creating ethical data collection frameworks, and implementing robust privacy-preserving techniques to make personalized learning both effective and responsible.

## The Future: Where This Technology Is Heading

The next generation of AI-powered education systems is poised to revolutionize learning with groundbreaking capabilities. These advanced platforms will deliver true multilingual support without requiring translation, seamlessly incorporating extracurricular activities like books read into their adaptive algorithms. Most transformative of all, they'll create comprehensive lifelong learning profiles that evolve alongside students, capturing their entire educational journey from childhood through adulthood. _“This suggests a pathway toward models that encode any activity—not just within one subject,”_ the speaker noted, envisioning systems that could synthesize learning across academic disciplines, languages, and real-world experiences into a unified, ever-growing knowledge map for each individual learner.

---

## The Path Forward: AI-Powered Education Is Here

As we stand at this educational crossroads, the evidence compels us to act. Bloom's 2 Sigma findings have waited nearly forty years for their moment - that moment is now. Through Knowledge Tracing systems, we're witnessing the emergence of AI tutors that don't just approximate human teaching, but systematically surpass it in scalability, consistency, and precision.

The hybrid AI approach represents more than technological progress - it's a fundamental reimagining of how learning systems should operate. By marrying the contextual understanding of large language models with the rigorous student modeling of Knowledge Tracing, we've cracked the code on true personalization at scale.

What excites me most isn't just what these systems can do today, but where they're headed. The next evolution - already visible on the horizon - will track learning across languages, disciplines, and life experiences. Imagine systems that recognize how a student's music training affects their math comprehension, or how their summer internship contributes to their physics understanding.

For educators and technologists ready to lead this change, the tools are waiting. The open-source PyKT library offers immediate access to cutting-edge models that were research projects just years ago. Implementation is no longer the barrier - vision is.

The question isn't whether AI will transform education, but who will shape that transformation. As these technologies mature, they demand our thoughtful application - not just technical expertise, but pedagogical wisdom and ethical consideration. The future of learning isn't coming; it's being built right now, and it's ours to design well.
