---
title: Dotislash Models
permalink: /models/
---

# Dotislash Models

*Last updated: November 4, 2026*

These are all the models and vision files Dotislash can download. The list comes from the catalog built into the app, and the App Store version downloads no other models. Each file is fixed to one commit of its repository on Hugging Face, so a change its publisher makes later doesn't reach the app.

Dotislash is rated 18+ on the App Store, and that one rating covers every model here. Models can make mistakes, and they can write things you may not want to read.

- **Publisher** is the Hugging Face account that publishes the file. It may have converted a model made by someone else.
- **Size** is the file alone. For a model with a vision file, the app shows the two together before you download.
- **Memory** is what an iPhone needs for the app to offer the model. The app also checks free memory before each load.
- **File** is an ordinary web link to the file's page on Hugging Face at that commit.

[Support](../) · [Privacy policy](../privacy.html)

## Models

### Qwen3.5 4B · IQ4_XS

- **Publisher:** unsloth
- **License:** Apache 2.0
- **Size:** 2.48 GB
- **Memory:** an iPhone with 8 GB or more
- **What it can do:** The fast default. It reads photos and, with tools on in Settings, searches Wikipedia and reads web pages.
- **Vision file:** Vision file for Qwen3.5 4B, 672.4 MB
- **File:** [`Qwen3.5-4B-IQ4_XS.gguf`](https://huggingface.co/unsloth/Qwen3.5-4B-GGUF/blob/e87f176479d0855a907a41277aca2f8ee7a09523/Qwen3.5-4B-IQ4_XS.gguf), commit `e87f176`

### K2 Horizon 0.9B · Q4_K_M

- **Publisher:** IFM
- **License:** Apache 2.0
- **Size:** 666.2 MB
- **Memory:** any iPhone that runs Dotislash
- **What it can do:** Small and quick to download: a good way to try the app. Text only, and its answers are basic.
- **File:** [`K2-Horizon-1B-Q4_K_M.gguf`](https://huggingface.co/IFM/K2-Horizon-0.9B-GGUF/blob/118965081cf1d876990219a1856a93a97b2668fa/K2-Horizon-1B-Q4_K_M.gguf), commit `1189650`

### K2 Horizon 3.7B · Q4_K_M

- **Publisher:** IFM
- **License:** Apache 2.0
- **Size:** 3.16 GB
- **Memory:** an iPhone with 6 GB or more
- **What it can do:** A text model for everyday questions. It can't read photos or use tools.
- **File:** [`K2-Horizon-4B-Q4_K_M.gguf`](https://huggingface.co/IFM/K2-Horizon-3.7B-GGUF/blob/78a0635e8f19b880e468a2fc82923ee6c8a469e4/K2-Horizon-4B-Q4_K_M.gguf), commit `78a0635`

### K2 Horizon 7B · IQ4_XS

- **Publisher:** bartowski
- **License:** Apache 2.0
- **Size:** 5.24 GB
- **Memory:** an iPhone with 8 GB or more
- **What it can do:** Better answers than the 3.7B, a little slower. It can't read photos or use tools.
- **File:** [`K2-Horizon-7B-IQ4_XS.gguf`](https://huggingface.co/bartowski/K2-Horizon-7B-GGUF/blob/0367e1981a5c01c45904b881c5a229694f626085/K2-Horizon-7B-IQ4_XS.gguf), commit `0367e19`

### Qwen3.8 27B · UD-IQ2_XXS

- **Publisher:** unsloth
- **License:** Apache 2.0
- **Size:** 7.27 GB
- **Memory:** an iPhone with 12 GB or more
- **What it can do:** Better answers than the 4B, but much slower: about 4 to 8 tokens per second. It reads photos and uses the same tools.
- **Vision file:** Vision file for Qwen3.8 27B, 629.2 MB
- **File:** [`Qwen3.8-27B-UD-IQ2_XXS.gguf`](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF/blob/4ca720788d1e01f1bff70c033e0d0028fd02e502/Qwen3.8-27B-UD-IQ2_XXS.gguf), commit `4ca7207`

## Vision files

A vision file lets its model read photos you attach. It comes with its model's download.

### Vision file for Qwen3.5 4B

- **Publisher:** bartowski
- **License:** Apache 2.0
- **Size:** 672.4 MB
- **Memory:** an iPhone with 8 GB or more, the same as Qwen3.5 4B · IQ4_XS
- **What it can do:** Lets Qwen3.5 4B read photos you attach. A photo takes a few seconds on iPhones with 12 GB of memory, longer on others.
- **File:** [`mmproj-Qwen_Qwen3.5-4B-f16.gguf`](https://huggingface.co/bartowski/Qwen_Qwen3.5-4B-GGUF/blob/4168f45a16a1290d65a4ec0fa312ae917a4c15d6/mmproj-Qwen_Qwen3.5-4B-f16.gguf), commit `4168f45`

### Vision file for Qwen3.8 27B

- **Publisher:** ggml-org
- **License:** Apache 2.0
- **Size:** 629.2 MB
- **Memory:** an iPhone with 12 GB or more, the same as Qwen3.8 27B · UD-IQ2_XXS
- **What it can do:** Lets Qwen3.8 27B read photos you attach. A photo takes a while to read.
- **File:** [`mmproj-Qwen3.8-27B-Q8_0.gguf`](https://huggingface.co/ggml-org/Qwen3.8-27B-GGUF/blob/a316ea527fde32c12487be7574e2db5ac2ad2a7e/mmproj-Qwen3.8-27B-Q8_0.gguf), commit `a316ea5`
