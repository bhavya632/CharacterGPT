# 🎭 CharacterGPT: Evaluating LLM Memorization on Friends Dataset

This project explores whether Large Language Models (LLMs) can mimic characters from the TV show Friends and evaluates the degree of memorization versus generalization in their responses.

We leverage a cleaned transcript dataset, format dialogue into conversational contexts, and then benchmark model outputs using semantic similarity and text generation evaluation metrics.

# 🔎 Key Insights

- LLMs do not replicate exact lines (low ROUGE).

- LLMs capture style and semantics fairly well (higher BERTScore).

- Indicates generalization rather than rote memorization of transcripts.

# ⚙️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, tqdm)

- LLM APIs (OpenAI GPT-4o-mini)

- Embedding Models: Sentence-BERT (all-MiniLM-L6-v2)

- Evaluation Libraries:

  - sentence-transformers

  - bert-score

  - rouge-score

  - evaluate

# 📌 Next Steps

- Expand tests to all ~2,300 conversations.

- Compare across multiple LLMs (GPT-4, Claude, LLaMA).

- Introduce memorization checks by holding out episodes.

# 🙌 Acknowledgments

- Friends dataset adapted from public transcripts.

- Inspired by ongoing research in LLM memorization and character simulation.

___

_I hope you found this project interesting! If you want to look at a more detailed report, please refer to - https://github.com/bhavya632/CharacterGPT/blob/630ace377c77223c54aaa72765053a257b4e0af9/CharacterGPT/Final_Report.pdf._
