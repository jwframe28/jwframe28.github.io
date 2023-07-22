---
layout: post
title:  "Sober reflections on the microbiome"
date:   2023-07-21 16:49:19 -0400
categories: post1 future llm
---

Unraveling the Microbiome Mystery: Fact from Fiction

Hey there, fellow clinicians and tech enthusiasts! Welcome to my humble blog, where I, John Frame, a lead data scientist in the Taur Lab at Memorial Sloan Kettering, share my thoughts and insights on the intriguing world of the gut microbiome. Having left the healthcare insurance industry three years ago to embark on this exciting journey, I now feel equipped to delve into the potential upsides and barriers of applying the microbiome in a clinical setting. One of my strengths lies in distinguishing fact from fiction, a skill that is much needed in our pursuit of progress.

So, who is this blog for? Well, if you're a clinician, tech-savvy individual, or anyone with an interest in the microbiome, you're in the right place. I've noticed that amidst the plethora of information out there, we need stronger adversarial relationships for funding mechanisms to ensure we explore the microbiome in the right direction. Don't worry if you're not well-versed in the clinical microbiome; I'll soon provide a primer for those new to the field.

Now, what sets this blog apart? My focus is resolutely clinical. I must admit, I don't lose sleep over petri dish experiments unless they offer real potential for further research. In this first post, I might ruffle some feathers, but I stand confidently behind my proclamations. Feel free to challenge me via email if you're serious about a constructive discussion.

There's good news and bad news if you're interested in the microbiome, whether it's gut, skin, lung, oral or vaginal.

Let's start with the bad news – many researchers seem to miss the bigger picture. They ask the wrong questions, focusing on pre/pro-biotics, bioinformatic tools, murine models, high-level analyses, and blindly trusting unsupervised data reliance. It's all too easy to get lost in the noise and forget what truly matters – does the microbiome significantly impact treatment or suggest potential interventions?

1. Pro/prebiotics
   * Do you seriously think that prebiotics matter?  If I give a patient an oral antibiotic before treatment do you really believe eating cottage cheese the week before is going to meaningfully affect surgical outcomes or infection probabilities? I could dig up a few studies which make my point more obvious but any research hospital will likely show the effects are minimal.  I'll backtrack on this if someone can show me something relevant, but at my hospital we're not giving patients special foods before treatment because it's a low-order effect.

2. Focus on computational studies/bioinformatics tools
   * Please for the love of god, do not spend your time focusing on some specific deep learning model which can detect motifs.  Are they useful?  Sure, probably.  Are they going to make or break an analysis?  Absolutely not.  The things which matter most are your target database and sample data.  Everything else is a second-order effect

3. High-level analyses
   * I don't care about alpha-diversity and you shouldn't either.  This is a proxy measure for the compositionality of the microbiome and does not mean anything on its own.  It's also possible to be an artefact of your data depending on how your pipelines/scripts work.  It's okay at a first glance but confers no new information on its own.

4. Blind reliance on data
   * If you're a computational researcher and you rely on the data more than clinical expertise you're going to miss something.  I'm not sure where, but I'm confident if I showed your work to a clinically-minded researcher they'd be able to pick apart any novel finding you think you might have.  Your work should mostly flow from existing hypothesis derived from the clinic (or at least grounded in a clear mechanism).


Many studies suffer from the in-vitro nature of their experiments, disconnecting clinicians and computational researchers like myself. Take the case of Clostridium difficile (C. diff), a recurrent and costly infection. False positives due to the microbiome's inherent presence skew the reported rates in studies, leading to misguided clinical trials and unfulfilled promises. Many millions of dollars have been burnt by noise in the data.

The key here is to recognize that the microbiome is compositional; simple species-level differences may be intriguing but don't necessarily provide meaningful direction for the field. We must be discerning and look for causality rather than mere correlations - and this requires a strict focus on differences with a meaningful clinical impact. 

Now, let's turn to the good news – there's still so much uncharted territory in the microbiome field, abundant data yet to be collected, and exciting applications with the potential for genuine causation!

One such promising intervention is fecal matter transplants (FMT), which has garnered considerable attention. Notable scientists like Eric Pamer, Dr. Robert Jenq, Dr. Ramnik Xavier, and Dr. Jen Wargo have shown compelling evidence of the microbiome's causative influence on human health.

In conclusion, this blog aims to strike a balance between highlighting the challenges and untapped potentials of the microbiome field. It's a Pareto distribution of relevance, where we need to discern the valuable insights from the noise. And please, feel free to challenge my ideas and provide additional studies for consideration. In this field, the null hypothesis should weigh heavily when evaluating new evidence.

Now, let's address a couple of common concerns that might arise:

1.   "But John, your h-index is only like 3! Why should we listen to you?" 
   * My current impact might not be the highest, but I collaborate with influential individuals and bring together diverse experiences in data, tech, and clinical realms. I'm actively involved in significant research projects and contribute substantially to the work I'm involved in. I have not been tacked on as third or fifth author to many studies and my most useful work is yet to come (it's been three years working towards several manuscripts!).

2.   "Here is a study showing XYZ, take back what you've said." 
   * I'm open to changing my views based on new evidence. Please send me multiple studies so that I can thoughtfully reconsider my stance. In this complex field, the weight of the null hypothesis is crucial when evaluating new information.

That's it for this inaugural blog post. Thanks for joining me on this fascinating journey through the world of the microbiome. Stay tuned for more insights and discussions on this enigmatic frontier!


