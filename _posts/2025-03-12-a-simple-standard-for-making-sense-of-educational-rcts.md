---
layout: default
title: "ERCT: A Simple Standard for Making Sense of Educational RCTs"
date: 2025-07-05
desc: "I was very happy to find so many papers on education that used Randomised/Randomised Control Trials. But after the first 20 papers, I stopped being happy and started to feel tired. Many papers contained logical black holes, compromising their conclusions. I kept seeing the same problems, so I built a system to analyse any educational paper."
image: './assets/images/article_imgs/article1_header.jpeg'
---

# ERCT: A Simple Standard for Making Sense of Educational RCTs

When you think about how to make education better, it's helpful to read good educational research papers. I was very happy to find so many papers on education that used Randomised/Randomised Control Trials. But after the first 20 papers, I stopped being happy and started to feel tired.

Many papers contained logical black holes, compromising their conclusions. I kept seeing the same problems:

- Custom metrics where they measure “something” but not what actually matters
- Very short studies
- Control groups that were barely described

So, I created a list of simple checks—12 things I look for to better understand how much I can trust a paper’s results—and built and trained an AI agent to use these 12 criteria to analyse any educational paper we give it.

[ERCT – Educational Randomised Controlled Trial (ERCT) Standard](https://erctpapers.com/)

---

## The Challenge of Educational Research

Let’s be honest: figuring out what really works in education is hard. Like, really hard. It’s not like testing a new lightbulb - you can’t just flip a switch and see immediate, clear results. We’re dealing with complex human beings, diverse classrooms, and a million interacting factors.

Think of it like trying to understand why one plant grows taller than another in a tangled, overgrown garden. Is it the soil? The sunlight? The whispered encouragement you give it every morning? (Okay, maybe not that last one… but you get the idea.)

## The Promise and Pitfalls of RCTs

When I started digging deep into educational research, I looked to Randomised Controlled Trials for solid ground. RCTs are often called the “gold standard,” the closest thing to a controlled lab experiment in the messy world of education: randomly assign groups to an intervention or control, then compare outcomes.

Sounds perfect, right? Well… not always. I ran into RCTs that felt flimsy, even while following the rules:

- Interventions that lasted a week.
- Outcomes measured with custom, narrow metrics.
- Control groups barely described.
- Designs that didn’t account for peer effects or spillovers.

It was like reading a recipe that said, “Bake until done.” Helpful? Not so much.


I needed a quick, practical way to assess whether a study was designed robustly enough to make its findings useful.

 Not “perfect” (perfection is unattainable in education research), but solid enough to inspire confidence. I wasn’t trying to declare winners or say whether an intervention “worked” universally. I just wanted to know whether the study minimised the most common pitfalls.

## Introducing the ERCT Standard

That’s how the ERCT Standard was born: a personal checklist of 12 criteria, organised into three levels—a series of sanity checks for educational RCTs. A few examples:

- **Duration**: Did the study run for a meaningful stretch (term/year) to detect real effects?
- **Randomisation unit**: Did they randomise at the class or school level to avoid student-to-student contamination?
- **Breadth of outcomes**: Did they look at impact on all core subjects (not only the one the intervention targets), with validated exams rather than custom metrics?

I built and trained an AI agent to apply these 12 criteria consistently. To reduce errors, we use detailed prompts, multiple LLM checks, manual reviews, and even a Deep Research mode when needed. It’s not magic - just a disciplined way to apply the same lens to many studies quickly.

![A 3 by 4 grid displaying the ERCT framework](/assets/images/article_imgs/erct_framework.jpeg)

---

## Important Considerations and Disclaimers

- This is a humble tool. It’s not the ultimate authority on RCT quality, just a set of criteria I found helpful (and designed with LLM evaluation in mind).
- It’s not about judging researchers. Educational studies are hard and resource-constrained. Many researchers know exactly how to improve their designs but lack funding or access. The studies evaluated here are valuable contributions regardless of their ERCT score.
- It’s specifically for educational RCTs. It doesn’t apply to meta-analyses, qualitative research, or non-education fields. And it doesn’t tell you whether an intervention “worked” for your context.
- Mistakes are possible. If you spot an error or disagree with an assessment, please let me know. I’ll review and correct promptly.

## A Lens, Not a Verdict

Think of the ERCT Standard like a pair of glasses. It can help you see the details of an RCT a little more clearly, but it won’t tell you what to do next. That judgment calls for your context, your goals, and your professional experience.

![3 examples of studies evaluated with ERCT](/assets/images/article_imgs/erct_studies.jpeg)

## A Call for Better Educational Research

Ultimately, I hope this standard - and the evaluations based on it - spark a broader conversation about how we design, conduct, and interpret educational research. Like Semmelweis and his handwashing, impactful progress often challenges our assumptions and pushes us to rethink what we thought we knew.

The goal is better. Perfection is unachievable - but that shouldn’t stop us from improving the rigor and usefulness of educational studies.

[Explore the criteria and browse evaluated papers](https://erctpapers.com/)