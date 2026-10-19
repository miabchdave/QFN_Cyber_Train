New Cybertrain Benchmark for Qwen Flash Next ;-) from https://www.reddit.com/r/LocalLLaMA/comments/1x85hfj/comment/phavui9/?utm_source=share

Prompt:  Build a beautiful 3D scene of a train driving through a futuristic cyberpunk city in HTML. dystopian vibes, detailed models, try not to use too many boxes in the models. Be creative and add some user interactivity like camera and weather controls.

Harness: Pi (browser use extension added - and the model definitely used it)

Model: https://huggingface.co/miabchdave/Qwen3.8-Flash-Next-oQ5e-mtp
Grafted: Replaced default quant PLE (ngram) safe tensors in this model with BF16 PLE from Qwen.  
NOTE: The BF16 PLE is not in HF linked model above.  The raw BF16 PLE layers are 102GB vs ~50GB default.  You can ask your friendly AI to graft layers from the Qwen repo.
<img width="640" height="360" alt="Screenshot 2026-10-18 at 7 41 47 PM Medium" src="https://github.com/user-attachments/assets/688502a6-8234-43bd-ae09-5d30542aad27" />

