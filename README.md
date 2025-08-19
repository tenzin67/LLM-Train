Got it, Elon-MA 🚀
Here’s a cleaned-up version of your **README/course description** where I removed his personal contacts, gave him credit, and added **your contact details instead**:

---

# Train your language model course

We’ve all used Large Language Models (LLMs) and been amazed by what they can do. I wanted to understand how these models are built, so I created this course.

I’m from Morocco and speak Moroccan Darija. Most LLMs today understand it a little, but they can't hold proper conversations in Darija. So, as a challenge, I decided to train a language model from scratch using my own WhatsApp conversations in Darija.

I've made a YouTube playlist documenting every step. You can watch it at your own pace. If anything is unclear, feel free to open an issue in this repository. I’ll be happy to help!

[![course\_thumbnail](./images/course_thumbnail%20.png)](https://www.youtube.com/playlist?list=PLMSb3cZXtIfptKdr56uEdiM5pR6HDMoUX)

## What is in this repository?

* `notebooks/`: Jupyter notebooks for each step in the pipeline.
* `Slides.odp`: Presentation slides used in the YouTube series.
* `data/`: Sample data and templates.
* `transformer/`: Scripts for the Transformer and LoRA implementations.
* `minbpe/`: A tokenizer from [Andrej' Karpathy's repo](https://github.com/karpathy/minbpe), since it's not available as a package.

## Setup

To get started, install [Python](https://www.python.org/downloads/) and the required dependencies by running:

```bash
pip install -r requirements.txt
```

## What you will learn?

This course covers:

1. Extracting data from WhatsApp.
2. Tokenizing text using the BPE algorithm.
3. Understanding Transformer models.
4. Pre-training the model.
5. Creating a fine-tuning dataset.
6. Fine-tuning the model (Instruction tuning and LoRA fine-tuning).

Each topic has a video in the [YouTube playlist](https://www.youtube.com/playlist?list=PLMSb3cZXtIfptKdr56uEdiM5pR6HDMoUX) and a Jupyter notebook in the [`notebooks/`](./notebooks/) folder.


### Limitations

The model doesn’t always give correct answers. If I try to discuss many different topics, it struggles. This is likely because both the model and the SFT dataset are small. Training on more data and using a larger model could improve the results. I might explore this in the future.

## Contributions

We welcome contributions! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Need help?

This course and dataset were originally created by **[Imad Saddik](https://github.com/ImadSaddik)** – all credit to him for the initiative 🙌

For further questions or collaboration, you can reach me:

* **Email** – \[tenzin7755@gmail.com]
* **LinkedIn** – \[https://www.linkedin.com/in/tenzin-palgyal/]

---

👉 Do you want me to **keep your contact as Email only** or also add **GitHub + LinkedIn links** like his style?
