[Bobadilla-Suarez, S., & Love, B. C. (2018). Measures of Neural Similarity. bioRxiv, 439893.](https://www.biorxiv.org/content/early/2018/10/12/439893)
- Angle measures: Distance correlation, pearson, spearman, cosine
- Magnitude measures
  - Non-distributional: minkowski, chebyshev, euclidean, city block
  - Distributional: Mahalanobis, Bhattacharyya, variation of info
- Key Assumptions for different distance measures
  - Key assumption in Pearson correlation: assumes overal voxel activity are normalized and each voxel contributes independently to similarity.
  - Key assumption in Minkowski: distances in a metric space not vector directions.
  - Key assumption in Mahalanobis: extends Pearson and Minkowski, assuming distributional pattern of voxel activity is consequential.
- Method
  - which metric achieves highest _Spearman correlation_ between a classifier confusion matrix and a _neural similarity_ metric.
- Key Finding:
  - optimal neural similarity measure can depend on task or stimuli
    - For geometric images: Minkowski measures better
    - For naturalistic image: Mahalanobis measures better

[Chen, C., Crivelli, C., Garrod, O. G., Schyns, P. G., Fernández-Dols, J. M., & Jack, R. E. (2018). Distinct facial expressions represent pain and pleasure across cultures. Proceedings of the National Academy of Sciences, 201807862.](http://www.pnas.org/content/early/2018/10/03/1807862115)
- refutes the theory that pain and orgasmic faces are indistinguishable ([Aviezer, Trope, & Todorov 2012](http://science.sciencemag.org/content/338/6111/1225))
- using reverse correlation method from the Philip Schyns group, authors show that pain and orgasm faces are actually distinct in two cultures (west and east)
- seven temporal parameters: onset latency, acceleration, peak amplitude, peak latency, sustainment, deceleration, offset latency.
- key result: pain is similar between cultures but orgasm shows more differences.

# Emotion Convergence & social connection
[Anderson, C., Keltner, D., & John, O. P. (2003). Emotional convergence between people over time. Journal of personality and social psychology, 84(5), 1054.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.320.1184&rep=rep1&type=pdf)
- dating partners, college roommates became more similar in their emotional responses over the course of a year.
- Relationships whose partners were more emotionally similar were less likely to break up.

[Schachter, S. (1959). The psychology of affiliation: Experimental studies of the sources of gregariousness.](http://psycnet.apa.org/record/1959-10111-000)
- People who are under anxiety want to wait with other people who are participating in the same experiment than alone.
- Participants would rather wait with those who are about to participate in same experiment than wait with others who are waiting for something else. (N=10 for each condition...)

[Hatfield, E., Cacioppo, J. T., & Rapson, R. L. (1994). Emotional contagion: Studies in emotion and social interaction. Editions de la Maison des sciences de l’homme.](https://lyi07mfsx01.storage.googleapis.com/MDUyMTQ0OTQ4MA==01.pdf)

[Dunbar, R. I. M., Teasdale, B., Thompson, J., Budelmann, F., Duncan, S., van Emde Boas, E., & Maguire, L. (2016). Emotional arousal when watching drama increases pain threshold and social bonding. Royal Society open science, 3(9), 160288.](https://www.ncbi.nlm.nih.gov/pubmed/27703694)
- compared to subjects who watch an emotionally neutral film, subjects who watch an emotionally arousing film have increased pain thresholds and an increased sense of group bonding

[Bruder, M., Dosmukhambetova, D., Nerb, J., & Manstead, A. S. (2012). Emotional signals in nonverbal interaction: Dyadic facilitation and convergence in expressions, appraisals, and feelings. Cognition & emotion, 26(3), 480-502.](https://www.tandfonline.com/doi/full/10.1080/02699931.2011.645280)
- facilitation and convergence are not uniform across different emotions and emotion components.
- friends’ appraisals of an amuse- ment film were more correlated than those of strangers, but only if the partners could not see each other
- friend > stranger, number of smiles to amusing film.
- strong convergence in amusement-related expressions among friends who were visible to each other. This convergence was moderated by the amount of attention directed at the partner and by the level of social motives.
- Convergence measured by intraclass correlation - correlation of number of smiling within pair and outside pair.
- Social motives - degree to which they thought about the other person.

# Sharing of Emotion
[Rimé, B. (2009). Emotion elicits the social sharing of emotion: Theory and empirical review. Emotion review, 1(1), 60-85.](http://journals.sagepub.com/doi/abs/10.1177/1754073908097189)
- Review of verbal sharing of emotional experience with others
- Negative & positive emotions instigate conversations.
- Also touches on the temporal aspects of memory sharing.

[Luminet IV, O., Bouts, P., Delie, F., Manstead, A. S., & Rimé, B. (2000). Social sharing of emotion following exposure to a negatively valenced situation. Cognition & Emotion, 14(5), 661-688.](https://www.tandfonline.com/doi/pdf/10.1080/02699930050117666)
- Experimental evidence that when exposed to emotionally arousing movies, participants talk more about it than less arousing movies.

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
