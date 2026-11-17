# Paper

## Explicit Mathematical Expressions Do Not Guarantee Physical Interpretability

### Abstract
Engineers use milling stability predictions to select spindle speeds and depths of cut that avoid chatter. For an explainable model to guide those choices, it matters how its predictions change as cutting conditions vary. We examined whether a mathematical expression extracted from a Kolmogorov-Arnold network (KAN) model could explain how these parameters affect milling stability. The KAN model classified simulated cuts with 80.36% accuracy against stability labels derived from cutting-force signals. We pruned the network, extracted its symbolic expression, and compared the full and simplified expressions with established milling relationships. The extracted expressions captured some established trends in milling stability but missed important physical behavior. For example, both predicted a higher chatter score as axial depth of cut increased, consistent with milling theory. However, every term in both expressions depended on a single input, so neither represented the interactions between parameters that govern chatter, and neither could reproduce the repeated transitions between stable cutting and chatter that can occur as spindle speed varies. The full expression predicted a linear decrease in chatter score with increasing speed, while simplification removed spindle speed entirely at a cost of only 1.45 percentage points in classification accuracy. Inspecting the expressions thus exposed a limitation that their similar accuracies obscured. Whether that limitation originated in the numerical KAN model or arose during symbolic extraction remains an open question.


# Projects

## Sarcasm Detection in Reddit Conversations 1/2026 - 4/2026, University of Michigan
### Abstract
Sarcasm detection remains an important unsolved challenge in natural language processing. Failure to detect sarcasm can cause negative statements to be misclassified as positive sentiment, thereby distorting the identification of the intended tone. To investigate the most effective strategy for sarcasm detection, we conducted a comprehensive study comparing explicit manual feature engineering, such as dual-channel architectures, with implicit contextual representation learning. Overall, we evaluated performance across five distinct models: a baseline model (TF-IDF + SVM), a custom Dual-Channel Multi-Scale Convolutional Neural Network (DMS-CNN) that incorporates a semantic channel and a rule-based sentiment (VADER) channel, a hybrid BERT-CNN, and two Transformer models (BERT and DeBERTa).

Our results show that explicit architectural attempts fail to capture sarcasm. The custom DMS-CNN achieved only 69\% accuracy, which is even lower than the simpler TF-IDF baseline (74\%). In contrast, removing the manually designed structure and relying solely on end-to-end fine-tuning of DeBERTa produced the highest performance, reaching 82\% accuracy. These findings suggest that the deep contextual attention mechanisms of pre-trained language models are substantially more effective for sarcasm detection than complex manually designed architectural channels.


## Relative Belief 5/2025-8/2024, University of Toronto 
### Accomplishment

•	Achieved A+, rated highest by the professor over years, and presented to all of the department

•	Researched on the feasibility of automating experimental bias evaluations within probabilistic programming frameworks, applied both analytical and simulation approaches to assess hypothesis testing and estimate bias in various statistical models, including beta-binomial and linear regression frameworks

•	Implemented the bias in favor and bias against calculation for different models, with R/Python; optimized the algorithm time complexity by mapping arrays to matrices to handle large-scale computations

### Abstract
A fundamental concern of a theory of statistical inference is how one should measure statistical evidence. Certainly the words “statistical evidence,” or perhaps just “evidence,” are much used in statistical contexts. It is fair to say, however, that the precise characterization of this concept is somewhat elusive. Our goal here is to provide a definition of how to measure statistical evidence for any particular statistical problem. Since evidence is what causes beliefs to change, it is proposed to measure evidence by the amount beliefs change from a priori to a posteriori. As such, our definition involves prior beliefs and this raises issues of subjectivity versus objectivity in statistical analyses. This is dealt with through a principle requiring the falsifiability of any ingredients to a statistical analysis. These concerns lead to checking for prior-data conflict and measuring the a priori bias in a prior.


