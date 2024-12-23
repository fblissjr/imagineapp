# imagine app
Ideally a better way to explore and automate with LLMs, vision, and audio models, with a multimodal-native design, and an on-device model with cloud API hybrid design for inference

## Why?
- Having spent the past few years building and tinkering and researching on three sides (both open source / local / on-device and API cloud-based) of the new AI era (originally, LLMs, TTS/STT/VAD audio mnodels, and diffusion models) - meaning generation of text on the LLM side, generation of images and video on the diffusion side (and now even better with flow matching) -  what I see now is a convergance across all of them into a [compound AI system](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/).
- Looking back over the years, there's always been this flow of innovation and efficiency improvement that tends to happen on one side of the equation, which leads to innovations on the other. Look at any modern image, video, or audio generation model, and you'll see it's not really one model - it's made up of modular ones - state-of-the-art (as of this writing) video generation models are actually made up of the base model itself, a VAE, multiple text encoders - more frequently including an autoregressive LLM - to guide CLIP embeddings. On the flip side of that, you have projects like LLaVA, that will aged just as much as CLIP - still power the vision encoders for video / image understanding.
- TL;DR: it's all coming together

## Vision (or the scratchpad of thoughts)
Given the longer term direction of AI is toward multimodal (inputs and outputs can be text, audio, images, video, or all the above), where multiple models make up a compound AI system, this needs to be conceptualized and imagined and designed as a multimodal, multimodal-native application. While today that means using LLMs with things like vision encoders that can handle images and videos, or audio codecs with transformer encoders and decoders, it also includes video understanding and even generation of audio, images, and video.

## Next
- to be seen?
