# Study Assistant

A lightweight **learning assistant** built with **Panel** and OpenAI’s **Responses API**.
Supports **text questions** and **image uploads** for step-by-step explanations and short quizzes. 📘

---

## Setup (Conda)

```bash
conda env create -f environment.yml
conda activate study-assistant
cp .env.example .env
```

Edit `.env`:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

---

## Run

Open the notebook and run all cells:

```bash
jupyter lab
```

Then open `inline_study_assistant.ipynb`.

---

## License

MIT

