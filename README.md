# Matin Roozbahani

MSc in Computer Science (Machine Intelligence) from the University of Basel. Before that I
worked four years as a network engineer.

I build machine learning models for medical data, and I care a lot about one question: is
the output actually right? Most of my projects end with a check that the model, the
explanation or the citation really holds up.

## What I've been working on

**[ecg-xai-faithfulness-benchmark](https://github.com/matinrooz/ecg-xai-faithfulness-benchmark)**
is my MSc thesis. I trained ECG classifiers to detect myocardial infarction (ROC-AUC 0.972)
and then tested whether explanation methods really point to the part of the signal the model
uses. The surprising part: how you design the test changed the result more than which
explanation method you pick.

**[rag-wiki-faithfulness](https://github.com/matinrooz/rag-wiki-faithfulness)** asks the same
question for LLMs. A RAG system cites its sources, but does the answer really depend on them?
I removed sources one at a time and checked. In my test, 20% of the cited sources made no
difference at all.

**[phylogenetic-tree-reconstruction](https://github.com/matinrooz/phylogenetic-tree-reconstruction)**
has four classic tree-building methods written from scratch, and a benchmark on simulated
data where I know the right answer. Maximum likelihood found the exact tree 67 times out of
200, UPGMA only 17.

**[flight-delays-graph-analysis](https://github.com/matinrooz/flight-delays-graph-analysis)**
puts 17 million US flights into Neo4j to look at delays, cancellations and how many plane
changes a trip needs. Every number from the graph is checked against the raw data.

**[machine-learning-privacy-analysis](https://github.com/matinrooz/machine-learning-privacy-analysis)**
is a group project where we protected a health-data model with anonymization and
differential privacy, then attacked it. None of the methods protected the data well, which
was the most useful thing we learned.

## Smaller projects

- [variational-bayesian-group-lasso](https://github.com/matinrooz/variational-bayesian-group-lasso): Bayesian group lasso with normalizing flows in PyTorch
- [modern-rl-from-agents-to-llms](https://github.com/matinrooz/modern-rl-from-agents-to-llms): reinforcement learning, from dynamic programming to RLHF, DPO and GRPO
- [femur_asm_segmentation](https://github.com/matinrooz/femur_asm_segmentation) and [femur-reconstruction-ssm](https://github.com/matinrooz/femur-reconstruction-ssm): statistical shape models for 3D CT, in Scala
- [nlp-text-analytics](https://github.com/matinrooz/nlp-text-analytics): where simple NLP methods beat neural ones, and where they don't
- [quasi-newton-methods-for-optimization](https://github.com/matinrooz/quasi-newton-methods-for-optimization): BFGS, DFP and SR1 compared with gradient descent

## Tools I use

Python (PyTorch, Hugging Face, scikit-learn, pandas), R, SQL, Java, Neo4j, Docker, SLURM, AWS
