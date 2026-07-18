<div align="center">

# Awesome Explainable NLP

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

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
- [Training Data Attribution](#training-data-attribution)
- [Concept-Based Explanations](#concept-based-explanations)
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
- **Interpretable machine learning: definitions, methods, and applications** — Murdoch et al., PNAS 2019. [[paper](https://arxiv.org/abs/1901.04592)]
- **From Anecdotal Evidence to Quantitative Evaluation Methods: A Systematic Review on Evaluating Explainable AI** — Nauta et al., ACM Computing Surveys 2023. [[paper](https://arxiv.org/abs/2201.08164)]

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
- **Self-Attention Attribution: Interpreting Information Interactions Inside Transformer** — Hao et al., AAAI 2021. [[paper](https://arxiv.org/abs/2004.11207)]

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
- **How Can We Know What Language Models Know?** — Jiang et al., TACL 2020. [[paper](https://arxiv.org/abs/1911.12543)]

## Counterfactuals and Behavioral Testing

- **Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR** — Wachter et al., Harvard Journal of Law & Technology 2017. [[paper](https://arxiv.org/abs/1711.00399)]
- **Learning the Difference that Makes a Difference with Counterfactually-Augmented Data** — Kaushik et al., ICLR 2020. [[paper](https://arxiv.org/abs/1909.12434)]
- **Polyjuice: Generating Counterfactuals for Explaining, Evaluating, and Improving Models** — Wu et al., ACL 2021. [[paper](https://arxiv.org/abs/2101.00288)]
- **Explaining NLP Models via Minimal Contrastive Editing (MiCE)** — Ross et al., Findings of ACL 2021. [[paper](https://arxiv.org/abs/2012.13985)]
- **Beyond Accuracy: Behavioral Testing of NLP Models with CheckList** — Ribeiro et al., ACL 2020. [[paper](https://arxiv.org/abs/2005.04118)]
- **Contrastive Explanations for Model Interpretability** — Jacovi et al., EMNLP 2021. [[paper](https://arxiv.org/abs/2103.01378)]
- **Right for the Wrong Reasons: Diagnosing Syntactic Heuristics in Natural Language Inference (HANS)** — McCoy et al., ACL 2019. [[paper](https://arxiv.org/abs/1902.01007)]
- **Annotation Artifacts in Natural Language Inference Data** — Gururangan et al., NAACL 2018. [[paper](https://arxiv.org/abs/1803.02324)]

## Rationales and Natural Language Explanations

- **Rationalizing Neural Predictions** — Lei et al., EMNLP 2016. [[paper](https://arxiv.org/abs/1606.04155)]
- **e-SNLI: Natural Language Inference with Natural Language Explanations** — Camburu et al., NeurIPS 2018. [[paper](https://arxiv.org/abs/1812.01193)]
- **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** — Rajani et al., ACL 2019. [[paper](https://arxiv.org/abs/1906.02361)]
- **Learning to Faithfully Rationalize by Construction** — Jain et al., ACL 2020. [[paper](https://arxiv.org/abs/2005.00115)]
- **WT5?! Training Text-to-Text Models to Explain their Predictions** — Narang et al., 2020. [[paper](https://arxiv.org/abs/2004.14546)]
- **Measuring Association Between Labels and Free-Text Rationales** — Wiegreffe et al., EMNLP 2021. [[paper](https://arxiv.org/abs/2010.12762)]
- **The Unreliability of Explanations in Few-shot Prompting for Textual Reasoning** — Ye & Durrett, NeurIPS 2022. [[paper](https://arxiv.org/abs/2205.03401)]
- **Using "Annotator Rationales" to Improve Machine Learning for Text Categorization** — Zaidan et al., NAACL 2007. [[paper](https://aclanthology.org/N07-1033/)]
- **Reframing Human-AI Collaboration for Generating Free-Text Explanations** — Wiegreffe et al., NAACL 2022. [[paper](https://arxiv.org/abs/2112.08674)]
- **Few-Shot Self-Rationalization with Natural Language Prompts** — Marasović et al., Findings of NAACL 2022. [[paper](https://arxiv.org/abs/2111.08284)]

## Faithfulness and Evaluation

- **Towards Faithfully Interpretable NLP Systems: How Should We Define and Evaluate Faithfulness?** — Jacovi & Goldberg, ACL 2020. [[paper](https://arxiv.org/abs/2004.03685)]
- **Aligning Faithful Interpretations with their Social Attribution** — Jacovi & Goldberg, TACL 2021. [[paper](https://arxiv.org/abs/2006.01067)]
- **Evaluating Explainable AI: Which Algorithmic Explanations Help Users Predict Model Behavior?** — Hase & Bansal, ACL 2020. [[paper](https://arxiv.org/abs/2005.01831)]
- **A Benchmark for Interpretability Methods in Deep Neural Networks (ROAR)** — Hooker et al., NeurIPS 2019. [[paper](https://arxiv.org/abs/1806.10758)]
- **A Diagnostic Study of Explainability Techniques for Text Classification** — Atanasova et al., EMNLP 2020. [[paper](https://arxiv.org/abs/2009.13295)]
- **Faithfulness Tests for Natural Language Explanations** — Atanasova et al., ACL 2023. [[paper](https://arxiv.org/abs/2305.18029)]
- **Pathologies of Neural Models Make Interpretations Difficult** — Feng et al., EMNLP 2018. [[paper](https://arxiv.org/abs/1804.07781)]

## Reasoning and Chain-of-Thought Faithfulness

- **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** — Wei et al., NeurIPS 2022. [[paper](https://arxiv.org/abs/2201.11903)]
- **Self-Consistency Improves Chain of Thought Reasoning in Language Models** — Wang et al., ICLR 2023. [[paper](https://arxiv.org/abs/2203.11171)]
- **Show Your Work: Scratchpads for Intermediate Computation with Language Models** — Nye et al., 2021. [[paper](https://arxiv.org/abs/2112.00114)]
- **Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting** — Turpin et al., NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.04388)]
- **Measuring Faithfulness in Chain-of-Thought Reasoning** — Lanham et al., 2023. [[paper](https://arxiv.org/abs/2307.13702)]
- **Question Decomposition Improves the Faithfulness of Model-Generated Reasoning** — Radhakrishnan et al., 2023. [[paper](https://arxiv.org/abs/2307.11768)]
- **Faithful Chain-of-Thought Reasoning** — Lyu et al., IJCNLP-AACL 2023. [[paper](https://arxiv.org/abs/2301.13379)]
- **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** — Yao et al., NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.10601)]
- **Large Language Models Cannot Self-Correct Reasoning Yet** — Huang et al., ICLR 2024. [[paper](https://arxiv.org/abs/2310.01798)]
- **Reasoning Models Don't Always Say What They Think** — Chen et al., 2025. [[paper](https://arxiv.org/abs/2505.05410)]

## Mechanistic Interpretability

- **A Mathematical Framework for Transformer Circuits** — Elhage et al., 2021. [[paper](https://transformer-circuits.pub/2021/framework/index.html)]
- **In-context Learning and Induction Heads** — Olsson et al., 2022. [[paper](https://arxiv.org/abs/2209.11895)]
- **Toy Models of Superposition** — Elhage et al., 2022. [[paper](https://arxiv.org/abs/2209.10652)]
- **Towards Monosemanticity: Decomposing Language Models With Dictionary Learning** — Bricken et al., 2023. [[paper](https://transformer-circuits.pub/2023/monosemantic-features/index.html)]
- **Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet** — Templeton et al., 2024. [[paper](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)]
- **Sparse Autoencoders Find Highly Interpretable Features in Language Models** — Cunningham et al., ICLR 2024. [[paper](https://arxiv.org/abs/2309.08600)]
- **Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 small** — Wang et al., ICLR 2023. [[paper](https://arxiv.org/abs/2211.00593)]
- **Locating and Editing Factual Associations in GPT (ROME)** — Meng et al., NeurIPS 2022. [[paper](https://arxiv.org/abs/2202.05262)]
- **Transformer Feed-Forward Layers Are Key-Value Memories** — Geva et al., EMNLP 2021. [[paper](https://arxiv.org/abs/2012.14913)]
- **Eliciting Latent Predictions from Transformers with the Tuned Lens** — Belrose et al., 2023. [[paper](https://arxiv.org/abs/2303.08112)]
- **Representation Engineering: A Top-Down Approach to AI Transparency** — Zou et al., 2023. [[paper](https://arxiv.org/abs/2310.01405)]
- **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model** — Li et al., NeurIPS 2023. [[paper](https://arxiv.org/abs/2306.03341)]
- **Progress Measures for Grokking via Mechanistic Interpretability** — Nanda et al., ICLR 2023. [[paper](https://arxiv.org/abs/2301.05217)]
- **Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task** — Li et al., ICLR 2023. [[paper](https://arxiv.org/abs/2210.13382)]
- **Language Models Represent Space and Time** — Gurnee & Tegmark, ICLR 2024. [[paper](https://arxiv.org/abs/2310.02207)]
- **Activation Addition: Steering Language Models Without Optimization** — Turner et al., 2023. [[paper](https://arxiv.org/abs/2308.10248)]
- **Towards Automated Circuit Discovery for Mechanistic Interpretability** — Conmy et al., NeurIPS 2023. [[paper](https://arxiv.org/abs/2304.14997)]
- **Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2** — Lieberum et al., 2024. [[paper](https://arxiv.org/abs/2408.05147)]
- **Refusal in Language Models Is Mediated by a Single Direction** — Arditi et al., NeurIPS 2024. [[paper](https://arxiv.org/abs/2406.11717)]
- **Language models can explain neurons in language models** — Bills et al., OpenAI 2023. [[paper](https://openaipublic.blob.core.windows.net/neuron-explainer/paper/index.html)]
- **Explaining black box text modules in natural language with language models** — Singh et al., 2023. [[paper](https://arxiv.org/abs/2305.09863)]
- **On the Biology of a Large Language Model** — Lindsey et al., 2025. [[paper](https://transformer-circuits.pub/2025/attribution-graphs/biology.html)]

## Training Data Attribution

- **Understanding Black-box Predictions via Influence Functions** — Koh & Liang, ICML 2017. [[paper](https://arxiv.org/abs/1703.04730)]
- **Estimating Training Data Influence by Tracing Gradient Descent (TracIn)** — Pruthi et al., NeurIPS 2020. [[paper](https://arxiv.org/abs/2002.08484)]
- **Studying Large Language Model Generalization with Influence Functions** — Grosse et al., 2023. [[paper](https://arxiv.org/abs/2308.03296)]
- **Data Shapley: Equitable Valuation of Data for Machine Learning** — Ghorbani & Zou, ICML 2019. [[paper](https://arxiv.org/abs/1904.02868)]
- **Datamodels: Predicting Predictions from Training Data** — Ilyas et al., ICML 2022. [[paper](https://arxiv.org/abs/2202.00622)]
- **TRAK: Attributing Model Behavior at Scale** — Park et al., ICML 2023. [[paper](https://arxiv.org/abs/2303.14186)]

## Concept-Based Explanations

- **Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)** — Kim et al., ICML 2018. [[paper](https://arxiv.org/abs/1711.11279)]
- **Towards Automatic Concept-based Explanations** — Ghorbani et al., NeurIPS 2019. [[paper](https://arxiv.org/abs/1902.03129)]
- **Concept Bottleneck Models** — Koh et al., ICML 2020. [[paper](https://arxiv.org/abs/2007.04612)]
- **Compositional Explanations of Neurons** — Mu & Andreas, NeurIPS 2020. [[paper](https://arxiv.org/abs/2006.14032)]
- **Natural Language Descriptions of Deep Visual Features (MILAN)** — Hernandez et al., ICLR 2022. [[paper](https://arxiv.org/abs/2201.11114)]

## Datasets and Benchmarks

- **ERASER: A Benchmark to Evaluate Rationalized NLP Models** — DeYoung et al., ACL 2020. [[paper](https://arxiv.org/abs/1911.03429)]
- **HateXplain: A Benchmark Dataset for Explainable Hate Speech Detection** — Mathew et al., AAAI 2021. [[paper](https://arxiv.org/abs/2012.10289)]
- **SemEval-2023 Task 10: Explainable Detection of Online Sexism** — Kirk et al., SemEval 2023. [[paper](https://arxiv.org/abs/2303.04222)]

## Tools and Libraries

- [Captum](https://github.com/pytorch/captum) — model interpretability library for PyTorch (Integrated Gradients, DeepLIFT, and many more)
- [shap](https://github.com/shap/shap) — game-theoretic feature attribution for any ML model
- [lime](https://github.com/marcotcr/lime) — local surrogate explanations for classifiers
- [BertViz](https://github.com/jessevig/bertviz) — interactive attention visualization for transformer models
- [Ecco](https://github.com/jalammar/ecco) — explorable explanations for transformer language models
- [Language Interpretability Tool (LIT)](https://github.com/PAIR-code/lit) — visual, interactive model-understanding workbench for NLP
- **AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models** — Wallace et al., EMNLP 2019 demo. [[paper](https://arxiv.org/abs/1909.09251)]
- [InterpretML](https://github.com/interpretml/interpret) — glassbox models and blackbox explainers in one package
- [SAELens](https://github.com/jbloomAus/SAELens) — training and analysis of sparse autoencoders for language models
- [nnsight](https://github.com/ndif-team/nnsight) — interpret and manipulate the internals of deep models
- [Alibi](https://github.com/SeldonIO/alibi) — production-oriented explainers (anchors, contrastive, counterfactual)
- [ELI5](https://github.com/TeamHG-Memex/eli5) — classic inspection library for scikit-learn era NLP models
- [Quantus](https://github.com/understandable-machine-intelligence-lab/Quantus) — metrics toolkit for evaluating explanation quality

## Contributing

Additions are welcome — one resource per pull request, with a link and a one-line description of why it belongs here.

## Maintainer

**Hadi Mohammadi** — [mohammadi.cv](https://mohammadi.cv)
