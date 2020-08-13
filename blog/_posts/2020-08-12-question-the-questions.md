---
title: Question the Questions
lede: How does an AI researcher decide what to work on, when it seems like everything may contribute to surveillance and oppression?
layout: blog
---

While stuck at home, I’ve done a lot of thinking on the kind of research I
should do. It seems that if you want to do AI work, while preserving a sense of
ethics, you can work on: AI “for social good”[^1], critiques of AI[^2], or
other technical work that isn’t Evidently Evil[^3].

This list bothers me: is “not picking Evidently Evil projects” enough? Are we
confined to only do things that are Not Bad? Wouldn’t you want to do something
that’s inherently Good? I don’t know. And I’m struggling to figure that out. 

I’ve come to question whether the only way to Do Good is to do AI for social
good, or critical AI. Why don’t I just do that?

One answer could be the constant gaslighting of ML fairness experts who, when
not outright dismissed, have to endure explanations of “AI bias” by people who
decided it was an important topic mere months ago.

Maybe it’s because I’m afraid[^4]. I want to be respected in the research field
and have a stable career (key for imigration). Doing justice work means being
unjustly branded as “less technical” and “controversial,” and by extension less
employable[^5]. This fucking sucks. Would I be able to get a job, or an
investor buy-in if I have a reputation for “not watching my tone” because I’m
speaking truth to power?

Yet, most importantly, it’s because there’s work I want to do _just_ because I
find it intellectually beautiful. I got into AI research because I genuinely
want to understand how the learning process works, and whether we can
artificially replicate it. Of course I’ll continue doing D&I work, but it’ll be
pointless unless we, as marginalized people, are hired to work on the questions
about cognition and learning that _we_ find elegant[^6].

So why does it feel impossible to do anything _other than_ critical AI without
contributing to our own surveillance and oppression?[^7] I’d guess most of us
started working in AI because of the elegance of the inquiry, not to improve
classification accuracy by 1%. At some point along the way, we forgot that
classification is merely a simplification created to simulate _one_ biological
ability the human brain has, and we started min-maxing classification
benchmarks[^8].

It’s common to hear that “biological inspiration should not constrain our
solutions for intelligence,” which I agree with! The hardware is different, so
why shouldn’t the software? Yet, letting go of the biological inspiration gave
machine learning permission to do _whatever_. Under capitalism, this means the
original goal - understanding the learning process - was corrupted in favor or
“usefulness.”

And this is the root of the problem: historically, the _questions_ we work on
have been picked by humans under capitalism[^9], who had an easier time not
questioning them because they turned out to be _useful_. Today, knowing the
ethical implications of these frameworks, many projects feel Evil because they
feel handed down to us by this system[^10].

But there’s no need to work on heirloom problems. We do it because we
underestimate the importance of our own ideas. In 1832, Évariste Galois, a
20-year-old mathematician widely rejected by academia at the time died in a
duel over a girl. Before his fate with destiny, he had been writing about his
frustrations with academia by fleshing out the ideas he found most interesting
in mathematics. Once these manuscripts were discovered, his ideas turned out to
yield a hugely influential new way to look at polynomial equations.

Questioning the questions of our time, and the assumptions built into them, is
a key part of science. We should, as marginalized peoples, trust our guts
more[^11]. Our lived experience will lead us to questions that truly matter, as
long as we seek them out. This, in itself, is a radical act.

So here’s my answer to this existential crisis: I will work on problems that
are _beautiful to me_, and that genuinely tackle understanding how learning
happens. I’m starting by writing down my own hamming problems, like Galois did.
I’ll be reading more cognitive psychology literature and thinking about the
similarities and discrepancies between the definitions of intelligence in
humans, and those in computers. I’ll refine the questions I ask and
continuously re-evaluate their alignment with my values. This way, they’ll
never be merely Not Evil.

I have no plans to get into any duels, but I hope that creating a research
agenda guided by my own values will be much more impactful and enriching than
any SOTA-chasing ever could.

---
Thanks to Katherine Lee, Natalia Bilenko, Ria Kalluri, Keren Gu, Ben Poole,
Joshua Morton, and William Agnew for thoughtful comments and discussion.

---
[^1]: This is usually applied work. Often on things that are perceived by many
    as uncontroversial, to the point where they are often done as a PR strategy.
    This results in limited impact. [“Good” isn’t good
    enough](https://aiforsocialgood.github.io/neurips2019/accepted/track3/pdfs/67_aisg_neurips2019.pdf).

[^2]: Works on ML fairness, accountability, transparency and justice fall in
    this category. It can be theoretical (some great pieces out there read as
    pure philosophy), or applied (often demonstrations of how biased/abusable AI
    systems are, and how they perpetuate systemic injustices). Both are very
    technical, and heavily shape policy.

[^3]: There are a lot of good strategies you can adopt today to have your work
    be Not Evil:
  - Discuss impacts of your research. Even if your research feels incredibly
    abstract and is completely application domain agnostic, your work can
    still have negative consequences. Think about those. Write them in the
    paper. Discuss ways to mitigate that harm. Make this a first-class
    feature of your work, not an extra paragraph added post-hoc.
  - [Cite underrepresented
    minorities](https://points.datasociety.net/how-to-cite-like-a-badass-tech-feminist-scholar-of-color-ebc839a3619c).
    These folks are pioneering tons of incredible work -- technical and
    otherwise -- and they are at a structural disadvantage for being recognized
    for their work. Pro tip: the ML fairness literature is filled with
    incredible BIPOC, queer and women authors. Cite them in the discussion you
    write above.
  - Steer the ship away from creating more harm. This can take many forms.
    Maybe it means not using datasets that notoriously lack diversity. Maybe
    it means writing your paper with a slightly different angle. The sky is
    the limit.
  -   Don’t pick Evidently Evil projects. [Facial
      recognition](https://xrds.acm.org/article.cfm?aid=3313129) is not used
      for anything other than mass surveillance and oppression. Why are we still
      working on it? 
  - Keep your peers accountable. Reject papers for ethical reasons. This
    matters.
  - You can find more tactics at the [Radical AI
    website](http://radicalaiproject.org/), which I co-wrote.

[^4]: Fear is a feeling [ubiquitous in modern day silicon
    valley](https://www.theatlantic.com/technology/archive/2020/06/facebook-silicon-valley-trump-silence/612877/).

[^5]: Tons of justice work is extremely technical. But, much like HCI and
    design, it is perceived as inferior to those doing “true technical work,”
    such as fucking facial recognition…

[^6]: “I am a black woman who enjoys thinking, and I don’t appreciate being
    told that I may only ponder questions that start with my own oppression” and
    other gems [can be read
    here](http://www.theliberatedmathematician.com/2017/08/in-defense-of-not-telling-me-what-to-think).

[^7]: As you might have guessed by now, the feelings in this post started when
    research work became massively silly to work on, due to the current
    mismanaging of the pandemic, immigration restrictions, and the oppression of
    Black Lives Matter protests. 

[^8]: “As I've dived into research wrt billions of affected people & massive
    systems, I've found it harder to review for/enjoy academic conferences. Many
    papers have the same issue: a sol'n that misses the bigger picture using
    datasets curated by colleagues also missing the bigger picture. Cynically,
    it seems like most papers have their main goal as simply putting
    *something* out towards a PhD, or aligning to grant funding to keep the
    people involved employed.” is another gem, which [you can read
    here](https://twitter.com/mmitchell_ai/status/1289247254797197313).

[^9]: [AI has a backend problem](https://youtu.be/WQfmMph8n0M?t=433)

[^10]: “When people talk about ‘unintended consequences,’ says @png\_marie, it
    sounds like they're saying the consequences couldn't have been predicted.
    But AI's unintended consequences are in fact highly predictable if you just
    look back at history.” [Read more
    here](https://twitter.com/_KarenHao/status/1289203931801772033).

[^11]: “It seems that the influence of your teacher has been to give you a
    false idea of what are worthwhile problems. The worthwhile problems are the
    ones you can really solve or help solve, the ones you can really contribute
    something to. (...) I would advise you to take even simpler, or as you say,
    humbler, problems until you find some you can really solve easily, no matter
    how trivial. (...) You must not take away from yourself these pleasures
    because you have some erroneous idea of what is worthwhile. (...) No
    problem is too small or too trivial if we can really do something about
    it.” [Read more
    here](https://lettersofnote.com/2015/10/23/do-not-remain-nameless-to-yourself/).

