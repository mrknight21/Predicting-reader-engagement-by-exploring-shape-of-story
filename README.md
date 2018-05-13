# Predicting-reader-engagement-by-exploring-shape-of-story

This approach is inspired by the journal article "The emotional arcs of stories are dominated by six basic shapes" from

Journal aritcle:https://arxiv.org/abs/1606.07772
Online article:https://www.technologyreview.com/s/601848/data-mining-reveals-the-six-basic-emotional-arcs-of-storytelling/?utm_campaign=owned_social&utm_medium=social&utm_source=facebook.com

This journal article explore emotional arc of story from 1,327 stories from Project Gutenberg's fiction collection. The emotional arcs
are mapped out by conducting sentiment classification with window shifting.

The current project attempt to firstly vectorize and normalize emotional arcs of stories, then use supervised neuronetwork to
build model for reader engagement predictions or popularity prediction.

This project will not focus on novels, but medium to long size online articles, as there has been a growing trend in online
readership that moving away from taboid short article to more decent long content.

Project steps are listed below:

1. Defined reader engagement.
2. Selection of dataset.
3. Selection of sentiment classification algorithm.
4. Train sentiment classifier.
5. Decide shifting window size.
6. Mapping out emotional arc of training data articles.
7. Selection and design vectorization and normalization methods.
8. Selection and design of neural network
9. Train neural network with emotional arc vectors.
10. Make prediction with built model and evaluation.


