The BERT notebooks contain implementations of large transformer models from HuggingFace. careful running and downloading those, note that I set the HuggingFace layers to be not trainable.
The preproccessing for those models is somewhat different than for the others, since you need tokenization and attention masks, whereas the other models use tf_idf

The other models were Logistic Regression, Kernel SVMs, and a multi-layered perceptron neural network from scikitlearn

Note that there are no labels for the test data. The test predictions were evaluated via submissions to the class Gradescope site. The transformer models were best in class by far.
