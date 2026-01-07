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

It is now common for developers to adopt libraries that aid their software development. Libraries provide pre‑tested, high‑quality functionality that can be easily integrated. 
These libraries frequently depend on other libraries, creating a complex web of interdependencies—a hallmark of the software ecosystem. 

The primary problems associated with libraries are bugs and, more importantly, security vulnerabilities. Studies have shown that outdated libraries pose significant risks to attackers, giving rise to initiatives such as the Global Software Supply Chain (GSSC) to protect libraries from supply‑chain attacks.

With the rise of generative AI in the developer workflow, tools like ChatGPT, Gemini and others are increasingly used to assist with daily tasks. However, using pre‑trained models presents challenges related to contextual understanding. Even agentic models often produce numerous errors during generation, potentially incurring significant time and monetary costs for developers.

Bringing together the Mining Software Repositories, Program Comprehension, and AIware software engineering communities, we invite students, researchers and industry to put their knowledge of new GenAI techniques to generate software libraries.  

## Competition Format

### Task

The competition challenges participants to design and present different GenAI techniques capable of generating software libraries. The scientific contribution is to evaluate how current AI models and workflows perform when asked to reproduce or adapt the behavior, structure, or interface of an existing library. 

In detail, participants are asked to complete the following task:

> *Generate a library software repository or library that is functionality similar or better than the existing human-written repository.*

Different to benchmarks and from a software engineering perspective, teams should demonstrate reproducibility, practical application and how these techniques are possible in a live demonstration. Novelty must be emphasized in the submission abstract and all scripts and methods will be made available. 

Participants may use any GenAI or strategies they prefer—fine-tuning, prompting strategies, program synthesis, RAG pipelines, multi-agent architectures, or any hybrid approach. The competition encourages creativity and experimentation.

Participants will develop demos for and end-to-end generation, testing, and maintenance of these AI-generated libraries, and to quantitatively compare their performance and quality against human-written counterparts. 

### Dataset

We will provide a listing of all package libraries from seven ecosystems (Crates, Go, Maven, NPM, PHP, PyPI, RubyGems). Participants are also encouraged to bring their own domain-specific data.  Participants may extend or refine the evaluation.

| Ecosystem | Packages | Source |
|-|-|-|
| Crates | 207,981 | https://crates.io |
| Go | 2,214,193 | https://index.golang.org |
| Maven     | 657,929 | https://zenodo.org/records/7553341 |
| NPM       | 3,706,503 | https://zenodo.org/records/7553341 |
| PHP       | 431,456 | https://packagist.org |
| PyPI      | 705,908 | https://pypi.org/simple |
| RubyGems  | 188,204 | https://rubygems.org/names |
| **Total**     | 8,112,179 | -- |

### Abstract and Video Submission Requirements

Each team must submit a short abstract and a mandatory video (up to 5 minutes) demonstrating their technique. The video must show novelty, key techniques used and the end-to-end generation. Optional links to repositories or demos are welcome.

### On site event

The competition will be held as a half-day event at FSE/AIWare 2026. Accepted teams will first present their approach through posters and open demo sessions, allowing attendees to interact with the tools and ask questions about the method. After the presentations, organizers will randomly select a set of libraries from the dataset. Teams will then attempt to apply their technique to these unseen targets. This live generation challenge is designed to test the robustness and generality of the proposed workflows.

Teams are encouraged to use their own resources (local or cloud), but for inclusiveness, we are open to providing cloud-computing resources for under-represented groups. We may also consider online participation for under-represented groups.

### Judging and Awards

Judges from the program committee will evaluate submissions based on novelty, feasibility of execution, similarity to human-written library and presentation. The assessment will consider both the submitted materials and the on-site performance. A combination of committee judgement and on-site voting may be used to recognise excellence. The best contributions will receive a certificate from the competition chairs.
