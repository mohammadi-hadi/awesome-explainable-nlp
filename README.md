<div align="center">

# Awesome Explainable NLP

*A curated list of papers, tools, and resources on explainability and interpretability for NLP and large language models.*

Companion list to the survey [Explainability in Practice: A Survey of Explainable NLP Across Various Domains](https://github.com/mohammadi-hadi/xnlp-survey).

</div>

## Contents

- [Surveys and Position Papers](#surveys-and-position-papers)
- [Feature Attribution](#feature-attribution)
- [Attention Analysis](#attention-analysis)
- [Probing and Representations](#probing-and-representations)
- [Counterfactuals and Behavioral Testing](#counterfactuals-and-behavioral-testing)
- [Rationales and Natural Language Explanations](#rationales-and-natural-language-explanations)
- [Faithfulness and Evaluation](#faithfulness-and-evaluation)
- [Reasoning and Chain-of-Thought Faithfulness](#reasoning-and-chain-of-thought-faithfulness)
- [Mechanistic Interpretability](#mechanistic-interpretability)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Tools and Libraries](#tools-and-libraries)

## Surveys and Position Papers

- **The Mythos of Model Interpretability** — Lipton, 2016. [[paper](https://arxiv.org/abs/1606.03490)]
- **Towards a Rigorous Science of Interpretable Machine Learning** — Doshi-Velez & Kim, 2017. [[paper](https://arxiv.org/abs/1702.08608)]
- **Explanation in Artificial Intelligence: Insights from the Social Sciences** — Miller, Artificial Intelligence 2019. [[paper](https://arxiv.org/abs/1706.07269)]
- **Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead** — Rudin, Nature Machine Intelligence 2019. [[paper](https://arxiv.org/abs/1811.10154)]
- **A Survey of the State of Explainable AI for Natural Language Processing** — Danilevsky et al., AACL 2020. [[paper](https://arxiv.org/abs/2010.00711)]
- **Post-hoc Interpretability for Neural NLP: A Survey** — Madsen et al., ACM Computing Surveys 2022. [[paper](https://arxiv.org/abs/2108.04840)]
- **Teach Me to Explain: A Review of Datasets for Explainable NLP** — Wiegreffe & Marasović, NeurIPS Datasets and Benchmarks 2021. [[paper](https://arxiv.org/abs/2102.12060)]
- **Explainability for Large Language Models: A Survey** — Zhao et al., ACM TIST 2024. [[paper](https://arxiv.org/abs/2309.01029)]
- **Rethinking Interpretability in the Era of Large Language Models** — Singh et al., 2024. [[paper](https://arxiv.org/abs/2402.01761)]
- **A Primer in BERTology: What We Know About How BERT Works** — Rogers et al., TACL 2020. [[paper](https://arxiv.org/abs/2002.12327)]

## Feature Attribution

- **"Why Should I Trust You?": Explaining the Predictions of Any Classifier (LIME)** — Ribeiro et al., KDD 2016. [[paper](https://arxiv.org/abs/1602.04938)]
- **A Unified Approach to Interpreting Model Predictions (SHAP)** — Lundberg & Lee, NeurIPS 2017. [[paper](https://arxiv.org/abs/1705.07874)]
- **Axiomatic Attribution for Deep Networks (Integrated Gradients)** — Sundararajan et al., ICML 2017. [[paper](https://arxiv.org/abs/1703.01365)]
- **Learning Important Features Through Propagating Activation Differences (DeepLIFT)** — Shrikumar et al., ICML 2017. [[paper](https://arxiv.org/abs/1704.02685)]
- **Anchors: High-Precision Model-Agnostic Explanations** — Ribeiro et al., AAAI 2018.
- **Visualizing and Understanding Neural Models in NLP** — Li et al., NAACL 2016. [[paper](https://arxiv.org/abs/1506.01066)]
- **Understanding Neural Networks through Representation Erasure** — Li et al., 2016. [[paper](https://arxiv.org/abs/1612.08220)]
- **Explaining Recurrent Neural Network Predictions in Sentiment Analysis** — Arras et al., WASSA 2017. [[paper](https://arxiv.org/abs/1706.07206)]
- **Beyond Word Importance: Contextual Decomposition to Extract Interactions from LSTMs** — Murdoch et al., ICLR 2018. [[paper](https://arxiv.org/abs/1801.05453)]
- **Sanity Checks for Saliency Maps** — Adebayo et al., NeurIPS 2018. [[paper](https://arxiv.org/abs/1810.03292)]
- **The (Un)reliability of Saliency Methods** — Kindermans et al., 2017. [[paper](https://arxiv.org/abs/1711.00867)]

## Attention Analysis

- **Attention is not Explanation** — Jain & Wallace, NAACL 2019. [[paper](https://arxiv.org/abs/1902.10186)]
- **Attention is not not Explanation** — Wiegreffe & Pinter, EMNLP 2019. [[paper](https://arxiv.org/abs/1908.04626)]
- **Is Attention Interpretable?** — Serrano & Smith, ACL 2019. [[paper](https://arxiv.org/abs/1906.03731)]
- **What Does BERT Look At? An Analysis of BERT's Attention** — Clark et al., BlackboxNLP 2019. [[paper](https://arxiv.org/abs/1906.04341)]
- **Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned** — Voita et al., ACL 2019. [[paper](https://arxiv.org/abs/1905.09418)]
- **Quantifying Attention Flow in Transformers** — Abnar & Zuidema, ACL 2020. [[paper](https://arxiv.org/abs/2005.00928)]
- **A Multiscale Visualization of Attention in the Transformer Model** — Vig, ACL 2019 demo. [[paper](https://arxiv.org/abs/1906.05714)]

## Probing and Representations

- **A Structural Probe for Finding Syntax in Word Representations** — Hewitt & Manning, NAACL 2019. [[paper](https://aclanthology.org/N19-1419/)]
- **Designing and Interpreting Probes with Control Tasks** — Hewitt & Liang, EMNLP 2019. [[paper](https://arxiv.org/abs/1909.03368)]
- **BERT Rediscovers the Classical NLP Pipeline** — Tenney et al., ACL 2019. [[paper](https://arxiv.org/abs/1905.05950)]
- **What do you learn from context? Probing for sentence structure in contextualized word representations** — Tenney et al., ICLR 2019. [[paper](https://arxiv.org/abs/1905.06316)]
- **What Does BERT Learn about the Structure of Language?** — Jawahar et al., ACL 2019. [[paper](https://aclanthology.org/P19-1356/)]
- **Information-Theoretic Probing with Minimum Description Length** — Voita & Titov, EMNLP 2020. [[paper](https://arxiv.org/abs/2003.12298)]
- **Information-Theoretic Probing for Linguistic Structure** — Pimentel et al., ACL 2020. [[paper](https://arxiv.org/abs/2004.03061)]
- **Probing Classifiers: Promises, Shortcomings, and Advances** — Belinkov, Computational Linguistics 2022. [[paper](https://arxiv.org/abs/2102.12452)]
- **Language Models as Knowledge Bases?** — Petroni et al., EMNLP 2019. [[paper](https://arxiv.org/abs/1909.01066)]

## Counterfactuals and Behavioral Testing

- **Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR** — Wachter et al., Harvard Journal of Law & Technology 2017. [[paper](https://arxiv.org/abs/1711.00399)]
- **Learning the Difference that Makes a Difference with Counterfactually-Augmented Data** — Kaushik et al., ICLR 2020. [[paper](https://arxiv.org/abs/1909.12434)]
- **Polyjuice: Generating Counterfactuals for Explaining, Evaluating, and Improving Models** — Wu et al., ACL 2021. [[paper](https://arxiv.org/abs/2101.00288)]
- **Explaining NLP Models via Minimal Contrastive Editing (MiCE)** — Ross et al., Findings of ACL 2021. [[paper](https://arxiv.org/abs/2012.13985)]
- **Beyond Accuracy: Behavioral Testing of NLP Models with CheckList** — Ribeiro et al., ACL 2020. [[paper](https://arxiv.org/abs/2005.04118)]
- **Contrastive Explanations for Model Interpretability** — Jacovi et al., EMNLP 2021. [[paper](https://arxiv.org/abs/2103.01378)]

## Rationales and Natural Language Explanations

- **Rationalizing Neural Predictions** — Lei et al., EMNLP 2016. [[paper](https://arxiv.org/abs/1606.04155)]
- **e-SNLI: Natural Language Inference with Natural Language Explanations** — Camburu et al., NeurIPS 2018. [[paper](https://arxiv.org/abs/1812.01193)]
- **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** — Rajani et al., ACL 2019. [[paper](https://arxiv.org/abs/1906.02361)]
- **Learning to Faithfully Rationalize by Construction** — Jain et al., ACL 2020. [[paper](https://arxiv.org/abs/2005.00115)]
- **WT5?! Training Text-to-Text Models to Explain their Predictions** — Narang et al., 2020. [[paper](https://arxiv.org/abs/2004.14546)]
- **Measuring Association Between Labels and Free-Text Rationales** — Wiegreffe et al., EMNLP 2021. [[paper](https://arxiv.org/abs/2010.12762)]
- **The Unreliability of Explanations in Few-shot Prompting for Textual Reasoning** — Ye & Durrett, NeurIPS 2022. [[paper](https://arxiv.org/abs/2205.03401)]

## Faithfulness and Evaluation

- **Towards Faithfully Interpretable NLP Systems: How Should We Define and Evaluate Faithfulness?** — Jacovi & Goldberg, ACL 2020. [[paper](https://arxiv.org/abs/2004.03685)]
- **Aligning Faithful Interpretations with their Social Attribution** — Jacovi & Goldberg, TACL 2021. [[paper](https://arxiv.org/abs/2006.01067)]
- **Evaluating Explainable AI: Which Algorithmic Explanations Help Users Predict Model Behavior?** — Hase & Bansal, ACL 2020. [[paper](https://arxiv.org/abs/2005.01831)]
- **A Benchmark for Interpretability Methods in Deep Neural Networks (ROAR)** — Hooker et al., NeurIPS 2019. [[paper](https://arxiv.org/abs/1806.10758)]
- **A Diagnostic Study of Explainability Techniques for Text Classification** — Atanasova et al., EMNLP 2020. [[paper](https://arxiv.org/abs/2009.13295)]
- **Faithfulness Tests for Natural Language Explanations** — Atanasova et al., ACL 2023. [[paper](https://arxiv.org/abs/2305.18029)]

## Reasoning and Chain-of-Thought Faithfulness

- **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** — Wei et al., NeurIPS 2022. [[paper](https://arxiv.org/abs/2201.11903)]
- **Self-Consistency Improves Chain of Thought Reasoning in Language Models** — Wang et al., ICLR 2023. [[paper](https://arxiv.org/abs/2203.11171)]
- **Show Your Work: Scratchpads for Intermediate Computation with Language Models** — Nye et al., 2021. [[paper](https://arxiv.org/abs/2112.00114)]

## Mechanistic Interpretability

## Datasets and Benchmarks

## Tools and Libraries

## Contributing

Additions are welcome — one resource per pull request, with a link and a one-line description of why it belongs here.

## Maintainer

**Hadi Mohammadi** — [mohammadi.cv](https://mohammadi.cv)
