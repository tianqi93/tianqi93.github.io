---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 1
---

> My current research centers on the intersection of psycholinguistics and natural language processing. More concretely, I use a combination of computational modeling and human experiments to understand how words are organized and retrieved, as well as how individuals are different in terms of their mental lexicon. Topics of my research include compositionality, lexical ambiguity, and automated extrapolation of lexical semantic ratings.
{: .block-warning }

##### **Project 1: A computational characterization of Chinese compound processing**
___

This project aims to provide a computational characterization for the dual-route framework of compound processing. To this end, we first trained a computational model to learn the complex rules of Chinese word formation. After training, the model could capture the role-dependent meanings of the constituent characters, which were further combined to generate the compound word’s compositional representation. Based on the actual and model-predicted embeddings, we defined two metrics to characterize (i) the extent to which the compositional meaning converges with the lexicalized meaning (i.e., **_compositionality_**), and (ii) the extent to which the compositional representation has a **_distinct_** presence in semantic space and thus can be readily activated during compound processing. Analyses on lexical decision and eye-tracking data revealed the main effects of the composition metrics, which indicated an active engagement of the combinatorial process in compound processing. Moreover, these compositional effects appeared to be dampened with the increase of compound frequency, i.e., an indicator of whether the whole-word meaning can be easily retrieved from semantic memory. The present study can serve as a theoretical and methodological extension to the dual-route framework of compound processing. In a more general sense, our findings illuminate how meaning composition is implemented in minds and machines.

{% include figure.liquid loading="eager" path="assets/img/project/PhD_Project_1.jpg" class="img-fluid rounded z-depth-1" %}
<div class="caption">
    Computational model (left panel) and computed metrics (right panel)
</div>

##### **Project 2: Perception and computation of lexical ambiguity in Chinese characters**
___

This project provided evidence from both human judgments and computational models for the graded nature of lexical ambiguity. With a special focus on Chinese characters, we first established that native speaker’s perception about a character’s number of meanings was heavily influenced by the availability of its distinct word formations, while whether these meanings would be perceived to be closely related was driven by further conceptual analysis. These notions were operationalized as two computed metrics, which assessed the degree of dispersion across individual word formations and the degree of propinquity across clusters of word formations, respectively, in a distributional semantic space. Our findings extended the previous observation that distributional semantics could inform about the quantity and relatedness of senses. Moreover, idiosyncratic features of Chinese characters render their word formations reliable and cognitively plausible probes of their meaning representations. Our study therefore has theoretical implications for understanding how Chinese characters are represented within the mental lexicon. It also sheds light on the representation of ambiguous words more generally.

{% include figure.liquid loading="eager" path="assets/img/project/PhD_Project_2.jpg" class="img-fluid rounded z-depth-1" %}
<div class="caption">
    Two-dimensional visualization of the vector space based on individual word formations (upper three panels) and clusters of word formations (lower three panels) for the three example characters
</div>

##### **Project 3: Advances in the extrapolation of psycholinguistic norms**
___

Word semantic norms are important tools in psycholinguistic research, natural language processing, and many other fields. However, even for well-studied languages, such norms are usually limited in scale. Recently, there have been a number of attempts to extrapolate psycholinguistic norms using computational models. However, existing methods can only predict rating central tendency (i.e., mean ratings averaged across participants for a given word), without considering that a large number of words are ambivalent in nature. In the first study, we implemented a mixture density network to capture how words’ vector-based semantic representations corresponded to the probability densities of their valence and arousal. Based on these probability density functions, we predicted not only a word’s affective values, but also their potential degrees of **_variability_** that could characterize individual differences in human affective ratings. Our results indicated that the estimates of affective values largely converged with human ratings for both valence and arousal. Moreover, they captured important features characteristic of the variability distributions along the respective rating scales. In the second study, we extended the computational approach to extrapolate word concreteness ratings. Using embeddings derived from different transformer-based language models, we successfully predicted how people represent this semantic dimension (as well as how differently they represent this dimension) within mental lexicon.

{% include figure.liquid loading="eager" path="assets/img/project/PhD_Project_3.jpg" class="img-fluid rounded z-depth-1" %}
<div class="caption">
    Model architecture (upper panel) and the variability of the extrapolated valence (lower left panel) and arousal (lower right panel)
</div>
