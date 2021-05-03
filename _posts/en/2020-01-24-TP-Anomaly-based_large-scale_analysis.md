---
title: Anomaly-based large-scale analysis of style and genre reflected in the use of stylistic devices in medieval literature
excerpt: "Joachim Denzler & Sophie Marshall"
lang: en
---

***Joachim Denzler & Sophie Marshall***

The goal of this project is the development of a novel distant-reading tool for the
quantitative analysis of the use of rhetorical devices. The developed methods will be applied
for a comparative stylometric analysis of three medieval genres: the Middle High German
adaptations of the trois matières. From the viewpoint of medieval studies, we aim for
identifying genre-specific stylistic differences between romances of antiquity, Arthurian
romances, and chanson de geste adaptations of the 12 th and 13 th century. Up to now,
quantifiable similarities and differences of these genres regarding their use of rhetorical
devices have not been analysed. Such an analysis would be valuable for the controversial
discussion about the medieval concepts of ‘genre’ and the genre-awareness of medieval
authors as well as for assessing the relevance of rhetorical devices taught in medieval
schools for the practice of vernacular authors. To this end, we intend to analyse whether
selection, use, and frequency of rhetorical devices depend on the scene type and whether
characteristic differences can be attributed to genres or just different authors or dates of
origin. Such a broad analysis requires computational methods for distant reading, which do
not yet exist for the detection of stylistic devices to a satisfactory degree, not to mention for
Middle High German texts. For this purpose, we seek to develop novel methods for
detecting rhetorical devices based on methods from the fields of anomaly detection as well
as active and life-long machine learning. In this context, we consider rhetorical devices as
‘anomalies’, as deviations from the quantitative norm established by the greater part of the
corpus, which can be detected using statistical methods (e.g., a chiasmus is an anomaly
amidst non-chiastic constructions). To reduce time-consuming manual annotation tasks to a
minimum, we propose to employ active learning techniques in a semi-supervised scenario
with the human in the loop: Based on an initially unsupervised process of detecting stylistic
anomalies, the system refines itself in an interactive process by actively asking the user for
annotations for a few informative examples. Furthermore, we intend to integrate prior
theoretical knowledge provided by experts into the anomaly detection procedure for
filtering out obvious false positives and steering it towards certain rhetorical devices. In this
project, we will focus on two exemplary stylistic devices: the chiasmus as a figure of
repetition and the metaphor as a trope. The latter can be seen as an anomaly as well due to
the unusual interactions between words from different domains, reflected in their word
embeddings. Since such embeddings need to be learned from huge corpora, which are not
available for low-resource languages such as Middle High German, we also strive for
developing a technique to adapt such embeddings learned on New High German corpora to
Middle High German.
