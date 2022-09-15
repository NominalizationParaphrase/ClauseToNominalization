# Automatic Nominalization of Clauses through Textual Entailment

## Abstract
Nominalization re-writes a clause as a noun phrase. It requires the transformation of the head verb of the clause into a deverbal noun, and the verb’s modifiers into nominal modifiers. Past research has focused on the selection of deverbal nouns, but has paid less attention to predicting the word order and word forms for the nominal modifiers. We propose the use of a textual entailment model for clause nominal- ization. We obtained the best performance by fine-tuning a textual entailment model on this task, outperforming a number of unsupervised approaches using language model scores from a state-of-the-art neural model.

## Tools
1. Spacy == 2.2.4
2. Pandas
3. BERT-based Masked Language Model : https://demo.allennlp.org/masked-lm
4. TextualEntailment : https://demo.allennlp.org/textual-entailment/roberta-snli
5. GPT & DistilBert : https://github.com/awslabs/mlm-scoring
