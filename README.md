# EluvioDS_NLP_problem
Challenge problem : Text data exploration

- Eluvio_NLP : Uses **Pandas** dataframe throughout. Text preprocessing is sort of a bottleneck but still works fine. Please refer to this for the full exploratory analysis.

- Eluvio_NLP-withSpark : Only consists of the topic modeling part. The idea here is show the significant speed up in the preprocessing part with a **spark** dataframe which distributes the process to multiple cores. The modeling part is then handled in **Pandas** and **scikit-learn** as the other notebook.
