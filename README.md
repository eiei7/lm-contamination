<img src="docs/blog/imgs/hitz_logo.png" width="300">

# LM Contamination Index

Large Language Models have seen trillions of tokens – who knows what is inside? Recent works have evaluated those models on many different tasks, but did they make sure the model had not already seen the training or even the evaluation datasets? In the [blog post](https://hitz-zentroa.github.io/lm-contamination/blog), we show that some popular benchmark datasets are already memorized by ChatGPT and that one can prompt ChatGPT to regenerate them.

In this repo, we aim to collect (as much as possible) contamination evidence to provide to the research community a reliable resource to quickly check whether the model has already seen their evaluation dataset. However, we are aware of the incompleteness of the index and therefore we ask researchers to in any case, perform an small experiment of contamination beforehand.

You can visit the search tool [LM Contamination Index](https://hitz-zentroa.github.io/lm-contamination/)

## Contributing
The amount of datasets and models is daunting. We are thus envisioning a community effort. If you are passionate about NLP research and want to contribute against contamination in LLM evaluation, please follow the [contribution guidelines](CONTRIBUTING.md)
