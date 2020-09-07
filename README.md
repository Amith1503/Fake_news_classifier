# Fake_news_classifier

The goal of the Fake News Challenge is to explore how artificial intelligence technologies, particularly machine learning and natural language processing, might be leveraged to combat the fake news problem. We believe that these AI technologies hold promise for significantly automating parts of the procedure human fact checkers use today to determine if a story is real or a hoax.

The Project description has been adapted from the description on the FNC-1 website (http://www.fakenewschallenge.org).

# Input

A headline and a body text - either from the same news article or from two different articles.

# Output

Classify the stance of the body text relative to the claim made in the headline into one of four categories:
1. Agrees: The body text agrees with the headline.
2. Disagrees: The body text disagrees with the headline.
3. Discusses: The body text discusses the same topic as the headline, but does not take a
position.
4. Unrelated: The body text discusses a different topic than the headline.

# Evaluation

Evaluation is based on a weighted, two-level scoring system:
Level 1: Classify headline and body text as related or unrelated 25% score weighting
Level 2: Classify related pairs as agrees, disagrees, or discusses 75% score weighting

This repository displays various methods experimented and the final model was a deep neural network approach which crossed the base line model and acheived an accuracy of 80.87%. A detailed report of our approach and our findings can also be found.
