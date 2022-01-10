# clustering-laion400m
Script and models for clustering LAION-400m CLIP embeddings.

Models were fit on the first million or so image embeddings. A subjective description of what the labels appear to be is included in `cluster-labels.txt` along with counts for the first million or so embeddings (aka the first file).

Precomputed labels are here: https://archive.org/details/laion400m-64-clustering-labels.tar

Run `Fit Clusters.ipynb` to reproduce the labels or create your own clusters / models. This requires the CLIP embeddings from the LAION 400m open dataset, which can be found here: https://laion.ai/laion-400-open-dataset/
