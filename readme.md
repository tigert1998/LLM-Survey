# MoE LLM Survey

## Models

|Model|Architecture|Paper|Date|# of Cites till 2023-06|
|-|-|-|-|-|
|MoE|LSTM (MoE)|[Outrageously large neural networks: The sparsely-gated mixture-of-experts layer](https://arxiv.org/pdf/1701.06538.pdf)|2017-01|1288|
|GShard|Encoder-Decoder (MoE)|[GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding](https://arxiv.org/pdf/2006.16668.pdf)|2020-06|413|
|Many-to-Many|Encoder-Decoder (MoE)|[Beyond English-Centric Multilingual Machine Translation](https://arxiv.org/pdf/2010.11125.pdf)|2020-10|365|
|Switch Transformer|Encoder-Decoder (MoE)|[Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/pdf/2101.03961.pdf)|2021-01|734|
|task-MoE|Encoder-Decoder (MoE)|[Beyond Distillation: Task-level Mixture-of-Experts for Efficient Inference](https://arxiv.org/pdf/2110.03742.pdf)|2021-09|34|
|GLaM|Decoder (MoE)|[GLaM: Efficient Scaling of Language Models with Mixture-of-Experts](https://arxiv.org/pdf/2112.06905.pdf)|2021-12|125|
|NLLB-MoE|Encoder-Decoder (MoE)|[No Language Left Behind: Scaling Human-Centered Machine Translation](https://arxiv.org/ftp/arxiv/papers/2207/2207.04672.pdf)|2022-07|71|

## Inference Frameworks

|Inference Framework|Organization|Link|
|-|-|-|
|FasterTransformer|NVIDIA|[Link](https://github.com/NVIDIA/FasterTransformer)|
|LLaMA.cpp||[Link](https://github.com/bytedance/ByteTransformer)|
|ByteTransformer|ByteDance|[Link](https://github.com/bytedance/ByteTransformer)|
|InferLLM|旷视|[Link](https://github.com/MegEngine/InferLLM)|