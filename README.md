# fake_news
ANNOTATED NEWS CORPUS: REAL AND FAKE NEWS IN RUSSIAN AND KAZAKH

This repository contains a dataset of annotated news articles in Kazakh and Russian languages, designed for research in fake news detection, claim verification, and natural language processing (NLP). Each news item is labeled with key elements such as SOURCE, CLAIM, EVIDENCE, and TIME, along with classifications for News Type, Fake News Subtype, Disinformation Technique, Author Intent, and Target Audience. The dataset is exported in JSON format and includes ground truth annotations for training machine learning models or analyzing misinformation patterns.
The data was collected and manually annotated following the structure used in Label Studio.

The dataset can be used for:
Training NLP models (NER, classification, multilabel).
Research in the field of Fake News Detection.
Testing annotation schemes.

Each news item is annotated in JSON format. The annotations include the following fields:
SOURCE: The source or author of the information.
CLAIM: The main claim or statement in the article.
EVIDENCE: Supporting details or evidence for the claim.
TIME: Temporal references, if present.
Classification Labels:
main_classification: Categorizes the article as REAL_NEWS or FAKE_NEWS.
fake_subtype: Specifies the type of fake news, if applicable (e.g., conspiracy_theory, fabricated_news, satire_or_parody).
disinfo_technique_subtype: Describes the disinformation technique, if applicable (e.g., emotional_pressure, misattribution, exaggeration).
author_intent_subtype: Indicates the author's intent (e.g., spread_fear, attract_attention, influence_opinion).
target_audience_subtype: Defines the target audience (e.g., general_public, youth, mothers).
