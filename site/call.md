---
layout: page
title: Call for Participation
---

## Important Dates

| Date | Event |
|-|-|
| January 9th, 2026 – February 27th, 2026 | Rolling Abstract Period |
| March 21st, 2026 | Full Paper Deadline |
| March 27th, 2026 | Full Paper Notification |
| April 2nd, 2026 | Camera-ready |
| July 6th, 2026 | On-site Competition Event at FSE/AIWare 2026 |

## Brief

It is common for developers to adopt libraries that aid their software development. Libraries provide pre‑tested, high‑quality functionality that can be easily integrated. 
These libraries frequently depend on other libraries, creating a complex web of interdependencies—a hallmark of the software ecosystem. However, library use introduces a risk of bugs and, more importantly, security vulnerabilities. Studies have shown that outdated libraries pose significant risks to attackers, giving rise to initiatives such as the Global Software Supply Chain (GSSC) to protect libraries from supply‑chain attacks.

With the rise of generative AI in the developer workflow, tools like ChatGPT, Gemini and others are increasingly used to assist with daily tasks. However, using pre‑trained models presents challenges related to contextual understanding. Even agentic models often produce numerous errors during generation, potentially incurring significant time and monetary costs for developers. Bringing together the Mining Software Repositories, Program Comprehension, and AIware software engineering communities, we invite students, researchers and industry to put their knowledge of new GenAI techniques to generate software libraries.  

The **ODAI-LIB Challenge 2026 (On-Demand Libraries: Prompting to Generate an Ecosystem Library)** is a competition held as part of the FSE-AIWare 2026 Competition Track. The challenge explores how generative AI techniques can be used to dynamically generate software libraries on demand, addressing challenges related to software ecosystem dependencies, security vulnerabilities, and maintenance overhead.

## Task

> *Generate a library software repository or library that is functionality similar or better than the existing human-written repository.*

The competition challenges participants to design and present different GenAI techniques capable of generating software libraries. Rather than focusing on traditional benchmarks, the competition emphasizes practical feasibility and real-world applicability. Participants are invited to demonstrate how their AI-based approaches can generate functional, high-quality libraries using real data from multiple software ecosystems. The goal is to better understand the capabilities and limitations of current generative AI techniques when applied to realistic software engineering scenarios.

Participants may use any GenAI or strategies they prefer—fine-tuning, prompting strategies, program synthesis, RAG pipelines, multi-agent architectures, or any hybrid approach. The competition encourages creativity and experimentation.

Participants will develop demos for end-to-end generation, testing, and maintenance of these AI-generated libraries, and are asked to quantitatively compare their performance and quality against human-written counterparts. 

## Submission Guidelines

Submission link: [ODAI-LIB Challenge Submission Portal (EasyChair)](https://easychair.org/conferences/?conf=odailib2026)

All submissions must be original and must not be simultaneously submitted to another journal or conference.

The ODAI-LIB Challenge follows a two-stage submission process:

#### Stage 1: Abstract and Video Submission

Each team must submit a short abstract together with a mandatory demo video (up to 5 minutes).The video must demonstrate the novelty of the approach, the key techniques used, and the end-to-end library generation workflow.Optional links to code repositories or supplementary material are welcome.

#### Stage 2: Full Paper Submission

After notification, accepted teams must submit a 2–4 page paper describing their approach in more detail. The paper should explain the generation workflow, AI models and strategies used, and any preliminary evaluation.The mandatory video link must be included in the paper.

**Important:** Posters and live demos are part of the on-site competition event and are not separate submission categories.

## Venue

The ODAI-LIB Challenge 2026 will be held in person as part of the FSE-AIWare 2026 Competition Track at FSE 2026, on July 6th, 2026, in Montreal, Canada. Accepted teams will first present their approach through posters and open demo sessions, allowing attendees to interact with the tools and ask questions about the method. After the presentations, organizers will randomly select a set of libraries from the dataset. Teams will then attempt to apply their technique to these unseen targets. This live generation challenge is designed to test the robustness and generality of the proposed workflows.

Teams are encouraged to use their own resources (local or cloud), but for inclusiveness, we are open to providing cloud-computing resources for under-represented groups. We may also consider online participation for under-represented groups.

## Dataset

Github link: [ODAI-LIB Challenge Dataset Repository](https://github.com/ODAI-LIB/ODAI-LIB-Dataset)

We provide a listing of all package libraries from six ecosystems (Crates, Go, Maven, NPM, PHP, PyPI). Participants are also encouraged to bring their own domain-specific data, and may extend or refine the evaluation.

| Ecosystem | Mining Date | Number of Packages |
|----------:|------------:|-------------------:|
| Crates    | 2025-12-01  | 207,981            |
| Go       | 2025-12-15  | 2,164,784          |
| Maven    | 2025-12-14  | 751,350            |
| NPM      | 2026-01-09  | 3,750,520          |
| PHP      | 2025-12-01  | 431,456            |
| PyPI     | 2025-11-30  | 705,908            |


## Judging and Awards

Judges from the program committee will evaluate submissions based on novelty, feasibility of execution, similarity to human-written library and presentation. The assessment will consider both the submitted materials and the on-site performance. A combination of committee judgement and on-site voting may be used to recognise excellence. The best contributions will receive a certificate from the competition chairs.
