# NeuralMachineTranslation EN➡️🇫🇷

This project implements a complete **Neural Machine Translation (NMT)** pipeline for English-to-French translation using three deep learning architectures:  
Vanilla Seq2Seq, Attention-enhanced Seq2Seq, and Transformers (via Hugging Face).

### Tasks Covered:

✅ Data Preprocessing & Tokenization  
✅ Padding & Sequence Handling  
✅ GloVe Embeddings Integration (English)  
✅ Model 1: Vanilla Seq2Seq (BiLSTM → LSTM)  
✅ Model 2: Seq2Seq + Additive Attention  
✅ Model 3: Transformer using Hugging Face  
✅ BLEU Score Evaluation & Inference  
✅ Attention Visualization for Interpretability  
✅ Bonus: Hugging Face Implementation

### Why Seq2Seq + Transformer?

Sequence-to-Sequence models are powerful for translation tasks where input and output lengths vary. Attention mechanisms improve focus on relevant words, while Transformers enable parallelism and state-of-the-art performance.

### Repository Structure:

- `part0_preprocessing.ipynb` → Loading, cleaning, tokenization, padding  
- `part1_seq2seq.ipynb` → Encoder-Decoder with BiLSTM  
- `part2_attention.ipynb` → Attention-based improvements  
- `part3_transformer.ipynb` → Hugging Face transformer implementation  
- `part4_bonus.ipynb`→ Bonus Attention Visualization Task
- `visualizations`→ Visualizations (`vis_1` to `vis_5`)  
- `report/` → Final Report 

---

### Result Highlights:

- **BLEU-4 Score**:  
  - Vanilla Seq2Seq: **~28.8%**  
  - With Attention: **~45.7%**  
  - Transformer: **~56.8%**  
- **Visualization**: Attention maps revealed linguistic alignment quality.  
- **Inference**: Smooth and fluent translations with the Transformer model.

---

**Note:** Large files (e.g., tokenizers, GloVe, `.npz`, model weights) are gitignored.  
**GloVe Embeddings** used: [`glove.6B.100d.txt`](https://nlp.stanford.edu/data/glove.6B.zip)  
**Dataset Source**: [`ManyThings.org`](http://www.manythings.org/anki/)

---
