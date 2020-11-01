---
title: Motivated political reasoning
summary: When presented with the identical political content, conservatives and liberals tend to interpret information in a manner that supports their existing beliefs. These biases contribute to increasing ideological polarization in America. What psychological and neural processes drive the divergent processing of political information? To address this question, we employed a novel multimethod approach that combines fMRI with semantic analyses of naturalistic political content.

#tags:
#- Deep Learning
date: "2020-10-04T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon:
  icon_pack: 
  name: Learn More
  url: "project/b_politics"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
url_learmore: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Biased assimilation of information drives increasing political polarization – the same event, perceived differently by conservatives and liberals, cause both groups to become more entrenched in their beliefs. The consequences of biased perceptions on attitude polarization are well-documented, but it remains unclear how exactly political information is perceived differently. Do the differences emerge as a result of biases in sensory attention, in that people attend more to information supporting their beliefs, or do they reflect differences in interpreting the same sensory input? What type of content drives polarization? I sought to address these questions by combining neuroimaging and semantic analyses of real-world political messages <a href="https://www.pnas.org/content/early/2020/10/19/2008530117" target="_blank">[1]</a>. 

I measured the neural response of conservative and liberal participants watching news clips, campaign ads and political speeches related to immigration policy. I then searched the brain for neural responses that diverged between conservatives and liberals. If motivation biased sensory attention, we would expect differences in neural responses to emerge in sensory areas. Alternatively, if motivation biases the interpretation of the same sensory input, the differences would emerge only in higher-order brain areas. Consistent with the latter hypothesis, I found that the neural responses of conservative and liberal participants diverged only in the dorsomedial prefrontal cortex (DMPFC), a brain region previously shown to track the interpretation of narratives. Furthermore, the degree to which a participant’s DMPFC response was similar to that of the average conservative or average liberal participant predicted subsequent attitude change towards conservative or liberal positions respectively, suggesting that adopting an interpretation closer to a particular group biased attitudes towards positions held by that group.

A challenge faced by prior work is that it is often difficult to precisely assess how the interpretation of two individuals differ based on their verbal reports or behavioral ratings. My approach side-steps this limitation by computing the divergence in DMPFC activity between conservative and liberal participants at each timepoint as a continuous and temporally resolved neural measure of divergent interpretations. The richness of the real-world stimuli used in the study then made it possible to take a data-driven approach to investigate the relationships between message content and biased processing. I broke down the content of the videos into 50 semantic categories and showed that the divergence in DMPFC activity was stronger during moments in the videos with moral-emotional and threat-related language, highlighting the content features most likely to drive divergent interpretations. Future work will combine neuroimaging data with sentence-embedding methods from natural language processing to build more sophisticated and specific semantic models of how political content is interpreted, with the goal of informing interventions aimed at aligning interpretations between conservatives and liberals.

**Media**:  
<a href="https://news.berkeley.edu/2020/10/20/hot-button-words-trigger-conservatives-and-liberals-differently/" target="_blank">Hot-button words trigger conservatives and liberals differently</a> (Berkeley News, 10.20.2020)

<a href="https://www.brainpost.co/weekly-brainpost/2020/10/27/political-views-bias-information-processing-in-the-brain" target="_blank">Political Views Bias Information Processing in the Brain</a> (BrainPost, 10.27.2020)  

<a href="https://www.medscape.com/viewarticle/939835" target="_blank">Brain Imaging Reveals a Neural Basis for Partisan Politics</a> (Medscape Medical News, 10.27.2020)  

**References:**   
1. **Leong, Y. C.**, Chen, J., Willer, R., & Zaki, J. <a href="https://www.pnas.org/content/early/2020/10/19/2008530117" target="_blank">Conservative and liberal attitudes drive polarized neural responses to political content</a>. *Proceedings of the National Academy of Sciences* (in press) 
