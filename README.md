# 🗣️ Open TTS Tracker

A one stop shop to track all open-access/ source TTS models as they come out. Feel free to make a PR for all those that aren't linked here.

This is aimed as a resource to increase awareness for these models and to make it easier for researchers, developers, and enthusiasts to stay informed about the latest advancements in the field.

> [!NOTE]  
> This repo will only track open source/access codebase TTS models. More motivation for everyone to open-source! 🤗

| Name | GitHub | Weights | License | Open Source License | Fine-tune | Languages | Paper | Demo | License Issues |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| XTTS | [Repo](https://github.com/coqui-ai/TTS) | [🤗 Hub](https://huggingface.co/coqui/XTTS-v2) | [CPML](https://coqui.ai/cpml) | No | [Yes](https://huggingface.slack.com/archives/C05QZTQJUDD/p1705418518292139) | Multilingual | [Technical notes](https://erogol.substack.com/p/xttsv2-notes) | [🤗 Space](https://huggingface.co/spaces/coqui/xtts) |  |
| TorToiSe TTS | [Repo](https://github.com/neonbjb/tortoise-tts) | [🤗 Hub](https://huggingface.co/jbetker/tortoise-tts-v2) | [Apache 2.0](https://github.com/neonbjb/tortoise-tts/blob/main/LICENSE) | Yes | [Yes](https://git.ecker.tech/mrq/tortoise-tts) | English | [Technical report](https://arxiv.org/abs/2305.07243) | [🤗 Space](https://huggingface.co/spaces/Manmay/tortoise-tts) |  |
| VITS/ MMS-TTS | [Repo](https://github.com/huggingface/transformers/tree/7142bdfa90a3526cfbed7483ede3afbef7b63939/src/transformers/models/vits) | [🤗 Hub](https://huggingface.co/kakao-enterprise) / [MMS](https://huggingface.co/models?search=mms-tts) | [Apache 2.0](https://github.com/huggingface/transformers/blob/main/LICENSE) | Yes | [Yes](https://github.com/ylacombe/finetune-hf-vits) | English | [Paper](https://arxiv.org/abs/2106.06103) | [🤗 Space](https://huggingface.co/spaces/kakao-enterprise/vits) |  |
| Pheme | [Repo](https://github.com/PolyAI-LDN/pheme) | [🤗 Hub](https://huggingface.co/PolyAI/pheme) | [CC-BY](https://github.com/PolyAI-LDN/pheme/blob/main/LICENSE) | Yes | [Yes](https://github.com/PolyAI-LDN/pheme#training) | English | [Paper](https://arxiv.org/abs/2401.02839) | [🤗 Space](https://huggingface.co/spaces/PolyAI/pheme) |  |
| OpenVoice | [Repo](https://github.com/myshell-ai/OpenVoice) | [🤗 Hub](https://huggingface.co/myshell-ai/OpenVoice) | [CC-BY-NC 4.0](https://github.com/myshell-ai/OpenVoice/blob/main/LICENSE) | No (soon) | No | ZH + EN | [Paper](https://arxiv.org/abs/2312.01479) | [🤗 Space](https://huggingface.co/spaces/myshell-ai/OpenVoice) |  |
| IMS-Toucan | [Repo](https://github.com/DigitalPhonetics/IMS-Toucan) | [GH release](https://github.com/DigitalPhonetics/IMS-Toucan/tags) | [Apache 2.0](https://github.com/DigitalPhonetics/IMS-Toucan/blob/ToucanTTS/LICENSE) | Yes | [Yes](https://github.com/DigitalPhonetics/IMS-Toucan#build-a-toucantts-pipeline) | Multilingual | [Paper](https://arxiv.org/abs/2206.12229) | [🤗 Space](https://huggingface.co/spaces/Flux9665/IMS-Toucan) |  |
| Matcha-TTS | [Repo](https://github.com/shivammehta25/Matcha-TTS) | [GDrive](https://drive.google.com/drive/folders/17C_gYgEHOxI5ZypcfE_k1piKCtyR0isJ) | [MIT](https://github.com/shivammehta25/Matcha-TTS/blob/main/LICENSE) | Yes (Issue) | [Yes](https://github.com/shivammehta25/Matcha-TTS/tree/main#train-with-your-own-dataset) | English | [Paper](https://arxiv.org/abs/2309.03199) | [🤗 Space](https://huggingface.co/spaces/shivammehta25/Matcha-TTS) | Inference relies on GPL-licensed phonemizer |
| pflowTTS | [Unofficial Repo](https://github.com/p0p4k/pflowtts_pytorch) | [GDrive](https://drive.google.com/drive/folders/1x-A2Ezmmiz01YqittO_GLYhngJXazaF0) | [MIT](https://github.com/p0p4k/pflowtts_pytorch/blob/master/LICENSE) | Yes (Issue) | [Yes](https://github.com/p0p4k/pflowtts_pytorch#instructions-to-run) | English | [Paper](https://openreview.net/pdf?id=zNA7u7wtIN) | Not Available | Inference relies on GPL-licensed phonemizer |
| StyleTTS 2 | [Repo](https://github.com/yl4579/StyleTTS2) | [🤗 Hub](https://huggingface.co/yl4579/StyleTTS2-LibriTTS/tree/main) | [MIT](https://github.com/yl4579/StyleTTS2/blob/main/LICENSE) | Yes (Issue) | [Yes](https://github.com/yl4579/StyleTTS2#finetuning) | English | [Paper](https://arxiv.org/abs/2306.07691) | [🤗 Space](https://huggingface.co/spaces/styletts2/styletts2) | Inference relies on GPL-licensed phonemizer |
| VALL-E | [Unofficial Repo](https://github.com/enhuiz/vall-e) | Not Available | [MIT](https://github.com/enhuiz/vall-e/blob/main/LICENSE) | Yes | [Yes](https://github.com/enhuiz/vall-e#get-started) | NA | [Paper](https://arxiv.org/abs/2301.02111) | Not Available |  |
| HierSpeech++ | [Repo](https://github.com/sh-lee-prml/HierSpeechpp) | [GDrive](https://drive.google.com/drive/folders/1-L_90BlCkbPyKWWHTUjt5Fsu3kz0du0w) | [CC-BY-NC-SA 4.0](https://github.com/sh-lee-prml/HierSpeechpp/blob/main/LICENSE) | No | No | KR + EN | [Paper](https://arxiv.org/abs/2311.12454) | [🤗 Space](https://huggingface.co/spaces/LeeSangHoon/HierSpeech_TTS) |  |
| Bark | [Repo](https://github.com/huggingface/transformers/tree/main/src/transformers/models/bark) | [🤗 Hub](https://huggingface.co/suno/bark) | [MIT](https://github.com/suno-ai/bark/blob/main/LICENSE) | Yes | No | Multilingual | [Paper](https://arxiv.org/abs/2209.03143) | [🤗 Space](https://huggingface.co/spaces/suno/bark) |  |
| EmotiVoice | [Repo](https://github.com/netease-youdao/EmotiVoice) | [GDrive](https://drive.google.com/drive/folders/1y6Xwj_GG9ulsAonca_unSGbJ4lxbNymM) | [Apache 2.0](https://github.com/netease-youdao/EmotiVoice/blob/main/LICENSE) | Yes? | [Yes](https://github.com/netease-youdao/EmotiVoice/wiki/Voice-Cloning-with-your-personal-data) | ZH + EN | Not Available | Not Available | Has a separate [agreement](https://github.com/netease-youdao/EmotiVoice/blob/main/EmotiVoice_UserAgreement_%E6%98%93%E9%AD%94%E5%A3%B0%E7%94%A8%E6%88%B7%E5%8D%8F%E8%AE%AE.pdf) for the GUI |
| Amphion | [Repo](https://github.com/open-mmlab/Amphion) | [🤗 Hub](https://huggingface.co/amphion) | [MIT](https://github.com/open-mmlab/Amphion/blob/main/LICENSE) | Yes | No | Multilingual | [Paper](https://arxiv.org/abs/2312.09911) | [🤗 Space](https://huggingface.co/amphion) |  |
| xVASynth | [Repo](https://github.com/DanRuta/xVA-Synth) | [GH commit](https://github.com/DanRuta/xVA-Synth/tree/master/python/xvapitch/speaker_rep) | [GPL-3.0](https://github.com/DanRuta/xVA-Synth/blob/master/LICENSE.md) | Yes (Issue) | [Yes](https://github.com/DanRuta/xva-trainer) | Multilingual | [Paper](https://arxiv.org/abs/2009.14153) | Not Available | Pretrained models, used for fine-tuning, made with copyrighted materials © |

## How can you help?

Help make this list more complete. Create demos on the Hugging Face Hub and link them here :)
Got any questions? Drop me a DM on Twitter [@reach_vb](https://twitter.com/reach_vb).   
