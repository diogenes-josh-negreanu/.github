# About JoshGPT

About page: [joshnegreanu.com/about-joshgpt](https://joshnegreanu.com/about-joshgpt)<br>
Chatbot: [joshnegreanu.com/chat](https://joshnegreanu.com/chat)<br>
Portfolio: [joshnegreanu.com](https://joshnegreanu.com)

### Personal introduction
My name is Josh Negreanu, and I am a current PhD student at Oregon State University. I study the design and development of modern deep learning models for various applications. Throughout my academic and personal pursuits in AI, I have found that the best way to learn something is to simply do it.

> So what better way to learn about modern LLMs and frontier models than to attempt to build one?

This is the core idea behind the project.

### About the project
JoshGPT is a from-scratch custom-built and -trained LLM chatbot, fully open source and fully experimental. It serves as a platform for me to build my AI development and deployment expertise. It also serves as a viable method of training and deploying language models with experimental architectures, closely pertaining to my research in diffusion language models.

### Organization structure
This organization contains three main repositories:
- `joshgpt`
- `joshgpt-server`
- `joshgpt-webapp`

The `joshgpt` repository contains code pertaining to the model architecture, training, and inference. There are also miscellaneous scripts for data downloading and configuration.

The `joshgpt-server` and `joshgpt-webapp` repositories contain code pertaining to the chatbot deployment of the model. Diogenes uses the ChatML standard; the server and webapp communicate through a FastAPI connection that allows streaming of individual tokens during generation.

### Chat with JoshGPT
JoshGPT is (during certain periods) available for use as a chatbot via [joshnegreanu.com/chat](https://joshnegreanu.com/chat). I am currently in the process of training `diogenes-beta`, a newer, more capable, and faster architecture. Please visit the blog at [joshnegreanu.com/about-joshgpt](https://joshnegreanu.com/about-joshgpt) for more information.
