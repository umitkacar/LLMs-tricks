# LLMs-tricks

- https://github.com/langgenius/dify

- FlashAttention never constructs a full attention matrix for the calculations
- [ALIBI](https://medium.com/@pajakamy/alibi-attention-with-linear-biases-942abe042e9f) adds a linear basis function to the attention calculation, which enables LLMs to extrapolate to longer context lengths than it was trained on
- bf16 has the same size as fp16, but the same range as fp32 (Google Brain) https://pytorch.org/docs/stable/generated/torch.Tensor.bfloat16.html

