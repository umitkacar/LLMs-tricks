# LLMs-tricks

- FlashAttention never constructs a full attention matrix for the calculations
- [ALIBI](https://medium.com/@pajakamy/alibi-attention-with-linear-biases-942abe042e9f) adds a linear basis function to the attention calculation, which enables LLMs to extrapolate to longer context lengths than it was trained on

