---
title: Motivated visual perception
summary: Individuals with different motivations often report seeing the same image differently, but it is unclear whether this reflects a bias in what they *see* or what they *report* seeing. Can people with diverse goals and motives truly perceive the same visual stimuli differently? In recent work, I combined computational modeling and fMRI to provide a neurocomputational account of how motivation biases visual perception. 

#tags:
#- Deep Learning
date: "2020-10-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon:
  icon_pack: 
  name: Learn More
  url: "project/a_visualperception"
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

Individuals with different motivations often report seeing the same image differently, but it has long been disputed whether this reflects a bias in what they *see* or what they *report* seeing. Can people with diverse goals and motives truly perceive the same visual stimuli differently? I re-examined this decades-old problem using computational modeling and fMRI <a href="https://www.nature.com/articles/s41562-019-0637-z" target="_blank">[1]</a>. I measured the neural responses of participants as they viewed visually ambiguous images created by morphing together a face and a scene. Participants were rewarded for correctly judging whether the image contained ‘more face’ or ‘more scene’. For each image, I motivated them to see one of the categories by instructing them that they would earn a bonus if the image contained more of that category. 

Participants were more likely to report seeing the image as containing more of the category they were motivated to see. If motivation altered perceptual experience, we would expect to observe a corresponding effect on neural representations in visual areas of the brain. Indeed, for a given image, face-related neural activity was higher when participants were motivated to see more face, while scene-related activity was higher when they were motivated to see more scene. Motivationally biased judgments were associated with increased activity in frontoparietal regions that I had previously found to be involved in the dynamic control of attention <a href="https://www.sciencedirect.com/science/article/pii/S089662731631039X" target="_blank">[2]</a>, suggesting a potential source of top-down signals driving these effects. 

Analyzing participants’ behavior using a computational model of the underlying decision processes, I further showed that participants’ motivational bias could be decomposed into an *a priori* bias to respond in a motivation-consistent manner (i.e. a ‘response’ bias), as well as a bias in the accumulation of sensory information (i.e. a ‘perceptual’ bias). The response bias was associated with anticipatory activity in the nucleus accumbens, a striatal structure implicated in reward processing and action selection. In contrast, the perceptual bias tracked modulations in category-selective neural activity in the visual cortex. 

Reframing the problem as a ‘how’ question opens the door to new lines of enquiry about mechanisms. Drawing on the intuition that motivation tends to be arousing, as well as prior work showing that arousal tunes visual attention, I hypothesized that motivational effects on perception are mediated by changes in physiological arousal. In my postdoctoral work, I show that heightened arousal, as measured using pupillometry, was indeed associated with motivational biases in the accumulation of perceptual information <a href="https://www.biorxiv.org/content/10.1101/2020.05.29.124115v1" target="_blank">[3]</a>. Ongoing and future work further explores this topic by examining the temporal dynamics of motivational biases, the neural mechanisms that mediate arousal effects, and the different effects of approach and avoidance motivations. In bringing together a formal characterization of behavior, affective states and brain function, this work seeks to advance an integrative understanding of motivated visual perception. 

**Media**:  
<a href="https://www.vox.com/science-and-health/2019/8/8/20706126/motivated-perception-psychology" target="_blank">How desire can warp our view of the world</a> (Vox, 8.8.2019)

<a href="https://www.psychologytoday.com/us/blog/between-cultures/201907/why-we-see-what-we-want-see" target="_blank">Why we see what we want to see</a> (Psychology Today, 7.9.2019)  

<a href="https://www.nature.com/articles/s41562-019-0639-x" target="_blank">Is visual representation coloured by desire?</a> (News and Views, Nature Human Beahvior, 7.1.2019)  

**References:**   
1. **Leong, Y. C.**, Hughes, B. L., Wang, Y., & Zaki, J. <a href="https://www.nature.com/articles/s41562-019-0637-z" target="_blank">Neurocomputational mechanisms underlying motivated seeing</a>. *Nature Human Behaviour*, 3(9): 962-973 (2019)   

2. **Leong, Y. C.`*`**, Radulescu, A.`*`, Daniel, R., DeWoskin, V., & Niv, Y. <a href="https://www.sciencedirect.com/science/article/pii/S089662731631039X" target="_blank">Dynamic interaction between reinforcement learning and attention in multidimensional environments</a>. *Neuron*, 93(2): 451-463 (2017)   

3. **Leong, Y. C.**, Dziembaj, R. & D'Esposito, M. <a href="https://www.biorxiv.org/content/10.1101/2020.05.29.124115v1" target="_blank">Pupil-linked arousal biases evidence accumulation towards desirable percepts during perceptual decision-making</a>. *bioRxiv* (2020)  
 
