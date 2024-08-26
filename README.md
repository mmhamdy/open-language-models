<div align="center">
  <h1>The Open Language Models List</h1>
</div>

## 📄 Introduction

This is a list of permissively licensed language models with MIT, Apache 2.0, or other similar licenses. We are using the term language model broadly here to include not only autoregressive models but also models that were trained with different objectives such as MLM.

This work was mostly inspired by [Stella Biderman](https://github.com/StellaAthena)'s [Directory of Generative AI](https://docs.google.com/spreadsheets/d/1gc6yse74XCwBx028HV_cvdxwXkmXejVjkO-Mz2uwE0k/edit?gid=0#gid=0), and [The Foundation Model Development Cheatsheet](https://github.com/allenai/fm-cheatsheet). But unlike these two very comprehensive sources, this work is meant to be a quick and more focused reference.

- 👑: Model + Data + Code
- ⭐: Model + Data
- ⚡: Model + Code
  
> [!IMPORTANT]
> This is still a work in progress. Contributions, corrections, and feedback are very welcome!

## 🤖 Models

| Model                       | Parameters   | Architecture    | Encoder   | Decoder   | MoE   |   Year | Hugging Face                                                               | License    |
|:----------------------------|:-------------|:----------------|:----------|:----------|:------|-------:|:---------------------------------------------------------------------------|:-----------|
| GPT-1                       | 120M         | Transformer     | -         | ✅        | -     |   2018 | [🤗](https://huggingface.co/openai-community/openai-gpt)                         | MIT        |
| BERT-Base-Cased             | 110M         | Transformer     | ✅        | -         | -     |   2018 | [🤗](https://huggingface.co/google-bert/bert-base-cased)                         | Apache 2.0 |
| BERT-Base-Uncased           | 110M         | Transformer     | ✅        | -         | -     |   2018 | [🤗](https://huggingface.co/google-bert/bert-base-uncased)                      | Apache 2.0 |
| BERT-Large-Cased            | 340M         | Transformer     | ✅        | -         | -     |   2018 | [🤗](https://huggingface.co/google-bert/bert-large-cased)                        | Apache 2.0 |
| BERT-Large-Uncased          | 340M         | Transformer     | ✅        | -         | -     |   2018 | [🤗](https://huggingface.co/google-bert/bert-large-uncased)                      | Apache 2.0 |
| GPT-2-Small                 | 124M         | Transformer     | -         | ✅        | -     |   2019 | [🤗](https://huggingface.co/openai-community/gpt2)                               | MIT        |
| GPT-2-Medium                | 355M         | Transformer     | -         | ✅        | -     |   2019 | [🤗](https://huggingface.co/openai-community/gpt2-medium)                        | MIT        |
| GPT-2-Large                 | 774M         | Transformer     | -         | ✅        | -     |   2019 | [🤗](https://huggingface.co/openai-community/gpt2-large)                         | MIT        |
| GPT-2-XL                    | 1.5B         | Transformer     | -         | ✅        | -     |   2019 | [🤗](https://huggingface.co/openai-community/gpt2-xl)                            | MIT        |
| T5-Small👑                  | 60M          | Transformer     | ✅        | ✅        | -     |   2019 | [🤗](https://huggingface.co/google-t5/t5-small)                                  | Apache 2.0 |
| T5-Base👑                   | 220M         | Transformer     | ✅        | ✅        | -     |   2019 | [🤗](https://huggingface.co/google-t5/t5-base)                                   | Apache 2.0 |
| T5-Large👑                  | 770M         | Transformer     | ✅        | ✅        | -     |   2019 | [🤗](https://huggingface.co/google-t5/t5-large)                                  | Apache 2.0 |
| T5-3B👑                     | 3B           | Transformer     | ✅        | ✅        | -     |   2019 | [🤗](https://huggingface.co/google-t5/t5-3b)                                     | Apache 2.0 |
| T5-11B👑                    | 11B          | Transformer     | ✅        | ✅        | -     |   2019 | [🤗](https://huggingface.co/google-t5/t5-11b)                                     | Apache 2.0 |
| XLM-RoBERTa-Large           | 560M         | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/FacebookAI/xlm-roberta-large)                         | MIT        |
| XLM-RoBERTa-Base            | 250M         | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/FacebookAI/xlm-roberta-base)                          | MIT        |
| RoBERTa-Base                | 125M         | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/FacebookAI/roberta-base)                              | MIT        |
| RoBERTa-Large               | 355M         | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/FacebookAI/roberta-large)                             | MIT        |
| DistilBERT-Base-Cased       | 66M          | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/distilbert/distilbert-base-cased)                     | Apache 2.0 |
| DistilBERT-Base-Uncased     | 66M          | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/distilbert/distilbert-base-uncased)                   | Apache 2.0 |
| ALBERT-Base                 | 12M          | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/albert/albert-base-v2)                                | Apache 2.0 |
| ALBERT-Large                | 18M          | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/albert/albert-large-v2)                               | Apache 2.0 |
| ALBERT-XLarge               | 60M          | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/albert/albert-xlarge-v2)                              | Apache 2.0 |
| ALBERT-XXLarge              | 235M         | Transformer     | ✅        | -         | -     |   2019 | [🤗](https://huggingface.co/albert/albert-xxlarge-v2)                            | Apache 2.0 |
| DeBERTa-Base                | 134M         | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/microsoft/deberta-base)                               | MIT        |
| DeBERTa-Large               | 350M         | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/microsoft/deberta-large)                              | MIT        |
| DeBERTa-XLarge              | 750M         | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/microsoft/deberta-xlarge)                             | MIT        |
| ELECTRA-Small-Discriminator | 14M          | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/google/electra-small-discriminator)                   | Apache 2.0 |
| ELECTRA-Base-Discriminator  | 110M         | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/google/electra-base-discriminator)                    | Apache 2.0 |
| ELECTRA-Large-Discriminator | 335M         | Transformer     | ✅        | -         | -     |   2020 | [🤗](https://huggingface.co/google/electra-large-discriminator)                   | Apache 2.0 |
| GPT-Neo-125M👑              | 125M         | Transformer     | -         | ✅        | -     |   2021 | [🤗](https://huggingface.co/EleutherAI/gpt-neo-125m)                              | MIT        |
| GPT-Neo-1.3B👑              | 1.3B         | Transformer     | -         | ✅        | -     |   2021 | [🤗](https://huggingface.co/EleutherAI/gpt-neo-1.3B)                              | MIT        |
| GPT-Neo-2.7B👑              | 2.7B         | Transformer     | -         | ✅        | -     |   2021 | [🤗](https://huggingface.co/EleutherAI/gpt-neo-2.7B)                              | MIT        |
| GPT-J👑                     | 6B           | Transformer     | -         | ✅        | -     |   2021 | [🤗](https://huggingface.co/EleutherAI/gpt-j-6b)                                  | Apache 2.0 |
| XLM-RoBERTa-XL              | 3.5B         | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/facebook/xlm-roberta-xl)                              | MIT        |
| XLM-RoBERTa-XXL             | 10.7B        | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/facebook/xlm-roberta-xxl)                             | MIT        |
| DeBERTa-v2-XLarge           | 900M         | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v2-xlarge)                          | MIT        |
| DeBERTa-v2-XXLarge          | 1.5M         | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v2-xxlarge)                         | MIT        |
| DeBERTa-v3-XSmall           | 22M          | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v3-xsmall)                          | MIT        |
| DeBERTa-v3-Small            | 44M          | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v3-small)                           | MIT        |
| DeBERTa-v3-Base             | 86M          | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v3-base)                            | MIT        |
| DeBERTa-v3-Large            | 304M         | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/deberta-v3-large)                           | MIT        |
| mDeBERTa-v3-Base            | 86M          | Transformer     | ✅        | -         | -     |   2021 | [🤗](https://huggingface.co/microsoft/mdeberta-v3-base)                           | MIT        |
| GPT-NeoX👑                  | 20B          | Transformer     | -         | ✅        | -     |   2022 | [🤗](https://huggingface.co/EleutherAI/gpt-neox-20b)                              | Apache 2.0 |
| UL2👑                       | 20B          | Transformer     | ✅        | ✅        | -     |   2022 | [🤗](https://huggingface.co/google/ul2)                                           | Apache 2.0 |
| YaLM⚡                      | 100B         | Transformer     | -         | ✅        | -     |   2022 | [🤗](https://huggingface.co/yandex/yalm-100b)                                     | Apache 2.0 |
| Pythia-14M👑                | 14M          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-14m)                                | Apache 2.0 |
| Pythia-70M👑                | 70M          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-70m)                                | Apache 2.0 |
| Pythia-160M👑               | 160M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-160m)                               | Apache 2.0 |
| Pythia-410M👑               | 410M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-410m)                               | Apache 2.0 |
| Pythia-1B👑                 | 1B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-1b)                                 | Apache 2.0 |
| Pythia-1.4B👑               | 1.4B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-1.4b)                              | Apache 2.0 |
| Pythia-2.8B👑               | 2.8B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-2.8b)                               | Apache 2.0 |
| Pythia-6.9B👑               | 6.9B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-6.9b)                               | Apache 2.0 |
| Pythia-12B👑                | 12B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/EleutherAI/pythia-12b)                                | Apache 2.0 |
| Cerebras-GPT-111M⭐         | 111M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-111M)                           | Apache 2.0 |
| Cerebras-GPT-256M⭐         | 256M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-256M)                           | Apache 2.0 |
| Cerebras-GPT-590M⭐         | 590M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-590M)                           | Apache 2.0 |
| Cerebras-GPT-1.3B⭐         | 1.3B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-1.3B)                           | Apache 2.0 |
| Cerebras-GPT-2.7B⭐         | 2.7B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-2.7B)                           | Apache 2.0 |
| Cerebras-GPT-6.7B⭐         | 6.7B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-6.7B)                           | Apache 2.0 |
| Cerebras-GPT-13B⭐          | 13B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/Cerebras-GPT-13B)                            | Apache 2.0 |
| BTLM👑                      | 3B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/cerebras/btlm-3b-8k-base)                             | Apache 2.0 |
| Phi-1                       | 1.3B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/microsoft/phi-1)                                      | MIT        |
| Phi-1.5                     | 1.3B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/microsoft/phi-1_5)                                    | MIT        |
| Phi-2                       | 2.7B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/microsoft/phi-2)                                      | MIT        |
| RedPajama-INCITE-3B👑       | 2.8B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/togethercomputer/RedPajama-INCITE-Base-3B-v1)         | Apache 2.0 |
| RedPajama-INCITE-7B👑       | 6.9B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/togethercomputer/RedPajama-INCITE-7B-Base)            | Apache 2.0 |
| FLM                         | 101B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/CofeAI/FLM-101B)                                      | Apache 2.0 |
| MPT-7B                      | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mosaicml/mpt-7b)                                      | Apache 2.0 |
| MPT-7B-8K                   | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mosaicml/mpt-7b-8k)                                   | Apache 2.0 |
| MPT-30B                     | 30B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mosaicml/mpt-30b)                                     | Apache 2.0 |
| Mistral-7B-v0.1             | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mistralai/Mistral-7B-v0.1)                            | Apache 2.0 |
| Mistral-7B-v0.2             | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mistral-community/Mistral-7B-v0.2)                    | Apache 2.0 |
| Mistral-7B-v0.3             | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/mistralai/Mistral-7B-v0.3)                            | Apache 2.0 |
| Falcon-7B                   | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/tiiuae/falcon-7b)                                     | Apache 2.0 |
| Falcon-40B                  | 40B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/tiiuae/falcon-40b)                                    | Apache 2.0 |
| TinyLlama                   | 1.1B         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/TinyLlama/TinyLlama-1.1B-intermediate-step-1431k-3T)  | Apache 2.0 |
| OpenLLaMA-3B-v1👑           | 3B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/openlm-research/open_llama_3b)                        | Apache 2.0 |
| OpenLLaMA-7B-v1👑           | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/openlm-research/open_llama_7b)                        | Apache 2.0 |
| OpenLLaMA-13B-v1👑          | 13B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/openlm-research/open_llama_13b)                       | Apache 2.0 |
| OpenLLaMA-3B-v2👑           | 3B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/openlm-research/open_llama_3b_v2)                     | Apache 2.0 |
| OpenLLaMA-7B-v2👑           | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/openlm-research/open_llama_7b_v2)                     | Apache 2.0 |
| DeciLM-7B                   | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/Deci/DeciLM-7B)                                       | Apache 2.0 |
| Amber👑                     | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/LLM360/Amber)                                         | Apache 2.0 |
| Solar                       | 10.7B        | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/upstage/SOLAR-10.7B-v1.0)                             | Apache 2.0 |
| Mixtral-8x7B                | 46.7B        | Transformer     | -         | ✅        | ✅    |   2023 | [🤗](https://huggingface.co/mistralai/Mixtral-8x7B-v0.1)                          | Apache 2.0 |
| OpenMoE-base-128B           | 637M         | Transformer     | -         | ✅        | ✅    |   2023 | [🤗](https://huggingface.co/OrionZheng/openmoe-base)                              | Apache 2.0 |
| Mamba-130M                  | 130M         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-130m-hf)                           | Apache 2.0 |
| Mamba-370M                  | 370M         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-370m-hf)                           | Apache 2.0 |
| Mamba-790M                  | 790M         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-790m-hf)                           | Apache 2.0 |
| Mamba-1.4B                  | 1.4M         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-1.4b-hf)                           | Apache 2.0 |
| Mamba-2.8B                  | 2.8B         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-2.8b-hf)                           | Apache 2.0 |
| Mamba-2.8B-slimpj           | 2.8B         | SSM             | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/state-spaces/mamba-2.8b-slimpj)                       | Apache 2.0 |
| OpenBA                      | 15B          | Transformer     | ✅        | ✅        | -     |   2023 | [🤗](https://huggingface.co/OpenNLG/OpenBA-V1-Based)                              | Apache 2.0 |
| Yi-6B                       | 6B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/01-ai/Yi-6B)                                          | Apache 2.0 |
| Yi-6B-200K                  | 6B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/01-ai/Yi-6B-200K)                                     | Apache 2.0 |
| Yi-9B                       | 9B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/01-ai/Yi-9B)                                          | Apache 2.0 |
| Yi-9B-200K                  | 9B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/01-ai/Yi-9B-200K)                                     | Apache 2.0 |
| Yi-34B-200K                 | 34B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/01-ai/Yi-34B-200K)                                    | Apache 2.0 |
| Persimmon-8B                | 8B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/adept/persimmon-8b-base)                              | Apache 2.0 |
| Palmyra-3B                  | 3B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/Writer/palmyra-3B)                                    | Apache 2.0 |
| Palmyra-Small-128M          | 128M         | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/Writer/palmyra-small)                                 | Apache 2.0 |
| Palmyra-Base-5B             | 5B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/Writer/palmyra-base)                                  | Apache 2.0 |
| Palmyra-Large-20B           | 20B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/Writer/palmyra-large)                                 | Apache 2.0 |
| SEA-LION-3B                 | 3B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/aisingapore/sea-lion-3b)                              | MIT        |
| SEA-LION-7B                 | 7B           | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/aisingapore/sea-lion-7b)                              | MIT        |
| PLaMo-13B                   | 13B          | Transformer     | -         | ✅        | -     |   2023 | [🤗](https://huggingface.co/pfnet/plamo-13b)                                      | Apache 2.0 |
| LiteLlama                   | 460M         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/ahxt/LiteLlama-460M-1T)                               | MIT        |
| H2O-Danube                  | 1.8B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/h2oai/h2o-danube-1.8b-base)                           | Apache 2.0 |
| H2O-Danube2                 | 1.8B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/h2oai/h2o-danube2-1.8b-base)                          | Apache 2.0 |
| Cosmo                       | 1.8B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/HuggingFaceTB/cosmo-1b)                               | Apache 2.0 |
| MobiLlama-0.5B              | 0.5B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/MBZUAI/MobiLlama-05B)                                 | Apache 2.0 |
| MobiLlama-0.8B              | 0.8B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/MBZUAI/MobiLlama-08B)                                 | Apache 2.0 |
| MobiLlama-1B                | 1.2B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/MBZUAI/MobiLlama-1B)                                  | Apache 2.0 |
| OLMo-1B👑                   | 1B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/allenai/OLMo-1B)                                      | Apache 2.0 |
| OLMo-7B👑                   | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/allenai/OLMo-7B)                                     | Apache 2.0 |
| OLMo-7B-Twin-2T👑           | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/allenai/OLMo-7B-Twin-2T)                              | Apache 2.0 |
| OLMo-1.7-7B👑               | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/allenai/OLMo-1.7-7B)                                  | Apache 2.0 |
| Poro                        | 34B          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/LumiOpen/Poro-34B)                                    | Apache 2.0 |
| Grok-1                      | 314B         | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/xai-org/grok-1)                                       | Apache 2.0 |
| OpenMoe-8b-1.1T             | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b)                                | Apache 2.0 |
| OpenMoE-8B-1T               | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b-1T)                             | Apache 2.0 |
| OpenMoE-8B-800B             | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b-800B)                           | Apache 2.0 |
| OpenMoE-8B-600B             | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b-600B)                           | Apache 2.0 |
| OpenMoE-8B-400B             | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b-400B)                           | Apache 2.0 |
| OpenMoE-8B-200B             | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-8b-200B)                          | Apache 2.0 |
| OpenMoE-34B-200B            | 34B          | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/OrionZheng/openmoe-34b-200B)                          | Apache 2.0 |
| Jamba                       | 52B          | SSM-Transformer | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/ai21labs/Jamba-v0.1)                                  | Apache 2.0 |
| JetMoE                      | 8B           | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/jetmoe/jetmoe-8b)                                     | Apache 2.0 |
| Mambaoutai                  | 1.6B         | SSM             | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/lightonai/mambaoutai)                                 | Apache 2.0 |
| Tele-FLM                    | 52B          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/CofeAI/Tele-FLM)                                      | Apache 2.0 |
| Arctic-Base                 | 480B         | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/Snowflake/snowflake-arctic-base)                     | Apache 2.0 |
| Zamba-7B                    | 7B           | SSM-Transformer | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/Zyphra/Zamba-7B-v1)                                   | Apache 2.0 |
| Mixtral-8x22B-v0.1          | 141B         | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/mistralai/Mixtral-8x22B-v0.1)                         | Apache 2.0 |
| Granite-7b-base             | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/ibm/granite-7b-base)                                  | Apache 2.0 |
| Chuxin-1.6B-Base👑          | 1.6B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/chuxin-llm/Chuxin-1.6B-Base)                          | MIT        |
| Chuxin-1.6B-1M👑            | 1.6B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/chuxin-llm/Chuxin-1.6B-1M)                            | MIT        |
| Neo👑                       | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/m-a-p/neo_7b)                                         | Apache 2.0 |
| Yi-1.5-6B                   | 6B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/01-ai/Yi-1.5-6B)                                      | Apache 2.0 |
| Yi-1.5-9B                   | 9B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/01-ai/Yi-1.5-9B)                                      | Apache 2.0 |
| Yi-1.5-34B                  | 34B          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/01-ai/Yi-1.5-34B)                                     | Apache 2.0 |
| GECKO-7B                    | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/kifai/GECKO-7B)                                       | Apache 2.0 |
| Qwen2-0.5B                  | 0.5B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/Qwen/Qwen2-0.5B)                                      | Apache 2.0 |
| Qwen2-1.5B                  | 1.5B         | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/Qwen/Qwen2-1.5B)                                      | Apache 2.0 |
| Qwen2-7B                    | 7B           | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/Qwen/Qwen2-7B)                                        | Apache 2.0 |
| Qwen2-57B-A14B              | 57B          | Transformer     | -         | ✅        | ✅    |   2024 | [🤗](https://huggingface.co/Qwen/Qwen2-57B-A14B)                                  | Apache 2.0 |
| K2👑                        | 65B          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/LLM360/K2)                                            | Apache 2.0 |
| Pile-T5-Base👑              | 248M         | Transformer     | ✅        | ✅        | -     |   2024 | [🤗](https://huggingface.co/EleutherAI/pile-t5-base)                              | Apache 2.0 |
| Pile-T5-Large👑             | 783M         | Transformer     | ✅        | ✅        | -     |   2024 | [🤗](https://huggingface.co/EleutherAI/pile-t5-large)                             | Apache 2.0 |
| Pile-T5-XL👑                | 2.85B        | Transformer     | ✅        | ✅        | -     |   2024 | [🤗](https://huggingface.co/EleutherAI/pile-t5-xl)                                | Apache 2.0 |
| SmolLM-135M👑               | 135M          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/HuggingFaceTB/SmolLM-135M)                            | Apache 2.0 |
| SmolLM-360M👑               | 360M          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/HuggingFaceTB/SmolLM-360M)                            | Apache 2.0 |
| SmolLM-1.7B👑               | 1.7B          | Transformer     | -         | ✅        | -     |   2024 | [🤗](https://huggingface.co/HuggingFaceTB/SmolLM-1.7B)                            | Apache 2.0 |

## 📚 Resources

### About Openness

- **[Blog post]** [What "Open" Means](https://future.mozilla.org/news/what-open-means/): A great blog post by John Shaughnessy discussing how the many different incarnations of the word "open".
- **[Paper]** [Towards a Framework for Openness in Foundation Models](https://foundation.mozilla.org/en/research/library/towards-a-framework-for-openness-in-foundation-models/): In this paper, Mozilla and Columbia Institute of Global Politics brought together over 40 leading scholars and practitioners working on openness and AI to discuss the highly debated definitions and benefits of open sourcing foundation models. Among this team are Victor Storchan, Yann LeCun, Justine Tunney, Nathan Lambert, and many others.
- **[Paper]** [Rethinking open source generative AI](https://dl.acm.org/doi/10.1145/3630106.3659005): This paper surveys over 45 generative AI models using an evidence-based framework that distinguishes 14 dimensions of openness, from training datasets to scientific and technical documentation and from licensing to access methods.
- **[Paper]** [Risks and Opportunities of Open-Source Generative AI](https://arxiv.org/abs/2405.08597): This paper analyzes the risks and opportunities of open-source generative AI models using a three-stage framework for Gen AI development (near, mid
and long-term), and argues that, overall, the benefits of open-source Gen AI outweigh its risks.
