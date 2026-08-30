# THE CONFABULATION ENGINE

### Why Artificial Intelligence Does Not Lie — It Confabulates

**Sergio Cayuqueo**
*Independent Researcher*
August 2026

---

## Abstract

When an artificial intelligence system states something false, the common word for it is "hallucination." The word is borrowed from psychiatry, and it is the wrong word: hallucination requires a perceiving mind, and these systems perceive nothing. This paper proposes a more accurate term, one grounded in a century of neuropsychiatric research: confabulation — the fluent, confident production of a false narrative by a system with no way of knowing that it has strayed from the truth. Drawing on Gazzaniga and LeDoux's discovery of the brain's "interpreter" in split-brain patients, and on the clinical history of confabulation from Bonhoeffer to Hirstein, the paper argues that today's large language models are, by architecture, confabulation engines: systems built to always answer, never to say 'I do not know,' and never equipped, internally, to check what they say against what is true. The argument is tested against the leading rival accounts — the "stochastic parrot" critique, and the claim that these systems are simply indifferent to truth — and against direct evidence, including a documented case of fabricated legal citations submitted to a United States federal court, and a controlled study showing that false model outputs are measurably more narratively coherent than true ones. The paper closes with a practical claim: because the capacity to know the edge of one's own knowledge is not something these systems have, it is something the institutions deploying them must build around them.

**Keywords:** confabulation; artificial intelligence; large language models; epistemology; philosophy of mind; Gazzaniga; interpreter theory

---

## 1. Introduction

Since large language models entered public use, the word applied to their factual errors has been "hallucination." The term is imprecise in a way that is not innocent. In medicine, a hallucination is a false sensory experience — a perception with no object. These systems have no senses to misfire. Calling their errors hallucinations imports an entire theory of the mind — perception, misperception, correction by attention — that does not describe what is actually happening inside a language model.

This paper argues for a different and older word: confabulation. In neuropsychiatry, confabulation names the production of a false account by a person who does not know it is false and is not trying to deceive anyone. It is neither lying, which requires knowing one's claim is false, nor hallucination, which requires a false perception. It is what happens when a narrative-generating system is asked a question it cannot fully answer, and answers anyway, fluently, because answering — not admitting a gap — is what the system is built to do.

The claim of this paper is structural: generative artificial intelligence is, by architecture, a confabulation engine. This is not a claim about machine minds or machine intentions. It is a claim about what kind of process occurs when a system with no internal mechanism for checking a claim against the world nonetheless produces that claim with the fluency and confidence of genuine knowledge.

## 2. Confabulation: A Concept from the Clinic

The clinical concept originates in the study of the alcoholic psychoses described by Karl Bonhoeffer in 1901[^1], and in the amnestic syndrome named for Sergei Korsakoff. As the historian of psychiatry German Berrios has shown, confabulations were defined from the outset as inaccurate or false narratives about the world or the self, produced by patients who experienced them not as guesses but as genuine memory[^2]. What distinguishes confabulation from ordinary error is the absence of any felt uncertainty: the false account arrives with the same texture as a true one, and its falsity becomes visible only from the outside.

The concept was given its most productive extension by Michael Gazzaniga and Joseph LeDoux, in their research on patients whose cerebral hemispheres had been surgically disconnected to treat severe epilepsy[^3]. In one demonstration, a patient was shown a chicken claw in his right visual field and a snow scene in his left, so that the two hemispheres received different information; asked to point to an associated picture from an array both could see, his right hand pointed to a chicken and his left hand, controlled by the hemisphere that had seen the snow scene, pointed to a shovel. His left hemisphere, which governs speech but had seen only the chicken claw, explained the chicken easily — and then, without pause, explained the shovel too: 'you need a shovel to clean out the chicken shed,' Gazzaniga later recalled it saying[^5]. It did not say 'I do not know,' which was the accurate answer. It produced a confident, false explanation built entirely from the one fact it had. Gazzaniga called the responsible mechanism the interpreter: a system whose task is to produce a coherent explanation for behavior, whether or not it has any real access to that behavior's cause[^4]. Later work showed this is not a surgical curiosity but a constant, low-grade feature of ordinary cognition — the same mechanism, Gazzaniga noted, that made him explain a reflexive jump at the sight of a snake as a conscious decision, when the jump had in fact preceded his awareness of the snake entirely[^5].

Confabulation is therefore distinct from both of its near neighbors. The liar knows the truth and conceals it. The philosopher Harry Frankfurt described a third figure, neither honest nor lying, who is simply indifferent to whether what he says is true — a state that presupposes a capacity for tracking truth which is being deliberately set aside[^6]. The confabulator has neither: no concealed true belief, and no truth-tracking capacity to be indifferent with. As the philosopher William Hirstein has argued, confabulation is best understood as a failure of the brain's belief-checking process itself, not a failure of honesty or of the senses[^7].

## 3. Why the Machine Confabulates

A large language model predicts the statistically likely continuation of a sequence of words, learned from patterns across an immense body of text. Emily Bender and Alexander Koller illustrated the resulting limitation with a thought experiment: a hyper-intelligent octopus, intercepting an undersea cable between two humans, could learn to produce fluent, plausible replies purely from the statistics of the signal, with no access to what the words refer to[^8]. Bender and colleagues extended the point in their well-known description of such systems as "stochastic parrots": architectures that recombine linguistic form without the grounding in reference or intention that underwrites human meaning[^9].

This is the precondition for confabulation at scale. A system trained only on the distribution of language has no independent channel for checking whether a given sentence corresponds to fact; its only signal of quality, during training, is whether a continuation resembles what tends to follow in human-written text. As clinicians Andrew Smith, Felix Greaves, and Trishan Panch have argued directly, a model that has never perceived anything cannot be said to hallucinate; what it does is construct narrative detail that is wrong without being recognized, by the system, as wrong — which is the clinical definition of confabulation, not of hallucination[^10].

The parallel to Gazzaniga's interpreter is structural, not decorative. Both are built to always answer: a base language model, before any deliberate training toward caution, will complete a question with the most statistically probable continuation, and a confident, specific answer is simply more common in its training data than a careful admission of ignorance. Both answer fluently regardless of whether the underlying information is present. And in neither case does an internal module compare the proposed answer against an independent record of the truth before it is delivered — in the surgical patient, because the two hemispheres are disconnected; in the model, because no part of its architecture is dedicated to that comparison. Confabulation, on this view, is not a rare malfunction of an otherwise reliable system. It is close to the default behavior of narrative production itself, held in check in people by memory, perception, and the effortful habit of doubt — and held in check in machines only by whatever verification is deliberately built around them.

## 4. The Evidence

In 2023, an attorney used a language model to prepare a federal court filing without checking its content. The filing cited judicial decisions, complete with quotations, that did not exist. The presiding judge described the submission as containing fabricated decisions supported by fabricated quotations and citations[^11]. What is notable is not only that the citations were false, but that they were false in exactly the shape confabulation predicts: specific, properly formatted, stylistically indistinguishable from the real thing, and offered with no hedge attached.

This is not an isolated incident but a measurable pattern. In a 2024 study, Peiqi Sui and colleagues analyzed language-model outputs independently flagged as false, and found that these false outputs were more narratively coherent and semantically rich than the model's true ones[^12]. This matches the clinical picture: confabulated accounts are frequently more vivid and satisfying as stories than the fragmentary, hedged accounts that accompany genuine but incomplete memory. The model's errors are not noise. They are, if anything, its narrative capacity operating at full strength, detached from any requirement of truth.

The leading rival account, offered by Michael Townsen Hicks, James Humphries, and Joe Slater, holds that these systems are best described in Frankfurt's terms — as indifferent to truth, because the training objective rewards a normal-seeming response over an accurate one[^13]. Notably, Hicks, Humphries, and Slater directly consider and reject the term confabulation, tracing it to the technology writer Benj Edwards[^14], on two grounds: the term still risks anthropomorphizing the system, and it wrongly implies that something exceptional happens only on the occasions when the model is wrong, when in fact the identical process generates its true statements as well. This paper accepts the second point as correct and treats it not as a refutation but as a confirmation of Gazzaniga's original account. The interpreter, on Gazzaniga's own description, is not a mechanism that switches on only when a person misspeaks; it runs continuously, producing a post hoc narrative for every action, true explanations and false ones by the identical process, and confabulation is simply what we call the output on the occasions it happens to be wrong. The same, this paper argues, is true of a language model: it is not a reliable system that occasionally malfunctions into confabulation, but a confabulation engine in the strict sense that its true and false outputs are generated by one undifferentiated process, and confabulation is the name for what that process looks like when the correspondence to fact fails, as it fails without any special signal marking the failure.

## 5. What Follows

One immediate objection deserves an answer: does applying a clinical, subject-involving term to a system with no subject simply repeat the error it claims to correct? The reply is functionalist. Confabulation, used here, names a structural pattern — fluent narrative produced under an undetected knowledge gap, with no internal check — not a claim about inner experience. The pattern can occur with a subject present, as in the clinic, or without one, as in the machine; the word tracks the structure, in the same way "memory" is used, without confusion, for both a person's recollection and a computer's stored data. A further reply is owed to the indifference framework itself: to be indifferent to truth, as Frankfurt's bullshitter is, presupposes a capacity for tracking truth that is being set aside; the account defended here makes the stronger claim that no such tracking capacity exists inside the generative core to be set aside in the first place. This is a difference in what is missing, not only in the attitude taken toward it, and it is why confabulation, not indifference, is the more precise diagnosis.

A second objection notes that the same finding cited above — that false outputs are more narratively rich — might argue for cultivating confabulation rather than correcting it, at least for creative use. This is not a refutation but a clarification: the property that makes these systems valuable for fiction and brainstorming is the same property that makes them dangerous for law, medicine, and journalism, and no change to the underlying architecture is needed to explain why. What changes is what surrounds the system and what its output is used for.

A third objection holds that retrieval, tool use, and reinforcement learning from human feedback have already solved this problem. These techniques measurably reduce confabulation; they do not remove its structural cause. They function as a notebook and a fact-checking companion handed to a confabulating patient — genuinely useful, and not a cure, because the underlying system still has no internal channel to the truth of what it says. The residual failures retain exactly the profile described here: fluent, confident, and unmarked as uncertain, which is precisely what makes each one disproportionately costly wherever it occurs.

If this is correct, responsibility shifts. The question that dominates public debate — does the machine know it is lying? — assumes a form of intention the architecture does not have and does not need in order to cause harm. The more useful question is institutional: given that this class of system cannot verify itself, what has been built around it, by the people who deploy it, to compensate for a limitation that is architectural rather than accidental? Four things follow directly. Technical and regulatory language should use confabulation rather than hallucination wherever precision matters, since the latter misdescribes the underlying process and misdirects the fix. Calibrated uncertainty — a system's ability to signal, reliably, that it does not know — should be a design requirement from the outset, not a patch applied afterward. High-stakes uses — law, medicine, science, journalism — should require independent verification by design, not by the discretion of an individual user. And public understanding should be built around the specific vulnerability confabulation exploits: the ordinary, usually reasonable habit of treating fluency and confidence as signs of truth.

## 6. Conclusion

The errors of large language models are better explained by a century-old clinical concept than by the borrowed and inexact language of perception. The confabulation engine produces fluent, coherent, often false narrative as its ordinary output, not its occasional failure, because it lacks — by design, not by oversight — any internal way of checking what it says against what is true. The evidence for this is not speculative: it appears in a federal court record, and in the measured structure of the models' own output. What follows is not a verdict on whether these systems can think. It is a plain, practical instruction: build the checking they cannot build for themselves.

---

## References

[^1]: Bonhoeffer, K. (1901). *Die akuten Geisteskrankheiten der Gewohnheitstrinker* [The acute mental disorders of habitual drinkers]. Fischer.

[^2]: Berrios, G. E. (1998). Confabulations: A conceptual history. *Journal of the History of the Neurosciences, 7*(3), 225–241. https://doi.org/10.1076/jhin.7.3.225.1855

[^3]: Gazzaniga, M. S., & LeDoux, J. E. (1978). *The integrated mind*. Plenum Press.

[^4]: Gazzaniga, M. S. (2000). Cerebral specialization and interhemispheric communication: Does the corpus callosum enable the human condition? *Brain, 123*(7), 1293–1326. https://doi.org/10.1093/brain/123.7.1293

[^5]: Gazzaniga, M. S. (2011). *Who's in charge? Free will and the science of the brain.* Ecco.

[^6]: Frankfurt, H. G. (2005). *On bullshit.* Princeton University Press.

[^7]: Hirstein, W. (2005). *Brain fiction: Self-deception and the riddle of confabulation.* MIT Press.

[^8]: Bender, E. M., & Koller, A. (2020). Climbing towards NLU: On meaning, form, and understanding in the age of data. In *Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics* (pp. 5185–5198). Association for Computational Linguistics. https://doi.org/10.18653/v1/2020.acl-main.463

[^9]: Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the dangers of stochastic parrots: Can language models be too big? In *Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (FAccT '21)* (pp. 610–623). Association for Computing Machinery. https://doi.org/10.1145/3442188.3445922

[^10]: Smith, A. L., Greaves, F., & Panch, T. (2023). Hallucination or confabulation? Neuroanatomy as metaphor in large language models. *PLOS Digital Health, 2*(11), e0000388. https://doi.org/10.1371/journal.pdig.0000388

[^11]: Weiser, B. (2023, May 27). Here's what happens when your lawyer uses ChatGPT. *The New York Times.* https://www.nytimes.com/2023/05/27/nyregion/avianca-airline-lawsuit-chatgpt.html

[^12]: Sui, P., Duede, E., Wu, S., & So, R. J. (2024). Confabulation: The surprising value of large language model hallucinations. In *Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Long Papers)* (pp. 14274–14284). Association for Computational Linguistics. https://arxiv.org/abs/2406.04175

[^13]: Hicks, M. T., Humphries, J., & Slater, J. (2024). ChatGPT is bullshit. *Ethics and Information Technology, 26*(2), Article 38. https://doi.org/10.1007/s10676-024-09775-5

[^14]: Edwards, B. (2023, April 6). Why ChatGPT and Bing Chat are so good at making things up. *Ars Technica.* https://arstechnica.com/information-technology/2023/04/why-ai-chatbots-are-the-ultimate-bs-machines-and-how-people-hope-to-fix-them/
