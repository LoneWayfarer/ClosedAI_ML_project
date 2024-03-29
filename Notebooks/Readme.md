This directory consists of notebooks, which were used during the completion of the final project.
In total there are 8 of them:
1. `Transactions_catboost_and_embed_size_experiment.ipynb` was used to get the embeddings for the downstream task, using transactions dataset and COLES method. Also the metrics for the downstream task was obtained, as well as experiment on the dependency between the embedding size and quality of the model was conducted using transactions
2. `clickstreams.ipynb` was used to preprocess large dataset of clickstreams using PySpark. Also here ids of clients was matched and .parquet files was created for further use in training the COLES model
3. `Clickstreams_catboost_and_embed_size_experiment.ipynb` was used to get the embeddings for the downstream task, using Clickstreams dataset and COLES method. Also the metrics for the downstream task was obtained, as well as experiment on the dependency between the embedding size and quality of the model was conducted using clickstreams
4. `Transactions_agg.ipynb` was used to obtain embeddings, using AggFeature encoder and get the metrics on the downstream task for transactions dataset
5. `Transactions_random_enc.ipynb` was used to obtain embeddings, using Random Encoder and get the metrics on the downstream task for transactions dataset
6. `clickstream_processor.ipynb` was used for processing cliskstream dataset and reducing it's size
7. `Clickstream_agg.ipynb` was used to obtain embeddings, using AggFeature encoder and get the metrics on the downstream task for clickstream dataset
8. `Clickstream_random_enc.ipynb` was used to obtain embeddings, using Random Encoder and get the metrics on the downstream task for clickstream dataset
9. `clickstream+hyperparams.ipynb` was used to obtain embeddings from preprocessed data from `clickstreams.ipynb` and run experimenets for different encoders and sampling methods for clickstream dataset.
10. `transactions+hyperparams.ipynb` was used to obtain embeddings for transaction dataset and run experiments for different encoders and sampling methods.
