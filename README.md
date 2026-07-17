# MUSHROOM-SVD
Energy-efficient LLM pruning algorithm

Still writing this paper. Will share everything here after the work is submitted. For now, an overview is shared.


<img width="1200" height="660" alt="image" src="https://github.com/user-attachments/assets/937fa50c-da6d-4a6f-9567-12809343882d" />
<br> <br>

# Experimental Results

Perplexity, energy consumption, and throughput across context lengths (512–16384 tokens) for the dense baseline and five pruning/compression
methods. Mushroom-SVD (mine) is the only method that reduces energy per token and increases throughput relative to dense at every context length, while also matching FLAP’s perplexity recovery and outperforming LLM-Pruner.

<img width="3714" height="1223" alt="image" src="https://github.com/user-attachments/assets/c6bb46b5-73de-4531-a5bc-028fd7f014c4" />

<br> <br>

Efficiency-quality trade-offs relative to the dense baseline for the layer-assignment ablation, averaged across context lengths 512–16384. (a) Energy savings vs. perplexity increase. (b) Throughput change vs. perplexity increase. Shroom-SVD and FLAP-Stem are the only methods that improve both energy and throughput over dense; cats_both is excluded due to anomalous perplexity values pending investigation.

<img width="2214" height="910" alt="image" src="https://github.com/user-attachments/assets/442ac1e0-1c1a-4a42-b53f-8be8bfa5c299" />
