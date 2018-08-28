# Emotion Convergence
[Anderson, C., Keltner, D., & John, O. P. (2003). Emotional convergence between people over time. Journal of personality and social psychology, 84(5), 1054.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.320.1184&rep=rep1&type=pdf)
- dating partners, college roommates became more similar in their emotional responses over the course of a year.
- Relationships whose partners were more emotionally similar were less likely to break up.

## Depression
Gibbons, F. X. (1986). Social comparison and depression: Company's effect on misery. Journal of Personality and Social Psychology, 51(1), 140.
- depressed subjects prefer information from subjects who are also experiencing negative affect, but not when they feel positive.

Rosenblatt, A., & Greenberg, J. (1991). Examining the world of the
depressed: Do depressed people prefer others who are depressed? Journal
of Personality and Social Psychology, 60, 620–629.
- best friends of depressed people more depressed bfs of non-depressed.
- dep-dep, dep-nondep, nondep-nondep subjects had conversations, but no difference in liking.

# Facial Expressions
[Littlewort, G., Whitehill, J., Wu, T., Fasel, I., Frank, M., Movellan, J., & Bartlett, M. (2011, March). The computer expression recognition toolbox (CERT). In Automatic Face & Gesture Recognition and Workshops (FG 2011), 2011 IEEE International Conference on (pp. 298-305). IEEE.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.367.3957&rep=rep1&type=pdf)
- CERT, later known as FACET.
- Emotion/AU recognition model through face detection, cropping, convolve with gabor filters, and SVM.

[Bartlett, M. S., Littlewort, G. C., Frank, M. G., & Lee, K. (2014). Automatic decoding of facial movements reveals deceptive pain expressions. Current Biology, 24(7), 738-743.](https://www.sciencedirect.com/science/article/pii/S096098221400147X)
- bag of temporal features for decoding fake vs real pain facial expressions

[Prkachin, K. M., & Solomon, P. E. (2008). The structure, reliability and validity of pain expression: Evidence from patients with shoulder pain. Pain, 139(2), 267-274.](https://journals.lww.com/pain/fulltext/2008/10150/The_structure,_reliability_and_validity_of_pain.6.aspx)
- Prkachin and Solomon Pain Intensity rating (PSPI)
- PSPI = AU4 + max(AU6, AU7) + max(AU9, AU10) + AU43

[Liu, D., Peng, F., Shea, A., & Picard, R. (2017). DeepFaceLIFT: interpretable personalized models for automatic estimation of self-reported pain. arXiv preprint arXiv:1708.04670.](https://arxiv.org/pdf/1708.04670.pdf)
- Personalized pain facial expression.
- Personal features included : complexion, age, and gender.

# fMRI
## Individual Differences
[Feilong, M., Nastase, S. A., Guntupalli, J. S., & Haxby, J. V. (2018). Reliable individual differences in fine-grained cortical functional architecture. bioRxiv, 296012.](https://www.sciencedirect.com/science/article/pii/S1053811918307274)
- Using hyperalignment to see if individual differences persist after alignment compared to anatomical alignment. Participants viewed Raiders of Lost Ark. Hyperalignment using separate 11 subjects, derived transformation from first half of movie from the 20 subjects. Uses searchlight, grabs TR x time matrix, flattens it as the "response profile" which was correlated across subjects to create intersubject similarity matrix at each searchlight. Two searchlights (first half of second-half of movie v second half of second-half of movie) were compared as a measure of reliability.
Using hyperalignment increased reliability in 82%.



# Stats
## LMER
[Harrison, X. A., Donaldson, L., Correa-Cano, M. E., Evans, J., Fisher, D. N., Goodwin, C. E., ... & Inger, R. (2018). A brief introduction to mixed effects modelling and multi-model inference in ecology. PeerJ, 6, e4794.](https://peerj.com/articles/4794/#p-16)
- A good set of recommendations on how to use LMER.  


# Replication
[Evaluating the replicability of social science experiments in Nature and Science between 2010 and 2015. (2018). Camerer et al. ](https://osf.io/preprints/socarxiv/4hmb6/)
- 13/21 (62%) studies replicated, effect size is half of original.
- Peer beliefs about replicability a strong predictor of actual replication.

[Evaluating replicability of laboratory experiments in economics (2016)/ Camerer et al. ](http://science.sciencemag.org/content/351/6280/1433)
- 11/18 (61%) studies replicated, effect size is about 2/3 of original.
- Prediction market allso a good predictor of replication.
