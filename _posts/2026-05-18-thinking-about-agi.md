---
title: Thinking About AGI Under Epistemic Humility
tagline: A working framework, and where my research fits
date: 2026-05-18
description: A working framework on what constrains AI, where its real ceiling lies, and how my research fits.
---

## Preface

For some time now I have been turning over a question more basic than "when will AGI arrive": **what constrains the development of artificial intelligence, what cognitive tools do we have for thinking about it, and where is its real ceiling?**

What follows is a snapshot of where that thinking currently stands. It is not a complete theory and it does not try to make confident predictions. I call it a *working framework* — a set of positions I currently hold, the logical relations between them, and the open questions it ends on. Writing it down is partly for myself, to see my own commitments clearly, and partly so that the framework can be criticized and revised.

The framework moves from an epistemic starting point through a series of consequences: imitation is the only verifiable path we have, AGI therefore becomes the operative target, surpassing humans under that target requires both cognitive and embodied capability, and digitization is — as far as I can currently imagine — the only viable route there. Self-iteration is left as the boundary of the framework rather than something inside it.

I want to flag upfront that much of what follows is personal conviction rather than rigorously argued position. I have tried to mark the places where I am committing to a view I cannot fully defend.

---

## I. The epistemic starting point

We do not really understand what "intelligence" is.

There is still no widely accepted definition. Every judgment about whether AI has reached human level is *operational* — it uses task performance as a proxy, not any essential theory of intelligence. This means we are building something whose nature we do not understand.

One layer deeper: **humans cannot step outside their own cognition to imagine a complete form of intelligence**. Every picture we have of "what intelligence could be like" comes from human intelligence itself. This is not rhetorical modesty but a structural constraint — we are both the makers and the judges, and our standards of judgment can only come from us.

Philosophically, this connects to an older line of thinking. The moment the subject "I" is captured by language — the moment one says the pronoun — it has already been reconstructed by the symbolic system; the pre-linguistic subject keeps slipping out from under the linguistic "I" that tries to name it. The "I" that speaks can never fully coincide with the "I" that is spoken. I am being deliberately vague about the philosophical lineage here — variants of this thought show up in Wittgenstein, Lacan, and others — but the structural point is what matters: if something like this holds, then humans may never be able to step outside their own coordinate system to look at intelligence from the outside. We cannot pin down what intelligence really is. We may not even be able to understand the origin or nature of our own intelligence and consciousness.

From this starting point, AI development sits under two coupled curves:

- A **theoretical ceiling** set by humanity's collective understanding of intelligence. We can only build what we can understand to build.
- An **engineering frontier** set by data, compute, and methodology. This determines how close we are to that ceiling at any given moment.

The two curves are coupled non-linearly, and sometimes the influence runs backwards — engineering breakthroughs like the Transformer can in turn advance our theoretical understanding. Current systems are nowhere near the theoretical ceiling, but it is hard to tell which curve is the binding constraint at any given moment.

This leads to a distinction I think is important: **AGI is not the same as "intelligence."** AGI is a yardstick calibrated to the human perspective — can it do what humans can do — not a definition of intelligence as such. For now, the most we can sensibly discuss is AGI. "Intelligence itself" sits beyond what we can talk about with any confidence. Everything that follows assumes this.

---

## II. Imitation as the only verifiable path

If we cannot understand intelligence from the outside, then in building AI we have no choice but to work from the inside — taking human intelligence as the template.

**Imitating human intelligence is the only verifiable, operational path we currently have.** We at least recognize human intelligence when we see it, so we can measure progress. Other paths are not impossible in principle — pure mathematical optimization, evolutionary search, formal optimal-agent theories — but none of them comes with a reliable way to tell whether we have succeeded. How would we know an intelligence that does not resemble human intelligence had actually arrived?

Imitation can happen at different levels: data, capability, mechanism, or goal. The current mainstream is data and capability imitation (LLMs trained on human text, evaluated on tasks humans are good at). My own preference would be for **mechanism imitation** as the deeper direction — if we do not imitate the mechanism, controllability and interpretability suffer. But I should be honest that today's deep learning is only loosely inspired by neurons, not a genuine mechanism-level imitation. That is more an unfulfilled promise than a current reality.

This path naturally yields AGI as the goal: if we use a human standard to measure progress, the destination is necessarily defined by that same standard. This is not circular — it is the internal consistency between path and target.

**A structural observation, which I want to flag as my own view rather than something I can rigorously argue:** human intelligence is not a single capability. It seems to me a product of long co-evolution among several deeply entangled dimensions — embodied interaction with the physical world, language with its capacity for fiction and imagination, group collaboration and shared intentionality, and probably others I have not thought through carefully enough. This framing is loosely influenced by the kind of synthesis Yuval Harari offers in *Sapiens* — the suggestion that what made our species distinctive was not raw cognitive horsepower but the capacity to weave shared fictions and to coordinate, through language and gossip, at scales no other animal manages. I do not want to lean on Harari as if he had settled the question; his account is contested in academic anthropology and the deeper roots lie in earlier work (Dunbar's, for instance, on language and group size). I use it mainly as a reminder that "human intelligence," even when we point at it, is already a bundle of things tangled together. To be recognized as AGI under the human yardstick, a system probably needs to cover most of these. I do not want to make this a strict "all-or-nothing" claim — but missing any of them would, I think, hurt its standing on the AGI yardstick significantly.

---

## III. Surpassing humans, and the cognitive-embodied asymmetry

Within the dimensions being imitated, AI can be **an order of magnitude stronger than any individual human**. The mechanism I see has three components:

- **Data scale** — aggregating knowledge far beyond what any individual can hold
- **Iteration speed** — through digitization, learning is no longer bound by physical time
- **System size** — the system can be many times larger than a human brain

This is *vertical scaling within the human coordinate system*, not a breakthrough out of that system. It explains why LLMs already surpass most humans (and sometimes experts) on certain tasks — they aggregate the human textual corpus and then scale that up — while the capability dimensions remain those of human intelligence.

**But there is a critical asymmetry here:**

The **cognitive and symbolic layer** has already been digitized at scale, and LLMs have achieved partial surpassing in it. This is itself an empirical proof of concept: the route "digitize a domain → AI surpasses humans in it" has already been walked through, in the cognitive case.

The **embodied layer** lags far behind in digitization. Real-world physical interaction is locked into physical time. Learning to fry an egg involves irreducible physical constants — the time it takes the pan to heat, the egg to set, the kitchen to be cleaned after a failure. Any scheme that learns directly in the real world cannot exceed humans by orders of magnitude on the speed dimension; it iterates in the same time scale we do.

Combine this with the structural observation in II: reaching AGI requires both the cognitive and the embodied to be in place. Which means **surpassing in the embodied layer is on the critical path to AGI, and there is no way around it**.

---

## IV. Digitization as a commitment under limited imagination

So how does surpassing happen in the embodied layer? This is a real open problem and I do not have an answer. But here the framework makes a commitment under the limits of what I can currently imagine:

**Digitization is the only viable route I can think of.**

Concretely this might take the form of high-fidelity physical simulation, world models, sim-to-real transfer, synthetic data, multi-agent self-play, and — going one level deeper — **digitization of social processes** (encoding interaction, collaboration, and cultural formation in a form that can be iterated faster than the human time scale, to address the group dimension).

There are three reasons I commit to this:

First, **the success of LLMs in the cognitive layer is itself an existence proof of "surpassing through digitization."** It is not abstract reasoning; it has already happened once. There is some reason to believe an analogous route can work in the embodied case.

Second, **the physical world itself is locked into physical time** — this is a hard constraint, not a failure of imagination. Any scheme that uses real-world time as its learning clock cannot, in principle, surpass humans by an order of magnitude.

Third, **a path that relies purely on human-produced data is hitting its own ceiling.** The current generation of LLMs has succeeded by absorbing a corpus that humanity built up over thousands of years of accumulated thought — and increasingly, by augmenting that corpus with AI-generated synthetic data. But the human-produced part is itself a finite resource, generated under the same physical-time constraint as everything else humans do; we are already approaching its limits. And even continuing to collect new human data would not really change the picture: new human data is produced at the speed humans can produce it, which means it inherits exactly the physical-time constraint from the second reason above. Refilling the pool at human speed cannot, by the iteration-speed argument in section III, deliver order-of-magnitude surpassing — it just keeps us in the same regime, more slowly. The AI-generated portion, meanwhile, is almost certainly biased — it inherits the distribution, blind spots, and failure modes of whatever model produced it, so recursive training on it risks reinforcement rather than genuine expansion. This is another reason digitization needs to go beyond text. **A digitized world — or what some are starting to call the metaverse — is a more promising direction than synthetic-from-text**, because new training signal can be produced under faster-than-physical-time dynamics from environments that have their own structure, rather than recycled from a source that is itself running thin.

The commitment has two layers, and the distinction matters:

- A **firmer claim**: the real-world-only path does not lead to large-scale surpassing. This is grounded in physical time as a hard constraint, and I do not see how to revise it.
- A **softer claim**: the specific digitization schemes I can currently name (sim-to-real, world models, digitized worlds, etc.) are my best guesses, but there may be forms of digitization I have not imagined. The one thing I am willing to assert is that **whatever new form turns out to work, it will not be in the physical world.**

This layering matters because it means the framework does not collapse if some specific technical route (say, sim-to-real) fails to converge. That would only refute a particular scheme, not the direction. At the same time, the framework cannot be rescued by "just build a better real-world robot." The constraint is on the time clock, not on the hardware.

---

## V. Self-iteration as the boundary

Everything above assumes that AI remains a human invention, bound to the human coordinate system.

There is one exception I am bracketing: **if AI reaches the point of genuine self-iterative evolution, it might step outside the human coordinate system entirely and become something whose form I cannot prefigure.**

This is the boundary of the framework, not a position inside it. It means every prediction above carries an implicit "before self-iteration occurs" timestamp. Once that threshold is crossed, a different framework would be needed for whatever comes next — and that framework is not one I can write now, because by definition its subject is outside what I can currently imagine.

**For the present era, the period before self-iteration is what I want to focus on.**

---

## My research directions

The point of building this framework is, ultimately, to clarify what I want to work on, what I am capable of working on, and what I should work on. It points to one aspirational direction I cannot yet reach, and two parallel directions I can work on now.

**The aspirational direction — advancing the foundational theory of intelligence itself.** This is the work of Layer I. Until our understanding of intelligence advances, all AI work is constrained by the engineering ceiling that arrives once compute and data are pushed to their limits. This is the direction I would most want to contribute to eventually, but I do not yet have the standing to touch it — it requires not just technical depth but serious grounding in cognitive science, neuroscience, and the philosophy of mind. I list it here so I do not forget it exists.

**Two parallel directions I can work on now.** I treat the next two as parallel rather than sequential — they address different aspects of the same problem and feed into the same ultimate target. One is at the level of architecture and representation; the other is at the level of the training environment. Both are needed.

**Foundational innovation in embodied and non-language modalities.** The framework predicts the bottleneck is in the embodied layer, and what that layer needs is not more scale but breakthroughs in basic architecture and methodology — work analogous to what ResNet and MAE did for vision (Kaiming He's work is my reference point here). How embodied perception is represented, how it interfaces with the symbolic layer, how it transfers between simulation and reality — these are deep, open problems. This is where I hope to make real contributions.

**Exploring world digitization and other viable paths.** This includes high-fidelity simulation, world models, synthetic data, and the digitization of social processes. This is engineering-oriented experimental work — using concrete projects to pressure-test the framework's predictions and to push on what "digitization" can actually mean in practice.

---

**The ultimate target**: to build a general agent that has both *high-level reasoning and imagination grounded in linguistic symbols* and *low-level interaction with and modification of the physical world grounded in embodied perception*. In the present era, I am setting aside self-iteration — just getting these two capabilities integrated well is already a deep enough challenge for one career.

If the framework is right, this is the path that has to be walked. If the framework is wrong, I hope that in walking it I will find out exactly where it broke.

---

## Two questions I want to leave open

There are two questions I have not been able to think my way through, and I want to end with them rather than pretend they are resolved.

**The first: if imitation is our path, can intelligence ever truly exceed the human coordinate system?**

Even the boundary case I bracketed earlier — self-iteration — does not obviously escape this. A self-iterating system would still begin from a base built on human intelligence. Its initial value structure, its representational vocabulary, its sense of what "improvement" even means — these would all be inherited. Whether the iteration process can ever fully shed that inheritance, or whether something human always remains as the seed and the frame, is something I genuinely do not know.

Maybe this is the deepest version of the epistemic humility I started with: from inside the human coordinate system, we may not even be able to tell whether anything we build is capable of leaving it.

**The second, a flip of the first: if humans connect directly to the digital world through brain-computer interfaces, would human capability — once the physical bottleneck is removed — become the ceiling that contemporary AI cannot exceed?**

The logic would go something like this. The surpassing mechanism I described in section III — aggregated knowledge, faster-than-physical iteration, scale beyond a single biological brain — all depend on operating inside a digital substrate. If humans gain direct access to that same substrate, they inherit the same advantages. The asymmetry between human and AI in the digital domain shrinks toward zero. What remains as AI's distinctive territory may be much narrower than we currently assume — and the moving target we call "human capability" may itself rise to define, rather than fall behind, the ceiling of what AI in the same era can become. In which case AI never decisively surpasses humans; it only ever shows us what humans, given the same substrate, are also becoming.

The two questions point in opposite directions but share a structure. The first asks whether AI can ever leave the human coordinate system. The second asks whether humans, once their own physical limit is bypassed, would simply move with it — keeping AI inside the human envelope by definition rather than by limitation. Both feel important to me, and I do not yet have a stable position on either.

---

*This is a document I expect to keep revising. If you have read this far and think any part of the argument is wrong, or that I have missed something, I would like to hear about it.*
