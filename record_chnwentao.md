### 2016-6-13

The implementation in spark.mllib has the following parameters:

- `numBlocks` is the number of blocks used to parallelize computation (set to -1 to auto-configure).
- `rank` is the number of latent factors in the model.
- `iterations` is the number of iterations to run.
- `lambda` specifies the regularization parameter in ALS.
- `implicitPrefs` specifies whether to use the explicit feedback ALS variant or one adapted for implicit - - feedback data.
- `alpha ` is a parameter applicable to the implicit feedback variant of ALS that governs the baseline confidence in preference observations.``
