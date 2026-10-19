New Cybertrain Benchmark for Qwen Flash Next ;-) from https://www.reddit.com/r/LocalLLaMA/comments/1x85hfj/comment/phavui9/?utm_source=share

Prompt:  Build a beautiful 3D scene of a train driving through a futuristic cyberpunk city in HTML. dystopian vibes, detailed models, try not to use too many boxes in the models. Be creative and add some user interactivity like camera and weather controls.

Harness: Pi (browser use extension added - and the model definitely used it)

Model: https://huggingface.co/miabchdave/Qwen3.8-Flash-Next-oQ5e-mtp
Grafted: Replaced quantum PLE (ngram) safe tensors with BF16 PLE from Qwen (not in HF model above, those layers are 102GB vs ~50GB default for quants).
