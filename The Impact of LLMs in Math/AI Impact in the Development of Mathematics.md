<details>
<summary>Navigate this collection</summary>

- [Home](../README.md)
- [AI Impact in the Development of Mathematics](AI%20Impact%20in%20the%20Development%20of%20Mathematics.md)
- [Summary](Sources/Summary.md)
  - [How Terry Tao Became an Evangelist for AI in Math](Sources/How%20Terry%20Tao%20Became%20an%20Evangelist%20for%20AI%20in%20Math%20_%20Quanta%20Magazine/How%20Terry%20Tao%20Became%20an%20Evangelist%20for%20AI%20in%20Math%20_%20Quanta%20Magazine.md)
  - [On the Navier–Stokes Millennium Prize Problem](Sources/On%20the%20Navier%E2%80%93Stokes%20Millennium%20Prize%20Problem%20_%20OpenAI/Navier%20Stokes.md)
  - [Terence Tao: AI companies are harming mathematics](Sources/Terence%20Tao_%20AI%20companies%20are%20harming%20mathematics%20_%20New%20Scientist/Terence%20Tao_%20AI%20companies%20are%20harming%20mathematics%20_%20New%20Scientist.md)
  - [The Equational Theories Project: Advancing Collaborative Mathematical Research at Scale](Sources/The%20Equational%20Theories%20Project/The%20Equational%20Theories%20Project.md)
  - [The machines are fine. I'm worried about us.](Sources/The%20machines%20are%20fine.%20I%27m%20worried%20about%20us_/The%20machines%20are%20fine.%20I%27m%20worried%20about%20us.md)
  - [Vibe physics: The AI grad student](Sources/Vibe%20physics_%20The%20AI%20grad%20student%20_%20Anthropic/Vibe%20physics_%20The%20AI%20grad%20student%20_%20Anthropic.md)
  - [On Proof and Progress in Mathematics](Sources/On%20Proof%20and%20Progress%20in%20Mathematics/On%20Proof%20and%20Progress%20in%20Mathematics.md)
  - [The Ideal Mathematician](Sources/The%20Ideal%20Mathematician/The%20Ideal%20Mathematician.md)
  - [NaturalProver: Grounded Mathematical Proof Generation with Language Models](Sources/NaturalProver%20-%20Grounded%20Mathematical%20Proof%20Generation%20with%20Language%20Models/NaturalProver%20-%20Grounded%20Mathematical%20Proof%20Generation%20with%20Language%20Models.md)
  - [The Open Proof Corpus: A Large-Scale Study of LLM-Generated Mathematical Proofs](Sources/The%20Open%20Proof%20Corpus%20-%20A%20Large-Scale%20Study%20of%20LLM-Generated%20Mathematical%20Proofs/The%20Open%20Proof%20Corpus%20-%20A%20Large-Scale%20Study%20of%20LLM-Generated%20Mathematical%20Proofs.md)
  - [Mathematics Isn’t Just a Game to Let A.I. Solve. History Shows Why.](Sources/Mathematics%20Isn%E2%80%99t%20Just%20a%20Game%20to%20Let%20A.I.%20Solve.%20History%20Shows%20Why./Mathematics%20Isn%E2%80%99t%20Just%20a%20Game%20to%20Let%20A.I.%20Solve.md)
  - [The Four Color Theorem](Sources/The%20Four%20Color%20Theorem/The%20Four%20Color%20Theorem.md)
  - [A year of work by two Spanish mathematicians versus 88 hours and €15 million by OpenAI](Sources/A%20year%20of%20work%20by%20two%20Spanish%20mathematicians%20versus%2088%20hours%20and%20%E2%82%AC15%20million%20by%20OpenAI/A%20year%20of%20work%20by%20two%20Spanish%20mathematicians%20versus%2088%20hours%20and%20%E2%82%AC15%20million%20by%20OpenAI.md)
- [Assignment Description](Assignment%20Description.md)
- [Calibration Test](Calibration%20Test.md)

</details>

---

# Introduction

The point of this repository is to bring together different sources in the current debate of AI usage for the development of mathematics. For this task, we gather the points of view of people with experience in their fields, people that knew how research level math was before AI and know what is being different now.  We also gather results from experts that try and use the latest models to do their research work and are getting results. Finally, there is a third point, which is the defects and particularities of human mathematics as something biased towards certain results and preferences, which will make us think if we were in a good state to start with.

# Logistics

This repository is a corpus of information about AI usage in Math. While some of these sources contain mathematical content, it is not our goal to fully comprehend the proofs and procedures, but rather the end results (if such results is doubted, then we have the possibilty to understand how they obtained them). The main reason to include such sources is that I wanted as many first-hand bibliography as possible (and the side reason is that I am a mathematician).

The structure of this corpus is simple, we have the *Sources* folder, that contains a [Summary](Sources/Summary.md) and a [Source Log](Sources/Source%20Log.base). These contain a list and a small description of each source. To access each source, one might simply click on the title, or navigate through the Sources folder, where each source has a folder named after it. For each source, its folder will contain a file corresponding to its entry in the source log (that has the same information) and a PDF with the source itself.

The reasoning behind this particular source gathering was (in decreasing order):
- First Hand: If I talk about $X$ happening, and there is an official article documenting $X$, then I will include it, as opposed to an article $Y$ that reviews $X$ from some perspective or criteria, or that focuses on a small subset of the aspects of $X$
- Recent: I would prioritize articles from 2026 or recently new articles, while this discussion is not new, some major results happened in this year, so this motivates the principle.
- Reliable: I picked articles from journals and authors I personally trust, this does not guarantee of course that each source is legitimate.

One flaw that I should mention is that these are subjective and are biased with respect to my point of view in the topic. While I want to be as general as possible, I am naturally more attracted to topics that resonate with my thinking. I have nonetheless added several sources with a view that I don't share, because it is critical to consider each different opinion.

# Relevance

This topic is of great importance to me, and I am sure it is to most mathematicians, it represents the early stages of a major shift in Mathematics, and because we are all part of it, we must ensure proper understanding of the situation. This collection works particularly well for me, because each source is relevant in its own way, it includes the opinions of experts that support, praise, condemn, or criticize the current AI usage in Math, but it also brings questions to the state of Research Mathematics as a system that encourages publishing over understanding.

This is not a solution essay, so we don't offer any particular fix to the situation that has not already been stated in the sources, our focus is to bring awareness to this topic, and narrate what has happened in a meaningful way that connects everything.


# Machine Verification

In 1976, two mathematicians from Illinois University managed to break down the [The Four Color Theorem](Sources/The%20Four%20Color%20Theorem/The%20Four%20Color%20Theorem.md) into finitely many cases left to be checked. This would have taken the two mathematicians and insufferable amount of time Instead, they searched for the aid of a computer, who could be taught on how to work on each case, and after having it run for over 1000 hours, it successfully checked all cases and asserted the correctness of the proof.

This comes to no surprise to the modern scientist, in which computational power is vital for mosts tasks, the scientists abstracts away the task into instructions to be followed by the machine, and billions of computations happens within a second. However, the balance on what the computer does and what the human does is changing, now that some abstraction is able to be carried by computers as well, we require a different approach.

## The Equational Theories Project and Proof Certifications

With the computational power of machines, mathematicians became extremely tempted to immortalize mathematical knowledge that was built from the axioms, thus creating a truly impartial system that can be relied on deciding the correctness of a proof: A machine that can check from implications rules if something is true. Among these theorem provers is Lean. Up to this date, it contains research-level mathematics and can give a vote of confidence on papers that take considerable time and effort to get peer-reviewed. With the aid of Lean, Terence Tao led [The Equational Theories Project](Sources/The%20Equational%20Theories%20Project/The%20Equational%20Theories%20Project.md), in which thousands of mathematicians would hop in and made their contribution. The goal was well-defined: To work with magma laws with up to four operations. Tao had a corpus of 22 million individual cases that required either a proof or a counterexample, so he led everyone work on individual cases and submit their proofs using *Lean*,  the theorem prover. 

[How Terry Tao Became an Evangelist for AI in Math _ Quanta Magazine](Sources/How%20Terry%20Tao%20Became%20an%20Evangelist%20for%20AI%20in%20Math%20_%20Quanta%20Magazine/How%20Terry%20Tao%20Became%20an%20Evangelist%20for%20AI%20in%20Math%20_%20Quanta%20Magazine.md)

# The Mathematical Standard

As it was presented by Thurston's [On Proof and Progress in Mathematics](Sources/On%20Proof%20and%20Progress%20in%20Mathematics/On%20Proof%20and%20Progress%20in%20Mathematics.md), Mathematics is a field that progresses through the development of new fields and new theorems within a field. This is mostly what [The Ideal Mathematician](Sources/The%20Ideal%20Mathematician/The%20Ideal%20Mathematician.md) cares about, and what the system that we have developed at the frontier of new Mathematics cares about. The important point is to develop the field, to publish more theories and generate proofs of these theories. 

Both sources understand that struggling is not rewarded, understanding a concept after hours of thinking has no direct effect on a published paper that proves something, yet it is the very first thing that drives you not only to the proof, but to further questions, analysis, and thus further investigations. Almost like a kid's story, where the true treasure is in the things we learned along the way. 

When we contrast the expectations of our current system of Research Mathematics (the so called "Publish or Perish") against the ideal view of exploring mathematics more calmly, to process what we discovered, and make more meaningful contributions, it comes to no surprise (and almost like a consequence) that AI usage is increasing, and that AI is becoming better at it because we demand it more.

People that use it are not to blame, the are a wide range of reasons of why someone might find itself in the need of AI assistance, and further use generates dependency, as stated in [The machines are fine. I'm worried about us](Sources/The%20machines%20are%20fine.%20I%27m%20worried%20about%20us_/The%20machines%20are%20fine.%20I%27m%20worried%20about%20us.md). This, however, brings as consequence the current state in which we are in: A non-perfect (human) model of Mathematics whose goals are inconsistent to the way in which advancement is made, faces a model who can meet such goals while jumping over proper human understanding (e.g books, conferences), and now humans within the field are worried of the meaning of their positions.

[Vibe physics_ The AI grad student _ Anthropic](Sources/Vibe%20physics_%20The%20AI%20grad%20student%20_%20Anthropic/Vibe%20physics_%20The%20AI%20grad%20student%20_%20Anthropic.md)
[Terence Tao_ AI companies are harming mathematics _ New Scientist](Sources/Terence%20Tao_%20AI%20companies%20are%20harming%20mathematics%20_%20New%20Scientist/Terence%20Tao_%20AI%20companies%20are%20harming%20mathematics%20_%20New%20Scientist.md)
[Mathematics Isn’t Just a Game to Let A.I. Solve](Sources/Mathematics%20Isn%E2%80%99t%20Just%20a%20Game%20to%20Let%20A.I.%20Solve.%20History%20Shows%20Why./Mathematics%20Isn%E2%80%99t%20Just%20a%20Game%20to%20Let%20A.I.%20Solve.md)

# The Ideals Collision
## The Jacobian Conjecture and the Navier Stokes Problem

Up to some months ago, AI and computers were used as a big source for finding counterexamples and brute-forcing a problem that requires hours of routine. At this stage, mathematicians were not too worried about AI, as their biggest contribution was in the finding of counterexamples. Recently, in an X (formerly Twitter) post, a counterexample of the Jacobian Conjecture was shared. The author used Fable AI to perform the search, finding a 7-degree polynomial that disproved the conjecture. 
![Pasted image 20260929151341](Images/Pasted%20image%2020260929151341.png)

A result like this would usually be presented in a formal paper, were lemmas and corollaries around it would be defined to build an intuition of why it fails. Rather we only got a straight "look at this case that doesn't work" answer. At this point, the line between things that can be done by AI and things that can be done by humans was still clear, but one thing was different: The mathematician wouldn't bother to try such a huge computational task, even at the aid of programming languages like Python or C++, because it became clear that AI can do so on its own. 

The true feeling of despair came some weeks ago when, following the work of Cordoba and Martinez-Zoroa, OpenAI managed to prove the [Navier Stokes](Sources/On%20the%20Navier%E2%80%93Stokes%20Millennium%20Prize%20Problem%20_%20OpenAI/Navier%20Stokes.md) Equation Problem, after endless hours of computations and resources. Rather than bringing joy to the mathematical community (for being the second Millennium Problem being solved) it brought fear. What we don't want, or so it seems, is that the (young) mathematician wouldn't bother to try any problem at all, but rather just to follow along AI's work, because it would have been made clear that AI can do so on its own.

[A year of work by two Spanish mathematicians versus 88 hours and €15 million by OpenAI](Sources/A%20year%20of%20work%20by%20two%20Spanish%20mathematicians%20versus%2088%20hours%20and%20%E2%82%AC15%20million%20by%20OpenAI/A%20year%20of%20work%20by%20two%20Spanish%20mathematicians%20versus%2088%20hours%20and%20%E2%82%AC15%20million%20by%20OpenAI.md)
[The Open Proof Corpus - A Large-Scale Study of LLM-Generated Mathematical Proofs](Sources/The%20Open%20Proof%20Corpus%20-%20A%20Large-Scale%20Study%20of%20LLM-Generated%20Mathematical%20Proofs/The%20Open%20Proof%20Corpus%20-%20A%20Large-Scale%20Study%20of%20LLM-Generated%20Mathematical%20Proofs.md)
[NaturalProver - Grounded Mathematical Proof Generation with Language Models](Sources/NaturalProver%20-%20Grounded%20Mathematical%20Proof%20Generation%20with%20Language%20Models/NaturalProver%20-%20Grounded%20Mathematical%20Proof%20Generation%20with%20Language%20Models.md)

# Conclusion

Having separated the different topics according to my line of thought, the message is complete and everything I wanted to say has been stated, thus coming to a conclusion. While we have summarized the ongoing debate and mentioned some of the main points, the reader is invited to read their sources of interest and make their own points and visions. We saw a range of perspectives and their connections, and argued on their points. This is everything that this corpus of information has to offer.

---

[Home](../README.md) · [Summary](Sources/Summary.md) · [Next →](Sources/Summary.md)
