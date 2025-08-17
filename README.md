# Philosophy of Interpretability Papers

A curated reading list for researchers in the Philosophy of Interpretability.

## Contents

- [Contents](#contents)
- [About](#about)
- [Philosophy of Mechanistic Interpretability](#philosophy-of-mechanistic-interpretability)
- [Philosophy of pre-Mechanistic Interpretability](#philosophy-of-pre-mechanistic-interpretability)
- [Non-Mechanistic Interpretability Paradigms](#non-mechanistic-interpretability-paradigms)
- [Philosophy of Explanations](#philosophy-of-explanations)
- [General Philosophy of Science](#general-philosophy-of-science)
- [Core Interpretability](#core-interpretability)
- [Evaluating Explanations](#evaluating-explanations)
- [Interpreting Representations](#interpreting-representations)
- [Interpreting Computations](#interpreting-computations)
- [Causal Abstractions](#causal-abstractions)
- [Limits of Interpretability](#limits-of-interpretability)
- [Human Studies in Interpretability](#human-studies-in-interpretability)
- [Neuroscience and Cognitive Science](#neuroscience-and-cognitive-science)
- [The Strange Science](#the-strange-science)
- [Other](#other)


## About

Interpretability is the study of producing scientific explanations of
artificial neural networks.
The Philosophy of Interpretability is concerned with understanding the methods and implications of interpretability research and has intersections with epistemology,
Philosophy of Mind, Philosophy of Science, Measurement, Philosophy of Neuroscience,
Cognitive Science and many other disciplines.

---

In this repo, links are organised by topic and have explanations so you can
decide what you would like to read. Especially recommended links are starred 🌟

Star this repository to see the latest developments in this research field.

We accept contributions! We strongly encourage researchers & practitioners to
make pull requests with papers, approaches and explanations that they feel
others in the community would benefit from 🤗

<!-- Ordered by topic, then date published -->

## Philosophy of Mechanistic Interpretability

🌟 **Mathematical Philosophy of Explanations in MechInterp, Ayonrinde & Jaburi (2025)**
[pdf](https://arxiv.org/pdf/2505.00808)

> Details a foundation for MechInterp research through an explanatory and information-theoretic lens. Also outlines a technical definition for MechInterp and the limits which follow from this project.

**Propositional Interpretability in Artificial Intelligence, Chalmers (2025)**
[pdf](https://arxiv.org/abs/2501.15740)

> Philosophy of Mind heavyweight David Chalmers lays out a research agenda for interpretability inspired by Psychosemantics and Radical Interpretation. He argues that a goal of interpretability should be to provide a thought log which contains a series of statements which can be understood as Propositional Attitudes - that is attitudes that the AI system holds towards propositional statements expressed in natural language.

<!-- Explaining AI through mechanistic interpretability (Crook) -->
<!-- Matt Farr paper -->

## Philosophy of pre-Mechanistic Interpretability

**The Mythos of Model Interpretability, CMU: Lipton (2016)**
[pdf](https://arxiv.org/abs/1606.03490)

> An early attempt to understand how the opacity problem in deep learning models affects the way that we seek explanations of them and how interpretable AI might function.

**Towards A Rigorous Science of Interpretable ML, Google: Doshi-Velez & Kim (2016)**
[pdf](https://arxiv.org/pdf/1702.08608)

> Discusses early waves of interpretability research and providing a taxonomy for the evaluation of interpretability - they see interpretability as a domain that is primarily evaluated based on pragmatic applications in task contexts. They also lay out (at the time) Open Problems in Interpretability Science, Theory and Practise.

**Towards falsifiable interpretability research, FAIR: Leavitt & Morcos (2020)**
[pdf](https://arxiv.org/pdf/2010.12016)

> Surveys the problems of saliency maps and single neuron based methods and concludes that the problem was that the hypotheses being tested were not sufficiently falsifiable. They set out a framework for strongly falsifiable interpretability research, mostly in the form of how to structure highly specific hypotheses to stop researchers from fooling themselves.

## Non-Mechanistic Interpretability Paradigms

**Representation Engineering, CAIS: Zou et al (2023)**
[pdf](https://arxiv.org/pdf/2310.01405)

> Instead of MechInterp, Representation Engineering takes a macroscopic view of representations and ignores computations. They suggest that this is more tractable in some use cases. They take inspiration from complex systems and argue that MechInterp as traditionally practised may find it difficult to understand emergent phenomena. Though their characterisation of MechInterp seems confused in places, their approach is generally useful and compatible with understanding representations in MechInterp (though we may need to go beyond purely analysing representations to truly understand and intervene on AI models).

**Agentic Interpretability, Google: Kim et al (2025)**
[pdf](https://arxiv.org/pdf/2506.12152)

> They suggest that LLMs provide a new interaction opportunity for interpretability: instead of an interpretability method which gives a single response to the human, there can be a multi-turn interaction which results in the human understanding the AI system. This is useful because for superhuman (or otherwise non-human) concepts that AIs have, teaching them to humans may require more interaction. They describe their methods as "human-entangled-in-the-loop". A useful framing which neatly solves the problem of the [Informativeness-Compression trade-off](https://link.springer.com/article/10.1007/s43681-025-00733-5) in a similar way as [AI Debate](https://arxiv.org/abs/1805.00899) by pruning down the tree to cruxes. See also [here](https://openreview.net/pdf?id=O4LaRH4zSI)

<!-- CoT Interp... -->

## Philosophy of Explanations

🌟 **SEP on Explanations, SEP: Woodward & Ross (2021/2023)**
[website](https://plato.stanford.edu/entries/scientific-explanation/),
[website](https://plato.stanford.edu/entries/causal-explanation-science/)

> Two SEP articles on Scientific Explanations and Causal Explanations (the kind of explanation that we seek in Mechanistic Interpretability). These are great primers on the core concepts of explanations. Given that the project of Mechanistic Interpretability is to produce explanations of neural networks, knowing the target is about understanding explanations.

**What Good Is An Explanation, Cambridge: Lipton (2021)**
[pdf](https://www.hps.cam.ac.uk/files/lipton-what-good.pdf)

> A wonderful paper about explanation, the types of explanations and how explanations lead to understanding. Less directly applicable to MechInterp but generally valuable.

**Explanation: A mechanist alternative, Bechtel & Abrahamsen (2005)**
[pdf](https://www.sciencedirect.com/science/article/abs/pii/S1369848605000269)

> An exposition of (Causal-)Mechanistic Explanations focusing on Biology and contrasting to earlier nomological approaches to explanation within the Philosophy of Science.

<!-- Craver book. etc. -->

## General Philosophy of Science

**Structure of Scientific Revolutions, Kuhn (1962)**
[pdf](https://www.lri.fr/~mbl/Stanford/CS477/papers/Kuhn-SSR-2ndEd.pdf)

> The classic Kuhn text which influenced much research in the Philosophy of Science. He introduces the "paradigms" view of Science of cycles of *Normal Science --> Anomalies --> Crisis --> Paradigm Shift --> New Normal Science*. Researchers understanding how to best support MechInterp may understand their work as contributing to Normal Science (e.g. optimising circuit-finding algorithms or SAEs), pointing out anomalies and inconsistencies which can cause a crisis (e.g. understanding non-linearly represented features) and then using this new evidence to create new paradigms. See also the SEP article [here](https://plato.stanford.edu/entries/thomas-kuhn/)

🌟 **The Beginning of Infinity, Deutsch (2011)**
[pdf](https://avalonlibrary.net/ebooks/David%20Deutsch%20-%20The%20Beginning%20of%20Infinity%20-%20Explanations%20that%20Transform%20the%20World.pdf)

> An incredible book on the Philosophy of Science and Epistemology by one of the leading Quantum Computing researchers of our time. The book's subtitle is "Explanations that Transform the World" which is as much a pitch for interpretability as for the natural sciences in general. In particular Deutsch introduces the concept that good explanations are hard-to-vary (see also [here](https://arxiv.org/abs/2505.01372)) and emphasises that what we seek for science is not merely predictive apparatus but falsifiable explanatory theories.

<!-- Popper -->

<!-- Thiel, Zero To One -->

## Core Interpretability

🌟 **Mechanistic Interpretability for AI Safety--A Review, Amsterdam: Bereska & Gavves (2024)**
[pdf](https://arxiv.org/pdf/2404.14082)

> A survey paper of Mechanistic Interpretability techniques and practises. Very well illustrated.

🌟 **Zoom In: An Introduction to Circuits, OpenAI: Olah et al (2020)**
[html](https://distill.pub/2020/circuits/zoom-in/)

> Arguably the first paper to outline the core ideas of Mechanistic Interpretability.

<!-- Mathematical Framework of Transformer Circuits -->

<!-- Toy Models of Superposition, 🌟 Biology of LLMs -->

<!-- Grokking Modular Arithmetic -->

## Evaluating Explanations

<!-- Compact proofs of model performance via mechanistic interpretability, MIB,
Hypothesis testing the circuit hypothesis in LLMs -->

**Explanatory Virtues Framework, Ayonrinde & Jaburi (2025)**
[pdf](https://arxiv.org/pdf/2505.01372)

> An application of Theory Choice to explanations in Mechanistic Interpretability from the Bayesian, Kuhnian, Deutschian, and Nomological lenses.

## Interpreting Representations

🌟 **Interpretability as compression: (MDL-SAEs), Ayonrinde et al (2024)**
[pdf](https://arxiv.org/pdf/2410.11179)

> An information-theoretic framework for principled unsupervised feature extraction using Interpreter Models (here SAEs).

🌟 **Operationalising Representation in Natural Language Processing, Harding (2023)**
[pdf](https://www.journals.uchicago.edu/doi/abs/10.1086/728685?journalCode=bjps)

> A translation of the core ideas of Representation in the philosophy literature into the NLP/ML framework. Provides the 3 criteria for Representation: Use, Information and Misrepresentation.


<!-- 🌟 Towards Monosemanticity, Projecting assumptions (Demba) -->

## Interpreting Computations

🌟 **Stochastic Parameter Decomposition, Goodfire: Bushnaq et al (2025)**
[pdf](https://arxiv.org/pdf/2506.20790)

> Where much interpretability has focused on understanding representations, true Mechanistic Interpretability must understand step-by-step mechanisms which includes understanding Computations. SPD is a core step in this direction and a large improvement upon the earlier [APD](https://arxiv.org/abs/2501.14926) method. Their approach to understanding Computations fit under the umbrella of (Linear) Parameter Decomposition and takes seriously interpretability in weight space (computations) rather than in activation space (representations).

<!-- SEP?/MOLT -->

## Causal Abstractions

🌟 **Causal abstraction: A theoretical foundation for mechanistic interpretability, Stanford: Geiger et al (2023)**
[pdf](https://arxiv.org/pdf/2301.04709)

> The canonical paper which provides the modern Causal Abstractions foundation for Mechanistic Interpretability.

<!-- Pearl (Causality), Lewis? -->

## Limits of Interpretability

<!-- The computational complexity of circuit discovery for inner interpretability,
An Interpretability Illusion for BERT,
Everything, everywhere, all at once: Is mechanistic interpretability identifiable?
-->

<!-- ## Information Theory and Complexity Theory -->

<!-- Classic texts, Nora's paper -->

<!-- ## Singular Learning Theory -->

<!-- Position paper -->

## Human Studies in Interpretability

**Interpretability is a bidirectional communication problem, UK AISI: Ayonrinde et al (2025)**
[pdf](https://openreview.net/pdf?id=O4LaRH4zSI)

> Analyses the human-interpretation part of interpretability and shows puts forward
> methods for humans to increase their understanding of explanations of model internals.
> A core component of this project is "Concept Enrichment": humans learning new concepts (neologisms)
> by interacting with the internals of AI systems.

<!-- 🌟 Chess (Schut et al) -->

## Neuroscience and Cognitive Science

<!-- Explanatory models in neuroscience (Cao), Shea, Vision (Marr) -->

**An Inner Interpretability Framework Inspired by Cognitive Neuroscience, Vilas et al (2024)**
[pdf](https://arxiv.org/pdf/2406.01352)

> Details the shared problems in interpretability and cognitive neuroscience
> and lays out a neuroscience-inspired way forwards. A nice bridging of approaches.

## The Strange Science

🌟 **Mathematical Philosophy of Explanations in MechInterp, Ayonrinde & Jaburi (2025)**
[pdf](https://arxiv.org/pdf/2505.00808)

> Details a foundation for MechInterp research through an explanatory and information-theoretic lens. Also outlines a technical definition for MechInterp and the limits which follow from this project.

**Explanatory Virtues Framework, Ayonrinde & Jaburi (2025)**
[pdf](https://arxiv.org/pdf/2505.01372)

> An application of Theory Choice to explanations in Mechanistic Interpretability from the Bayesian, Kuhnian, Deutschian, and Nomological lenses.

**Interpretability is a bidirectional communication problem, UK AISI: Ayonrinde et al (2025)**
[pdf](https://openreview.net/pdf?id=O4LaRH4zSI)

> Analyses the human-interpretation part of interpretability and shows puts forward
> methods for humans to increase their understanding of explanations of model internals.
> A core component of this project is "Concept Enrichment": humans learning new concepts (neologisms)
> by interacting with the internals of AI systems.

## Other

**The Urgency of Interpretability, Anthropic: Amodei (2025)**
[html](https://www.darioamodei.com/post/the-urgency-of-interpretability)

> Provides a(n opinionated) history of interpretability and gives a moral case for why interpretability is required from the CEO of one of the frontier AI labs.

<!-- 🌟 Sparsify (Sharkey), Understanding as compression (Wilkenfeld), MechInterp Needs Phil, 🌟 MechInterp is not pre-paradigmatic, Natural Kinds, Platonic Representation Hypothesis -->

<br>

---

<br>

Thanks for reading, if you have any suggestions or corrections please submit a
pull request! And please hit the star button to show your appreciation.
