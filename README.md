# Matin Roozbahani

MSc in Computer Science (Machine Intelligence) from the University of Basel. Before that I
worked four years as a network engineer.

I build machine learning models for medical data, and I care a lot about one question: is
the output actually right? Most of my projects end with a check that the model, the
explanation or the citation really holds up.

## Projects

| project | what it is | result |
|---|---|---|
| [ecg-xai-faithfulness-benchmark](https://github.com/matinrooz/ecg-xai-faithfulness-benchmark) | MSc thesis: do explanation methods for ECG classifiers point to what the model really uses? | ROC-AUC 0.972 for MI detection; the test design changed the result more than the explanation method |
| [rag-wiki-faithfulness](https://github.com/matinrooz/rag-wiki-faithfulness) | RAG with a local LLM, plus checks on whether its citations are real | 20% of cited sources made no difference to the answer |
| [phylogenetic-tree-reconstruction](https://github.com/matinrooz/phylogenetic-tree-reconstruction) | Four tree reconstruction methods from scratch, benchmarked on data with known answers | maximum likelihood found the exact tree 67/200 times, UPGMA 17/200 |
| [flight-delays-graph-analysis](https://github.com/matinrooz/flight-delays-graph-analysis) | 17 million US flights in Neo4j, delays and trip search in Cypher | every total checked against the raw data |
| [machine-learning-privacy-analysis](https://github.com/matinrooz/machine-learning-privacy-analysis) | Anonymization and differential privacy on a health-data model, then attacks | none of the methods protected the data well |

## Tools

Python (PyTorch, Hugging Face, scikit-learn, pandas), R, SQL, Java, Neo4j, Docker, SLURM, AWS
