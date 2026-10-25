# DS_sharingNB

Two Jupyter notebooks about data science tools and generative AI:

| Notebook | What it covers |
|---|---|
| [data_science_ecosystem](notebooks/data_science_ecosystem.ipynb) | A short overview of the data science ecosystem: popular languages, libraries and development tools, plus Python examples of arithmetic expressions and unit conversion (minutes to hours). |
| [genai_chatbot](notebooks/genai_chatbot.ipynb) | Two console chatbots built with Hugging Face Transformers using pretrained models: BlenderBot 400M (distilled) and FLAN-T5 base. |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/navendu10/DS_sharingNB/blob/main/notebooks/genai_chatbot.ipynb)
&nbsp;Run the chatbot notebook in Google Colab, no setup needed.

## Run locally

```bash
git clone https://github.com/navendu10/DS_sharingNB.git
cd DS_sharingNB
python -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

In the chatbot notebook, run the cells in order and type your message in the input box. Type `quit`, `exit` or `bye` to stop.
The models are downloaded from the Hugging Face Hub on first use (several hundred MB each), so the first run takes a while.

## Screenshots

The [`screenshots/`](screenshots/) folder holds numbered screenshots (01 to 11) of the data science ecosystem notebook, in the order its sections appear.

## Repository layout

```
.
├── notebooks/
│   ├── data_science_ecosystem.ipynb
│   └── genai_chatbot.ipynb
├── screenshots/
├── requirements.txt
├── LICENSE
└── README.md
```

## License

[MIT](LICENSE)
