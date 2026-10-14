<div align="center">

# Awesome Explainable NLP

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21837426.svg)](https://doi.org/10.5281/zenodo.21837426)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

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
- [Tutorials and Courses](#tutorials-and-courses)
- [Workshops and Venues](#workshops-and-venues)
- [Maintainer](#maintainer)

## Surveys and Position Papers

- [The Mythos of Model Interpretability](https://arxiv.org/abs/1606.03490) - Lipton, 2016.
- [Towards a Rigorous Science of Interpretable Machine Learning](https://arxiv.org/abs/1702.08608) - Doshi-Velez & Kim, 2017.
- [Explanation in Artificial Intelligence: Insights from the Social Sciences](https://arxiv.org/abs/1706.07269) - Miller, Artificial Intelligence 2019.
- [Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead](https://arxiv.org/abs/1811.10154) - Rudin, Nature Machine Intelligence 2019.
- [A Survey of the State of Explainable AI for Natural Language Processing](https://arxiv.org/abs/2010.00711) - Danilevsky et al., AACL 2020.
- [Post-hoc Interpretability for Neural NLP: A Survey](https://arxiv.org/abs/2108.04840) - Madsen et al., ACM Computing Surveys 2022.
- [Teach Me to Explain: A Review of Datasets for Explainable NLP](https://arxiv.org/abs/2102.12060) - Wiegreffe & Marasović, NeurIPS Datasets and Benchmarks 2021.
- [Explainability for Large Language Models: A Survey](https://arxiv.org/abs/2309.01029) - Zhao et al., ACM TIST 2024.
- [Rethinking Interpretability in the Era of Large Language Models](https://arxiv.org/abs/2402.01761) - Singh et al., 2024.
- [A Primer on the Inner Workings of Transformer-based Language Models](https://arxiv.org/abs/2405.00208) - Ferrando et al., 2024.
- [A Primer in BERTology: What We Know About How BERT Works](https://arxiv.org/abs/2002.12327) - Rogers et al., TACL 2020.
- [Interpretable machine learning: definitions, methods, and applications](https://arxiv.org/abs/1901.04592) - Murdoch et al., PNAS 2019.
- [From Anecdotal Evidence to Quantitative Evaluation Methods: A Systematic Review on Evaluating Explainable AI](https://arxiv.org/abs/2201.08164) - Nauta et al., ACM Computing Surveys 2023.
- [Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/abs/1806.00069) - Gilpin et al., DSAA 2018.
- [The Urgency of Interpretability](https://www.darioamodei.com/post/the-urgency-of-interpretability) - Amodei, 2025.

## Feature Attribution

- ["Why Should I Trust You?": Explaining the Predictions of Any Classifier (LIME)](https://arxiv.org/abs/1602.04938) - Ribeiro et al., KDD 2016.
- [A Unified Approach to Interpreting Model Predictions (SHAP)](https://arxiv.org/abs/1705.07874) - Lundberg & Lee, NeurIPS 2017.
- [Axiomatic Attribution for Deep Networks (Integrated Gradients)](https://arxiv.org/abs/1703.01365) - Sundararajan et al., ICML 2017.
- [Learning Important Features Through Propagating Activation Differences (DeepLIFT)](https://arxiv.org/abs/1704.02685) - Shrikumar et al., ICML 2017.
- [Anchors: High-Precision Model-Agnostic Explanations](https://ojs.aaai.org/index.php/AAAI/article/view/11491) - Ribeiro et al., AAAI 2018.
- [Visualizing and Understanding Neural Models in NLP](https://arxiv.org/abs/1506.01066) - Li et al., NAACL 2016.
- [Understanding Neural Networks through Representation Erasure](https://arxiv.org/abs/1612.08220) - Li et al., 2016.
- [Explaining Recurrent Neural Network Predictions in Sentiment Analysis](https://arxiv.org/abs/1706.07206) - Arras et al., WASSA 2017.
- [Beyond Word Importance: Contextual Decomposition to Extract Interactions from LSTMs](https://arxiv.org/abs/1801.05453) - Murdoch et al., ICLR 2018.
- [Sanity Checks for Saliency Maps](https://arxiv.org/abs/1810.03292) - Adebayo et al., NeurIPS 2018.
- [The (Un)reliability of Saliency Methods](https://arxiv.org/abs/1711.00867) - Kindermans et al., 2017.
- [Self-Attention Attribution: Interpreting Information Interactions Inside Transformer](https://arxiv.org/abs/2004.11207) - Hao et al., AAAI 2021.
- [SmoothGrad: removing noise by adding noise](https://arxiv.org/abs/1706.03825) - Smilkov et al., 2017.

## Attention Analysis

- [Attention is not Explanation](https://arxiv.org/abs/1902.10186) - Jain & Wallace, NAACL 2019.
- [Attention is not not Explanation](https://arxiv.org/abs/1908.04626) - Wiegreffe & Pinter, EMNLP 2019.
- [Is Attention Interpretable?](https://arxiv.org/abs/1906.03731) - Serrano & Smith, ACL 2019.
- [What Does BERT Look At? An Analysis of BERT's Attention](https://arxiv.org/abs/1906.04341) - Clark et al., BlackboxNLP 2019.
- [Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned](https://arxiv.org/abs/1905.09418) - Voita et al., ACL 2019.
- [Quantifying Attention Flow in Transformers](https://arxiv.org/abs/2005.00928) - Abnar & Zuidema, ACL 2020.
- [A Multiscale Visualization of Attention in the Transformer Model](https://arxiv.org/abs/1906.05714) - Vig, ACL 2019 demo.
- [Learning to Deceive with Attention-Based Explanations](https://arxiv.org/abs/1909.07913) - Pruthi et al., ACL 2020.

## Probing and Representations

- [A Structural Probe for Finding Syntax in Word Representations](https://aclanthology.org/N19-1419/) - Hewitt & Manning, NAACL 2019.
- [Designing and Interpreting Probes with Control Tasks](https://arxiv.org/abs/1909.03368) - Hewitt & Liang, EMNLP 2019.
- [BERT Rediscovers the Classical NLP Pipeline](https://arxiv.org/abs/1905.05950) - Tenney et al., ACL 2019.
- [What do you learn from context? Probing for sentence structure in contextualized word representations](https://arxiv.org/abs/1905.06316) - Tenney et al., ICLR 2019.
- [What Does BERT Learn about the Structure of Language?](https://aclanthology.org/P19-1356/) - Jawahar et al., ACL 2019.
- [Information-Theoretic Probing with Minimum Description Length](https://arxiv.org/abs/2003.12298) - Voita & Titov, EMNLP 2020.
- [Information-Theoretic Probing for Linguistic Structure](https://arxiv.org/abs/2004.03061) - Pimentel et al., ACL 2020.
- [Probing Classifiers: Promises, Shortcomings, and Advances](https://arxiv.org/abs/2102.12452) - Belinkov, Computational Linguistics 2022.
- [Language Models as Knowledge Bases?](https://arxiv.org/abs/1909.01066) - Petroni et al., EMNLP 2019.
- [How Can We Know What Language Models Know?](https://arxiv.org/abs/1911.12543) - Jiang et al., TACL 2020.
- [Patchscopes: A Unifying Framework for Inspecting Hidden Representations of Language Models](https://arxiv.org/abs/2401.06102) - Ghandeharioun et al., ICML 2024.
- [Do Llamas Work in English? On the Latent Language of Multilingual Transformers](https://arxiv.org/abs/2402.10588) - Wendler et al., ACL 2024.

## Counterfactuals and Behavioral Testing

- [Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR](https://arxiv.org/abs/1711.00399) - Wachter et al., Harvard Journal of Law & Technology 2017.
- [Learning the Difference that Makes a Difference with Counterfactually-Augmented Data](https://arxiv.org/abs/1909.12434) - Kaushik et al., ICLR 2020.
- [Polyjuice: Generating Counterfactuals for Explaining, Evaluating, and Improving Models](https://arxiv.org/abs/2101.00288) - Wu et al., ACL 2021.
- [Explaining NLP Models via Minimal Contrastive Editing (MiCE)](https://arxiv.org/abs/2012.13985) - Ross et al., Findings of ACL 2021.
- [Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](https://arxiv.org/abs/2005.04118) - Ribeiro et al., ACL 2020.
- [Contrastive Explanations for Model Interpretability](https://arxiv.org/abs/2103.01378) - Jacovi et al., EMNLP 2021.
- [Right for the Wrong Reasons: Diagnosing Syntactic Heuristics in Natural Language Inference (HANS)](https://arxiv.org/abs/1902.01007) - McCoy et al., ACL 2019.
- [Annotation Artifacts in Natural Language Inference Data](https://arxiv.org/abs/1803.02324) - Gururangan et al., NAACL 2018.

## Rationales and Natural Language Explanations

- [Rationalizing Neural Predictions](https://arxiv.org/abs/1606.04155) - Lei et al., EMNLP 2016.
- [e-SNLI: Natural Language Inference with Natural Language Explanations](https://arxiv.org/abs/1812.01193) - Camburu et al., NeurIPS 2018.
- [Explain Yourself! Leveraging Language Models for Commonsense Reasoning](https://arxiv.org/abs/1906.02361) - Rajani et al., ACL 2019.
- [Learning to Faithfully Rationalize by Construction](https://arxiv.org/abs/2005.00115) - Jain et al., ACL 2020.
- [WT5?! Training Text-to-Text Models to Explain their Predictions](https://arxiv.org/abs/2004.14546) - Narang et al., 2020.
- [Measuring Association Between Labels and Free-Text Rationales](https://arxiv.org/abs/2010.12762) - Wiegreffe et al., EMNLP 2021.
- [The Unreliability of Explanations in Few-shot Prompting for Textual Reasoning](https://arxiv.org/abs/2205.03401) - Ye & Durrett, NeurIPS 2022.
- [Using "Annotator Rationales" to Improve Machine Learning for Text Categorization](https://aclanthology.org/N07-1033/) - Zaidan et al., NAACL 2007.
- [Reframing Human-AI Collaboration for Generating Free-Text Explanations](https://arxiv.org/abs/2112.08674) - Wiegreffe et al., NAACL 2022.
- [Few-Shot Self-Rationalization with Natural Language Prompts](https://arxiv.org/abs/2111.08284) - Marasović et al., Findings of NAACL 2022.
- [SelfIE: Self-Interpretation of Large Language Model Embeddings](https://arxiv.org/abs/2403.10949) - Chen et al., ICML 2024.

## Faithfulness and Evaluation

- [Towards Faithfully Interpretable NLP Systems: How Should We Define and Evaluate Faithfulness?](https://arxiv.org/abs/2004.03685) - Jacovi & Goldberg, ACL 2020.
- [Aligning Faithful Interpretations with their Social Attribution](https://arxiv.org/abs/2006.01067) - Jacovi & Goldberg, TACL 2021.
- [Evaluating Explainable AI: Which Algorithmic Explanations Help Users Predict Model Behavior?](https://arxiv.org/abs/2005.01831) - Hase & Bansal, ACL 2020.
- [A Benchmark for Interpretability Methods in Deep Neural Networks (ROAR)](https://arxiv.org/abs/1806.10758) - Hooker et al., NeurIPS 2019.
- [A Diagnostic Study of Explainability Techniques for Text Classification](https://arxiv.org/abs/2009.13295) - Atanasova et al., EMNLP 2020.
- [Faithfulness Tests for Natural Language Explanations](https://arxiv.org/abs/2305.18029) - Atanasova et al., ACL 2023.
- [Pathologies of Neural Models Make Interpretations Difficult](https://arxiv.org/abs/1804.07781) - Feng et al., EMNLP 2018.

## Reasoning and Chain-of-Thought Faithfulness

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) - Wei et al., NeurIPS 2022.
- [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171) - Wang et al., ICLR 2023.
- [Show Your Work: Scratchpads for Intermediate Computation with Language Models](https://arxiv.org/abs/2112.00114) - Nye et al., 2021.
- [Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting](https://arxiv.org/abs/2305.04388) - Turpin et al., NeurIPS 2023.
- [Measuring Faithfulness in Chain-of-Thought Reasoning](https://arxiv.org/abs/2307.13702) - Lanham et al., 2023.
- [Question Decomposition Improves the Faithfulness of Model-Generated Reasoning](https://arxiv.org/abs/2307.11768) - Radhakrishnan et al., 2023.
- [Faithful Chain-of-Thought Reasoning](https://arxiv.org/abs/2301.13379) - Lyu et al., IJCNLP-AACL 2023.
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601) - Yao et al., NeurIPS 2023.
- [Large Language Models Cannot Self-Correct Reasoning Yet](https://arxiv.org/abs/2310.01798) - Huang et al., ICLR 2024.
- [Reasoning Models Don't Always Say What They Think](https://arxiv.org/abs/2505.05410) - Chen et al., 2025.
- [STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465) - Zelikman et al., NeurIPS 2022.
- [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050) - Lightman et al., 2023.

## Mechanistic Interpretability

- [A Mathematical Framework for Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html) - Elhage et al., 2021.
- [In-context Learning and Induction Heads](https://arxiv.org/abs/2209.11895) - Olsson et al., 2022.
- [Toy Models of Superposition](https://arxiv.org/abs/2209.10652) - Elhage et al., 2022.
- [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html) - Bricken et al., 2023.
- [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html) - Templeton et al., 2024.
- [Sparse Autoencoders Find Highly Interpretable Features in Language Models](https://arxiv.org/abs/2309.08600) - Cunningham et al., ICLR 2024.
- [Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 small](https://arxiv.org/abs/2211.00593) - Wang et al., ICLR 2023.
- [Locating and Editing Factual Associations in GPT (ROME)](https://arxiv.org/abs/2202.05262) - Meng et al., NeurIPS 2022.
- [Transformer Feed-Forward Layers Are Key-Value Memories](https://arxiv.org/abs/2012.14913) - Geva et al., EMNLP 2021.
- [Eliciting Latent Predictions from Transformers with the Tuned Lens](https://arxiv.org/abs/2303.08112) - Belrose et al., 2023.
- [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405) - Zou et al., 2023.
- [Inference-Time Intervention: Eliciting Truthful Answers from a Language Model](https://arxiv.org/abs/2306.03341) - Li et al., NeurIPS 2023.
- [Progress Measures for Grokking via Mechanistic Interpretability](https://arxiv.org/abs/2301.05217) - Nanda et al., ICLR 2023.
- [Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task](https://arxiv.org/abs/2210.13382) - Li et al., ICLR 2023.
- [Language Models Represent Space and Time](https://arxiv.org/abs/2310.02207) - Gurnee & Tegmark, ICLR 2024.
- [Steering Language Models With Activation Engineering](https://arxiv.org/abs/2308.10248) - Turner et al., 2023.
- [Towards Automated Circuit Discovery for Mechanistic Interpretability](https://arxiv.org/abs/2304.14997) - Conmy et al., NeurIPS 2023.
- [Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2](https://arxiv.org/abs/2408.05147) - Lieberum et al., 2024.
- [Refusal in Language Models Is Mediated by a Single Direction](https://arxiv.org/abs/2406.11717) - Arditi et al., NeurIPS 2024.
- [Language models can explain neurons in language models](https://openaipublic.blob.core.windows.net/neuron-explainer/paper/index.html) - Bills et al., OpenAI 2023.
- [Explaining black box text modules in natural language with language models](https://arxiv.org/abs/2305.09863) - Singh et al., 2023.
- [On the Biology of a Large Language Model](https://transformer-circuits.pub/2025/attribution-graphs/biology.html) - Lindsey et al., 2025.
- [Function Vectors in Large Language Models](https://arxiv.org/abs/2310.15213) - Todd et al., ICLR 2024.
- [In-Context Learning Creates Task Vectors](https://arxiv.org/abs/2310.15916) - Hendel et al., Findings of EMNLP 2023.
- [Does Localization Inform Editing? Surprising Differences in Causality-Based Localization vs. Knowledge Editing](https://arxiv.org/abs/2301.04213) - Hase et al., NeurIPS 2023.
- [Towards Best Practices of Activation Patching in Language Models: Metrics and Methods](https://arxiv.org/abs/2309.16042) - Zhang and Nanda, ICLR 2024.
- [Steering Llama 2 via Contrastive Activation Addition](https://arxiv.org/abs/2312.06681) - Rimsky et al., ACL 2024.
- [Sparse Feature Circuits: Discovering and Editing Interpretable Causal Graphs in Language Models](https://arxiv.org/abs/2403.19647) - Marks et al., ICLR 2025.
- [Not All Language Model Features Are One-Dimensionally Linear](https://arxiv.org/abs/2405.14860) - Engels et al., ICLR 2025.
- [Circuit Tracing: Revealing Computational Graphs in Language Models](https://transformer-circuits.pub/2025/attribution-graphs/methods.html) - Ameisen et al., 2025.

## Training Data Attribution

- [Understanding Black-box Predictions via Influence Functions](https://arxiv.org/abs/1703.04730) - Koh & Liang, ICML 2017.
- [Estimating Training Data Influence by Tracing Gradient Descent (TracIn)](https://arxiv.org/abs/2002.08484) - Pruthi et al., NeurIPS 2020.
- [Studying Large Language Model Generalization with Influence Functions](https://arxiv.org/abs/2308.03296) - Grosse et al., 2023.
- [Data Shapley: Equitable Valuation of Data for Machine Learning](https://arxiv.org/abs/1904.02868) - Ghorbani & Zou, ICML 2019.
- [Datamodels: Predicting Predictions from Training Data](https://arxiv.org/abs/2202.00622) - Ilyas et al., ICML 2022.
- [TRAK: Attributing Model Behavior at Scale](https://arxiv.org/abs/2303.14186) - Park et al., ICML 2023.

## Concept-Based Explanations

- [Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)](https://arxiv.org/abs/1711.11279) - Kim et al., ICML 2018.
- [Towards Automatic Concept-based Explanations](https://arxiv.org/abs/1902.03129) - Ghorbani et al., NeurIPS 2019.
- [Concept Bottleneck Models](https://arxiv.org/abs/2007.04612) - Koh et al., ICML 2020.
- [Compositional Explanations of Neurons](https://arxiv.org/abs/2006.14032) - Mu & Andreas, NeurIPS 2020.
- [Natural Language Descriptions of Deep Visual Features (MILAN)](https://arxiv.org/abs/2201.11114) - Hernandez et al., ICLR 2022.

## Datasets and Benchmarks

- [ERASER: A Benchmark to Evaluate Rationalized NLP Models](https://arxiv.org/abs/1911.03429) - DeYoung et al., ACL 2020.
- [HateXplain: A Benchmark Dataset for Explainable Hate Speech Detection](https://arxiv.org/abs/2012.10289) - Mathew et al., AAAI 2021.
- [SemEval-2023 Task 10: Explainable Detection of Online Sexism](https://arxiv.org/abs/2303.04222) - Kirk et al., SemEval 2023.
- [MIB: A Mechanistic Interpretability Benchmark](https://arxiv.org/abs/2504.13151) - Mueller et al., ICML 2025.

## Tools and Libraries

- [Captum](https://github.com/meta-pytorch/captum) - Model interpretability library for PyTorch (Integrated Gradients, DeepLIFT, and many more).
- [shap](https://github.com/shap/shap) - Game-theoretic feature attribution for any ML model.
- [lime](https://github.com/marcotcr/lime) - Local surrogate explanations for classifiers.
- [BertViz](https://github.com/jessevig/bertviz) - Interactive attention visualization for transformer models.
- [Ecco](https://github.com/jalammar/ecco) - Explorable explanations for transformer language models.
- [Language Interpretability Tool (LIT)](https://github.com/PAIR-code/lit) - Visual, interactive model-understanding workbench for NLP.
- [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](https://arxiv.org/abs/1909.09251) - Wallace et al., EMNLP 2019 demo.
- [InterpretML](https://github.com/interpretml/interpret) - Glassbox models and blackbox explainers in one package.
- [SAELens](https://github.com/decoderesearch/SAELens) - Training and analysis of sparse autoencoders for language models.
- [nnsight](https://github.com/ndif-team/nnsight) - Interpret and manipulate the internals of deep models.
- [Alibi](https://github.com/SeldonIO/alibi) - Production-oriented explainers (anchors, contrastive, counterfactual).
- [ELI5](https://github.com/TeamHG-Memex/eli5) - Classic inspection library for scikit-learn era NLP models.
- [Quantus](https://github.com/understandable-machine-intelligence-lab/Quantus) - Metrics toolkit for evaluating explanation quality.
- [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens) - The standard library for mechanistic interpretability of GPT-style language models.
- [Neuronpedia](https://www.neuronpedia.org/) - Open platform for exploring sparse-autoencoder features in language models.
- [pyvene](https://github.com/stanfordnlp/pyvene) - Composable interventions on PyTorch model internals, from Stanford NLP.
- [Inseq](https://github.com/inseq-team/inseq) - Feature attribution and analysis for sequence generation models.

## Tutorials and Courses

- [Interpreting Predictions of NLP Models](https://github.com/Eric-Wallace/interpretability-tutorial-emnlp2020) - Wallace, Gardner & Singh, EMNLP 2020 tutorial.
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/) - Molnar, online book.
- [Interfaces for Explaining Transformer Language Models](https://jalammar.github.io/explaining-transformers/) - Alammar, 2020.
- [ARENA: Transformer Interpretability Curriculum](https://github.com/ARENA-education/ARENA_materials) - McDougall et al.
- [A Comprehensive Mechanistic Interpretability Explainer and Glossary](https://www.neelnanda.io/mechanistic-interpretability/glossary) - Nanda.
- [200 Concrete Open Problems in Mechanistic Interpretability](https://www.alignmentforum.org/posts/LbrPTJ4fmABEdEnLf/200-concrete-open-problems-in-mechanistic-interpretability) - Nanda, 2022.

## Workshops and Venues

- [BlackboxNLP](https://blackboxnlp.github.io/) - Annual workshop on analyzing and interpreting neural networks for NLP, co-located with EMNLP.
- [TrustNLP](https://trustnlpworkshop.github.io/) - Workshop on trustworthy natural language processing.
- [Actionable Interpretability](https://actionable-interpretability.github.io/) - ICML workshop on putting interpretability findings to use.
- [World Conference on eXplainable Artificial Intelligence](https://xaiworldconference.com/) - Annual conference dedicated to XAI.
- [Transformer Circuits Thread](https://transformer-circuits.pub/) - Ongoing publication venue for mechanistic interpretability research.
- [InDeep](https://projects.illc.uva.nl/indeep/) - Dutch NWO consortium project on interpreting deep learning models for text and sound.

## Contributing

Contributions are welcome. Please read the [contributing guide](CONTRIBUTING.md) first.

- Suggest a paper or tool with the [entry template](https://github.com/mohammadi-hadi/awesome-explainable-nlp/issues/new/choose), or open a pull request directly.
- Report dead or moved links with the broken-link template.
- Ideas for new sections are tracked in the [roadmap](ROADMAP.md) and in [discussions](https://github.com/mohammadi-hadi/awesome-explainable-nlp/discussions).

## Maintainer

**Hadi Mohammadi** — [mohammadi.cv](https://mohammadi.cv)

## Citation

If this list is useful in your work, please cite it (see [CITATION.cff](CITATION.cff)):

```bibtex
@misc{mohammadi_awesome_explainable_nlp,
  author    = {Mohammadi, Hadi},
  title     = {Awesome Explainable NLP},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.21837426},
  url       = {https://github.com/mohammadi-hadi/awesome-explainable-nlp}
}
```
